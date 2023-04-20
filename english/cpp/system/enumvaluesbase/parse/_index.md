---
title: Parse()
second_title: Aspose.Slides for C++ API Reference
description: Returns an object that represents a value of enumeration constant of the specified enumeration type with the specified name.
type: docs
weight: 14
url: /cpp/system/enumvaluesbase/parse/
---
## EnumValuesBase::Parse(const TypeInfo\&, const String\&, bool) method


Returns an object that represents a value of enumeration constant of the specified enumeration type with the specified name.

```cpp
static SharedPtr<Object> System::EnumValuesBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | The [TypeInfo](../../typeinfo/) object representing the type of the enumeration value to return |
| str | const [String](../../string/)\& | The name of the enum constant |
| ignoreCase | **bool** | Specifeis if the case should be ignored when interpreting the name of the enum constant |

### Return Value

An object that represents the value of the enum constant whose name is specified in **str**.

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Class [Object](../../object/)
* Class [TypeInfo](../../typeinfo/)
* Class [String](../../string/)
* Class [EnumValuesBase](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)