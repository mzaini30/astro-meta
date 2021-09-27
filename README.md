# Astro Meta

You only need the _title_ and _description_ attributes to use this library!

## Example

```astro
---
import Meta from 'astro-meta'
---

<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<Meta title='Hello world' description="It's a page about my hobby"></Meta>
</head>
<body>
	<h1>Hello world...</h1>
</body>
</html>
```

## Results

```html
<!DOCTYPE html>
<html lang="en">
   <head>
      <meta charset="UTF-8">
      <meta name="viewport" content="width=device-width, initial-scale=1.0">

      <title>Hello world</title>
      <meta name="description" content="It's a page about my hobby">
      <meta property="og:locale" content="id_ID">
      <meta property="og:type" content="article">
      <meta property="og:title" content="Hello world">
      <meta property="og:description" content="It's a page about my hobby">
      <meta property="og:image" content="https://cdn.statically.io/og/Hello%20world.jpg">
      <meta property="og:image:width" content="2048">
      <meta property="og:image:height" content="1170">
      <meta name="twitter:card" content="summary_large_image">
      <meta property="twitter:title" content="Hello world" />
      <meta property="twitter:description" content="It's a page about my hobby" />
      <meta property="twitter:image" content="https://cdn.statically.io/og/Hello%20world.jpg" />

   </head>
   <body>
      <h1>Hello world...</h1>
   </body>
</html>
```
