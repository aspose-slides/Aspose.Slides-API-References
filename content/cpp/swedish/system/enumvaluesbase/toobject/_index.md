---
title: ToObject()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar det angivna 64-bitars osignerade heltalsvärdet till ett uppräkningselement.
type: docs
weight: 40
url: /sv/system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) metod

Konverterar det angivna 64-bitars osignerade heltalsvärdet till ett uppräkningselement.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Den uppräkningstyp som ska returneras. |
| value | **uint64_t** | Värdet som ska konverteras till ett uppräkningselement. |

### Returvärde

En instans av uppräkningen satt till värdet.

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) metod

Konverterar det angivna objektet med ett heltalsvärde till ett uppräkningselement.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Den uppräkningstyp som ska returneras. |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Värdet konverteras till ett uppräkningselement. |

### Returvärde

Ett uppräkningsobjekt vars värde är värdet.

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [Object](../../object/)
* Klass [TypeInfo](../../typeinfo/)
* Klass [EnumValuesBase](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)