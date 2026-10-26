---
title: Convert
second_title: Aspose.Slides for C++ API-referentie
description: Representeert een groep methoden die bedoeld zijn om Presentation te converteren.
type: docs
weight: 27
url: /nl/aspose.slides.lowcode/convert/
---
## Convert klasse

Representeert een groep methoden die bedoeld zijn om [Presentation](../../aspose.slides/presentation/) te converteren.

```cpp
class Convert
```

## Methoden

| Methode | Beschrijving |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | Converteert [Presentation](../../aspose.slides/presentation/) met behulp van de opgegeven extensie van het uitvoerpad om het vereiste exportformaat te bepalen. |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Converteert de invoerpresentatie naar een reeks JPEG-formaatafbeeldingen. 

 Als de uitvoerbestandsnaam is opgegeven als \"myPath/myFilename.jpeg\", wordt het resultaat opgeslagen als een reeks \"myPath/myFilename_N.jpeg\" bestanden, waarbij N een dia-nummer is. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Converteert de invoerpresentatie naar een reeks JPEG-formaatafbeeldingen. 

 Als de uitvoerbestandsnaam is opgegeven als \"myPath/myFilename.jpeg\", wordt het resultaat opgeslagen als een reeks \"myPath/myFilename_N.jpeg\" bestanden, waarbij N een dia-nummer is. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Converteert de invoerpresentatie naar een reeks JPEG-formaatafbeeldingen. 

 Als de uitvoerbestandsnaam is opgegeven als \"myPath/myFilename.jpeg\", wordt het resultaat opgeslagen als een reeks \"myPath/myFilename_N.jpeg\" bestanden, waarbij N een dia-nummer is. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | Converteert [Presentation](../../aspose.slides/presentation/) naar PDF. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Converteert [Presentation](../../aspose.slides/presentation/) naar PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Converteert [Presentation](../../aspose.slides/presentation/) naar PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Converteert [Presentation](../../aspose.slides/presentation/) naar PDF. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Converteert de invoerpresentatie naar een reeks PNG-formaatafbeeldingen. 

 Als de uitvoerbestandsnaam is opgegeven als \"myPath/myFilename.png\", wordt het resultaat opgeslagen als een reeks \"myPath/myFilename_N.png\" bestanden, waarbij N een dia-nummer is. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Converteert de invoerpresentatie naar een reeks PNG-formaatafbeeldingen. 

 Als de uitvoerbestandsnaam is opgegeven als \"myPath/myFilename.png\", wordt het resultaat opgeslagen als een reeks \"myPath/myFilename_N.png\" bestanden, waarbij N een dia-nummer is. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Converteert de invoerpresentatie naar een reeks PNG-formaatafbeeldingen. 

 Als de uitvoerbestandsnaam is opgegeven als \"myPath/myFilename.png\", wordt het resultaat opgeslagen als een reeks \"myPath/myFilename_N.png\" bestanden, waarbij N een dia-nummer is. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | Converteert [Presentation](../../aspose.slides/presentation/) naar SVG. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | Converteert [Presentation](../../aspose.slides/presentation/) naar SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | Converteert [Presentation](../../aspose.slides/presentation/) naar SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Converteert [Presentation](../../aspose.slides/presentation/) naar SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Converteert [Presentation](../../aspose.slides/presentation/) naar SVG. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Converteert de invoerpresentatie naar een reeks TIFF-formaatafbeeldingen. 

 Als de uitvoerbestandsnaam is opgegeven als \"myPath/myFilename.tiff\", wordt het resultaat opgeslagen als een reeks \"myPath/myFilename_N.tiff\" bestanden, waarbij N een dia-nummer is. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | Converteert de invoerpresentatie naar TIFF-formaat met aangepaste opties. Als de uitvoerbestandsnaam is opgegeven als \"myPath/myFilename.tiff\" en *multipage*  is **false**, wordt het resultaat opgeslagen als een reeks \"myPath/myFilename_N.tiff\" bestanden, waarbij N een dia-nummer is. Anders, als *multipage*  **true** is, wordt het resultaat een meer-pagina \"myPath/myFilename.tiff\" document. |

## Typedefs

| Typedef | Beschrijving |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | Callback die wordt aangeroepen voor elke [Slide](../../aspose.slides/slide/), waarbij het uitvoerpad moet worden geretourneerd. |

## Opmerkingen



```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## Zie ook

* Namespace [Aspose::Slides::LowCode](../)
* Library [Aspose.Slides](../../)