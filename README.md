# Solution before docker
- configuration managment tools (chef, puppet, ansible)
    - require knowledge about hardware and operating systems.
- virtual machines as code ( Vagrant )
    - heavy, slow-ish, requires inconvenient configuration.

# Docker solved : 👇

- Dockers makes containers easy:
    - Configuration through Dockerfiles, not shell commands.
    - Share image with others through image registries.
    - A super easy command line client and API.

# Docker explained

- ##### Containers vs virtual machines
| Containers                        | Virtual Machines              |
| -------------                     |:-----------------------------:|
| Run in container runtimes         | Run on top of hypervisors     |
| work alongside operating system   | Need hardware emulation       |
| Do not require OS configuration   | Require OS configuration      |
| Run one app at a time ( usually ) | Can run many apps at a time   |
