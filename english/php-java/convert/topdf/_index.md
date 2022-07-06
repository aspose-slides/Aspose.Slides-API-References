---
title: toPdf
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 30
url: /php-java/convert/topdf/
---

## toPdf(String presPath, String outPath)  method

 Converts  Presentation to PDF.
 

 
```php
  Convert->toPdf("pres.pptx", "pres.pdf");
```

### Parameters

| Name | Description |
| --- | --- |
| presPath | Path of the input presentation |
| outPath | Output path |

### Returns
Presentation


---


## toPdf(String presPath, String outPath, [../../PdfOptions]PdfOptions options)  method

 Converts  Presentation to PDF.
 

 
```php
  $pdfOptions = new PdfOptions();
  $pdfOptions->setCompliance(PdfCompliance.PdfUa);
  Convert->toPdf("pres.pptx", "pres.pdf", $pdfOptions);
```

### Parameters

| Name | Description |
| --- | --- |
| presPath | Path of the input presentation |
| outPath | Output path |
| options | Output PDF options |

### Returns
Presentation


---


## toPdf([../../Presentation]Presentation pres, String outPath)  method

 Converts  Presentation to PDF.
 

 
```php
  $pres = new Presentation("input.pptx");
  try {
    Convert->toPdf($pres, "output.pdf");
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
| outPath | Output path |

### Returns
Presentation


---


## toPdf([../../Presentation]Presentation pres, String outPath, [../../PdfOptions]PdfOptions options)  method

 Converts  Presentation to PDF.
 

 
```php
  $pres = new Presentation("input.pptx");
  try {
    $pdfOptions = new PdfOptions();
    $pdfOptions->setCompliance(PdfCompliance.PdfUa);
    Convert->toPdf($pres, "output.pdf", $pdfOptions);
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
| outPath | Output path |
| options | Output PDF options |

### Returns
Presentation


---


