---
title: toSvg
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 70
url: /php-java/convert/tosvg/
---

## toSvg(String presPath)  method

 Converts  Presentation to SVG.
 

 
```php
  Convert->toSvg("pres.pptx");
```

### Parameters

| Name | Description |
| --- | --- |
| presPath | Path of the input presentation |

### Returns
Presentation


---



 Converts  Presentation to SVG.
 

 
```php
```

### Parameters

| Name | Description |
| --- | --- |
| presPath | Path of the input presentation |
| getOutPath | Callback that returns the SVG output path for each slide in the presentation |

### Returns
Presentation


---



 Converts  Presentation to SVG.
 

 
```php
  $pres = new Presentation("input.pptx");
```

### Parameters

| Name | Description |
| --- | --- |
| pres | Input presentation |
| getOutPath | Callback that returns the SVG output path for each slide in the presentation |

### Returns
Presentation


---


## toSvg(Presentation pres, SVGOptions options)  method

 Converts  Presentation to SVG.
 

 
```php
  $pres = new Presentation("input.pptx");
  try {
    $svgOptions = new SVGOptions();
    $svgOptions->setVectorizeText(true);
    Convert->toSvg($pres, $svgOptions);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Description |
| --- | --- |
| pres | Input presentation |
| options | SVG export options |

### Returns
Presentation


---



 Converts  Presentation to SVG.
 

 
```php
  $pres = new Presentation("input.pptx");
  $svgOptions = new SVGOptions();
  $svgOptions->setVectorizeText(true);
```

### Parameters

| Name | Description |
| --- | --- |
| pres | Input presentation |
| getOutPath | Callback that returns the SVG output path for each slide in the presentation |
| options | SVG export options |

### Returns
Presentation


---


