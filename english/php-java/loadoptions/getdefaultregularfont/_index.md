---
title: getDefaultRegularFont
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 50
url: /php-java/loadoptions/getdefaultregularfont/
---

## getDefaultRegularFont()  method

 Returns or sets Regular font used in case source font is not found.
 Read/write  String.
 

 The following example shows how to set default fonts for rendering PowerPoint Presentation.
 
```php
  // Use load options to define the default regular and asian fonts
  $loadOptions = new LoadOptions(LoadFormat::Auto);
  $loadOptions->setDefaultRegularFont("Wingdings");
  $loadOptions->setDefaultAsianFont("Wingdings");
  // Load the presentation
  $pres = new Presentation("DefaultFonts.pptx", $loadOptions);
  try {
    // Generate slide thumbnail
    $slideImage = $pres->getSlides()->get_Item(0)->getThumbnail(1, 1);
    ImageIO->write($slideImage, "PNG", new File("output_out.png"));
    // Generate PDF
    $pres->save("output_out.pdf", SaveFormat.Pdf);
    // Generate XPS
    $pres->save("output_out.xps", SaveFormat.Xps);
  } catch (JavaException $e) {
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Returns
String


---


