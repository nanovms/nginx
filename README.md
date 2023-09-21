Collection of patches that convert nginx to a single-process multi-threaded application, allowing it to exploit the parallelism of multi-thread operation while running as a Nanos unikernel.
The syntax of the nginx configuration file has been left unmodified, so the `worker_processes` setting is now used to configure the number of worker threads.

