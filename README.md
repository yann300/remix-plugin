# remix-plugin
Contains everything you need to start coding a remix plugin

## how to get started

git clone https://github.com/ethereum/remix-ide

Serve the `src` folder through a web server `http-server .`

Go in Remix / settings tab, under the `Plugin` section paste the following declaration:

{
    "title": "<name of plugin>",
    "url": "http://127.0.0.1:<port>"
}

Then start the plugin by licking on its icon.
