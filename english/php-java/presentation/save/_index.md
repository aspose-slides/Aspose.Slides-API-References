---
title: save
second_title: Aspose.Sildes for PHP via Java API Reference
description: 
type: docs
weight: 510
url: /php-java/presentation/save/
---

## save(String fname, int format)  method

 Saves all slides of a presentation to a file with the specified format.
 

### Parameters

| Name | Description |
| --- | --- |
| fname | Path to the created file. |
| format | Format of the exported data. |


---


## save(OutputStream stream, int format)  method

 Saves all slides of a presentation to a stream in the specified format.
 

### Parameters

| Name | Description |
| --- | --- |
| stream | Output stream. |
| format | Format of the exported data. |


---


## save(String fname, int format, GifOptions options)  method
## save(String fname, int format, Html5Options options)  method
## save(String fname, int format, HtmlOptions options)  method
## save(String fname, int format, PdfOptions options)  method
## save(String fname, int format, PptOptions options)  method
## save(String fname, int format, PptxOptions options)  method
## save(String fname, int format, RenderingOptions options)  method
## save(String fname, int format, SaveOptions options)  method
## save(String fname, int format, SVGOptions options)  method
## save(String fname, int format, SwfOptions options)  method
## save(String fname, int format, TiffOptions options)  method
## save(String fname, int format, XamlOptions options)  method
## save(String fname, int format, XpsOptions options)  method

 Saves all slides of a presentation to a file with the specified format and with additional options.
 

### Parameters

| Name | Description |
| --- | --- |
| fname | Path to the created file. |
| format | Format of the exported data. |
| options | Additional format options. |


---


## save(OutputStream stream, int format, GifOptions options)  method
## save(OutputStream stream, int format, Html5Options options)  method
## save(OutputStream stream, int format, HtmlOptions options)  method
## save(OutputStream stream, int format, PdfOptions options)  method
## save(OutputStream stream, int format, PptOptions options)  method
## save(OutputStream stream, int format, PptxOptions options)  method
## save(OutputStream stream, int format, RenderingOptions options)  method
## save(OutputStream stream, int format, SaveOptions options)  method
## save(OutputStream stream, int format, SVGOptions options)  method
## save(OutputStream stream, int format, SwfOptions options)  method
## save(OutputStream stream, int format, TiffOptions options)  method
## save(OutputStream stream, int format, XamlOptions options)  method
## save(OutputStream stream, int format, XpsOptions options)  method

 Saves all slides of a presentation to a stream in the specified format and with additional options.
 

### Parameters

| Name | Description |
| --- | --- |
| stream | Output stream. |
| format | Format of the exported data. |
| options | Additional format options. |

### Exception

| Exception | Condition |
| --- | --- |
 | NotSupportedException | If you try to save encrypted file in none Office 2007-2010 format |


---


## save(XamlOptions options)  method

 Saves all slides of a presentation to a set of files representing XAML markup.
 

 
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

### Parameters

| Name | Description |
| --- | --- |
| options | The XAML format options. |


---


## save(String fname, int[] slides, int format)  method

 Saves specified slides of a presentation to a file with the specified format with page number keeping.
 

### Parameters

| Name | Description |
| --- | --- |
| fname | Path to the created file. |
| slides | Array with slide positions, starting from 1. |
| format | Format of the exported data. |

### Exception

| Exception | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


## save(String fname, int[] slides, int format, GifOptions options)  method
## save(String fname, int[] slides, int format, Html5Options options)  method
## save(String fname, int[] slides, int format, HtmlOptions options)  method
## save(String fname, int[] slides, int format, PdfOptions options)  method
## save(String fname, int[] slides, int format, PptOptions options)  method
## save(String fname, int[] slides, int format, PptxOptions options)  method
## save(String fname, int[] slides, int format, RenderingOptions options)  method
## save(String fname, int[] slides, int format, SaveOptions options)  method
## save(String fname, int[] slides, int format, SVGOptions options)  method
## save(String fname, int[] slides, int format, SwfOptions options)  method
## save(String fname, int[] slides, int format, TiffOptions options)  method
## save(String fname, int[] slides, int format, XamlOptions options)  method
## save(String fname, int[] slides, int format, XpsOptions options)  method

 Saves specified slides of a presentation to a file with the specified format with page number keeping.
 

### Parameters

| Name | Description |
| --- | --- |
| fname | Path to the created file. |
| slides | Array with slide positions, starting from 1. |
| format | Format of the exported data. |
| options | Additional format options. |


---


## save(OutputStream stream, int[] slides, int format)  method

 Saves specified slides of a presentation to a stream in the specified format with page number keeping.
 

### Parameters

| Name | Description |
| --- | --- |
| stream | Output stream. |
| slides | Array with slide positions, starting from 1. |
| format | Format of the exported data. |


---


## save(OutputStream stream, int[] slides, int format, GifOptions options)  method
## save(OutputStream stream, int[] slides, int format, Html5Options options)  method
## save(OutputStream stream, int[] slides, int format, HtmlOptions options)  method
## save(OutputStream stream, int[] slides, int format, PdfOptions options)  method
## save(OutputStream stream, int[] slides, int format, PptOptions options)  method
## save(OutputStream stream, int[] slides, int format, PptxOptions options)  method
## save(OutputStream stream, int[] slides, int format, RenderingOptions options)  method
## save(OutputStream stream, int[] slides, int format, SaveOptions options)  method
## save(OutputStream stream, int[] slides, int format, SVGOptions options)  method
## save(OutputStream stream, int[] slides, int format, SwfOptions options)  method
## save(OutputStream stream, int[] slides, int format, TiffOptions options)  method
## save(OutputStream stream, int[] slides, int format, XamlOptions options)  method
## save(OutputStream stream, int[] slides, int format, XpsOptions options)  method

 Saves specified slides of a presentation to a stream in the specified format with page number keeping.
 

### Parameters

| Name | Description |
| --- | --- |
| stream | Output stream. |
| slides | Array with slide positions, starting from 1. |
| format | Format of the exported data. |
| options | Additional format options. |

### Exception

| Exception | Condition |
| --- | --- |
 | InvalidOperationException | When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP. |


---


