# ToolTip KIT

Lightweight tooltips library developed exclusively with CSS, with no JavaScript dependencies. Easy to integrate, customizable and compatible with all modern browsers.

## How to use

Add the data-ttk and aria-label attributes to any html element:

| Attribute  | Description      |
| ---------- | ---------------- |
| data-ttk   | Tooltip position |
| aria-label | Text to display  |

```html
<div data-ttk aria-label="Hello world!">Custom element</div>
```

### Positioning

If no orientation is specified, the default value (up) will be used:

```html
<div data-ttk="up" aria-label="Tooltip Up">Custom element</div>
<div data-ttk="down" aria-label="Tooltip Down">Custom element</div>
<div data-ttk="left" aria-label="Tooltip Left">Custom element</div>
<div data-ttk="right" aria-label="Tooltip Right">Custom element</div>
```

### Customize

Define new values for the tooltip's CSS variables to change its appearance. The available design variables are:

| Variable           | Default    | Description                             |
| ------------------ | ---------- | --------------------------------------- |
| `--ttk-arrow-size` | `6px`      | Arrow size                              |
| `--ttk-offset`     | `4px`      | Margin between arrow and parent element |
| `--ttk-text`       | `10px`     | Text size                               |
| `--ttk-bg`         | `#000`     | Background color                        |
| `--ttk-padding`    | `5px 10px` | Internal space                          |
| `--ttk-radius`     | `4px`      | Border radius                           |
| `--ttk-color`      | `#fff`     | Text color                              |
| `--ttk-duration`   | `0.5s`     | Transition duration                     |
