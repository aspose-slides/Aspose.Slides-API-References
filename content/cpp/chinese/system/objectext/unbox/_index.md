---
title: Unbox()
second_title: Aspose.Slides for C++ API 参考
description: 在转换为 Object 后解箱值类型。针对枚举类型的实现。
type: docs
weight: 53
url: /zh/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method

在转换为 [Object](../../object/) 后解箱值类型。针对枚举类型的实现。

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | [Enum](../../enum/) 类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 用于解箱。 |

### 返回值

[Enum](../../enum/) 值。

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method

在转换为 [Object](../../object/) 后解箱值类型。针对非枚举且不可为空类型的实现。

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 值类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 用于解箱。 |

### 返回值

已解箱的值。

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method

在转换为 [Object](../../object/) 后解箱值类型。针对非枚举且不可为空类型的实现。

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 值类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 用于解箱。 |

### 返回值

已解箱的值。

## ObjectExt::Unbox(E) method

将枚举类型解箱为整数。

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标整数类型。 |
| E | 源枚举类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| e | E | 用于解箱的值。 |

### 返回值

枚举的整数表示。

## ObjectExt::Unbox(E) method

转换枚举类型。

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标枚举类型。 |
| E | 源枚举类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| e | E | 用于解箱的值。 |

### 返回值

已转换的枚举值。

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) method

解箱字符串值。

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 用于解箱 |

### 返回值

[String](../../string/) 表示已装箱的字符串，如果装箱的字符串为 null，则可为 null。

## 另见

* 类 [SmartPtr](../../smartptr/)
* 类 [Object](../../object/)
* 类 [ObjectExt](../)
* 类 [String](../../string/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)