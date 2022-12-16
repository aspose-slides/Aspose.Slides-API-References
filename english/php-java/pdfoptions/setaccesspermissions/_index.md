---
title: setAccessPermissions
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 180
url: /php-java/pdfoptions/setaccesspermissions/
---

## setAccessPermissions(int value)  method

 Contains a set of flags specifying which access permissions should be granted when the document is opened
 with user access. See  PdfAccessPermissions.
 

 
```php
  $pdfOptions = new PdfOptions();
  $pdfOptions->setPassword("my_password");
  $pdfOptions->setAccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
  $presentation = new Presentation();
  try {
    $presentation->save($pdfFilePath, SaveFormat.Pdf, $pdfOptions);
  } finally {
    if ($presentation != null) {
      $presentation->dispose();
    }
  }
```

### Returns
void


---


