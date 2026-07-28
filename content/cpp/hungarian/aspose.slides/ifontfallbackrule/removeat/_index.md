---
title: RemoveAt()
second_title: Aspose.Slides C++ API referencia
description: Eltávolítja a FallBack betűtípust a lista megadott indexén.
type: docs
weight: 92
url: /hu/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) metódus

Eltávolítja a FallBack betűtípust a lista megadott indexén.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | A betűtípus eltávolításához használt nulla-alapú index. |
## Megjegyzések

```cpp
// Létrehoz egy szabályt, amely betűtípusok listáját tartalmazza.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Tahoma eltávolítása a listából
newRule->RemoveAt(2);
```

## Lásd még

* Osztály [IFontFallBackRule](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)