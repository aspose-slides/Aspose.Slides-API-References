---
title: GetCustomAttributes()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar en array som innehåller objekt som representerar alla anpassade attribut som tillämpas på typen.
type: docs
weight: 586
url: /sv/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const metod

Returnerar en array som innehåller objekt som representerar alla anpassade attribut som tillämpas på typen.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```

## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const metod

Returnerar en array som innehåller objekt som representerar specifika attribut som tillämpas på typen.

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | Typ av attributet att söka efter. |
| inherit | **bool** | Om ärvd attribut även ska sökas. |

## Se även

* Typedef [ArrayPtr](../../arrayptr/)
* Class [SmartPtr](../../smartptr/)
* Class [TypeInfo](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)