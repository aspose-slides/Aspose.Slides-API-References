---
title: get_InkEffectImages()
second_title: Aspose.Slides per l'API di Riferimento C++
description: Restituisce la collezione di immagini personalizzate utilizzate per simulare effetti visivi per i pennelli a inchiostro. Queste immagini vengono usate durante il rendering dell'inchiostro con valori specifici di InkEffectType, come Galaxy, Rainbow, ecc. Fornendo le proprie immagini, è possibile controllare l'aspetto di ciascun effetto di inchiostro.
type: docs
weight: 14
url: /it/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() metodo


Restituisce la collezione di immagini personalizzate utilizzate per simulare effetti visivi per i pennelli a inchiostro. Queste immagini vengono usate durante il rendering dell'inchiostro con valori specifici [InkEffectType](../../inkeffecttype/), come Galaxy, Rainbow, ecc. Fornendo le proprie immagini, è possibile controllare l'aspetto di ciascun effetto di inchiostro.

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## Osservazioni


Questa proprietà consente di sostituire le texture predefinite degli effetti di inchiostro con quelle definite dall'utente, operazione particolarmente utile quando le risorse predefinite sono limitate da licenze o non disponibili a runtime.

Ogni voce nel dizionario deve associare un valore [InkEffectType](../../inkeffecttype/) a un oggetto [IImage](../../../aspose.slides/iimage/) corrispondente (ad es., Bitmap, o un'interfaccia immagine **Aspose**).


```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## Vedi anche

* Enum [InkEffectType](../../inkeffecttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDictionary](../../../system.collections.generic/idictionary/)
* Classe [IImage](../../../aspose.slides/iimage/)
* Classe [Ink](../)
* Namespace [Aspose::Slides::Ink](../../)
* Libreria [Aspose.Slides](../../../)