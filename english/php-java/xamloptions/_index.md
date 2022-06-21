---
title: XamlOptions
second_title: Aspose.Sildes PHP for Java API Reference
description: 
type: docs
weight: 10
url: /php-java/xamloptions/
---

## XamlOptions class

 Options that control how a XAML document is saved.
 

 
```php
  $pres = new Presentation("pres.pptx");
  try {
    $xamlOptions = new XamlOptions();
    $xamlOptions->setExportHiddenSlides(true);
    $pres->save($xamlOptions);
  } finally {
    if ($pres != null) {
      $pres->dispose();
    }
  }
```

## Constructors

| Name | Description |
| --- | --- |
| [XamlOptions](xamloptions)() | Creates the XamlOptions instance. |

## Methods

| Name | Description |
| --- | --- |
| [getExportHiddenSlides](getexporthiddenslides)() | Determines whether hidden slides will be exported. |
| [getOutputSaver](getoutputsaver)() | Represents an implementation of IOutputSaver interface. |
| [setExportHiddenSlides](setexporthiddenslides)(boolean) | Determines whether hidden slides will be exported. |
| [setOutputSaver](setoutputsaver)(IXamlOutputSaver) | Represents an implementation of IOutputSaver interface. |
