---
title: Round()
second_title: Aspose.Slides för C++ API-referens
description: Avrundar det specificerade värdet till närmaste heltal. En parameter anger funktionens beteende om det specificerade värdet är lika nära två närmaste tal.
type: docs
weight: 404
url: /sv/system/decimal/round/
---
## Decimal::Round(const Decimal\&, MidpointRounding) method


Avrundar det specificerade värdet till närmaste heltal. En parameter anger funktionens beteende om det specificerade värdet är lika nära två närmaste tal.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, MidpointRounding mode=MidpointRounding::ToEven)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| d | const [Decimal](../)\& | Värdet att avrunda |
| mode | [MidpointRounding](../../midpointrounding/) | Anger hur avrundningen ska utföras om **värde** är lika nära två närmaste tal. |

### Returvärde

**d** avrundat till det närmaste heltal

## Decimal::Round(const Decimal\&, int, MidpointRounding) method


Avrundar det specificerade värdet till närmaste värde med det angivna antalet decimaler. En parameter anger funktionens beteende om det specificerade värdet är lika nära två närmaste tal.

```cpp
static Decimal System::Decimal::Round(const Decimal &d, int digits, MidpointRounding mode=MidpointRounding::ToEven)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| d | const [Decimal](../)\& | Värdet att avrunda |
| digits | int | Antalet decimaler i det avrundade värdet |
| mode | [MidpointRounding](../../midpointrounding/) | Anger hur avrundningen ska utföras om **värde** är lika nära två närmaste tal. |

### Returvärde

Det tal med det angivna antalet siffror som ligger närmast **värde**

## Se även

* Enum [MidpointRounding](../../midpointrounding/)
* Klass [Decimal](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)