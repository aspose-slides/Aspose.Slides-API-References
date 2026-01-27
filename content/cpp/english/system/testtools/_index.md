---
title: TestTools
second_title: Aspose.Slides for C++ API Reference
description: Provides a set of useful methods that check some basic properties of different types and functions.
type: docs
weight: 1873
url: /system/testtools/
---
## TestTools struct


Provides a set of useful methods that check some basic properties of different types and functions.

```cpp
class TestTools
```

## Methods

| Method | Description |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | Checks if function throws exception of any type. |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | Checks if string is empty. |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Checks if collection is empty. |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | Checks if specific value is null. [Version](../version/) for arithmetic and enum types. |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | Checks if specific value is null. [Version](../version/) for non-arithmetic and non-enum value types. |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Checks if specific value is null. [Version](../version/) for non-arithmetic value types. |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | Checks if specific value is null. [Version](../version/) for key-value pairs. |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | Checks if string is null. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | Checks if collection is null or empty. |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | Checks if string is null or empty. |
## See Also

* Namespace [System](../)
* Library [Aspose.Slides](../../)