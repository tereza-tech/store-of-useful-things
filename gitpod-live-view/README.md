###### This repo is serving just as a template for configuration of GitPod on //localhost.

# GITPOD Localhost

Some of the libraries, by default, will only respond to requests from localhost server.

To create a new project living in browser localhost (127.0.0.1/0.0.0.0), follow next steps.

❤️ 🚀️

For more information on setting up live preview visit Gitpod original [article](https://www.gitpod.io/blog/local-app).

This template for Svelte apps was forked from this repo in [Github](https://github.com/sveltejs/template). For start run:

```bash
npm run dev
```

...commands start [Rollup](https://rollupjs.org).

*Note that for this app you will need to have [Node.js](https://nodejs.org) installed.*

## Live-Companion

Download the *Gitpod Local Companion* app:

* [Linux 64 bit](https://gitpod.io/static/bin/gitpod-local-companion-linux-arm64)
* [Windows 64 bit](https://gitpod.io/static/bin/gitpod-local-companion-windows.exe)

To run it using your local keyring for long term storage of the access token:

```bash
 ./gitpod-local-companion-[linux|windows]
```

To run it without storing the access token (it will generate a new token every time);

```bash
./gitpod-local-companion-[linux|windows] --mock-keyring
```

Go back to your workspace and navigate to [localhost:8080](http://localhost:8080). You should see your app running. Edit a component file in `src`, save it, and reload the page to see your changes.

To allow connections from other computers, edit the `sirv` commands in package.json to include the option `--host 0.0.0.0`.

If you're using [Visual Studio Code](https://code.visualstudio.com/) we recommend installing the official extension [Svelte for VS Code](https://marketplace.visualstudio.com/items?itemName=svelte.svelte-vscode). If you are using other editors you may need to install a plugin in order to get syntax highlighting and intellisense.

