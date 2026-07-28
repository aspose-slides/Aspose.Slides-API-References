---
title: Remove()
second_title: Aspose.Slides C++ API Referencia
description: Eltávolítja a listából egy adott FallBack betűtípus első előfordulását.
type: docs
weight: 118
url: /hu/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) metódus


Eltávolítja a listából egy adott FallBack betűtípus első előfordulását.

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | A betűtípus neve, amelyet el kell távolítani a listából. |
## Megjegyzések



```cpp
// Létrehoz egy szabályt, amely betűkészleteket tartalmaz.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Eltávolítja a Tahoma betűtípust a listáról.
newRule->Remove(u"Tahoma");
```


## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [FontFallBackRule](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)