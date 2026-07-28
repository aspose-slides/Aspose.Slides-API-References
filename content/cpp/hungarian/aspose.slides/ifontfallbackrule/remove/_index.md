---
title: Remove()
second_title: Aspose.Slides C++ API referencia
description: Eltávolítja egy adott FallBack betűtípus első előfordulását a listából.
type: docs
weight: 79
url: /hu/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) metódus


Eltávolítja egy adott FallBack betűtípus első előfordulását a listából.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | A betűtípus neve, amelyet el kell távolítani a listából. |
## Megjegyzések



```cpp
// Létrehoz egy szabályt, amely betűkészlet-listát tartalmaz.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Tahoma eltávolítása a listáról
newRule->Remove(u"Tahoma");
```


## Lásd még

* Osztály [String](../../../system/string/)
* Osztály [IFontFallBackRule](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)