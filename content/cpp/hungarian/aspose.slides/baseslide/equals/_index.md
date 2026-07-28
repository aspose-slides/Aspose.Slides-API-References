---
title: Equals()
second_title: Aspose.Slides a C++ API referencia
description: Megállapítja, hogy a két IBaseSlide példány egyenlő-e. A visszatérési érték a dia szerkezete és a statikus tartalom alapján kerül kiszámításra. Két dia akkor egyenlő, ha az összes alakzat, stílus, szöveg, animáció és egyéb beállítás, stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t és a dinamikus tartalmat, például az aktuális dátum értékét a Date Placeholder-ben.
type: docs
weight: 170
url: /hu/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) metódus

Megállapítja, hogy a két [IBaseSlide](../../ibaseslide/) példány egyenlő-e. A visszatérési érték a dia szerkezete és statikus tartalma alapján kerül kiszámításra. Két dia akkor egyenlő, ha az összes alakzat, stílus, szöveg, animáció és egyéb beállítás, stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t és a dinamikus tartalmat, például az aktuális dátumértéket a Date [Placeholder](../../placeholder/)-ben.

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | A [IBaseSlide](../../ibaseslide/) a jelenlegi [IBaseSlide](../../ibaseslide/)-val összehasonlítandó. |

### Visszatérési érték

**true** ha a megadott [IBaseSlide](../../ibaseslide/) egyenlő a jelenlegi [IBaseSlide](../../ibaseslide/)-val; egyébként **false**.

## Megjegyzések

A következő példa bemutatja, hogyan lehet összehasonlítani két diát. 
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

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IBaseSlide](../../ibaseslide/)
* Osztály [BaseSlide](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)