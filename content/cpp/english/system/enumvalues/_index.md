---
title: EnumValues
second_title: Aspose.Slides for C++ API Reference
description: Provides meta information about enumeration constants of enum type E.
type: docs
weight: 768
url: /system/enumvalues/
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
| [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)() const override | Returns an array containing all names of enumeration **E**. |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](../enumvaluesbase/getnames/)(const [TypeInfo](../typeinfo/)\&) | Retrieves an array of the names of the constants in a specified enumeration. |
| const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)() const override | Returns the underlying type of the specified enumeration. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](../enumvaluesbase/getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Returns the underlying type of the specified enumeration. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(const [String](../string/)\&, **bool**) const override | Returns boxed value of the enum constant with the specified name. |
| [SharedPtr](../sharedptr/)\<[Object](../object/)\> [GetValueOf](./getvalueof/)(long) const override | Returns boxed value of the enum constant with the specified value. |
| [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)() const override | Returns an array containing all values of enumeration **E**. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](../enumvaluesbase/getvalues/)(const [TypeInfo](../typeinfo/)\&) | Returns an array containing all values of the specified enumeration type. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](../enumvaluesbase/parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Returns an object that represents a value of enumeration constant of the specified enumeration type with the specified name. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Converts the specified 64-bit unsigned integer value to an enumeration member. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](../enumvaluesbase/toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Converts the specified object with an integer value to an enumeration member. |
| virtual  [~EnumValues](./~enumvalues/)() | Destructor. |

## See Also

* Class [EnumValuesBase](../enumvaluesbase/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)