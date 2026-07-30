---
title: get_InkEffectImages()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Získá kolekci vlastních obrázků používaných k simulaci vizuálních efektů pro inkové štětce. Tyto obrázky se používají při vykreslování ink pomocí konkrétních hodnot InkEffectType, jako jsou Galaxy, Rainbow atd. Poskytnutím vlastních obrázků můžete ovládat, jak se každý inkový efekt zobrazí.
type: docs
weight: 14
url: /cs/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() metoda

Získá kolekci vlastních obrázků používaných k simulaci vizuálních efektů pro inkové štětce. Tyto obrázky se používají při vykreslování inku s konkrétními hodnotami [InkEffectType](../../inkeffecttype/), jako je Galaxy, Rainbow atd. Poskytnutím vlastních obrázků můžete ovládat, jak se každý inkový efekt zobrazuje.

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## Poznámky

Tato vlastnost umožňuje nahradit výchozí textury inkových efektů uživatelem definovanými, což je zvláště užitečné, když jsou výchozí prostředky omezeny licencí nebo nejsou za běhu dostupné.

Každý záznam ve slovníku musí přiřadit hodnotu [InkEffectType](../../inkeffecttype/) k odpovídajícímu objektu [IImage](../../../aspose.slides/iimage/) (např. Bitmap nebo **Aspose** rozhraní obrázku).

```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## Viz také

* Výčet [InkEffectType](../../inkeffecttype/)
* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [IDictionary](../../../system.collections.generic/idictionary/)
* Třída [IImage](../../../aspose.slides/iimage/)
* Třída [Ink](../)
* Jmenný prostor [Aspose::Slides::Ink](../../)
* Knihovna [Aspose.Slides](../../../)