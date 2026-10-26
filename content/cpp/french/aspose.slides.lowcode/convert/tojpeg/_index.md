---
title: ToJpeg()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la présentation d'entrée en un ensemble d'images au format JPEG. Si le nom du fichier de sortie est fourni sous la forme \"myPath/myFilename.jpeg\", le résultat sera enregistré sous forme d'un ensemble de fichiers \"myPath/myFilename_N.jpeg\", où N est le numéro de la diapositive.
type: docs
weight: 40
url: /fr/aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) method

Convertit la présentation d'entrée en un ensemble d'images au format JPEG.  

Si le nom du fichier de sortie est fourni sous la forme \"myPath/myFilename.jpeg\", le résultat sera enregistré sous forme d'un ensemble de fichiers \"myPath/myFilename_N.jpeg\", où N est le numéro de la diapositive.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La présentation d'entrée. |
| outputFileName | [System::String](../../../system/string/) | Le nom du fichier de sortie. |

## Remarques

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) method

Convertit la présentation d'entrée en un ensemble d'images au format JPEG.  

Si le nom du fichier de sortie est fourni sous la forme \"myPath/myFilename.jpeg\", le résultat sera enregistré sous forme d'un ensemble de fichiers \"myPath/myFilename_N.jpeg\", où N est le numéro de la diapositive.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La présentation d'entrée |
| outputFileName | [System::String](../../../system/string/) | Le nom du fichier de sortie. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | La taille de chaque image générée. |

## Remarques

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) method

Convertit la présentation d'entrée en un ensemble d'images au format JPEG.  

Si le nom du fichier de sortie est fourni sous la forme \"myPath/myFilename.jpeg\", le résultat sera enregistré sous forme d'un ensemble de fichiers \"myPath/myFilename_N.jpeg\", où N est le numéro de la diapositive.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La présentation d'entrée. |
| outputFileName | [System::String](../../../system/string/) | Le nom du fichier de sortie. |
| scale | **float** | Le facteur d'échelle appliqué aux images de sortie par rapport à la taille originale de la diapositive. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Les options de rendu. |

## Remarques

```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
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