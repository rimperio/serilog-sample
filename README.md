# serilog-sample

## serilog-webapi-sample
Project developed and tested with Centos 8. During initial run, I ran into the following error:

Unhandled exception. System.Reflection.TargetInvocationException: Exception has been thrown by the target of an invocation.
---> System.DllNotFoundException: Unable to load shared library 'libdl.so' or one of its dependencies. 

Error was resolved by installing the following lib using:
sudo dnf update && install glibc-devel



 