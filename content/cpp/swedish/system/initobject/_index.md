---
title: InitObject()
second_title: Aspose.Slides för C++ API-referens
description: Startar initialisering av ett objekt med delat ägande.
type: docs
weight: 2263
url: /sv/system/initobject/
---
## System::InitObject(const SharedPtr\<T\>\&) funktion

Startar initialisering av ett objekt med delat ägande.

```cpp
template<typename T> Details::ObjectBuilder<T, SharedPtr<T>> System::InitObject(const SharedPtr<T> &object)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T | Typ av objekt att initialisera |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| object | const [SharedPtr](../sharedptr/)\<T\>\& | [Object](../object/) för att initialisera |

### Returvärde

ObjectBuilder konfigurerad för konstruktion av delad pekare
## Anmärkningar



[Object](../object/) initialisering måste slutföras med [Get()](../get/)-anrop

## Se även

* Typedef [SharedPtr](../sharedptr/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)