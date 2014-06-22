Terminator-Color-Schemes
========================

This project is based on [iTerm2 Color Schemes](https://github.com/mbadolato/iTerm2-Color-Schemes)
I only have ported the xrdb files with [this script](tools/xrdb2terminator.py), [all the credits are for those people](https://github.com/mbadolato/iTerm2-Color-Schemes#credits)


Give me the themes!
-------------------

The terminator configuration file is in: `$HOME/.config/terminator/config`.
You need to edit this file

Select the theme or themes that you like in `schemes/` directory, open the file
and add to your termiantor config file in the profiles block.

that's it! you can customize the font and stuff afterwards

Lets see an example :)

This is my terminator config file:

    [global_config]
        [keybindings]
        [profiles]
          [[default]]
            palette = "#1a1a1a:#f4005f:#98e024:#fa8419:#9d65ff:#f4005f:#58d1eb:#c4c5b5:#625e4c:#f4005f:#98e024:#e0d561:#9d65ff:#f4005f:#58d1eb:#f6f6ef"
            background_image = None
            use_system_font = False
            cursor_color = "#f6f7ec"
            foreground_color = "#c4c5b5"
            font = Source Code Pro Light 11
            background_color = "#1a1a1a"
        [layouts]
          [[default]]
            [[[child1]]]
              type = Terminal
              parent = window0
            [[[window0]]]
              type = Window
              parent = ""
        [plugins]

And I like the *Smyck* theme, this file in `schemes/Smyck.config` has:
    
    [[Smyck]]
        palette = "#000000:#b84131:#7da900:#c4a500:#62a3c4:#ba8acc:#207383:#a1a1a1:#7a7a7a:#d6837c:#c4f137:#fee14d:#8dcff0:#f79aff:#6ad9cf:#f7f7f7"
        background_color = "#1b1b1b"
        cursor_color = "#bbbbbb"
        foreground_color = "#f7f7f7"
        background_image = None

So I add this likes to my profiles:

    [global_config]
        [keybindings]
        [profiles]
          [[default]]
            palette = "#1a1a1a:#f4005f:#98e024:#fa8419:#9d65ff:#f4005f:#58d1eb:#c4c5b5:#625e4c:#f4005f:#98e024:#e0d561:#9d65ff:#f4005f:#58d1eb:#f6f6ef"
            background_image = None
            use_system_font = False
            cursor_color = "#f6f7ec"
            foreground_color = "#c4c5b5"
            font = Source Code Pro Light 11
            background_color = "#1a1a1a"
          [[Smyck]]
            palette = "#000000:#b84131:#7da900:#c4a500:#62a3c4:#ba8acc:#207383:#a1a1a1:#7a7a7a:#d6837c:#c4f137:#fee14d:#8dcff0:#f79aff:#6ad9cf:#f7f7f7"
            background_color = "#1b1b1b"
            cursor_color = "#bbbbbb"
            foreground_color = "#f7f7f7"
            background_image = None
        [layouts]
          [[default]]
            [[[child1]]]
              type = Terminal
              parent = window0
            [[[window0]]]
              type = Window
              parent = ""
        [plugins]

After this I can add to Smyck profile the customizations like the font in the default
profile...

Screenshoots
------------
[See iTerm repository Screenshots](https://github.com/mbadolato/iTerm2-Color-Schemes)




