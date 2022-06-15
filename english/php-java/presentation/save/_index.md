---
title: save
type: docs
weight: 510
url: /php-java/presentation/save/
---

# save(java.lang.String, int) method

 Saves all slides of a presentation to a file with the specified format.
 

##  Parameters

| name | description |
| --- | --- |
| fname | Path to the created file. |
| format | Format of the exported data. |


# save(java.io.OutputStream, int) method

 Saves all slides of a presentation to a stream in the specified format.
 

##  Parameters

| name | description |
| --- | --- |
| stream | Output stream. |
| format | Format of the exported data. |


# save(java.lang.String, int, com.aspose.slides.ISaveOptions) method

 Saves all slides of a presentation to a file with the specified format and with additional options.
 

##  Parameters

| name | description |
| --- | --- |
| fname | Path to the created file. |
| format | Format of the exported data. |
| options | Additional format options. |


# save(java.io.OutputStream, int, com.aspose.slides.ISaveOptions) method

 Saves all slides of a presentation to a stream in the specified format and with additional options.
 

##  Parameters

| name | description |
| --- | --- |
| stream | Output stream. |
| format | Format of the exported data. |
| options | Additional format options. |

##  Exception
NotSupportedException If you try to save encrypted file in none Office 2007-2010 format


# save(com.aspose.slides.IXamlOptions) method

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

##  Parameters

| name | description |
| --- | --- |
| options | The XAML format options. |


# save(java.lang.String, int[], int) method

 Saves specified slides of a presentation to a file with the specified format with page number keeping.
 

##  Parameters

| name | description |
| --- | --- |
| fname | Path to the created file. |
| slides | Array with slide positions, starting from 1. |
| format | Format of the exported data. |

##  Exception
InvalidOperationException When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP.


# save(java.lang.String, int[], int, com.aspose.slides.ISaveOptions) method

 Saves specified slides of a presentation to a file with the specified format with page number keeping.
 

##  Parameters

| name | description |
| --- | --- |
| fname | Path to the created file. |
| slides | Array with slide positions, starting from 1. |
| format | Format of the exported data. |
| options | Additional format options. |


# save(java.io.OutputStream, int[], int) method

 Saves specified slides of a presentation to a stream in the specified format with page number keeping.
 

##  Parameters

| name | description |
| --- | --- |
| stream | Output stream. |
| slides | Array with slide positions, starting from 1. |
| format | Format of the exported data. |


# save(java.io.OutputStream, int[], int, com.aspose.slides.ISaveOptions) method

 Saves specified slides of a presentation to a stream in the specified format with page number keeping.
 

##  Parameters

| name | description |
| --- | --- |
| stream | Output stream. |
| slides | Array with slide positions, starting from 1. |
| format | Format of the exported data. |
| options | Additional format options. |

##  Exception
InvalidOperationException When an unsupported SaveFormat is used, e.g. PPTX, PPTM, PPSX, PPSM, POTX, POTM, PPT, ODP.


