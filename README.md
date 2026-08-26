# Builtt Dark Theme

A dark VSCode theme built for OLED. Near-black surfaces, a small earthy palette — brick, gold, sage, ash — no italics, no bolds.

Tuned for TypeScript, JavaScript, JSX/TSX, JSON and `.env` files.

## Palette

| Color | Hex | Used for |
| --- | --- | --- |
| Brick | `#CC5747` | Keywords, errors, deletions |
| Gold | `#CFA35C` | JSX tags, components (PascalCase functions), types, warnings, modified files |
| Dusty gold | `#C6A97B` | JSON keys, `.env` keys |
| Sage | `#A8C280` | Strings, additions |
| Teal | `#82B5A2` | Numbers, booleans, `null`/`undefined` |
| Blue | `#8AA9C4` | camelCase functions, info |
| White / grays | — | Identifiers, punctuation, comments, all UI chrome |

## Details

- The code area (`#0A0A0A`) sits darker than the window chrome (`#111111`) — content sinks into the screen, the frame floats.
- PascalCase and camelCase function calls are colored differently via a small injection grammar, so `<Card>` and `Card()` match while `cn()` stays distinct.
- Interaction chrome (selections, brackets, badges, scrollbars) stays monochrome by design — color is reserved for meaning: syntax, diagnostics, git state.

## Install

From the Marketplace, or grab the `.vsix` from releases:

```
code --install-extension builtt-dark-theme-<version>.vsix
```
