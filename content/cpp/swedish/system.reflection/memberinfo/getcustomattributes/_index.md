---
title: GetCustomAttributes()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en array som innehåller objekt som representerar alla anpassade attribut som tillämpas på typen som representeras av det aktuella objektet.
type: docs
weight: 66
url: /sv/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const metod


Returnerar en array som innehåller objekt som representerar alla anpassade attribut som tillämpas på typen som representeras av det aktuella objektet.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | Typ av attribut att söka efter. |
| inherit | **bool** | Om ärvda attribut också ska kontrolleras. |

## MemberInfo::GetCustomAttributes(bool) const metod


Returnerar en array som innehåller objekt som representerar alla anpassade attribut som tillämpas på typen som representeras av det aktuella objektet.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inherit | **bool** | Om ärvda attribut också ska kontrolleras. |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [Object](../../../system/object/)
* Klass [TypeInfo](../../../system/typeinfo/)
* Klass [MemberInfo](../)
* Namnrymd [System::Reflection](../../)
* Bibliotek [Aspose.Slides](../../../)