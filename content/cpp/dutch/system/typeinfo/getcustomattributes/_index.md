---
title: GetCustomAttributes()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert een array met objecten die alle aangepaste attributen vertegenwoordigen die op het type zijn toegepast.
type: docs
weight: 586
url: /nl/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const method

Retourneert een array met objecten die alle aangepaste attributen vertegenwoordigen die op het type zijn toegepast.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```

## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const method

Retourneert een array met objecten die specifieke attributen vertegenwoordigen die op het type zijn toegepast.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```

### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Type van het attribuut om naar te zoeken. |
| inherit | **bool** | Geeft aan of ook geërfde attributen moeten worden opgezocht. |

## Zie ook

* Typedef [ArrayPtr](../../arrayptr/)
* Klasse [SmartPtr](../../smartptr/)
* Klasse [TypeInfo](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)