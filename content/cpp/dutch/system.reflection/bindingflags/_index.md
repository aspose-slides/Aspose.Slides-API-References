---
title: BindingFlags
second_title: Aspose.Slides voor C++ API-referentie
description: Definieert leden en type-zoekmodi en bindings.
type: docs
weight: 157
url: /nl/system.reflection/bindingflags/
---
## BindingFlags enum

Definieert leden- en type-zoekmodi en bindings.

```cpp
enum class BindingFlags
```

### Waarden

| Naam | Waarde | Beschrijving |
| --- | --- | --- |
| Default | 0 | Geen speciale opties. |
| IgnoreCase | 1 | Negeer hoofdlettergebruik van de naam bij het zoeken naar een item. |
| DeclaredOnly | 2 | Zoek alleen naar leden die in het type zijn gedeclareerd en niet in basistypen. |
| Instance | 4 | Doorzoek instantie-leden. |
| Static | 8 | Doorzoek statische leden. |
| Public | 16 | Doorzoek openbare leden. |
| NonPublic | 32 | Doorzoek niet-openbare leden. |
| FlattenHierarchy | 64 | Doorzoek openbare en beschermde statische leden van het basistype. |
| InvokeMethod | 256 | Roept een methode aan. |
| CreateInstance | 512 | Creëert een instantie van het gereflecteerde type. |
| GetField | 1024 | Haalt veldwaarde op. |
| SetField | 2048 | Stelt veldwaarde in. |
| GetProperty | 4096 | Haalt eigenschapwaarde op. |
| SetProperty | 8192 | Stelt eigenschapwaarde in. |
| PutDispProperty | 16384 | Stelt COM-eigenschap in. |
| PutRefDispProperty | 32768 | Stelt COM-referentie-eigenschap in. |
| ExactBinding | 65536 | Typebinding moet exact zijn, zonder enige type-wijzigingen. |
| SuppressChangeType | 131072 | Niet ondersteund. |
| OptionalParamBinding | 262144 | Selecteert overload op basis van het aantal argumenten. |
| IgnoreReturn | 16777216 | Negeert de retourwaarde van COM-interop. |

## Zie ook

* Namespace [System::Reflection](../)
* Library [Aspose.Slides](../../)