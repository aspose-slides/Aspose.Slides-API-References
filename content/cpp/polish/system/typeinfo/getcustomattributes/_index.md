---
title: GetCustomAttributes()
second_title: Referencja API Aspose.Slides dla C++
description: Zwraca tablicę zawierającą obiekty, które reprezentują wszystkie niestandardowe atrybuty zastosowane do tego typu.
type: docs
weight: 586
url: /pl/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const metoda

Zwraca tablicę zawierającą obiekty, które reprezentują wszystkie niestandardowe atrybuty zastosowane do tego typu.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```

## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const metoda

Zwraca tablicę zawierającą obiekty, które reprezentują konkretne atrybuty zastosowane do tego typu.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Typ atrybutu, którego należy szukać. |
| inherit | **bool** | Określa, czy szukać także atrybutów odziedziczonych. |

## Zobacz także

* Typedef [ArrayPtr](../../arrayptr/)
* Klasa [SmartPtr](../../smartptr/)
* Klasa [TypeInfo](../)
* Przestrzeń nazw [System](../../)
* Biblioteka [Aspose.Slides](../../../)