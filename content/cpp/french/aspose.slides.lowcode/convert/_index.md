---
title: Convert
second_title: Référence de l'API Aspose.Slides pour C++
description: Représente un groupe de méthodes destinées à convertir Presentation.
type: docs
weight: 27
url: /fr/aspose.slides.lowcode/convert/
---
## Classe Convert


Représente un groupe de méthodes destiné à convertir [Presentation](../../aspose.slides/presentation/).

```cpp
class Convert
```

## Méthodes

| Méthode | Description |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | Convertit [Presentation](../../aspose.slides/presentation/) en utilisant l'extension du chemin de sortie fournie pour déterminer le format d'exportation requis. |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Convertit la présentation d'entrée en un ensemble d'images au format JPEG. 

 Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.jpeg", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.jpeg", où N est le numéro d'une diapositive. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Convertit la présentation d'entrée en un ensemble d'images au format JPEG. 

 Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.jpeg", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.jpeg", où N est le numéro d'une diapositive. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Convertit la présentation d'entrée en un ensemble d'images au format JPEG. 

 Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.jpeg", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.jpeg", où N est le numéro d'une diapositive. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | Convertit [Presentation](../../aspose.slides/presentation/) en PDF. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Convertit [Presentation](../../aspose.slides/presentation/) en PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Convertit [Presentation](../../aspose.slides/presentation/) en PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Convertit [Presentation](../../aspose.slides/presentation/) en PDF. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Convertit la présentation d'entrée en un ensemble d'images au format PNG. 

 Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.png", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.png", où N est le numéro d'une diapositive. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Convertit la présentation d'entrée en un ensemble d'images au format PNG. 

 Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.png", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.png", où N est le numéro d'une diapositive. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Convertit la présentation d'entrée en un ensemble d'images au format PNG. 

 Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.png", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.png", où N est le numéro d'une diapositive. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | Convertit [Presentation](../../aspose.slides/presentation/) en SVG. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | Convertit [Presentation](../../aspose.slides/presentation/) en SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | Convertit [Presentation](../../aspose.slides/presentation/) en SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Convertit [Presentation](../../aspose.slides/presentation/) en SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Convertit [Presentation](../../aspose.slides/presentation/) en SVG. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Convertit la présentation d'entrée en un ensemble d'images au format TIFF. 

 Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.tiff", le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.tiff", où N est le numéro d'une diapositive. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | Convertit la présentation d'entrée au format TIFF avec des options personnalisées. Si le nom du fichier de sortie est donné sous la forme "myPath/myFilename.tiff" et que *multipage* est **false**, le résultat sera enregistré sous forme d'un ensemble de fichiers "myPath/myFilename_N.tiff", où N est le numéro d'une diapositive. Sinon, si *multipage* est **true**, le résultat sera un document multi-pages "myPath/myFilename.tiff". |
## Types définis

| Typedef | Description |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | Rappel qui sera invoqué pour chaque [Slide](../../aspose.slides/slide/), le chemin de sortie devant être renvoyé. |
## Remarques



```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## Voir aussi

* Espace de noms [Aspose::Slides::LowCode](../)
* Bibliothèque [Aspose.Slides](../../)