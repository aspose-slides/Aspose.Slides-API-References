---
title: Equals< float, float >()
second_title: Aspose.Slides för C++ API-referens
description: "Specialisering för enkelprecisions flyttal. Även om två flyttal-NaN definieras av IEC 60559:1989 att alltid jämföras som olika, kräver kontraktet för System.Object.Equals att översättningar måste uppfylla kraven för en ekvivalensoperator. Därför returnerar System.Double.Equals och System.Single.Equals True när två NaN jämförs, medan likhetsoperatorn returnerar False i det fallet, enligt standarden."
type: docs
weight: 2705
url: /sv/system/equals_less_float,_float__greater/
---
## System::Equals< float, float >(const float\&, const float\&) funktion


Specialisering för enkelprecisions flyttal. Även om två flyttal-NaN definieras av IEC 60559:1989 att alltid jämföras som olika, kräver kontraktet för [System.Object.Equals](../object/equals/), att översättningar måste uppfylla kraven för en ekvivalensoperator. Därför returnerar System.Double.Equals och System.Single.Equals True när två NaN jämförs, medan likhetsoperatorn returnerar False i det fallet, enligt standarden.

```cpp
bool System::Equals<float, float>(const float &a, const float &b)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | const **float**\& | Den första jämförelsetermen |
| b | const **float**\& | Den andra jämförelsetermen |

### Returvärde

True om båda värdena är NaN eller är lika, annars - false

## Se även

* Namespace [System](../)
* Library [Aspose.Slides](../../)