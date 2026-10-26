---
title: GetCustomAttribute()
second_title: Aspose.Slides för C++ API-referens
description: Söker efter det anpassade attributet som har den angivna typen och som är tillämpat på den typ som representeras av det aktuella objektet.
type: docs
weight: 573
url: /sv/system/typeinfo/getcustomattribute/
---
## TypeInfo::GetCustomAttribute(const TypeInfo\&) const metod

Söker efter det anpassade attributet som har den angivna typen och som är tillämpat på den typ som representeras av det aktuella objektet.

```cpp
ObjectPtr System::TypeInfo::GetCustomAttribute(const TypeInfo &attributeType) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Den konstanta referensen till [TypeInfo](../)-objektet som representerar typen av attributet som ska sökas |

### Returvärde

En pekare till ett objekt som representerar det hittade attributet, eller null-pekare om inget attribut som matchar sökkriterierna hittades

## Se även

* Klass [SmartPtr](../../smartptr/)
* Klass [TypeInfo](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)