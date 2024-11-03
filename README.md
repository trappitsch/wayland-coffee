# wayland-coffee

This is the `wayland-idle-inhibitor.py` script
from [stwa here](https://github.com/stwa/wayland-idle-inhibitor).
I wrapped it into a python package,
such that it can, e.g., be installed with `uv` or `pipx`,
and can directly be called by typing `coffee` on the terminal.

## Installation

Please use a tool installer like `uv` or `pipx` to install this package.

For `uv` use the following command:

```bash
uv tool install git+https://github.com/trappitsch/wayland-coffee
```

For `pipx` use the following command:

```bash
pipx install git+https://github.com/trappitsch/wayland-coffee.git
```

## Execution

After installation, you can call the script by typing `coffee` on the terminal.

```bash
coffee
```

This will keep your wayland session alive.
To stop the script, press `Ctrl+C`.



