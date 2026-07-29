---
title: Build()
second_title: Aspose.Slides för C++ API-referens
description: Bygg ett objekt med direkt ägande.
type: docs
weight: 2289
url: /sv/system/build/
---
## System::Build(Args\&&...) funktion


Bygg ett objekt med direkt ägande.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T> System::Build(Args &&... args)
```


### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av objekt att bygga |
| Args | Argumenttyper för objektkonstruktion |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| args | Args\&&... | Argument att vidarebefordra till objektkonstruktorn |

### Returvärde

ObjectBuilder konfigurerad för direkt objektkonstruktion
## Anmärkningar



[Object](../object/) konstruktion måste avslutas med [Get()](../get/) anrop 

## Se även

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)