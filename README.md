# css-images

Functional CSS for images

## Filesize

| File | Size |
|------|------|
| `dist/images.css` | 27 bytes |
| `dist/images.min.css` | 19 bytes (39 Gzipped) |

## Install

```sh
npm install css-images
```

## Usage

### Import

```css
@import "css-images";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-images/dist/images.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-images/dist/images.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|


### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.example-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/images.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/images.css` — formatted
- `dist/images.min.css` — minified

## License

MIT
