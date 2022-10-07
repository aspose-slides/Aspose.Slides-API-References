---
title: getAccessPermissions
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 20
url: /php-java/pdfoptions/getaccesspermissions/
---

## getAccessPermissions()  method

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
int


---


