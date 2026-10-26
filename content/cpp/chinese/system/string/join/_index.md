---
title: Join()
second_title: Aspose.Slides C++ API 参考
description: 使用字符串作为分隔符连接数组。
type: docs
weight: 846
url: /zh/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) method


使用字符串作为分隔符连接数组。

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) 用于在连接时放置在数组元素之间。 |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | 要连接的部分的 [Array](../../array/)。 |
| startIndex | int | First index in array to start joining from. |
| count | int | Number of array elements to join. -1 means 'until array ends'. |

### 返回值

[String](../) 表示连接后的数组元素。

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) method


使用字符串作为分隔符连接数组。

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) 用于在连接时放置在数组元素之间。 |
| parts | const System::Details::ArrayView\<[String](../)\>\& | 用于连接的部分的 ArrayView。 |
| startIndex | int | First index in array to start joining from. |
| count | int | Number of array elements to join. -1 means 'until array ends'. |

### 返回值

[String](../) 表示连接后的数组元素。

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) method


使用字符串作为分隔符连接数组。

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) 用于在连接时放置在数组元素之间。 |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - 可枚举的部件对象 |

### 返回值

[String](../) 表示连接后的元素。

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) method


使用字符串作为分隔符连接数组。

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) 用于在连接时放置在数组元素之间。 |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | 要连接的部件的 [Array](../../array/)。 |

### 返回值

[String](../) 表示连接后的元素。

## 另见

* 类型定义 [ArrayPtr](../../arrayptr/)
* 类型定义 [SharedPtr](../../sharedptr/)
* 类 [String](../)
* 类 [IEnumerable](../../../system.collections.generic/ienumerable/)
* 类 [Object](../../object/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)