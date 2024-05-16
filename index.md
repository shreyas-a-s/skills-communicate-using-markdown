# Adding header 1

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

# Lua code
```lua
function M.config()
  require("ibl").setup({
    indent = { char = "┊" },
    scope = { enabled = false },
    exclude = {
      filetypes = {
        "help",
        "startify",
        "dashboard",
        "lazy",
        "neogitstatus",
        "NvimTree",
        "Trouble",
        "text",
      },
    },
  })
end
```
