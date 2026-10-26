---
title: ToArray()
second_title: Aspose.Slides for C++ API referencia
description: Létrehozza és visszaadja a tömböt az összes FallBack betűtípussal ehhez a szabályhoz.
type: docs
weight: 105
url: /hu/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() metódus

Létrehozza és visszaadja a tömböt az összes FallBack betűtípussal ehhez a szabályhoz.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```

### Visszatérési érték

A [System::String](../../../system/string/) tömbje

## Megjegyzések

```cpp
// Létrehoz egy szabályt, amely betűtípusok listáját tartalmaz.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Lekéri az összes betűtípus-nevet tömbként
ArrayPtr<String> fontNames = newRule->ToArray();
```

## IFontFallBackRule::ToArray(int32_t, int32_t) metódus

Létrehozza és visszaadja a tömböt az összes FallBack betűtípussal a listában megadott tartományból.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | **int32_t** | Az első hozzáadandó betűtípus indexe. |
| count | **int32_t** | A hozzáadandó betűtípusok száma. |

### Visszatérési érték

A [System::String](../../../system/string/) tömbje

## Megjegyzések

```cpp
// Létrehoz egy szabályt, amely betűtípusok listáját tartalmaz.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Lekéri az utolsó két betűtípus-nevet tömbként
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [IFontFallBackRule](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)