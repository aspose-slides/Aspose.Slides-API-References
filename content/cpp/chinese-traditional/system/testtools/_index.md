---
title: TestTools
second_title: Aspose.Slides for C++ API 參考
description: 提供一組有用的方法，用於檢查不同類型和函式的基本屬性。
type: docs
weight: 1925
url: /zh-hant/system/testtools/
---
## TestTools struct

Provides a set of useful methods that check some basic properties of different types and functions.

```cpp
class TestTools
```

## Methods

| 方法 | 描述 |
| --- | --- |
| static **bool** [AssertThrows](./assertthrows/)(const std::function\<void()>\&) | 檢查函式是否拋出任何類型的例外。 |
| static **bool** [IsEmpty](./isempty/)(const [System::String](../string/)\&) | 檢查字串是否為空。 |
| static **bool** [IsEmpty](./isempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 檢查集合是否為空。 |
| static std::enable_if\<std::is_arithmetic\<T\>::value||std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(T) | 檢查特定值是否為 null。[Version](../version/) 用於算術和列舉類型。 |
| static std::enable_if<\!std::is_arithmetic\<T\>::value\&&\!std::is_enum\<T\>::value, **bool**\>::type [IsNull](./isnull/)(const T\&) | 檢查特定值是否為 null。[Version](../version/) 用於非算術且非列舉的值類型。 |
| static **bool** [IsNull](./isnull/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 檢查特定值是否為 null。[Version](../version/) 用於非算術的值類型。 |
| static **bool** [IsNull](./isnull/)([System::Collections::Generic::KeyValuePair](../../system.collections.generic/keyvaluepair/)\<K, V\>\&) | 檢查特定值是否為 null。[Version](../version/) 用於鍵值對。 |
| static **bool** [IsNull](./isnull/)(const [System::String](../string/)\&) | 檢查字串是否為 null。 |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [SharedPtr](../sharedptr/)\<T\>\&) | 檢查集合是否為 null 或為空。 |
| static **bool** [IsNullOrEmpty](./isnullorempty/)(const [System::String](../string/)\&) | 檢查字串是否為 null 或為空。 |

## See Also

* 命名空間 [System](../)
* 程式庫 [Aspose.Slides](../../)