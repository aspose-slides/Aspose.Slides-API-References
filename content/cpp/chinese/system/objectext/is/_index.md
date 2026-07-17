---
title: Is()
second_title: Aspose.Slides for C++ API 参考
description: 实现 'is' 运算符的转换。针对可装箱（值）类型的特化，即它们正是如此。
type: docs
weight: 92
url: /zh/system/objectext/is/
---
## ObjectExt::Is(const T\&) 方法

实现 'is' 运算符的转换。针对可装箱（值）类型的特化，它们正是如此。

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) 用于测试 'is' 运算符。已忽略。 |

### 返回值

始终为 true

## ObjectExt::Is(const U\&) 方法

实现 'is' 运算符的转换。针对指针类型的特化，针对 'final' 类进行了优化。

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标类型。 |
| U | 被测试的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) 用于测试 'is' 运算符。 |

### 返回值

如果 'is' 返回 true，则为 true；否则为 false。

## ObjectExt::Is(const U\&) 方法

实现 'is' 运算符的转换。针对指针类型的特化。

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标类型。 |
| U | 被测试的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) 用于测试 'is' 运算符。 |

### 返回值

如果 'is' 返回 true，则为 true；否则为 false。

## ObjectExt::Is(const Object\&) 方法

实现 'is' 运算符的转换。针对值类型的特化。

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) 用于测试 'is' 运算符。 |

### 返回值

如果 'is' 返回 true，则为 true；否则为 false。

## ObjectExt::Is(const Object\&) 方法

实现 'is' 运算符的转换。针对不可转换类型的特化。

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) 用于测试 'is' 运算符。 |

### 返回值

始终返回 false，因为类型不可转换。

## ObjectExt::Is(const SmartPtr\<U\>\&) 方法

实现 'is' 运算符的转换。针对指针类型的特化。

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) 用于测试 'is' 运算符。 |

### 返回值

如果 'is' 返回 true，则为 true；否则为 false。

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) 方法

实现 'is' 运算符的转换。针对异常包装类型的特化。

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) 用于测试 'is' 运算符。 |

### 返回值

如果 'is' 返回 true，则为 true；否则为 false。

## ObjectExt::Is(const SmartPtr\<Object\>\&) 方法

实现 'is' 运算符的转换。针对可为空类型的特化。

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 用于测试 'is' 运算符。 |

### 返回值

如果 'is' 返回 true，则为 true；否则为 false。

## ObjectExt::Is(const SmartPtr\<Object\>\&) 方法

实现 'is' 运算符的转换。针对定义了 == 运算符的可装箱类型的特化。

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 用于测试 'is' 运算符。 |

### 返回值

如果 'is' 返回 true，则为 true；否则为 false。

## ObjectExt::Is(const SmartPtr\<Object\>\&) 方法

实现 'is' 运算符的转换。针对未定义 == 的可装箱类型的特化。

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 用于测试 'is' 运算符。 |

### 返回值

如果 'is' 返回 true，则为 true；否则为 false。

## ObjectExt::Is(const SmartPtr\<V\>\&) 方法

实现 'is' 运算符的转换。针对值类型装箱为接口的特化。

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标类型。 |
| V | 指向对象的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) 用于测试 'is' 运算符。 |

### 返回值

如果 'is' 返回 true，则为 true；否则为 false。

## ObjectExt::Is(const SmartPtr\<U\>\&) 方法

实现 'is' 运算符的转换。针对枚举类型的特化。

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标类型。 |
| U | 指向对象的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) 用于测试 'is' 运算符。 |

### 返回值

如果 'is' 返回 true，则为 true；否则为 false。

## ObjectExt::Is(const WeakPtr\<U\>\&) 方法

实现 'is' 运算符的转换。针对枚举类型与弱指针的特化。

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标类型。 |
| U | 指向对象的类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) 用于测试 'is' 运算符。 |

### 返回值

如果 'is' 返回 true，则为 true；否则为 false。

## ObjectExt::Is(const Nullable\<U\>\&) 方法

实现 'is' 运算符的转换。针对 [Nullable](../../nullable/) 类型的特化。

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) 类型。 |

### 返回值

如果 'is' 返回 true，则为 true；否则为 false。

## ObjectExt::Is(const char16_t *) 方法

实现 'is' 运算符的转换。针对字符串字面量的特化。

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) 字面量。 |

### 返回值

如果 'is' 返回 true，则为 true；否则为 false。

## ObjectExt::Is(int32_t) 方法

实现 'is' 运算符的转换。针对整数字面量的特化。

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```

### 模板参数

| 参数 | 描述 |
| --- | --- |
| T | 目标类型。 |

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | **int32_t** | 整数字面量。 |

### 返回值

如果 'is' 返回 true，则为 true；否则为 false。

## 另请参见

* 类 [ObjectExt](../)
* 类 [Object](../../object/)
* 类 [SmartPtr](../../smartptr/)
* 类 [ExceptionWrapper](../../exceptionwrapper/)
* 类 [WeakPtr](../../weakptr/)
* 类 [Nullable](../../nullable/)
* 结构体 [IsBoxable](../../isboxable/)
* 结构体 [IsSmartPtr](../../issmartptr/)
* 结构体 [IsExceptionWrapper](../../isexceptionwrapper/)
* 结构体 [IsNullable](../../isnullable/)
* 命名空间 [System](../../)
* 库 [Aspose.Slides](../../../)