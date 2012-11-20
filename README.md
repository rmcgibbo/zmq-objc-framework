#ZeroMQ Objective-C Bindings as a Xcode Private Framework

This is a fork of jeremy-w's objective-c bindings for ZeroMQ: https://github.com/jeremy-w/objc-zmq

Besides repackaging it as a private framework, I also changed the API somewhat and fixed
the issue where nonblocking reads weren't done correctly. (https://github.com/jeremy-w/objc-zmq/issues/4)

Also, this includes the ZeroMQ 2.2.0 code within it, so you can deploy even if the people
don't have zeromq installed.

