HTTPServerPY
=======

Author: **[Moin Khan](https://github.com/mo-inkhan)**

# HTTPServerPY: A lightweight static HTTP server written in Python

## Introduction

`HTTPServerPY` is a simple, zero-configuration command-line static HTTP server.

## Installation:

#### Globally via `pip`

    pip install HTTPServerPY

This will install `HTTPServerPY` globally so that it may be run from the command line anywhere.

## Usage:

    py -m HTTPServerPY [host] [port] [path] [options]

`[host]` defaults `localhost` | `0.0.0.0`.
`[port]` defaults `8000`.
`[path]` defaults `./` the current directory.

*Now you can visit http://localhost:8080 to view your server*

## Available Options:

| Command                      | Description                                                                                      | Defaults |
| :--------------------------- | :----------------------------------------------------------------------------------------------- | :------- |
| `-p` or `--port`             | Port to use. Use `-p=8080` to serve at 8080 port                                                 | 8000     |
| `-h` or `--host`             | Host to use. Use `-h=0.0.0.0` to serve at localhost                                              | 0.0.0.0  |
| `-pth`&nbsp;or&nbsp;`--path` | Path to serve from. Use `--path=./my_folder` to serve from `my_folder` present in current folder | ./       |

## Magic Files

- `index.html` will be served as the default file to any directory requests.
- `404.html` will be served if a file is not found.
- `405.html` will be served if a requested method is not supported.

*Now you can visit http://localhost:8080 to view your server*

---

## Contributing
All contributions are welcome. Please create an issue first for any feature request
or bug. Then fork the repository, create a branch and make any changes to fix the bug
or add the feature and create a pull request. That's it!
Thanks!

---

## License
**HTTPServerPY** is released under the MIT License.
Check out the full license [here](LICENSE).
