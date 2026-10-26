---
title: RegexOptions
second_title: Aspose.Slides för C++ API-referens
description: Regex-alternativ.
type: docs
weight: 118
url: /sv/system.text.regularexpressions/regexoptions/
---
## RegexOptions enum


[Regex](../regex/) options.

```cpp
enum class RegexOptions
```

### Värden

| Namn | Värde | Beskrivning |
| --- | --- | --- |
| None | 0 | Standardbeteende. |
| Compiled | 1 | Kompilera regex för prestanda. Alltid gjort som standard. |
| CultureInvariant | 2 | Använd kultursoberoende matchning. Ignoreras. |
| ECMAScript | 4 | Använd ECMAScript-syntax. Ignoreras. |
| ExplicitCapture | 8 | Endast explicit fångst. Ignoreras. |
| IgnoreCase | 16 | Ignorera skiftläge vid matchning. |
| IgnorePatternWhitespace | 32 | Ignorera mellanslag i mönster. Stöds ej. |
| Multiline | 64 | Behandla '^' och '$' som början och slut på rad, inte hela strängen. |
| RightToLeft | 128 | Höger-till-vänster matchning. Stöds ej. |
| Singleline | 256 | Gör att '.' matchar alla tecken utan undantag (vanligtvis matchas inte radbrytningstecken). |

## Se även

* Namnrymd [System::Text::RegularExpressions](../)
* Bibliotek [Aspose.Slides](../../)