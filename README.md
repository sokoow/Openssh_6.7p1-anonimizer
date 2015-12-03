# Openssh_6.7p1-anonimizer

This is a simple trick to disable SSH version banner, so instead of looking like this:

SSH-2.0-OpenSSH_6.7p1 Ubuntu-6

it looks more like this

SSH-2.0-BAZINGA

Idea was born due to lack of suck option in the config file, basically banner is hardcoded. This hopefully gives more security, and makes it for attacked to put more effort in guessing the version string of the service.
