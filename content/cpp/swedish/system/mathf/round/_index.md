---
title: Round()
second_title: Aspose.Slides för C++ API-referens
description: Rundar det angivna värdet till det närmaste heltalsvärdet.
type: docs
weight: 157
url: /sv/system/mathf/round/
---
## MathF::Round(float) metod

Rundar det angivna värdet till det närmaste heltalsvärdet.

```cpp
static float System::MathF::Round(float a)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | **float** | Värdet som ska avrundas |

### Returvärde

**a** avrundat till det närmaste heltalsvärdet

## MathF::Round(float, int) metod

Rundar det angivna värdet till det närmaste värdet med det angivna antalet decimaler.

```cpp
static float System::MathF::Round(float value, int digits)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **float** | Värdet som ska avrundas |
| digits | int | Antalet decimaler i det avrundade värdet |

### Returvärde

Det tal med det angivna antalet decimaler närmast **value**

## MathF::Round(float, MidpointRounding) metod

Rundar det angivna värdet till det närmaste heltalsvärdet. En parameter specificerar funktionens beteende om det angivna värdet är lika nära två närmaste tal.

```cpp
static float System::MathF::Round(float value, MidpointRounding mode)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **float** | Värdet som ska avrundas |
| mode | [MidpointRounding](../../midpointrounding/) | Specificerar hur avrundningen ska utföras om **value** är lika nära två närmaste tal. |

### Returvärde

**value** avrundat till det närmaste heltalsvärdet

## MathF::Round(float, int, MidpointRounding) metod

Rundar det angivna värdet till det närmaste värdet med det angivna antalet decimaler. En parameter specificerar funktionens beteende om det angivna värdet är lika nära två närmaste tal.

```cpp
static float System::MathF::Round(float value, int digits, MidpointRounding mode)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **float** | Värdet som ska avrundas |
| digits | int | Antalet decimaler i det avrundade värdet |
| mode | [MidpointRounding](../../midpointrounding/) | Specificerar hur avrundningen ska utföras om **value** är lika nära två närmaste tal. |

### Returvärde

Det tal med det angivna antalet decimaler närmast **value**

## Se även

* Enum [MidpointRounding](../../midpointrounding/)
* Struct [MathF](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)