---
title: Cast()
second_title: Aspose.Slides C++ API 参考
description: 将源类型转换为结果类型。当源类型和结果类型相同时使用。
type: docs
weight: 14
url: /zh/system.collections.generic.details.castrules/cast/
---
## System::Collections::Generic::Details::CastRules::Cast(Source) 函数

将源类型转换为结果类型。当源类型和结果类型相同时使用。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 返回值

转换结果。

## System::Collections::Generic::Details::CastRules::Cast(Source) 函数

将源类型转换为结果类型。当源类型可以静态转换为结果类型时使用。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 返回值

转换结果。

## System::Collections::Generic::Details::CastRules::Cast(Source) 函数

将源类型转换为结果类型。当类型不同且源类型无法静态转换为结果类型时使用。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 返回值

转换结果。

## System::Collections::Generic::Details::CastRules::Cast(Source) 函数

将源类型转换为结果类型。当源类型被装箱为 [Nullable](../../system/nullable/) 类实例时使用。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 返回值

转换结果。

## System::Collections::Generic::Details::CastRules::Cast(Source) 函数

将源类型转换为结果类型。当源类型从 [Nullable](../../system/nullable/) 类实例中拆箱时使用。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 返回值

转换结果。

## System::Collections::Generic::Details::CastRules::Cast(Source) 函数

将源类型转换为结果类型。当源类型被装箱为 [Object](../../system/object/) 类实例时使用。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 返回值

转换结果。

## System::Collections::Generic::Details::CastRules::Cast(Source) 函数

将源类型转换为结果类型。当源类型从 [Object](../../system/object/) 类实例中拆箱时使用。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, Result> System::Collections::Generic::Details::CastRules::Cast(Source value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 返回值

转换结果。

## System::Collections::Generic::Details::CastRules::Cast(Source) 函数

将源类型转换为结果类型。当转换无效或需要显式转换时使用。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, Result> System::Collections::Generic::Details::CastRules::Cast(Source)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 返回值

转换结果。

## 另见

* Struct [CastType](../casttype/)
* Namespace [System::Collections::Generic::Details::CastRules](../)
* Library [Aspose.Slides](../../)