Viewing Documentation for Mininet's Python API
----------------------------------------------

Mininet's modules and Python API are documented using Python documentation strings which may be accessed from Python's regular `help()` mechanism. For example,

    python
    >>> from mininet.node import Host
    >>> help(Host.IP)
    Help on method IP in module mininet.node:
    IP(self, intf=None) unbound mininet.node.Host method
            Return IP address of a node or specific interface.</verbatim>

You may also wish to generate HTML documentation using =doxypy=:

    sudo apt-get install doxypy
    cd ~/mininet