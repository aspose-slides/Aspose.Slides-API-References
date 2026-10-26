---
title: DynamicCast()
second_title: Aspose.Slides for C++ API 参考
description: 对 Exception 对象执行动态转换。
type: docs
weight: 2497
url: /zh/system/dynamiccast/
---
## System::DynamicCast(const TFrom\&) 函数

对 Exception 对象执行动态转换。

```cpp
template<typename TTo,typename TFrom> std::enable_if<IsExceptionWrapper<TFrom>::value &&IsExceptionWrapper<TTo>::value &&(std::is_convertible<TTo, TFrom>::value||std::is_base_of<TTo, TFrom>::value), TTo>::type System::DynamicCast(const TFrom &obj)
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

如果允许转换，则返回转换结果。

已弃用
:   保留用于向后兼容。请改用 ExplicitCast。

## System::DynamicCast(SmartPtr\<TFrom\> const\&) 函数

对 [SmartPtr](../smartptr/) 对象执行动态转换。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!std::is_enum<TTo>::value &&!IsExceptionWrapper<TTo>::value, typenameCastResult<TTo>::type>::type System::DynamicCast(SmartPtr<TFrom> const &obj)
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

已弃用
:   保留用于向后兼容。请改用 ExplicitCast。

## System::DynamicCast(SmartPtr\<TFrom\>) 函数

通过转换解箱已装箱的枚举。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_enum<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TTo | 目标枚举类型。 |
| TFrom | 源指向类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | [SmartPtr](../smartptr/)\<TFrom\> | 用于解箱数据的对象指针。 |

### 返回值

解箱后的枚举值。

已弃用
:   保留用于向后兼容。请改用 ExplicitCast。

## System::DynamicCast(std::nullptr_t) 函数

对空对象执行动态转换。

```cpp
template<typename TTo> CastResult<TTo>::type System::DynamicCast(std::nullptr_t) noexcept
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TTo | 目标指向类型。 |

### 返回值

nullptr。

已弃用
:   保留用于向后兼容。请改用 ExplicitCast。

## System::DynamicCast(TFrom\&) 函数

对非指针对象执行动态转换。

```cpp
template<typename TTo,typename TFrom> std::enable_if<!IsExceptionWrapper<TFrom>::value &&!IsSmartPtr<TFrom>::value &&std::is_convertible<TTo, TFrom>::value, TTo>::type System::DynamicCast(TFrom &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TTo | 目标类型。 |
| TFrom | 源类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | TFrom\& | 源对象。 |

### 返回值

转换结果。

已弃用
:   保留用于向后兼容。请改用 ExplicitCast。

## System::DynamicCast(SmartPtr\<TFrom\>) 函数

对对象执行动态转换为 Exception 对象。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_same<System::Object, TFrom>::value &&IsExceptionWrapper<TTo>::value, TTo>::type System::DynamicCast(SmartPtr<TFrom> obj)
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

如果允许转换，则返回转换结果。

已弃用
:   保留用于向后兼容。请改用 ExplicitCast。

## System::DynamicCast(TFrom) 函数

从 IntPtr 到指针执行动态转换。

```cpp
template<typename TTo,typename TFrom> std::enable_if<std::is_pointer<TTo>::value &&std::is_same<IntPtr, TFrom>::value, TTo>::type System::DynamicCast(TFrom value) noexcept
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| TTo | 目标类型。 |
| TFrom | 源类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | TFrom | 源 IntPtr 值。 |

### 返回值

转换结果。

已弃用
:   保留用于向后兼容。请改用 ExplicitCast。

## 另见

* 类 [SmartPtr](../smartptr/)
* 类 [Object](../object/)
* 结构体 [IsExceptionWrapper](../isexceptionwrapper/)
* 结构体 [CastResult](../castresult/)
* 结构体 [IsSmartPtr](../issmartptr/)
* 命名空间 [System](../)
* 库 [Aspose.Slides](../../)