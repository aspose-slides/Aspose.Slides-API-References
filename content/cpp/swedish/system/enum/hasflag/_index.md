---
title: HasFlag()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om de angivna bitarna är satta i en bitvis representation av det angivna enum-värdet.
type: docs
weight: 14
url: /sv/system/enum/hasflag/
---
## Enum::HasFlag(E, E) method


Bestämmer om de angivna bitarna är satta i en bitvis representation av det angivna enum-värdet.

```cpp
static bool System::Enum<E, Guard>::HasFlag(E value, E mask)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | E | Enum-värdet som ska testas |
| mask | E | Masken för att kontrollera värdets bitar mot |

### Returvärde

True om bitarna som är satta i **mask** också är satta i **value**, annars - false

## Se även

* Struct [Enum](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)