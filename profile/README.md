<a name="readme-top"></a>
<div align="center">
	<img src="../res/logo.png" width="150px">
	<h1 align="center">Trinity</h1>
	<p align="center">A retro 2.5D game engine</p>
	<p align="center">
		<a href="https://github.com/trinity-engine/trinity">Source code [WIP]</a>
		.
		<a href="https://github.com/trinity-engine/trinity-demos">Demos [WIP]</a>
	</p>
	<br>
</div>

## Introduction
> [!NOTE]
> Trinity is a work-in-progress and is currently not public.

**Trinity** is a retro 2.5D software rendered game engine written in [C99](https://en.wikipedia.org/wiki/C99)
using the [SDL2](https://wiki.libsdl.org/SDL2/FrontPage) library and [Lua](https://www.lua.org/about.html)
for scripting. It is inspired by game engines like [Valve's Source engine](https://en.wikipedia.org/wiki/Source_(game_engine)),
the [Doom engine](https://en.wikipedia.org/wiki/Doom_engine), the [Build engine](https://en.wikipedia.org/wiki/Build_(game_engine))
the [Quake engine](https://en.wikipedia.org/wiki/Quake_engine) and [Roblox](https://en.wikipedia.org/wiki/Roblox).

Trinity aims to support the following platforms:
- Windows
- Linux
- MacOS

## Previous unpublished version
<img src="../res/old-trinity.png" width="45%" align="right">

The first scrapped version of Trinity was an advanced [raycaster](https://lodev.org/cgtutor/raycasting.html).
It had a sky with proper 3D perspective, angled walls and supported varying floor and ceiling height,
just like Doom. I achieved that using a simple "sector" technique I came up with, which split each
screen column into parts based on the floor/ceiling height. It basically grouped together multiple
tiles of the same height into a "sector" and rendered it. If the sector floor is higher than the
previous sector floor, a wall is rendered. If the sector ceiling is lower than the previous sector
ceiling, a wall is rendered too.

This engine was cool as an advanced raycaster engine, but really limited as just a game engine.
That's why I decided to make the new Trinity a Build-style engine, which is probably the most
flexible type of 2.5D software rendered engine.

<br>
<h1></h1>
<br>

<div align="center">
	<div align="center"><img src="../res/banner.png" width="90%"></div>
	<br>
	<a href="https://en.wikipedia.org/wiki/C_(programming_language)">
		<img alt="C99" src="https://img.shields.io/badge/C99-0069a9?style=for-the-badge&logo=c&logoColor=white">
	</a>
	<a href="https://www.libsdl.org/">
		<img alt="SDL2" src="https://img.shields.io/badge/SDL2-1d4979?style=for-the-badge&logoColor=white">
	</a>
	<a href="https://www.lua.org/">
		<img alt="Lua" src="https://img.shields.io/badge/Lua-00007f?style=for-the-badge&logoColor=white">
	</a>
	<p align="center">Made with ❤️ love</p>
</div>

<p align="right">(<a href="#readme-top">Back to top</a>)</p>
