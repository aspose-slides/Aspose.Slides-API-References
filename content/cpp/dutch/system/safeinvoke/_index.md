---
title: SafeInvoke()
second_title: Aspose.Slides voor C++ API-referentie
description: Implementatie van de vertaling van de '?.' operator.
type: docs
weight: 2653
url: /nl/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) functie

Implementatie van de vertaling van de '?.' operator.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```

### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T0 | expressietype. |
| T1 | Type van lambda die de 'WhenTrue' expressie omvat. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| expr | T0\&& | expressiewaarde. |
| func | T1\&& | 'WhenTrue' expressie gekoppeld aan functor. |

### Retourwaarde

Als de waarde van expr niet null is, retourneert het func dat wordt aangeroepen met zijn waarde als eerste argument; anders wordt null geretourneerd.

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)