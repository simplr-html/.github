# SimplerHTML: HTML made simpler

SimplerHTML in:
```
[h2] Hello, [b]World[b]! [rem] This is a H2 heading.

Drink options: [rem] This is a paragraph.

[rem] Here are some nested lists:
[oli] Water
[begin][oli]
Milk:
[uli] Regular
[uli] Strawberry
[uli] Chocolate
[end][oli]
[begin][oli]
Coffee:
[uli] Regular
[uli] Mocha
[uli] Espresso
[uli] Cappucino

[i][[Note that creamer and/or milk can be added to reduce the coffee's strength.][i] [rem] Note the extra opened square bracket after the "[i]" tag.
[end][oli]
```
Rendered output:

> ## Hello, **World**!
>
> Drink options:
>
> 1. Water
> 1. Milk:
>    - Regular
>    - Strawberry
>    - Chocolate
> 1. Coffee:
>    - Regular
>    - Mocha
>    - Espresso
>    - Cappucino
>
>    *[Note that creamer and/or milk can be added to reduce the coffee's strength.]*

Check out the spec to see what SimplerHTML looks like :point_down:
