## How to use this stoopid shit.
Just run the `PackageManager.lua` script and then you can use `import(<Package Name>)` in any script.
## Example
```lua
local mt = import("MetatableHooking")
mt.namecallhook("FireServer", function(namecall, ...)
  print(...)
  return namecall(...)
end)
```
## Adding your own paclages
If you want to add your own packages just fork this repo and change the `packages.json` url in the `PackageManager.lua` script.
## Current packages
* MetatableHooking
