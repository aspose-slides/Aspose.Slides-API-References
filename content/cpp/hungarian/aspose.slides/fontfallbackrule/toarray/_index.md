---
title: ToArray()
second_title: Aspose.Slides for C++ API Referencia
description: Létrehozza és visszaad egy tömböt az összes FallBack betűtípussal ehhez a szabályhoz.
type: docs
weight: 144
url: /hu/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() metódus

Létrehozza és visszaadja az összes FallBack betűtípus tömbjét ehhez a szabályhoz.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```

### Visszatérési érték

Tömb [System::String](../../../system/string/)
## Megjegyzések



```cpp
// Létrehoz egy szabályt, amely betűkészlet-listát tartalmaz.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Az összes betűtípus nevet tömbként kapja meg.
ArrayPtr<String> fontNames = newRule->ToArray();
```

## FontFallBackRule::ToArray(int32_t, int32_t) metódus

Létrehozza és visszaadja az adott tartományban a listából származó összes FallBack betűtípus tömbjét.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | **int32_t** | Az első hozzáadandó betűtípus indexe. |
| count | **int32_t** | A hozzáadandó betűtípusok száma. |

### Visszatérési érték

Tömb [System::String](../../../system/string/)
## Megjegyzések



```cpp
// Létrehoz egy szabályt, amely betűkészlet-listát tartalmaz.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Az utolsó két betűtípus nevet tömbként kapja meg.
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [FontFallBackRule](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)