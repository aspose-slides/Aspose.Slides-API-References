---
title: ToObject()
second_title: Aspose.Slides for C++ API Reference
description: Converts the specified 64-bit unsigned integer value to an enumeration member.
type: docs
weight: 40
url: /system/enumvaluesbase/toobject/
---
## EnumValuesBase::ToObject(const TypeInfo\&, uint64_t) method


Converts the specified 64-bit unsigned integer value to an enumeration member.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, uint64_t value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | The enumeration type to return. |
| value | **uint64_t** | The value to convert to an enumeration member. |

### Return Value

An instance of the enumeration set to value.

## EnumValuesBase::ToObject(const TypeInfo\&, const SharedPtr\<Object\>\&) method


Converts the specified object with an integer value to an enumeration member.

```cpp
static SharedPtr<Object> System::EnumValuesBase::ToObject(const TypeInfo &type, const SharedPtr<Object> &value)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | The enumeration type to return. |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | The value convert to an enumeration member. |

### Return Value

An enumeration object whose value is value.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [EnumValuesBase](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)