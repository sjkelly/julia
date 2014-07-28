<a name="logo"/>
<div align="center">
<a href="http://julialang.org/" target="_blank">
<img src="http://julialang.org/images/logo_hires.png" alt="Julia Logo" width="210" height="142"></img>
</a>
</div>
<a name="The-Julia-Language"/>
## The Julia Language

Julia is a high-level, high-performance dynamic language for technical computing.
The main homepage for Julia can be found at [julialang.org](http://julialang.org/).

This is my fork of Julia and branch for notetaking. I make it default on GitHub so I can reference quickly what I am following.


## Things to document
* https://github.com/JuliaLang/julia/issues/5432
* args to make
* https://github.com/JuliaLang/julia/issues/5135
* https://github.com/JuliaLang/julia/issues/5862
* https://github.com/JuliaLang/julia/issues/5523
* https://github.com/JuliaLang/julia/issues/7437
* https://github.com/JuliaLang/julia/issues/2501


## Issues I want to fix
* https://github.com/JuliaLang/julia/issues/4908

### More detailed tests
Started in:
* https://github.com/JuliaLang/julia/pull/7586

## Ideas for Base
Expand graphics.jl and cross-pollinate the function and type names with PolygonClipping.jl and MeshSlicer.jl. Also, https://github.com/mroughan/Geometry2D.jl/issues/1. We can define promote rules for interoperability.

An easy way to install programs from Pkg.


## Notes
### Precompilation
Precompilation is a way to speedup loading packages. For applications, this leads to better UX.
https://github.com/JuliaLang/julia/issues/6442
