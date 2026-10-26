---
title: Equals()
second_title: Aspose.Slides C++ API Referenciája
description: Megállapítja, hogy a két IBaseSlide példány egyenlő-e. A visszatérési érték a dia szerkezete és statikus tartalma alapján kerül kiszámításra. Két dia akkor egyenlő, ha minden alakzat, stílus, szöveg, animáció és egyéb beállítás, stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t, és a dinamikus tartalmat, például a Dátumhelyőrzőben szereplő aktuális dátum értékét.
type: docs
weight: 183
url: /hu/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) metódus

Megállapítja, hogy a két [IBaseSlide](../) példány egyenlő-e. A visszatérési érték a dia struktúrája és statikus tartalma alapján kerül kiszámításra. Két dia akkor egyenlő, ha az összes alakzat, stílus, szöveg, animáció és egyéb beállítás stb. egyenlő. Az összehasonlítás nem veszi figyelembe az egyedi azonosító értékeket, például a SlideId-t, és a dinamikus tartalmat, például a dátum [Placeholder](../../placeholder/) aktuális értékét.

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | A [IBaseSlide](../) a jelenlegi [IBaseSlide](../)-val való összehasonlításhoz. |

### Visszatérési érték

**true** ha a megadott [IBaseSlide](../) egyenlő a jelenlegi [IBaseSlide](../)-val; egyébként **false**.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IBaseSlide](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)