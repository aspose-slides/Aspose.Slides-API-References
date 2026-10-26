---
title: IndexOf()
second_title: Aspose.Slides C++ API referencia
description: Visszaadja a megadott szabály indexét a gyűjteményben.
type: docs
weight: 157
url: /hu/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) metódus


Visszaadja a megadott szabály indexét a gyűjteményben.

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | A keresendő betűtípus neve. |

### Visszatérési érték

A betűtípus indexe, vagy -1, ha a betűtípus nem található a listában.
## Megjegyzések



```cpp
// Létrehoz egy szabályt, amely betűkészlet-listát tartalmaz.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Lekéri a Tahoma indexét.
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [FontFallBackRule](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)