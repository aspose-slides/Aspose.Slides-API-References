---
title: writeAsSvg
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 320
url: /php-java/slide/writeassvg/
---

## writeAsSvg(OutputStream stream)  method

 Saves content of slide as SVG file.
 

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Target stream |

### Returns
void


---


## writeAsSvg(OutputStream stream, [SVGOptions](../../svgoptions) svgOptions)  method

 Saves content of slide as SVG file.
 

 The following example code shows how to generate SVG image with Custom Shape IDS from PowerPoint Presentation.
 
```php
  $pres = new Presentation("CreateSlidesSVGImage.pptx");
  try {
    // Access the first slide
    $sld = $pres->getSlides()->get_Item(0);
    // Create a memory stream object
    $svgStream = new ByteArrayOutputStream();
    // Generate SVG image of slide and save in memory stream
    $sld->writeAsSvg($svgStream);
    // Save memory stream to file
    $fileStream = new FileOutputStream("Aspose_out.svg");
    try {
      $svgStream->writeTo($fileStream);
    } finally {
      if ($fileStream != null) {
        $fileStream->close();
      }
    }
    $svgStream->close();
  } catch (JavaException $e) {
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Target stream |
| svgOptions | [SVGOptions](../../svgoptions) | SVG generation options |

### Returns
void


---


