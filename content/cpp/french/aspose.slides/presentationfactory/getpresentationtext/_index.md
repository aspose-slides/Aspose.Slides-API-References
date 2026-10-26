---
title: GetPresentationText()
second_title: Aspose.Slides pour C++ Référence d'API
description: Récupère le texte brut des diapositives
type: docs
weight: 53
url: /fr/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) méthode

Récupère le texte brut des diapositives

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Fichier d'entrée |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Mode d'extraction |

### Valeur de retour

L'instance de [PresentationText](../../presentationtext/) contenant le tableau SlideText représentant le texte brut des diapositives

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) méthode

Récupère le texte brut des diapositives

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux d'entrée |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Mode d'extraction |

### Valeur de retour

L'instance de [PresentationText](../../presentationtext/) contenant le tableau SlideText représentant le texte brut des diapositives

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) méthode

Récupère le texte brut des diapositives

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux d'entrée |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Mode d'extraction |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Options de chargement |

### Valeur de retour

L'instance de [PresentationText](../../presentationtext/) contenant le tableau SlideText représentant le texte brut des diapositives

## Voir aussi

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPresentationText](../../ipresentationtext/)
* Classe [String](../../../system/string/)
* Classe [PresentationFactory](../)
* Classe [Stream](../../../system.io/stream/)
* Classe [ILoadOptions](../../iloadoptions/)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)