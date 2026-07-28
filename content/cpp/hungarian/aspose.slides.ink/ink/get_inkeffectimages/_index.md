---
title: get_InkEffectImages()
second_title: Aspose.Slides for C++ API referencia
description: Visszaadja az egyedi képek gyűjteményét, amelyeket a tinta ecsetek vizuális effektusainak szimulálására használnak. Ezeket a képeket a tinta megjelenítésekor konkrét InkEffectType értékekkel, például Galaxy, Rainbow stb. alkalmazzák. Saját képek megadásával szabályozhatja, hogyan jelenik meg minden egyes tintaeffektus.
type: docs
weight: 14
url: /hu/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() metódus


A toll ecsetek vizuális effektjeinek szimulálásához használt egyedi képek gyűjteményét adja vissza. Ezeket a képeket a tinta megjelenítésekor konkrét [InkEffectType](../../inkeffecttype/) értékekkel, például Galaxy, Rainbow stb. használják. Saját képek megadásával szabályozhatja, hogy egyes tintaeffektek hogyan jelenjenek meg.

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## Megjegyzések


Ez a tulajdonság lehetővé teszi az alapértelmezett tintaeffektus-textúrák felhasználó által meghatározottakkal való helyettesítését, ami különösen hasznos, ha az alapértelmezett eszközök licencelés miatt korlátozottak vagy futásidőben nem érhetők el.

A szótár minden bejegyzésének egy [InkEffectType](../../inkeffecttype/) értéket kell társítania egy megfelelő [IImage](../../../aspose.slides/iimage/) objektummal (például Bitmap, vagy egy **Aspose** képinterfészzel).


```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## Lásd még

* Enum [InkEffectType](../../inkeffecttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [IImage](../../../aspose.slides/iimage/)
* Class [Ink](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)