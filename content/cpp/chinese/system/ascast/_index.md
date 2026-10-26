---
title: AsCast()
second_title: Aspose.Slides for C++ API 参考
description: 使用 'as' 运算符将源类型转换为结果类型。当需要简单的类似构造函数的转换时使用。
type: docs
weight: 2601
url: /zh/system/ascast/
---
## System::AsCast(const Source\&) 函数

使用 'as' 运算符进行转换，将源类型转换为结果类型。用于需要简单构造函数式转换的情况。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Static, Result> System::AsCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::AsCast(const Source\&) 函数

使用 'as' 运算符进行转换，将源类型转换为结果类型。用于源类型和结果类型相同的情况。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::None, Result> System::AsCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::AsCast(const Source\&) 函数

使用 'as' 运算符进行转换，将源类型转换为结果类型。用于异常包装器。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Exception, Result> System::AsCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::AsCast(const Source\&) 函数

使用 'as' 运算符进行转换，将源类型转换为结果类型。用于将对象转换为异常。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::ObjectToException, Result> System::AsCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::AsCast(const Source\&) 函数

使用 'as' 运算符进行转换，将源类型转换为结果类型。当源和结果都是智能指针时使用。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Pointer, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 转换。 |

### 返回值

转换结果。如果没有可用的转换，则返回 nullptr。

## System::AsCast(const Source\&) 函数

使用 'as' 运算符进行转换，将源类型转换为结果类型。当源和结果都是智能指针（结果类型中显式使用 SmartPtr<...>）时使用。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::PointerToPointer, Result> System::AsCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 转换。 |

### 返回值

转换结果。如果没有可用的转换，则返回 nullptr。

## System::AsCast(const Source\&) 函数

使用 'as' 运算符进行转换，将源类型转换为结果类型。用于将对象解箱为可空类型。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToNullable, Result> System::AsCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 转换。 |

### 返回值

转换结果。如果没有可用的转换，则返回空的可空类型。

## System::AsCast(const Source\&) 函数

使用 'as' 运算符进行转换，将源类型转换为结果类型。无效的将非对象类型解箱。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceUnboxingToNullable, Result> System::AsCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 转换。 |

### 返回值

始终返回 null。

## System::AsCast(const Source\&) 函数

无效的将非对象类型解箱。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InvalidUnboxing, Result> System::AsCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 转换。 |

### 返回值

始终返回 null。

## System::AsCast(const Source\&) 函数

使用 'as' 运算符进行转换，将源类型转换为结果类型。用于装箱可空对象。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::NullableBoxing, Result> System::AsCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::AsCast(const Source\&) 函数

使用 'as' 运算符进行转换，将源类型转换为结果类型。用于装箱普通对象。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::InterfaceBoxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::AsCast(const Source\&) 函数

使用 'as' 运算符进行转换，将源类型转换为结果类型。用于装箱普通对象。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Boxing, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::AsCast(const Source\&) 函数

使用 'as' 运算符进行转换，将源类型转换为结果类型。用于字符串解箱。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::UnboxingToString, Result> System::AsCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::AsCast(const Source\&) 函数

使用 'as' 运算符进行转换，将源类型转换为结果类型。用于 nullptr 场景的转换。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Null, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 转换。 |

### 返回值

转换结果。

## System::AsCast(const Source\&) 函数

使用 'as' 运算符进行转换，将源类型转换为结果类型。用于在数组之间进行转换。

```cpp
template<typename Result,typename Source> std::enable_if_t<Details::CastType<Source, Result>::Array, typename CastResult<Result>::type> System::AsCast(const Source &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| Source | 源类型。 |
| Result | 结果类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const Source\& | [Object](../object/) 转换。 |

### 返回值

转换结果。如果任何数组成员都没有可用的转换，则返回 nullptr。

## 另请参见

* 类型定义 [Exception](../exception/)
* 结构体 [CastResult](../castresult/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)