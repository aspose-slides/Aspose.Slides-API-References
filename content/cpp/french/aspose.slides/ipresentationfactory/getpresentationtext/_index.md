---
title: GetPresentationText()
second_title: Référence API Aspose.Slides pour C++
description: Récupère le texte brut des diapositives
type: docs
weight: 40
url: /fr/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) méthode

Récupère le texte brut des diapositives

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Fichier d'entrée |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Mode d'extraction |

### Valeur de retour

L'instance de [PresentationText](../../presentationtext/) contenant le tableau SlideText représentant le texte brut des diapositives

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) méthode

Récupère le texte brut des diapositives

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```

### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Flux d'entrée |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Mode d'extraction |

### Valeur de retour

L'instance de [PresentationText](../../presentationtext/) contenant le tableau SlideText représentant le texte brut des diapositives

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) méthode

Récupère le texte brut des diapositives

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```

### Paramètres

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
* Class [IPresentationText](../../ipresentationtext/)
* Class [String](../../../system/string/)
* Class [IPresentationFactory](../)
* Class [Stream](../../../system.io/stream/)
* Class [ILoadOptions](../../iloadoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)