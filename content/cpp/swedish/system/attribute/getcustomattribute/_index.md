---
title: GetCustomAttribute()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar ett anpassat attribut av en angiven typ som tillämpas på den angivna typen.
type: docs
weight: 1
url: /sv/system/attribute/getcustomattribute/
---
## Attribute::GetCustomAttribute(const TypeInfo\&, const TypeInfo\&) metod

Returnerar ett anpassat attribut av en angiven typ som tillämpas på den angivna typen.

```cpp
static Object::ptr System::Attribute::GetCustomAttribute(const TypeInfo &type, const TypeInfo &attributeType)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Typattribut som hämtas |
| attributeType | const [TypeInfo](../../typeinfo/)\& | Typ av attributet som ska hämtas |

### Returvärde

Ett hämtat attribut eller null om den angivna typen inte har ett attribut av den angivna typen.

## Se även

* Typedef [ptr](../../object/ptr/)
* Klass [TypeInfo](../../typeinfo/)
* Klass [Attribute](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)