---
title: Convert
second_title: Aspose.Slides för C++ API-referens
description: Representerar en grupp metoder avsedda att konvertera Presentation.
type: docs
weight: 27
url: /sv/aspose.slides.lowcode/convert/
---
## Convert klass


Representerar en grupp metoder avsedda att konvertera [Presentation](../../aspose.slides/presentation/).

```cpp
class Convert
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | Konverterar [Presentation](../../aspose.slides/presentation/) med den angivna utökningen för sökväg för utdata för att bestämma det erforderliga exportformatet. |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Konverterar den inmatade presentationen till en uppsättning JPEG-formatbilder. 

 Om filnamnet för utdata anges som "myPath/myFilename.jpeg", sparas resultatet som en uppsättning filer "myPath/myFilename_N.jpeg", där N är bildens nummer. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Konverterar den inmatade presentationen till en uppsättning JPEG-formatbilder. 

 Om filnamnet för utdata anges som "myPath/myFilename.jpeg", sparas resultatet som en uppsättning filer "myPath/myFilename_N.jpeg", där N är bildens nummer. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Konverterar den inmatade presentationen till en uppsättning JPEG-formatbilder. 

 Om filnamnet för utdata anges som "myPath/myFilename.jpeg", sparas resultatet som en uppsättning filer "myPath/myFilename_N.jpeg", där N är bildens nummer. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | Konverterar [Presentation](../../aspose.slides/presentation/) till PDF. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Konverterar [Presentation](../../aspose.slides/presentation/) till PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Konverterar [Presentation](../../aspose.slides/presentation/) till PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Konverterar [Presentation](../../aspose.slides/presentation/) till PDF. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Konverterar den inmatade presentationen till en uppsättning PNG-formatbilder. 

 Om filnamnet för utdata anges som "myPath/myFilename.png", sparas resultatet som en uppsättning filer "myPath/myFilename_N.png", där N är bildens nummer. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Konverterar den inmatade presentationen till en uppsättning PNG-formatbilder. 

 Om filnamnet för utdata anges som "myPath/myFilename.png", sparas resultatet som en uppsättning filer "myPath/myFilename_N.png", där N är bildens nummer. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Konverterar den inmatade presentationen till en uppsättning PNG-formatbilder. 

 Om filnamnet för utdata anges som "myPath/myFilename.png", sparas resultatet som en uppsättning filer "myPath/myFilename_N.png", där N är bildens nummer. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | Konverterar [Presentation](../../aspose.slides/presentation/) till SVG. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | Konverterar [Presentation](../../aspose.slides/presentation/) till SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | Konverterar [Presentation](../../aspose.slides/presentation/) till SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Konverterar [Presentation](../../aspose.slides/presentation/) till SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Konverterar [Presentation](../../aspose.slides/presentation/) till SVG. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Konverterar den inmatade presentationen till en uppsättning TIFF-formatbilder. 

 Om filnamnet för utdata anges som "myPath/myFilename.tiff", sparas resultatet som en uppsättning filer "myPath/myFilename_N.tiff", där N är bildens nummer. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | Konverterar den inmatade presentationen till TIFF-format med anpassade alternativ. Om filnamnet för utdata anges som "myPath/myFilename.tiff" och *multipage* är **false**, sparas resultatet som en uppsättning filer "myPath/myFilename_N.tiff", där N är bildens nummer. Annars, om *multipage* är **true**, blir resultatet ett flersidigt dokument "myPath/myFilename.tiff". |

## Typdefinitioner

| Typdef | Beskrivning |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | Callback som kommer att anropas för varje [Slide](../../aspose.slides/slide/), den förväntade utdata-sökvägen ska returneras. |

## Anmärkningar



```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## Se även

* Namnrymd [Aspose::Slides::LowCode](../)
* Bibliotek [Aspose.Slides](../../)