logKext
=======

logKext clone from https://code.google.com/p/logkext/ and support for xocde5 

BuildInstructions
=======

1) Set the build configuration to Development or Deployment. Deployment builds in 32/64bit Intel/PPC universal. Development builds for whatever processor/architecture is currently in use.

1) Compile main project. All subprojects should automatically be compiled.

2) Check build output. If PackageMaker (last build step) said "Error: source not on disk" or something like that; or if no logkext.pkg exists, the build didn't fully complete. In this case, you need to just run the build again and it should work.

NOTE: Currently due to issue 30, this won't work properly. Follow the workaround in the issue report to build the package correctly.

3) Install logKext.pkg.

packagemaker
========

you need download packagemaker
https://developer.apple.com/downloads/index.action?name=packagemaker
