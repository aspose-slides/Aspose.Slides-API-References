---
title: FontFallBackRule()
second_title: Aspose.Slides C++ API Referencia
description: Új példányt hoz létre.
type: docs
weight: 66
url: /hu/aspose.slides/fontfallbackrule/fontfallbackrule/
---
## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::String) konstruktor

Új példányt hoz létre.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::String fontNames)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | **uint32_t** | Az unicode-tartomány kezdőindexe |
| endIndex | **uint32_t** | Az unicode-tartomány befejezőindexe |
| fontNames | [System::String](../../../system/string/) | Betűtípus neve vagy nevei (vesszővel elválasztva) a FallBackhez |

## Megjegyzések

```cpp
// Új példányt hoz létre a FantFallBackRule-ból egy betűtípussal.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
// Új példányt hoz létre a FantFallBackRule-ból több betűtípussal.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma");
```

## FontFallBackRule::FontFallBackRule(uint32_t, uint32_t, System::ArrayPtr\<System::String\>) konstruktor

Új példányt hoz létre.

```cpp
Aspose::Slides::FontFallBackRule::FontFallBackRule(uint32_t startIndex, uint32_t endIndex, System::ArrayPtr<System::String> fontNames)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | **uint32_t** | Az unicode-tartomány kezdőindexe |
| endIndex | **uint32_t** | Az unicode-tartomány befejezőindexe |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Betűtípus neve vagy nevei (vesszővel elválasztva) a FallBackhez |

## Megjegyzések

```cpp
// Új példányt hoz létre a FantFallBackRule-ral két betűtípussal
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Mincho", u"MS Gothic"}));
// Új példányt hoz létre a FantFallBackRule-ral több betűtípussal.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Osztály [String](../../../system/string/)
* Osztály [FontFallBackRule](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)