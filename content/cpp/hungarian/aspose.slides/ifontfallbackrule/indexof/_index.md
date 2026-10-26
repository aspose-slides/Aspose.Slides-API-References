---
title: IndexOf()
second_title: Aspose.Slides C++ API referenciája
description: Visszaadja a megadott szabály indexét a gyűjteményben.
type: docs
weight: 118
url: /hu/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) metódus

Visszaadja a megadott szabály indexét a gyűjteményben.

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | A megtalálandó betűkészlet neve. |

### Visszatérési érték

A betűkészlet indexe, vagy -1, ha a betűkészlet nincs a listában.

## Megjegyzések

```cpp
// Hozzon létre egy szabályt, amely betűkészletek listáját tartalmazza.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Lekérdezi a Tahoma indexét
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```

## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [IFontFallBackRule](../)
* Névtere [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)