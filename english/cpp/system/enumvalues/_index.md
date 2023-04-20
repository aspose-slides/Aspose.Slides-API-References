---
title: EnumValues
second_title: Aspose.Slides for C++ API Reference
description: Provides meta information about enumeration constants of enum type E.
type: docs
weight: 742
url: /cpp/system/enumvalues/
---
## EnumValues class


Provides meta information about enumeration constants of enum type **E**.

```cpp
template<typename E,class Guard>class EnumValues : public System::EnumValuesBase
```


### Template parameters

| Parameter | Description |
| --- | --- |
| E | The type of enumeration |
## Methods

| Method | Description |
| --- | --- |
|  [EnumValues](./enumvalues/)() | Constructs an instance. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | Returns boxed value of the enum constant with the specified name. |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | Returns an array containing all values of enumeration **E**. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | Returns an array containing all values of the specified enumeration type. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Returns an object that represents a value of enumeration constant of the specified enumeration type with the specified name. |
| virtual  [~EnumValues](./~enumvalues/)() | Destructor. |

## See Also

* Class [EnumValuesBase](../enumvaluesbase/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)