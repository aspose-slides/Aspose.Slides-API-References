---
title: Round()
second_title: Aspose.Slides för C++ API-referens
description: Rundar det angivna värdet till närmaste heltalsvärde.
type: docs
weight: 157
url: /sv/system/math/round/
---
## Math::Round(double) metod


Rundar det angivna värdet till närmaste heltalsvärde.

```cpp
static double System::Math::Round(double a)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| a | **double** | Värdet som ska rundas |

### Returvärde

**a** rundat till närmaste heltalsvärde

## Math::Round(double, int) metod


Rundar det angivna värdet till det närmaste värdet med det angivna antalet decimaler.

```cpp
static double System::Math::Round(double value, int digits)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **double** | Värdet som ska rundas |
| digits | int | Antalet decimaler i det avrundade värdet |

### Returvärde

Talet med det angivna antalet decimaler närmast **value**

## Math::Round(double, MidpointRounding) metod


Rundar det angivna värdet till närmaste heltal. En parameter specificerar funktionens beteende om det angivna värdet är lika nära två närmaste tal.

```cpp
static double System::Math::Round(double value, MidpointRounding mode)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **double** | Värdet som ska rundas |
| mode | [MidpointRounding](../../midpointrounding/) | Specificerar hur avrundningen ska utföras om **value** är lika nära två närmaste tal. |

### Returvärde

**value** rundat till närmaste heltalsvärde

## Math::Round(double, int, MidpointRounding) metod


Rundar det angivna värdet till det närmaste värdet med det angivna antalet decimaler. En parameter specificerar funktionens beteende om det angivna värdet är lika nära två närmaste tal.

```cpp
static double System::Math::Round(double value, int digits, MidpointRounding mode)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **double** | Värdet som ska rundas |
| digits | int | Antalet decimaler i det avrundade värdet |
| mode | [MidpointRounding](../../midpointrounding/) | Specificerar hur avrundningen ska utföras om **value** är lika nära två närmaste tal. |

### Returvärde

Talet med det angivna antalet decimaler närmast **value**

## Math::Round(const Decimal\&) metod


Rundar det angivna värdet till närmaste heltalsvärde.

```cpp
static Decimal System::Math::Round(const Decimal &d)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | Värdet som ska rundas |

### Returvärde

**d** rundat till närmaste heltalsvärde

## Math::Round(const Decimal\&, int) metod


Rundar det angivna värdet till det närmaste värdet med det angivna antalet decimaler.

```cpp
static Decimal System::Math::Round(const Decimal &value, int digits)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [Decimal](../../decimal/)\& | Värdet som ska rundas |
| digits | int | Antalet decimaler i det avrundade värdet |

### Returvärde

Talet med det angivna antalet decimaler närmast **value**

## Math::Round(const Decimal\&, MidpointRounding) metod


Rundar det angivna värdet till närmaste heltal. En parameter specificerar funktionens beteende om det angivna värdet är lika nära två närmaste tal.

```cpp
static Decimal System::Math::Round(const Decimal &d, MidpointRounding mode)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | Värdet som ska rundas |
| mode | [MidpointRounding](../../midpointrounding/) | Specificerar hur avrundningen ska utföras om **value** är lika nära två närmaste tal. |

### Returvärde

**d** rundat till närmaste heltalsvärde

## Math::Round(const Decimal\&, int, MidpointRounding) metod


Rundar det angivna värdet till det närmaste värdet med det angivna antalet decimaler. En parameter specificerar funktionens beteende om det angivna värdet är lika nära två närmaste tal.

```cpp
static Decimal System::Math::Round(const Decimal &d, int digits, MidpointRounding mode)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| d | const [Decimal](../../decimal/)\& | Värdet som ska rundas |
| digits | int | Antalet decimaler i det avrundade värdet |
| mode | [MidpointRounding](../../midpointrounding/) | Specificerar hur avrundningen ska utföras om **value** är lika nära två närmaste tal. |

### Returvärde

Talet med det angivna antalet decimaler närmast **value**

## Se även

* Enum [MidpointRounding](../../midpointrounding/)
* Class [Decimal](../../decimal/)
* Struct [Math](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)