---
title: XamlOptions
type: docs
weight: 0
url: /php-java/xamloptions/
---

# XamlOptions class

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

| name | description |
| --- | --- |
| [XamlOptions](/php-java/xamloptions/xamloptions/)() | Creates the XamlOptions instance. |

## Methods

| name | return type | description |
| --- | --- | --- |
| [getExportHiddenSlides](/php-java/xamloptions/getexporthiddenslides/)() | boolean | Determines whether hidden slides will be exported. |
| [getOutputSaver](/php-java/xamloptions/getoutputsaver/)() | IXamlOutputSaver | Represents an implementation of IOutputSaver interface. |
| [setExportHiddenSlides](/php-java/xamloptions/setexporthiddenslides/)(boolean) | void | Determines whether hidden slides will be exported. |
| [setOutputSaver](/php-java/xamloptions/setoutputsaver/)(IXamlOutputSaver) | void | Represents an implementation of IOutputSaver interface. |