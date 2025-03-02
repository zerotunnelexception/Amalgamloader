# Amalgamloader


A fork of Fedoraloader for use with Amalgam.

> [!NOTE]  
> VAC-Bypass is enabled by default and might cause issues with other games such as CS2 and Dota.

## Usage

- Run Amalgamloader as administrator
- Right click on the tray icon to open the menu
- Click **Load** or **Load + Exit**


## FAQ

### How do I fix "MSVCP140.dll not found"?

Download and install the [Microsoft Visual C++ Redistributable](https://aka.ms/vs/17/release/vc_redist.x86.exe).


### Why did Amalgamloader disappear?

You need to add the loader file to your antivirus' exception list or disable it completely.
This is a false positive due to the nature of injectors and their similarity to malware.


## Options

Amalgamloader allows some options to be set via command line arguments.
To use them, create a shortcut to the loader and add the arguments to the target field.

| Argument | Description |
| --- | --- |
| `-silent` | Run the loader without GUI |
| `-nobypass` | Don't restart Steam with VAC-Bypass |
| `-ll` | Use LoadLibrary-Injection *(only works with local files)* |
| `-debug` | Show debug console |
| `-file "..."` | Custom local file *(.zip or .dll)* |
| `-url "..."` | Custom download URL *(.zip or .dll)* |

## Credits

- [Inx00](https://github.com/lnx00)
- [miniz](https://github.com/richgel999/miniz)
- [VAC Bypass](https://github.com/danielkrupinski/VAC-Bypass)
- [Simple Manual Map Injector](https://github.com/TheCruZ/Simple-Manual-Map-Injector)
