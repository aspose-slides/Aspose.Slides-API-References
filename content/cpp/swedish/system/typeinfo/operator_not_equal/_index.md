---
title: operator!=()
second_title: Aspose.Slides för C++ API-referens
description: Avgör om det aktuella och de specificerade TypeInfo-objekten inte är lika.
type: docs
weight: 456
url: /sv/system/typeinfo/operator_not_equal/
---
## TypeInfo::operator!=(const TypeInfo\&) const metod


Avgör om det aktuella och det specificerade [TypeInfo](../)-objektet inte är lika.

```cpp
bool System::TypeInfo::operator!=(const TypeInfo &info) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | Det [TypeInfo](../)-objektet att jämföra med |

### Returvärde

Sant om objektens hashvärden inte är lika, annars - falskt

## TypeInfo::operator!=(std::nullptr_t) const metod


Avgör om det aktuella [TypeInfo](../)-objektet inte är ett null-objekt, d.v.s. det representerar någon typ.

```cpp
bool System::TypeInfo::operator!=(std::nullptr_t) const
```


### Returvärde

Sant om det aktuella [TypeInfo](../)-objektet inte är ett null-objekt, annars - falskt

## Se även

* Klass [TypeInfo](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)