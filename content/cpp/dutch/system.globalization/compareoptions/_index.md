---
title: CompareOptions
second_title: Aspose.Slides voor C++ API-referentie
description: Opties voor tekenreeksvergelijking.
type: docs
weight: 430
url: /nl/system.globalization/compareoptions/
---
## CompareOptions enum


[String](../../system/string/) vergelijkingsopties.

```cpp
enum class CompareOptions : int32_t
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| None | 0 | Geen speciale opties. |
| IgnoreCase | 1 | Negeer hoofdlettergebruik. |
| IgnoreNonSpace | 2 | Negeer niet-ruimte samengevoegde tekens, bijv. diakritische tekens. |
| IgnoreSymbols | 4 | Inclusief witruimtes, leestekens enzovoort. |
| IgnoreKanaType | 8 | Negeer kana-type (Japans). |
| IgnoreWidth | 16 | Negeer tekenbreedte bij het vergelijken van strings. |
| OrdinalIgnoreCase | 268435456 | Ordinale vergelijking waarbij hoofdletterverschil wordt genegeerd. |
| StringSort | 536870912 | Gebruik het string-sorteeralgoritme om tekens te vergelijken. |
| Ordinal | 1073741824 | Vergelijk UTF-codes direct voor de eerste vergelijking. |

## Zie ook

* Naamruimte [System::Globalization](../)
* Bibliotheek [Aspose.Slides](../../)