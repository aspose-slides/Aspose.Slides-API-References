---
title: CanCast()
second_title: Aspose.Slides for C++ API 参考
description: 检查转换的可能性。
type: docs
weight: 40
url: /zh/system.collections.generic.details.castrules/cancast/
---
## System::Collections::Generic::Details::CastRules::CanCast(Source) 函数

检查转换的可能性。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::None, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 返回值

当在转换后返回的值不是 nullptr 时返回 true，否则返回 false。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 函数

检查转换的可能性。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Static, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 返回值

当在转换后返回的值不是 nullptr 时返回 true，否则返回 false。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 函数

检查转换的可能性。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Dynamic, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 返回值

当在转换后返回的值不是 nullptr 时返回 true，否则返回 false。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 函数

检查转换的可能性。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableBoxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 返回值

始终返回 true。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 函数

检查转换的可能性。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::NullableUnboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 返回值

当在转换后返回的值不是 nullptr 时返回 true，否则返回 false。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 函数

检查转换的可能性。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Boxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 返回值

始终返回 true。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 函数

检查转换的可能性。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Unboxing, bool> System::Collections::Generic::Details::CastRules::CanCast(Source value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 返回值

如果转换操作成功完成则返回 true，否则返回 false。

## System::Collections::Generic::Details::CastRules::CanCast(Source) 函数

检查转换的可能性。

```cpp
template<typename Source,typename Result> std::enable_if_t<CastType<Source, Result>::Invalid, bool> System::Collections::Generic::Details::CastRules::CanCast(Source)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 返回值

始终返回 false。

## 另请参见

* 结构体 [CastType](../casttype/)
* 命名空间 [System::Collections::Generic::Details::CastRules](../)
* 库 [Aspose.Slides](../../)