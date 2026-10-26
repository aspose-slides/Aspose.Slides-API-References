---
title: ExplicitCast()
second_title: Aspose.Slides C++ API 参考
description: 使用显式转换将源类型转换为结果类型。当源类型和结果类型相同时使用。
type: docs
weight: 2588
url: /zh/system/explicitcast/
---
## System::ExplicitCast(const Source&) 函数

使用显式转换将源类型转换为结果类型。当源类型和结果类型相同时使用。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::ExplicitCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::ExplicitCast(const Source&) 函数

使用显式转换将源类型转换为结果类型。当需要类似构造函数的简单转换时使用。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::ExplicitCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::ExplicitCast(const Source&) 函数

使用显式转换将源类型转换为结果类型。用于异常包装器。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::ExplicitCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::ExplicitCast(const Source&) 函数

使用显式转换将源类型转换为结果类型。用于将对象转换为异常。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::ExplicitCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::ExplicitCast(const Source&) 函数

使用显式转换将源类型转换为结果类型。当源和结果都是智能指针（结果类型中没有显式的 SmartPtr<...>）时使用。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::ExplicitCast(Source) 函数

使用显式转换将源类型转换为结果类型。用于将原始指针转换为智能指针。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::RawPointer, typename CastResult<std::remove_pointer_t<Result>>::type> System::ExplicitCast(Source value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | Source | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::ExplicitCast(const Source&) 函数

使用显式转换将源类型转换为结果类型。当源和结果都是智能指针（结果类型中包含显式的 SmartPtr<...>）时使用。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::ExplicitCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::ExplicitCast(const Source&) 函数

使用显式转换将源类型转换为结果类型。用于将对象装箱为可空类型。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::ExplicitCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::ExplicitCast(const Source&) 函数

使用显式转换将源类型转换为结果类型。用于将可空类型装箱。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::ExplicitCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::ExplicitCast(const Source&) 函数

使用显式转换将源类型转换为结果类型。用于将可空对象拆箱。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableUnboxing, Result> System::ExplicitCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::ExplicitCast(const Source&) 函数

使用显式转换将源类型转换为结果类型。用于枚举装箱。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::EnumBoxing, SmartPtr<BoxedValueBase>> System::ExplicitCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::ExplicitCast(const Source&) 函数

使用显式转换将源类型转换为结果类型。用于在需要以智能指针引用值类型时将值类型复制到堆上（在受接口约束的泛型中，但使用实现该接口的结构体进行专门化）。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::HeapifyBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::ExplicitCast(const Source&) 函数

使用显式转换将源类型转换为结果类型。用于从值类型获取接口。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::ExplicitCast(const Source&) 函数

使用显式转换将源类型转换为结果类型。用于通用装箱。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::ExplicitCast(const Source&) 函数

使用显式转换将源类型转换为结果类型。用于 [System::String](../string/) 装箱。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::StringBoxing, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::ExplicitCast(const Source&) 函数

使用显式转换将源类型转换为结果类型。用于拆箱接口。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxing, Result> System::ExplicitCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::ExplicitCast(const Source&) 函数

使用显式转换将源类型转换为结果类型。用于通用拆箱。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Unboxing, Result> System::ExplicitCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::ExplicitCast(const Source&) 函数

使用显式转换将源类型转换为结果类型。用于 nullptr 转换。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::ExplicitCast(const Source&) 函数

使用显式转换将源类型转换为结果类型。用于在数组之间进行转换。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::ExplicitCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## 另见

* 类型别名 [Exception](../exception/)
* 类 [SmartPtr](../smartptr/)
* 类 [BoxedValueBase](../boxedvaluebase/)
* 结构体 [CastResult](../castresult/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)