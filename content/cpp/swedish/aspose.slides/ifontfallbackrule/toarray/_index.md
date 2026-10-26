---
title: ToArray()
second_title: Aspose.Slides för C++ API-referens
description: Skapar och returnerar en array med alla FallBack-typsnitt för denna regel.
type: docs
weight: 105
url: /sv/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() metod

Skapar och returnerar en array med alla FallBack-typsnitt för denna regel.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```

### Returvärde

Array av [System::String](../../../system/string/)

## Anmärkningar



```cpp
// Skapa en regel som innehåller en lista med typsnitt.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Hämta alla typsnittsnamn som en array
ArrayPtr<String> fontNames = newRule->ToArray();
```

## IFontFallBackRule::ToArray(int32_t, int32_t) metod

Skapar och returnerar en array med alla FallBack-typsnitt från det angivna intervallet i listan.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| startIndex | **int32_t** | Ett index för det första typsnittet som ska läggas till. |
| count | **int32_t** | Antal typsnitt att lägga till. |

### Returvärde

Array av [System::String](../../../system/string/)

## Anmärkningar



```cpp
// Skapa en regel som innehåller en lista med typsnitt.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Hämta de två sista typsnittsnamnen som en array
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## Se även

* Typdefinition [ArrayPtr](../../../system/arrayptr/)
* Klass [String](../../../system/string/)
* Klass [IFontFallBackRule](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)