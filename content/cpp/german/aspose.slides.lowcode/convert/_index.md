---
title: Convert
second_title: Aspose.Slides für C++ API-Referenz
description: Stellt eine Gruppe von Methoden dar, die dazu bestimmt sind, Presentation zu konvertieren.
type: docs
weight: 27
url: /de/aspose.slides.lowcode/convert/
---
## Convert-Klasse


Stellt eine Gruppe von Methoden dar, die dazu bestimmt sind, [Presentation](../../aspose.slides/presentation/) zu konvertieren.

```cpp
class Convert
```

## Methoden

| Methode | Beschreibung |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | Konvertiert [Presentation](../../aspose.slides/presentation/) mithilfe der übergebenen Ausgabepfade-Erweiterung, um das erforderliche Exportformat zu bestimmen. |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Konvertiert die Eingabepräsentation in eine Menge von JPEG-Format-Bildern. 

 Wenn der Ausgabedateiname als \"myPath/myFilename.jpeg\" angegeben wird, wird das Ergebnis als Menge von \"myPath/myFilename_N.jpeg\"-Dateien gespeichert, wobei N die Foliennummer ist. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Konvertiert die Eingabepräsentation in eine Menge von JPEG-Format-Bildern. 

 Wenn der Ausgabedateiname als \"myPath/myFilename.jpeg\" angegeben wird, wird das Ergebnis als Menge von \"myPath/myFilename_N.jpeg\"-Dateien gespeichert, wobei N die Foliennummer ist. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Konvertiert die Eingabepräsentation in eine Menge von JPEG-Format-Bildern. 

 Wenn der Ausgabedateiname als \"myPath/myFilename.jpeg\" angegeben wird, wird das Ergebnis als Menge von \"myPath/myFilename_N.jpeg\"-Dateien gespeichert, wobei N die Foliennummer ist. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | Konvertiert [Presentation](../../aspose.slides/presentation/) nach PDF. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Konvertiert [Presentation](../../aspose.slides/presentation/) nach PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Konvertiert [Presentation](../../aspose.slides/presentation/) nach PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Konvertiert [Presentation](../../aspose.slides/presentation/) nach PDF. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Konvertiert die Eingabepräsentation in eine Menge von PNG-Format-Bildern. 

 Wenn der Ausgabedateiname als \"myPath/myFilename.png\" angegeben wird, wird das Ergebnis als Menge von \"myPath/myFilename_N.png\"-Dateien gespeichert, wobei N die Foliennummer ist. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Konvertiert die Eingabepräsentation in eine Menge von PNG-Format-Bildern. 

 Wenn der Ausgabedateiname als \"myPath/myFilename.png\" angegeben wird, wird das Ergebnis als Menge von \"myPath/myFilename_N.png\"-Dateien gespeichert, wobei N die Foliennummer ist. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Konvertiert die Eingabepräsentation in eine Menge von PNG-Format-Bildern. 

 Wenn der Ausgabedateiname als \"myPath/myFilename.png\" angegeben wird, wird das Ergebnis als Menge von \"myPath/myFilename_N.png\"-Dateien gespeichert, wobei N die Foliennummer ist. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | Konvertiert [Presentation](../../aspose.slides/presentation/) nach SVG. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | Konvertiert [Presentation](../../aspose.slides/presentation/) nach SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | Konvertiert [Presentation](../../aspose.slides/presentation/) nach SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Konvertiert [Presentation](../../aspose.slides/presentation/) nach SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Konvertiert [Presentation](../../aspose.slides/presentation/) nach SVG. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Konvertiert die Eingabepräsentation in eine Menge von TIFF-Format-Bildern. 

 Wenn der Ausgabedateiname als \"myPath/myFilename.tiff\" angegeben wird, wird das Ergebnis als Menge von \"myPath/myFilename_N.tiff\"-Dateien gespeichert, wobei N die Foliennummer ist. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | Konvertiert die Eingabepräsentation in TIFF-Format mit benutzerdefinierten Optionen. Wenn der Ausgabedateiname als \"myPath/myFilename.tiff\" angegeben wird und *multipage* **false** ist, wird das Ergebnis als Menge von \"myPath/myFilename_N.tiff\"-Dateien gespeichert, wobei N die Foliennummer ist. Andernfalls, wenn *multipage* **true** ist, wird das Ergebnis ein mehrseitiges Dokument \"myPath/myFilename.tiff\" sein. |
## Typedefs

| Typedef | Beschreibung |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | Callback, der für jedes [Slide](../../aspose.slides/slide/) aufgerufen wird, wobei der Ausgabepfad zurückgegeben werden soll. |
## Anmerkungen



```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## Siehe auch

* Namespace [Aspose::Slides::LowCode](../)
* Library [Aspose.Slides](../../)