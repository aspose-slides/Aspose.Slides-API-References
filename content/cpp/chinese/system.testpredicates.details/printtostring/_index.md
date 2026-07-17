---
title: PrintToString()
second_title: Aspose.Slides C++ API 参考
description: 通过选择适当的序列化函数将对象打印为字符串。
type: docs
weight: 1
url: /zh/system.testpredicates.details/printtostring/
---
## System::TestPredicates::Details::PrintToString(const T\&) 函数

Prints object to string by selecting proper serializer function.

```cpp
template<typename T> std::enable_if_t<!TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) 用于打印。 |

### 返回值

[String](../../system/string/) 传递的对象的表示。

## System::TestPredicates::Details::PrintToString(const T\&) 函数

Prints ICollection-style containers to string by printing their elements (not more than 32).

```cpp
template<typename T> std::enable_if_t<TypeTraits::IsEnumerable<T>::value, std::string> System::TestPredicates::Details::PrintToString(const T &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const T\& | [Object](../../system/object/) 用于打印。 |

### 返回值

包含元素的联合字符串表示。

## System::TestPredicates::Details::PrintToString(std::nullptr_t) 函数

Prints nullptr to string.

```cpp
std::string System::TestPredicates::Details::PrintToString(std::nullptr_t)
```

### 返回值

"nullptr" 字符串。

## System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable\<bool\>\&) 函数

Prints [IEnumerable<bool>](../../system.collections.generic/ienumerable/) collections to string by printing their elements (not more than 32).

```cpp
std::string System::TestPredicates::Details::PrintToString(const Collections::Generic::IEnumerable<bool> &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Object](../../system/object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<**bool**\>\& | [Object](../../system/object/) 用于打印。 |

### 返回值

包含元素的联合字符串表示。

## 另请参见

* 类 [IEnumerable](../../system.collections.generic/ienumerable/)
* 结构体 [IsEnumerable](../../system.testpredicates.typetraits/isenumerable/)
* 命名空间 [System::TestPredicates::Details](../)
* 库 [Aspose.Slides](../../)