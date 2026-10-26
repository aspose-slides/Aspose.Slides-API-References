---
title: StaticCast_noexcept()
second_title: Aspose.Slides C++ API 参考
description: 对 SmartPtr 对象执行静态转换。
type: docs
weight: 2510
url: /zh/system/staticcast_noexcept/
---
## System::StaticCast_noexcept(SmartPtr\<TFrom\> const\&) 函数


对 [SmartPtr](../smartptr/) 对象执行静态转换。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::StaticCast_noexcept(SmartPtr<TFrom> const &obj)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| TTo | 目标指向的类型。 |
| TFrom | 源指向的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> const\& | 源指针。 |

### 返回值

Cast result if cast is allowed or nullptr otherwise.

已弃用
:   为了向后兼容而保留。请改用 AsCast。

## System::StaticCast_noexcept(WeakPtr\<TFrom\> const\&) 函数


对 [WeakPtr](../weakptr/) 对象执行静态转换。

```cpp
template<typename TTo,typename TFrom> CastResult<TTo>::type System::StaticCast_noexcept(WeakPtr<TFrom> const &obj)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| TTo | 目标指向的类型。 |
| TFrom | 源指向的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [WeakPtr](../weakptr/)\<TFrom\> const\& | 源指针。 |

### 返回值

Cast result if cast is allowed or nullptr otherwise.

已弃用
:   为了向后兼容而保留。请改用 AsCast。

## System::StaticCast_noexcept(const TFrom\&) 函数


对 Exception 对象执行静态转换。

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::StaticCast_noexcept(const TFrom &obj)
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| TTo | 目标 Exception 类型。 |
| TFrom | 源 Exception 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const TFrom\& | 源指针。 |

### 返回值

Cast result if cast is allowed or nullptr otherwise.

已弃用
:   为了向后兼容而保留。请改用 AsCast。

## System::StaticCast_noexcept(SmartPtr\<TFrom\>) 函数


对对象执行静态转换为 Exception 对象。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::StaticCast_noexcept(SmartPtr<TFrom> obj) noexcept
```


### 模板参数

| 参数 | 描述 |
| --- | --- |
| TTo | 目标 Exception 类型。 |
| TFrom | [Object](../object/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | 源指针。 |

### 返回值

Cast result if cast is allowed or nullptr otherwise.

已弃用
:   为了向后兼容而保留。请改用 AsCast。

## 另请参阅

* 类 [SmartPtr](../smartptr/)
* 类 [WeakPtr](../weakptr/)
* 类 [Object](../object/)
* 结构体 [IsExceptionWrapper](../isexceptionwrapper/)
* 结构体 [CastResult](../castresult/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)