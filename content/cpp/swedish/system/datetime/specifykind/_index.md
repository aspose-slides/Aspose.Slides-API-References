---
title: SpecifyKind()
second_title: Aspose.Slides för C++ API-referens
description: Skapar ett nytt DateTime-objekt som representerar samma antal tickar som det angivna DateTime-objektet och representerar lokal tid, UTC-tid eller ingen av delarna enligt argumentet kind.
type: docs
weight: 833
url: /sv/system/datetime/specifykind/
---
## DateTime::SpecifyKind(DateTime, DateTimeKind) method


Skapar ett nytt [DateTime](../)-objekt som representerar samma antal tickar som det angivna [DateTime](../)-objektet och representerar lokal tid, UTC-tid eller ingen av delarna enligt argumentet **kind**.

```cpp
static DateTime System::DateTime::SpecifyKind(DateTime value, DateTimeKind kind)
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [DateTime](../) | Det [DateTime](../)-objektet att kopiera antalet tickar från |
| kind | [DateTimeKind](../../datetimekind/) | Anger om det nya objektet ska representera lokal tid, UTC-tid eller ingen av delarna. |

### Returvärde

Ett nytt [DateTime](../)-objekt som representerar samma antal tickar som **value** och DateTimeKind-värdet som anges av **kind**.

## Se även

* Enum [DateTimeKind](../../datetimekind/)
* Klass [DateTime](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)