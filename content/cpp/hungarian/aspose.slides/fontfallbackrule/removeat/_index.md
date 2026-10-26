---
title: RemoveAt()
second_title: Aspose.Slides C++ API referencia
description: Eltávolítja a FallBack betűtípust a lista megadott indexén.
type: docs
weight: 131
url: /hu/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) metódus

Eltávolítja a FallBack betűtípust a lista megadott indexén.

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az eltávolítandó betűtípus nullától induló indexe. |

## Megjegyzések

```cpp
// Hozzon létre egy szabályt, amely betűtípusok listáját tartalmazza.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Eltávolítja a Tahoma betűtípust a listáról.
newRule->RemoveAt(2);
```

## Lásd még

* Osztály [FontFallBackRule](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)