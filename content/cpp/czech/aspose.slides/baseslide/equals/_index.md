---
title: Equals()
second_title: Aspose.Slides pro C++ – referenční dokumentace API
description: Určuje, zda jsou dvě instance IBaseSlide stejné. Vrácená hodnota je vypočítána na základě struktury snímku a statického obsahu. Dva snímky jsou stejné, pokud jsou všechny tvary, styly, texty, animace a další nastavení atd. stejné. Při porovnání se neberou v úvahu jedinečné hodnoty identifikátorů, např. SlideId, a dynamický obsah, např. aktuální datum v Date Placeholder.
type: docs
weight: 170
url: /cs/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) metoda


Určuje, zda jsou dvě instance [IBaseSlide](../../ibaseslide/) stejné. Návratová hodnota je vypočítána na základě struktury snímku a statického obsahu. Dva snímky jsou stejné, pokud jsou všechny tvary, styly, texty, animace a další nastavení atd. stejné. Porovnání nebere v úvahu jedinečné hodnoty identifikátorů, např. SlideId, a dynamický obsah, např. aktuální datum v Date [Placeholder](../../placeholder/).

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | [IBaseSlide](../../ibaseslide/) k porovnání s aktuálním [IBaseSlide](../../ibaseslide/). |

### Návratová hodnota

**true** pokud je zadaný [IBaseSlide](../../ibaseslide/) roven aktuálnímu [IBaseSlide](../../ibaseslide/); jinak **false**.
## Poznámky



Následující příklad ukazuje, jak porovnat dva snímky. 
```cpp
auto presentation1 = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto presentation2 = System::MakeObject<Presentation>(u"HelloWorld.pptx");
for (int32_t i = 0; i < presentation1->get_Masters()->get_Count(); i++)
{
    auto master1 = presentation1->get_Masters()->idx_get(i);
    for (int32_t j = 0; j < presentation2->get_Masters()->get_Count(); j++)
    {
        auto master2 = presentation2->get_Masters()->idx_get(j);
        if (System::ObjectExt::Equals(master1, master2))
        {
            System::Console::WriteLine(System::String::Format(u"SomePresentation1 MasterSlide#{0} is equal to SomePresentation2 MasterSlide#{1}", i, j));
        }
    }
}
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IBaseSlide](../../ibaseslide/)
* Třída [BaseSlide](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)