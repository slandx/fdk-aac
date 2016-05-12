# fdk-aac
Clone from https://sourceforge.net/projects/opencore-amr/

Based on version 0.1.4

This project compiles a static library of fdk-aac which is used to [compile ffmpeg with MSVC](https://github.com/ho1iarty/ffmpeg_vs/wiki).

### Compile
1. Open MSVC project file in Visual Studio 2010.  
2. Change to Release config.
3. Build

A static lib named "fdk-aac.lib" will be generated in msvc\Release folder.

Copy to ffmpeg lib folder.
Configure ffmpeg with `--enable-libfdk-aac --enable-nonfree`.
More details about compile ffmpeg with MSVC, check the link above.

### Modified
- Add MSVC project files.
