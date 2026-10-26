---
title: ToTiff()
second_title: Référence de l'API Aspose.Slides pour C++
description: Convertit la présentation d’entrée en un ensemble d’images au format TIFF. Si le nom du fichier de sortie est fourni sous la forme \"myPath/myFilename.tiff\", le résultat sera enregistré sous forme d’un ensemble de fichiers \"myPath/myFilename_N.tiff\", où N correspond au numéro de la diapositive.
type: docs
weight: 66
url: /fr/aspose.slides.lowcode/convert/totiff/
---
## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String) method

Convertit la présentation d’entrée en un ensemble d’images au format TIFF.  

Si le nom du fichier de sortie est fourni sous la forme "myPath/myFilename.tiff", le résultat sera enregistré sous forme d’un ensemble de fichiers "myPath/myFilename_N.tiff", où N correspond au numéro de la diapositive.

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La présentation d’entrée. |
| outputFileName | [System::String](../../../system/string/) | Le nom du fichier de sortie. |
## Remarques




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"presImage.tiff");
```

## Convert::ToTiff(System::SharedPtr\<Presentation\>, System::String, System::SharedPtr\<Aspose::Slides::Export::ITiffOptions\>, bool) method

Convertit la présentation d’entrée en format TIFF avec des options personnalisées. Si le nom du fichier de sortie est fourni sous la forme "myPath/myFilename.tiff" et que *multipage* est **false**, le résultat sera enregistré sous forme d’un ensemble de fichiers "myPath/myFilename_N.tiff", où N correspond au numéro de la diapositive. Sinon, si *multipage* est **true**, le résultat sera un document multi-pages "myPath/myFilename.tiff".

```cpp
static void Aspose::Slides::LowCode::Convert::ToTiff(System::SharedPtr<Presentation> pres, System::String outputFileName, System::SharedPtr<Aspose::Slides::Export::ITiffOptions> options, bool multipage)
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | La présentation d’entrée. |
| outputFileName | [System::String](../../../system/string/) | Le nom du fichier de sortie. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Les options de sauvegarde TIFF. |
| multipage | **bool** | Indique si le document TIFF généré doit être multi-page. |
## Remarques




```cpp
System::SharedPtr<ITiffOptions> options = System::MakeObject<TiffOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);
options->set_CompressionType(TiffCompressionTypes::CCITT3);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToTiff(pres, u"pres.tiff", options, false);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [Presentation](../../../aspose.slides/presentation/)
* Classe [String](../../../system/string/)
* Classe [Convert](../)
* Classe [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Espace de noms [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)