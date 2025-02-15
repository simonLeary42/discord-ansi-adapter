# daad: Discord Ansi ADapter

converts ANSI color escape sequences from stdin into the limited 4-bit sequences supported by discord.
rounds 256color and true color escape sequences to the colors displayed in the discord client using Euclidian distance.

## example:

```sh
git diff --color=always | discord-ansi-adapter.py | discord-message.py
```

![image](https://github.com/user-attachments/assets/adca74d9-9125-47f9-9b7a-be4aad53ea93)


![image](https://github.com/user-attachments/assets/941d3594-b8a0-4f0f-9944-02e70b4b209c)
