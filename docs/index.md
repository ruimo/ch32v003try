# CH32V003でLチカ

秋月電子さんで、[CH32V003J4M6](https://akizukidenshi.com/catalog/g/gI-18062/)の扱いが始まったので試してみた。スペックを見て良いなと思ったのは、

* 安価(40円!)
* ローエンドだけど高いスペック(32bitコア、クロック48MHz、ROM 16KB、RAM 2KB)。ADC/UART/I2C付き
* 電源の範囲が広いl(2.7V - 5.5V)

## プログラマ

プログラマには

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

    mkdocs.yml    # The configuration file.
    docs/
        index.md  # The documentation homepage.
        ...       # Other markdown pages, images and other files.
