---
title: operator==()
second_title: Aspose.Slides för C++ API-referens
description: Bestämmer om den aktuella och den specificerade TypeInfo-objekten är lika.
type: docs
weight: 443
url: /sv/system/typeinfo/operator_equal_equal/
---
## TypeInfo::operator==(const TypeInfo\&) const metod

Bestämmer om den aktuella och den specificerade [TypeInfo](../) objekten är lika.

```cpp
bool System::TypeInfo::operator==(const TypeInfo &info) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| info | const [TypeInfo](../)\& | Det [TypeInfo](../) objektet att jämföra med |

### Returvärde

Sant om objektens hashvärden är lika, annars - falskt

## TypeInfo::operator==(std::nullptr_t) const metod

Bestämmer om det aktuella [TypeInfo](../) objektet är ett null-objekt, d.v.s. inte representerar någon typ.

```cpp
bool System::TypeInfo::operator==(std::nullptr_t) const
```

### Returvärde

Sant om det aktuella [TypeInfo](../) objektet är ett null-objekt, annars - falskt

## Se även

* Klass [TypeInfo](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)