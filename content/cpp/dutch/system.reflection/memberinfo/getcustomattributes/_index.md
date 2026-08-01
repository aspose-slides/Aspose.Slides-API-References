---
title: GetCustomAttributes()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een array met objecten die alle aangepaste attributen weergeven die op het type van het huidige object zijn toegepast.
type: docs
weight: 66
url: /nl/system.reflection/memberinfo/getcustomattributes/
---
## MemberInfo::GetCustomAttributes(const TypeInfo\&, bool) const methode


Retourneert een array met objecten die alle aangepaste attributen vertegenwoordigen die op het type zijn toegepast dat wordt vertegenwoordigd door het huidige object.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit=false) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| attributeType | const [TypeInfo](../../../system/typeinfo/)\& | Type van attribuut om naar te zoeken. |
| inherit | **bool** | Of geërfde attributen ook moeten worden gecontroleerd. |

## MemberInfo::GetCustomAttributes(bool) const methode


Retourneert een array met objecten die alle aangepaste attributen vertegenwoordigen die op het type zijn toegepast dat wordt vertegenwoordigd door het huidige object.

```cpp
ArrayPtr<SharedPtr<Object>> System::Reflection::MemberInfo::GetCustomAttributes(bool inherit=false) const
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| inherit | **bool** | Of geërfde attributen ook moeten worden gecontroleerd. |

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Object](../../../system/object/)
* Klasse [TypeInfo](../../../system/typeinfo/)
* Klasse [MemberInfo](../)
* Namespace [System::Reflection](../../)
* Library [Aspose.Slides](../../../)