---
title: ToArray()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een array met alle fallback-lettertypen voor deze regel en retourneert deze.
type: docs
weight: 105
url: /nl/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() methode

Maakt een array met alle fallback-lettertypen voor deze regel en retourneert deze.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```

### Retourwaarde

Array van [System::String](../../../system/string/)
## Opmerkingen

```cpp
// Maak een regel die een lijst met lettertypen bevat.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Haal alle lettertypenamen op als array
ArrayPtr<String> fontNames = newRule->ToArray();
```

## IFontFallBackRule::ToArray(int32_t, int32_t) methode

Maakt een array met alle fallback-lettertypen uit het opgegeven bereik in de lijst en retourneert deze.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | **int32_t** | Een index van het eerste lettertype om toe te voegen. |
| count | **int32_t** | Een aantal lettertypen om toe te voegen. |

### Retourwaarde

Array van [System::String](../../../system/string/)
## Opmerkingen

```cpp
// Maak een regel die een lijst met lettertypen bevat.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Haal de laatste twee lettertypenamen op als array
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [IFontFallBackRule](../)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)