---
title: EnumValuesBase
second_title: Aspose.Slides for C++ API Reference
description: A base class for a class that represents meta information of enumeration type.
type: docs
weight: 768
url: /system/enumvaluesbase/
---
## EnumValuesBase class


A base class for a class that represents meta information of enumeration type.

```cpp
class EnumValuesBase
```

## Methods

| Method | Description |
| --- | --- |
| static [ArrayPtr](../arrayptr/)\<[String](../string/)\> [GetNames](./getnames/)(const [TypeInfo](../typeinfo/)\&) | Retrieves an array of the names of the constants in a specified enumeration. |
| static const [System::TypeInfo](../typeinfo/)\& [GetUnderlyingType](./getunderlyingtype/)(const [TypeInfo](../typeinfo/)\&) | Returns the underlying type of the specified enumeration. |
| static [ArrayPtr](../arrayptr/)\<**int64_t**\> [GetValues](./getvalues/)(const [TypeInfo](../typeinfo/)\&) | Returns an array containing all values of the specified enumeration type. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [Parse](./parse/)(const [TypeInfo](../typeinfo/)\&, const [String](../string/)\&, **bool**) | Returns an object that represents a value of enumeration constant of the specified enumeration type with the specified name. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, **uint64_t**) | Converts the specified 64-bit unsigned integer value to an enumeration member. |
| static [SharedPtr](../sharedptr/)\<[Object](../object/)\> [ToObject](./toobject/)(const [TypeInfo](../typeinfo/)\&, const [SharedPtr](../sharedptr/)\<[Object](../object/)\>\&) | Converts the specified object with an integer value to an enumeration member. |
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)