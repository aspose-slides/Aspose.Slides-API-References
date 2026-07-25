---
title: Is()
second_title: Aspose.Slides for C++ API リファレンス
description: 「is」演算子の変換を実装します。ボックス可能（value）型に対する特殊化で、正確にそれらです。
type: docs
weight: 92
url: /ja/system/objectext/is/
---
## ObjectExt::Is(const T&) メソッド


Implements 'is' operator translation. Specialization for boxable (value) types which exactly is that they are.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | Target type. |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) to test for 'is' operator. Ignored. |

### 戻り値

Always true

## ObjectExt::Is(const U&) メソッド


Implements 'is' operator translation. Specialization for pointer types optimized for 'final' classes.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | Target type. |
| U | Tested type. |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) to test for 'is' operator. |

### 戻り値

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const U&) メソッド


Implements 'is' operator translation. Specialization for pointer types.

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | Target type. |
| U | Tested type. |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) to test for 'is' operator. |

### 戻り値

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const Object&) メソッド


Implements 'is' operator translation. Specialization for value types.

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | Target type. |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) to test for 'is' operator. |

### 戻り値

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const Object&) メソッド


Implements 'is' operator translation. Specialization for unconvertible types.

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | Target type. |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) to test for 'is' operator. |

### 戻り値

Always returns false as types are unconvertible.

## ObjectExt::Is(const SmartPtr\<U\>&) メソッド


Implements 'is' operator translation. Specialization for pointer types.

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | Target type. |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) to test for 'is' operator. |

### 戻り値

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const ExceptionWrapper\<U\>&) メソッド


Implements 'is' operator translation. Specialization for exception wrapper types.

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | Target type. |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) to test for 'is' operator. |

### 戻り値

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const SmartPtr\<Object\>&) メソッド


Implements 'is' operator translation. Specialization for nullable types.

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | Target type. |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) to test for 'is' operator. |

### 戻り値

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const SmartPtr\<Object\>&) メソッド


Implements 'is' operator translation. Specialization for boxable types with == operator defined.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | Target type. |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) to test for 'is' operator. |

### 戻り値

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const SmartPtr\<Object\>&) メソッド


Implements 'is' operator translation. Specialization for boxable types without defined ==.

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | Target type. |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) to test for 'is' operator. |

### 戻り値

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const SmartPtr\<V\>&) メソッド


Implements 'is' operator translation. Specialization value types boxed to interfaces.

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | Target type. |
| V | Type of the pointed object. |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) to test for 'is' operator. |

### 戻り値

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const SmartPtr\<U\>&) メソッド


Implements 'is' operator translation. Specialization for enum types.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | Target type. |
| U | Type of the pointed object. |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) to test for 'is' operator. |

### 戻り値

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const WeakPtr\<U\>&) メソッド


Implements 'is' operator translation. Specialization for enum types vs weak pointers.

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | Target type. |
| U | Type of the pointed object. |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) to test for 'is' operator. |

### 戻り値

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const Nullable\<U\>&) メソッド


Implements 'is' operator translation. Specialization for [Nullable](../../nullable/) type.

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | Target type. |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) type. |

### 戻り値

True if 'is' returns true, false otherwise.

## ObjectExt::Is(const char16_t *) メソッド


Implements 'is' operator translation. Specialization for string literal.

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | Target type. |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) literal. |

### 戻り値

True if 'is' returns true, false otherwise.

## ObjectExt::Is(int32_t) メソッド


Implements 'is' operator translation. Specialization for integer literal.

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```


### テンプレート パラメータ

| Parameter | Description |
| --- | --- |
| T | Target type. |

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| value | **int32_t** | integer literal. |

### 戻り値

True if 'is' returns true, false otherwise.

## 参照

* クラス [ObjectExt](../)
* クラス [Object](../../object/)
* クラス [SmartPtr](../../smartptr/)
* クラス [ExceptionWrapper](../../exceptionwrapper/)
* クラス [WeakPtr](../../weakptr/)
* クラス [Nullable](../../nullable/)
* 構造体 [IsBoxable](../../isboxable/)
* 構造体 [IsSmartPtr](../../issmartptr/)
* 構造体 [IsExceptionWrapper](../../isexceptionwrapper/)
* 構造体 [IsNullable](../../isnullable/)
* 名前空間 [System](../../)
* ライブラリ [Aspose.Slides](../../../)