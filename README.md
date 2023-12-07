# dir2wxs
Tool to update XML file used to create MSI using WiX
## Arguments
- `-i` input file, if absent then stdin
- `-o` ouput file, if absent then stdout
- `-s` source directory, defaults to current directory with .
- `-d` destination directory label, defaults to `INSTALLDIR`

Tool will replicate the `Component` element for each file in the source directory.
