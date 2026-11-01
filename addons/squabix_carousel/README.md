# SQUABIX Carousel

A UI control that slides between pages. Use it for menus, tutorials, and level pickers.

## Classes

- `Carousel`

## Use

1. Add a `Carousel` node.
2. Add a `Control` node for each page as a child.
3. Set `previous_button` and `next_button` if you want buttons.
4. Set `dot_container` and the dot styles if you want page dots.
5. Call `next()`, `previous()`, or `select_page()` to change page.
6. Connect to `page_changed` to react to the new page.

## Demo

See it in the game: https://github.com/squabix/craftlander

## Needs

Godot 4.5 or newer.

## License

MIT. See `LICENSE`.
Icons are from another project. See `THIRD_PARTY.md`.
