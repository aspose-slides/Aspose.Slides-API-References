---
title: StaticCast()
second_title: Aspose.Slides for C++ API 参考
description: 对 SmartPtr 对象执行静态强制转换。
type: docs
weight: 2523
url: /zh/system/staticcast/
---
## System::StaticCast(SmartPtr\<TFrom\> const\&) 函数


对 [SmartPtr](../smartptr/) 对象执行静态强制转换。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast(SmartPtr<TFrom> const &obj)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| TTo | 目标指向类型。 |
| TFrom | 源指向类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | 源指针。 |

### 返回值

如果允许转换，则返回转换结果。

已废弃
:   为了向后兼容而保留。请改用 ExplicitCast。

## System::StaticCast(WeakPtr\<TFrom\> const\&) 函数


对 [WeakPtr](../weakptr/) 对象执行静态强制转换。

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast(WeakPtr<TFrom> const &obj)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| TTo | 目标指向类型。 |
| TFrom | 源指向类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | 源指针。 |

### 返回值

如果允许转换，则返回转换结果。

已废弃
:   为了向后兼容而保留。请改用 ExplicitCast。

## System::StaticCast(std::nullptr_t) 函数


对空对象执行静态强制转换。

```cpp
template<typename TTo> CastResult<TTo>::type System::StaticCast(std::nullptr_t)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| TTo | 目标指向类型。 |

### 返回值

nullptr。

已废弃
:   为了向后兼容而保留。请改用 ExplicitCast。

## System::StaticCast(TFrom) 函数


针对算术类型的特化。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(TFrom value)
```

## System::StaticCast(TTo) 函数


处理从 [String](../string/) 到 [String](../string/) 的转换。

```cpp
template<typename TTo> std::enable_if<std::is_same<TTo, System::String>::value, TTo>::type System::StaticCast(TTo value)
```

## System::StaticCast(const TFrom *) 函数


针对算术类型的特化。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom *value)
```

## System::StaticCast(const TFrom\&) 函数


对非指针对象执行静态强制转换。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_same<TFrom, System::String>::value &&!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&!std::is_arithmetic<TFrom>::value, TTo>::type System::StaticCast(const TFrom &obj)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| TTo | 目标类型。 |
| TFrom | 源类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const TFrom\& | 源对象。 |

### 返回值

如果允许转换，则返回转换结果。

已废弃
:   为了向后兼容而保留。请改用 ExplicitCast。

## System::StaticCast(const TFrom\&) 函数


对 Exception 对象执行静态强制转换。

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast(const TFrom &obj)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| TTo | 目标异常类型。 |
| TFrom | 源异常类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const TFrom\& | 源指针。 |

### 返回值

如果允许转换，则返回转换结果。

已废弃
:   为了向后兼容而保留。请改用 ExplicitCast。

## System::StaticCast(SmartPtr\<TFrom\>) 函数


对 Objects 执行静态强制转换为 Exception 对象。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast(SmartPtr<TFrom> obj) noexcept
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| TTo | 目标异常类型。 |
| TFrom | [Object](../object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | 源指针。 |

### 返回值

如果允许转换，则返回转换结果。

已废弃
:   为了向后兼容而保留。请改用 ExplicitCast。

## 参见

* 类 [SmartPtr](../smartptr/)
* 类 [WeakPtr](../weakptr/)
* 类 [String](../string/)
* 类 [Object](../object/)
* 结构体 [IsExceptionWrapper](../isexceptionwrapper/)
* 结构体 [CastResult](../castresult/)
* 结构体 [IsSmartPtr](../issmartptr/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)