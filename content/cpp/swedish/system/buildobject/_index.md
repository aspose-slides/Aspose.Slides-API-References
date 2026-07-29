---
title: BuildObject()
second_title: Aspose.Slides för C++ API-referens
description: Skapa ett objekt med delat ägande.
type: docs
weight: 2250
url: /sv/system/buildobject/
---
## System::BuildObject(Args\&&...) funktion


Skapa ett objekt med delat ägande.

```cpp
template<typename T,typename...> Details::ObjectBuilder<T, SharedPtr<T>> System::BuildObject(Args &&... args)
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

ObjectBuilder konfigurerad för konstruktion av delad pekare
## Anmärkningar



Skapar en SharedPtr<T> och returnerar en byggare för den [Object](../object/) konstruktion måste avslutas med [Get()](../get/) anrop 

## Se även

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)