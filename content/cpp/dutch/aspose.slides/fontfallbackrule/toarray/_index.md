---
title: ToArray()
second_title: Aspose.Slides voor C++ API-referentie
description: Creëert en retourneert een array met alle FallBack-lettertypen voor deze regel.
type: docs
weight: 144
url: /nl/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() methode


Creëert en retourneert een array met alle FallBack-lettertypen voor deze regel.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```


### Return Value

Array van [System::String](../../../system/string/)
## Opmerkingen



```cpp
// Maak een regel die een lijst met lettertypen bevat.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Haal alle lettertypen op als array.
ArrayPtr<String> fontNames = newRule->ToArray();
```


## FontFallBackRule::ToArray(int32_t, int32_t) methode


Creëert en retourneert een array met alle FallBack-lettertypen uit het opgegeven bereik in de lijst.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
```


### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | **int32_t** | Een index van het eerste lettertype om toe te voegen. |
| count | **int32_t** | Een aantal lettertypen om toe te voegen. |

### Return Value

Array van [System::String](../../../system/string/)
## Opmerkingen



```cpp
// Maak een regel die een lijst met lettertypen bevat.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Haal de laatste twee lettertypen op als array.
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [FontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)