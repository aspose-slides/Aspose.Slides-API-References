---
title: IsNull()
second_title: Aspose.Slides for C++ API 参考
description: 检查表示的值是否为 nullptr。
type: docs
weight: 27
url: /zh/system.collections.generic.details.castrules/isnull/
---
## System::Collections::Generic::Details::CastRules::IsNull(T) 函数


检查表示的值是否为 nullptr。

```cpp
template<typename T> bool System::Collections::Generic::Details::CastRules::IsNull(T)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 值的类型。 |

### 返回值

始终返回 false。

## System::Collections::Generic::Details::CastRules::IsNull(SharedPtr\<T\>) 函数


检查表示的值是否为 nullptr。

```cpp
template<typename T> bool System::Collections::Generic::Details::CastRules::IsNull(SharedPtr<T> value)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 值的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [SharedPtr](../../system/sharedptr/)\<T\> | 必须检查的值。 |

### 返回值

如果值为 nullptr 则返回 true，否则返回 false。

## System::Collections::Generic::Details::CastRules::IsNull(Nullable\<T\>) 函数


检查表示的值是否为 nullptr。

```cpp
template<typename T> bool System::Collections::Generic::Details::CastRules::IsNull(Nullable<T> value)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 值的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Nullable](../../system/nullable/)\<T\> | 必须检查的值。 |

### 返回值

如果值为 nullptr 则返回 true，否则返回 false。

## 另请参见

* 类型定义 [SharedPtr](../../system/sharedptr/)
* 类 [Nullable](../../system/nullable/)
* 命名空间 [System::Collections::Generic::Details::CastRules](../)
* 库 [Aspose.Slides](../../)