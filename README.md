# http-server-ssl: a command-line https server

folk from http-server-ssl , you can use `http-server-ssl -S` or `hss -S` run a https server.

This command using [pem](https://github.com/Dexus/pem#readme) creatas an invalid certificate to run a https server for debug.


## Usage

`npm install http-server-ssl`

in package.json -go to scripts and add, `"hss": "http-server-ssl -S"`, then run `npm run hss`

---

OR install globally
`npm install -g http-server-ssl`, and then you can just run `http-server-ssl -S` in the terminal in any project.

Then, in your Chromium based browser, go to url `chrome://flags/#allow-insecure-localhost` and enable, restart. Then you can go to the `https://127.0.0.1:8080/` URL with no problem
