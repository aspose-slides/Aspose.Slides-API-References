---
title: DynamicCast_noexcept()
second_title: Aspose.Slides for C++ API 参考
description: 旧的已废弃转换。将在未来的版本中移除。
type: docs
weight: 2484
url: /zh/system/dynamiccast_noexcept/
---
## System::DynamicCast_noexcept(const TFrom\&) 函数


旧的已废弃转换。将在未来的版本中移除。

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast_noexcept(const TFrom &obj) noexcept
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

如果允许转换则返回转换结果，否则返回 nullptr。

## 备注


对 Exception 对象执行动态转换。已弃用
:   为了向后兼容而保留。请改用 AsCast。

## System::DynamicCast_noexcept(SmartPtr\<TFrom\> const\&) 函数


对 [SmartPtr](../smartptr/) 对象执行动态转换。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast_noexcept(SmartPtr<TFrom> const &obj) noexcept
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

如果允许转换则返回转换结果，否则返回 nullptr。

已弃用
:   为了向后兼容而保留。请改用 AsCast。

## System::DynamicCast_noexcept(SmartPtr\<TFrom\>) 函数


对对象执行动态转换为 Exception 对象。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast_noexcept(SmartPtr<TFrom> obj) noexcept
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

如果允许转换则返回转换结果，否则返回 nullptr。

已弃用
:   为了向后兼容而保留。请改用 AsCast。

## 参见

* 类 [SmartPtr](../smartptr/)
* 类 [Object](../object/)
* 结构体 [IsExceptionWrapper](../isexceptionwrapper/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)