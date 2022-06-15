---
title: toPdf
type: docs
weight: 30
url: /php-java/convert/topdf/
---

# toPdf(java.lang.String, java.lang.String) method

 Converts  Presentation to PDF.
 

 
```php
  Convert->toPdf("pres.pptx", "pres.pdf");
```

##  Parameters

| name | description |
| --- | --- |
| presPath | Path of the input presentation |
| outPath | Output path |

##  Returns
Presentation


# toPdf(java.lang.String, java.lang.String, com.aspose.slides.IPdfOptions) method

 Converts  Presentation to PDF.
 

 
```php
  $pdfOptions = new PdfOptions();
  $pdfOptions->setCompliance(PdfCompliance.PdfUa);
  Convert->toPdf("pres.pptx", "pres.pdf", $pdfOptions);
```

##  Parameters

| name | description |
| --- | --- |
| presPath | Path of the input presentation |
| outPath | Output path |
| options | Output PDF options |

##  Returns
Presentation


# toPdf(com.aspose.slides.Presentation, java.lang.String) method

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

##  Parameters

| name | description |
| --- | --- |
| pres | Input presentation |
| outPath | Output path |

##  Returns
Presentation


# toPdf(com.aspose.slides.Presentation, java.lang.String, com.aspose.slides.IPdfOptions) method

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

##  Parameters

| name | description |
| --- | --- |
| pres | Input presentation |
| outPath | Output path |
| options | Output PDF options |

##  Returns
Presentation


