---
title: Convert
type: docs
weight: 0
url: /php-java/convert/
---

# Convert class

 Represents a group of methods intended to convert  Presentation.
 

 
```php
  Convert->AutoByExtension("pres.pptx", "pres.pdf");
```

## Constructors

| name | description |
| --- | --- |
| [Convert](/slides/php-java/convert/convert/)() |  |

## Methods

| name | return type | description |
| --- | --- | --- |
| [autoByExtension](/slides/php-java/convert/autobyextension/)(String, String) | void | Converts Presentation using the passed output path extension to determine the required export format. |
| [toPdf](/slides/php-java/convert/topdf/)(String, String) | void | Converts Presentation to PDF. |
| [toPdf](/slides/php-java/convert/topdf/)(String, String, IPdfOptions) | void | Converts Presentation to PDF. |
| [toPdf](/slides/php-java/convert/topdf/)(Presentation, String) | void | Converts Presentation to PDF. |
| [toPdf](/slides/php-java/convert/topdf/)(Presentation, String, IPdfOptions) | void | Converts Presentation to PDF. |
| [toSvg](/slides/php-java/convert/tosvg/)(String) | void | Converts Presentation to SVG. |
| [toSvg](/slides/php-java/convert/tosvg/)(String, Convert.GetOutPathCallback) | void | Converts Presentation to SVG. |
| [toSvg](/slides/php-java/convert/tosvg/)(Presentation, Convert.GetOutPathCallback) | void | Converts Presentation to SVG. |
| [toSvg](/slides/php-java/convert/tosvg/)(Presentation, ISVGOptions) | void | Converts Presentation to SVG. |
| [toSvg](/slides/php-java/convert/tosvg/)(Presentation, Convert.GetOutPathCallback, ISVGOptions) | void | Converts Presentation to SVG. |
