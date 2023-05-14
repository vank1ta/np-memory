# np-memorygame
NoPixel 3.0 Inspired Thermite Game

# Usage
Put the folder in your resources and start in resources.cfg
``ensure np-memory``

# How to use export
```
    -- correctBlocks = Number of correct blocks the player needs to click
    -- incorrectBlocks = number of incorrect blocks after which the game will fail
    -- timetoShow = time in secs for which the right blocks will be shown
    -- timetoLose = maximum time after timetoshow expires for player to select the right blocks
 exports["np-memory"]:Thermite(10, 3, 3, 10,
    function() -- success
        print("success")
    end,
    function() -- failure
        print("failure")
    end)
```

# Discord
https://discord.gg/Dnthwv6xkE

# Tebex
https://vank1ta.tebex.io

# Youtube
https://www.youtube.com/@vank1ta671

# VT-Developments
Copyright (C) 2022 VT Development's

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>

# Credit

https://github.com/pushkart2/memorygame