---
title: RoundImpl()
second_title: Aspose.Slides för C++ API-referens
description: Rundar av det angivna värdet till närmaste värde med det angivna antalet decimaler. En parameter bestämmer funktionens beteende om det angivna värdet är lika nära två närmaste tal.
type: docs
weight: 287
url: /sv/system/mathf/roundimpl/
---
## MathF::RoundImpl(float, int, MidpointRounding) metod


Rundar av det angivna value till närmaste värde med det angivna antalet decimaler. En parameter bestämmer funktionens beteende om value är lika nära två närmaste tal.

```cpp
static float System::MathF::RoundImpl(float value, int digits, MidpointRounding mode)
```


### Arguments

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **float** | Värdet som ska avrundas |
| digits | int | Antalet decimaler i det avrundade värdet |
| mode | [MidpointRounding](../../midpointrounding/) | Anger hur avrundningen ska utföras om value är lika nära två närmaste tal. |

### Returvärde

Numret med det angivna antalet siffror närmast value

## Se även

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)