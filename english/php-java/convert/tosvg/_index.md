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

| Name | Type | Description |
| --- | --- | --- |
| presPath | String | Path of the input presentation |

### Returns
void


---


## toSvg(String presPath, [Convert.GetOutPathCallback](../../convert.getoutpathcallback) getOutPath)  method

 Converts  Presentation to SVG.
 

 
```php
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| presPath | String | Path of the input presentation |
| getOutPath | [Convert.GetOutPathCallback](../../convert.getoutpathcallback) | Callback that returns the SVG output path for each slide in the presentation |

### Returns
void


---


## toSvg([Presentation](../../presentation) pres, [Convert.GetOutPathCallback](../../convert.getoutpathcallback) getOutPath)  method

 Converts  Presentation to SVG.
 

 
```php
  $pres = new Presentation("input.pptx");
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Input presentation |
| getOutPath | [Convert.GetOutPathCallback](../../convert.getoutpathcallback) | Callback that returns the SVG output path for each slide in the presentation |

### Returns
void


---


## toSvg([Presentation](../../presentation) pres, [SVGOptions](../../svgoptions) options)  method

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

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Input presentation |
| options | [SVGOptions](../../svgoptions) | SVG export options |

### Returns
void


---


## toSvg([Presentation](../../presentation) pres, [Convert.GetOutPathCallback](../../convert.getoutpathcallback) getOutPath, [SVGOptions](../../svgoptions) options)  method

 Converts  Presentation to SVG.
 

 
```php
  $pres = new Presentation("input.pptx");
  $svgOptions = new SVGOptions();
  $svgOptions->setVectorizeText(true);
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| pres | [Presentation](../presentation) | Input presentation |
| getOutPath | [Convert.GetOutPathCallback](../convert.getoutpathcallback) | Callback that returns the SVG output path for each slide in the presentation |
| options | [SVGOptions](../../svgoptions) | SVG export options |

### Returns
void


---


