---
title: ToPng()
second_title: Référence API Aspose.Slides pour C++
description: Convertit la présentation d'entrée en un ensemble d'images au format PNG.  Si le nom du fichier de sortie est donné sous la forme \"myPath/myFilename.png\", le résultat sera enregistré sous forme d'ensemble de fichiers \"myPath/myFilename_N.png\", où N est le numéro d'une diapositive.
type: docs
weight: 53
url: /fr/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) méthode

Convertit la présentation d’entrée en un ensemble d’images au format PNG.  

Si le nom du fichier de sortie est fourni sous la forme « myPath/myFilename.png », le résultat sera enregistré sous forme d’ensemble de fichiers « myPath/myFilename_N.png », où N est le numéro de la diapositive.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La présentation d’entrée. |
| outputFileName | [System::String](../../../system/string/) | Le nom du fichier de sortie. |
## Remarques

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) méthode

Convertit la présentation d’entrée en un ensemble d’images au format PNG.  

Si le nom du fichier de sortie est fourni sous la forme « myPath/myFilename.png », le résultat sera enregistré sous forme d’ensemble de fichiers « myPath/myFilename_N.png », où N est le numéro de la diapositive.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La présentation d’entrée |
| outputFileName | [System::String](../../../system/string/) | Le nom du fichier de sortie. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | La taille de chaque image générée. |
## Remarques

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) méthode

Convertit la présentation d’entrée en un ensemble d’images au format PNG.  

Si le nom du fichier de sortie est fourni sous la forme « myPath/myFilename.png », le résultat sera enregistré sous forme d’ensemble de fichiers « myPath/myFilename_N.png », où N est le numéro de la diapositive.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La présentation d’entrée. |
| outputFileName | [System::String](../../../system/string/) | Le nom du fichier de sortie. |
| scale | **float** | Le facteur d’échelle appliqué aux images de sortie par rapport à la taille originale de la diapositive. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Les options de rendu. |
## Remarques

```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [String](../../../system/string/)
* Classe [Convert](../)
* Classe [Size](../../../system.drawing/size/)
* Classe [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Espace de noms [Aspose::Slides::LowCode](../../)
* Bibliothèque [Aspose.Slides](../../../)