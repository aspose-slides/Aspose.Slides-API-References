---
title: ToArray()
second_title: Aspose.Slides för C++ API-referens
description: Skapar och returnerar en array med alla FallBack-typsnitt för denna regel.
type: docs
weight: 144
url: /sv/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() metod

Skapar och returnerar en array med alla FallBack-typsnitt för den här regeln.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```

### Returnvärde

Array av [System::String](../../../system/string/)
## Anmärkningar

```cpp
// Skapa en regel som innehåller en lista med typsnitt.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Hämta alla typsnittsnamn som en array.
ArrayPtr<String> fontNames = newRule->ToArray();
```

## FontFallBackRule::ToArray(int32_t, int32_t) metod

Skapar och returnerar en array med alla FallBack-typsnitt från det angivna intervallet i listan.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | **int32_t** | Ett index för det första typsnittet att lägga till. |
| count | **int32_t** | Ett antal typsnitt att lägga till. |

### Returnvärde

Array av [System::String](../../../system/string/)
## Anmärkningar

```cpp
// Skapa en regel som innehåller en lista med typsnitt.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Hämta de två sista typsnittsnamnen som en array.
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klass [String](../../../system/string/)
* Klass [FontFallBackRule](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)