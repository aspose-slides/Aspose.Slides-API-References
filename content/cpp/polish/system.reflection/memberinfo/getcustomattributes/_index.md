---
title: GetCustomAttributes()
second_title: Aspose.Slides dla C++ – Referencja API
description: Zwraca tablicę zawierającą obiekty, które reprezentują wszystkie niestandardowe atrybuty zastosowane do typu reprezentowanego przez bieżący obiekt.
type: docs
weight: 66
url: /pl/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const metoda

Zwraca tablicę zawierającą obiekty, które reprezentują wszystkie niestandardowe atrybuty zastosowane do typu reprezentowanego przez bieżący obiekt.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | Typ atrybutu, którego należy szukać. |
| inherit | **bool** | Czy również sprawdzać atrybuty odziedziczone. |

## MemberInfo::GetCustomAttributes(bool) const metoda

Zwraca tablicę zawierającą obiekty, które reprezentują wszystkie niestandardowe atrybuty zastosowane do typu reprezentowanego przez bieżący obiekt.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| inherit | **bool** | Czy również sprawdzać atrybuty odziedziczone. |

## Zobacz także

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Object](../../../system/object/)
* Klasa [TypeInfo](../../../system/typeinfo/)
* Klasa [MemberInfo](../)
* Przestrzeń nazw [System::Reflection](../../)
* Biblioteka [Aspose.Slides](../../../)