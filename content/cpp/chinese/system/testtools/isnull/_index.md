---
title: IsNull()
second_title: Aspose.Slides for C++ API 参考
description: 检查特定值是否为 null。适用于算术和枚举类型的版本。
type: docs
weight: 1
url: /zh/system/testtools/isnull/
---
## TestTools::IsNull(T) 方法


检查特定值是否为 null。[Version](../../version/) 用于算术和枚举类型。

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 被检查值的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | T | 要检查是否为 null 的值。 |

### 返回值

始终返回 false。

## TestTools::IsNull(const T\&) 方法


检查特定值是否为 null。[Version](../../version/) 用于非算术和非枚举值类型。

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 被检查值的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const T\& | 要检查是否为 null 的值。 |

### 返回值

如果对象与 nullptr 比较结果为 true，则返回 true；否则返回 false。

## TestTools::IsNull(const SharedPtr\<T\>\&) 方法


检查特定值是否为 null。[Version](../../version/) 用于非算术值类型。

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 被检查值的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | 要检查是否为 null 的值。 |

### 返回值

如果对象与 nullptr 比较结果为 true，则返回 true；否则返回 false。

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) 方法


检查特定值是否为 null。[Version](../../version/) 用于键值对。

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| K | 键类型。 |
| V | 值类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | 键值对对象。 |

### 返回值

如果键值对被视为 null，则返回 true；否则返回 false。

## TestTools::IsNull(const System::String\&) 方法


检查字符串是否为 null。

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) 要检查的。 |

### 返回值

如果字符串被视为 null，则返回 true；否则返回 false。

## 另请参见

* typedef [SharedPtr](../../sharedptr/)
* 类 [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* 类 [String](../../string/)
* 结构体 [TestTools](../)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)