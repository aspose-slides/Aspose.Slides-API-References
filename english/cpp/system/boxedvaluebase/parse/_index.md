---
title: Parse()
second_title: Aspose.Slides for C++ API Reference
description: Boxes the value of enumeration constant of the specified enumeration with the specified name. A parameter specifies if the case should be ignored when interpreting the string specifying the name of the enumeration constant.
type: docs
weight: 40
url: /cpp/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) method


Boxes the value of enumeration constant of the specified enumeration with the specified name. A parameter specifies if the case should be ignored when interpreting the string specifying the name of the enumeration constant.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Specifies the type of the enumeration |
| str | const [String](../../string/)\& | The name of the enumeration constant, value of which is to be boxed |
| ignoreCase | **bool** | Specifies if case should be ignored when interpreting the string representing the name of the enumeration constant |

### Return Value

A shared pointer to the object representing boxed value of the specified enumeration constant

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) method


Boxes the value of enumeration constant of the specified enumeration with the specified name.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Specifies the type of the enumeration |
| str | const [String](../../string/)\& | The name of the enumeration constant, value of which is to be boxed |

### Return Value

A shared pointer to the object representing boxed value of the specified enumeration constant

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Class [BoxedValueBase](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)