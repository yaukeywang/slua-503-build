# slua-503-build
The build project for slua plugins with lua5.3.

##简介
为了方便使用 Lua5.3 的开发者编译适用于 SLua 的 Unity 插件。

##包含内容：
Lua 5.3.1

Lpeg

SLua

sproto

##注意事项
未使用命令行或 Makefile 来编译；

仅支持 XCode(3.1及以上) 与 Visual Studio 2015 来编译生成所有的文件（Android 项目的生成请确保安装了正确版本的 NDK）。

Visual Studio 2015 已经免费将所有强大的功能提供给开源社区和小企业，有这么棒的工具为何不用。

##未来发展
后续希望完全通过 Premake 来生成不同的编译文件，目前 premake-android 项目不完善，希望通过完善该项目来更好的生成 vs2015 下 Android 的编译项目。
