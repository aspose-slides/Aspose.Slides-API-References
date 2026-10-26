---
title: get_InkEffectImages()
second_title: Aspose.Slides voor C++ API-referentie
description: Haalt de collectie aangepaste afbeeldingen op die worden gebruikt om visuele effecten voor inktpennen te simuleren. Deze afbeeldingen worden gebruikt bij het renderen van inkt met specifieke InkEffectType waarden, zoals Galaxy, Rainbow, enz. Door uw eigen afbeeldingen te leveren, kunt u bepalen hoe elk inkt effect wordt weergegeven.
type: docs
weight: 14
url: /nl/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() methode

Haalt de collectie aangepaste afbeeldingen op die worden gebruikt om visuele effecten voor inktpennen te simuleren. Deze afbeeldingen worden gebruikt bij het renderen van inkt met specifieke [InkEffectType](../../inkeffecttype/) waarden, zoals Galaxy, Rainbow, enz. Door uw eigen afbeeldingen te leveren, kunt u bepalen hoe elk inkt effect wordt weergegeven.

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## Opmerkingen

Deze eigenschap maakt het mogelijk de standaard inkt-effecttexturen te vervangen door door gebruikers gedefinieerde, wat vooral nuttig is wanneer standaardactiva beperkt zijn door licenties of niet beschikbaar zijn tijdens runtime.

Elk item in de woordenboek moet een [InkEffectType](../../inkeffecttype/) waarde koppelen aan een overeenkomstig [IImage](../../../aspose.slides/iimage/) object (bijv. Bitmap, of een **Aspose** afbeeldinginterface).

```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## Zie ook

* Enum [InkEffectType](../../inkeffecttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [IImage](../../../aspose.slides/iimage/)
* Class [Ink](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)