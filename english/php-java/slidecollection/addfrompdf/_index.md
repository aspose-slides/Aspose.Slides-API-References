---
title: addFromPdf
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 100
url: /php-java/slidecollection/addfrompdf/
---

## addFromPdf(String path)  method

 Creates slides from the PDF document and adds them to the end of the collection.
 
Example:
 
```php
  $pres = new Presentation();
  try {
    $pres->getSlides()->addFromPdf("document.pdf");
    $pres->save("fromPdfDocument.pptx", SaveFormat::Pptx);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

### Parameters

| Name | Type | Description |
| --- | --- | --- |
| path | String | A path to the PDF document |

### Returns
[Slide](../../slide)


---


## addFromPdf(InputStream pdfStream)  method

 Creates slides from the PDF document and adds them to the end of the collection.
 
Example:
 
```php
  $pres = new Presentation();
  try {
    $stream = new FileInputStream("document.pdf");
    {
      $pres->getSlides()->addFromPdf($stream);
    }
    $pres->save("fromPdfDocument.pptx", SaveFormat::Pptx);
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
| pdfStream | InputStream | A stream which will be used as a source of the PDF document |

### Returns
[Slide](../../slide)


---


