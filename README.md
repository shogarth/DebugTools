# DebugTools

*Debugger Configs for MSVC*

Provides config files which improve debugging with MSVC. When working 
with STL containers, smart pointers, and boost signals, it is nice to 
debug directly into your own code without making side trips into 
container internals. These configs also provide custom object views 
which make debugging easier.

## To Use

You need to reference these files from your project or copy them into 
<user>\Documents\Visual Studio ####\Visualizers. If you copy them, you
must copy the files directly, VS will not recognize any files in subfolders. 
VS will usually detect edits to registered files when starting a debug 
session, but requires a restart to register a new configuration file.
