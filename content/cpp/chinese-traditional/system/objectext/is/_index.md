---
title: Is()
second_title: Aspose.Slides for C++ API 參考
description: 實作 'is' 運算子翻譯。針對可箱裝（值）型別的特殊化，即它們本身即為該型別。
type: docs
weight: 92
url: /zh-hant/system/objectext/is/
---
## ObjectExt::Is(const T\&) 方法


實作 'is' 運算子翻譯。針對可箱裝（值）型別的特殊化，即它們本身即為該型別。

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value, bool>::type System::ObjectExt::Is(const T &obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) 以測試 'is' 運算子。已忽略。 |

### 傳回值

永遠傳回 true

## ObjectExt::Is(const U\&) 方法


實作 'is' 運算子翻譯。針對 'final' 類別最佳化的指標型別的特殊化。

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標型別。 |
| U | 測試型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) 以測試 'is' 運算子。 |

### 傳回值

如果 'is' 傳回 true，則回傳 true；否則回傳 false。

## ObjectExt::Is(const U\&) 方法


實作 'is' 運算子翻譯。針對指標型別的特殊化。

```cpp
template<class T,class U> static std::enable_if<std::is_convertible<T, Object>::value &&!std::is_final<T>::value &&!System::IsBoxable<T>::value &&System::IsSmartPtr<U>::value, bool>::type System::ObjectExt::Is(const U &obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標型別。 |
| U | 測試型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const U\& | [Object](../../object/) 以測試 'is' 運算子。 |

### 傳回值

如果 'is' 傳回 true，則回傳 true；否則回傳 false。

## ObjectExt::Is(const Object\&) 方法


實作 'is' 運算子翻譯。針對值型別的特殊化。

```cpp
template<class T> static std::enable_if<std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) 以測試 'is' 運算子。 |

### 傳回值

如果 'is' 傳回 true，則回傳 true；否則回傳 false。

## ObjectExt::Is(const Object\&) 方法


實作 'is' 運算子翻譯。針對不可轉換型別的特殊化。

```cpp
template<class T> static std::enable_if<!std::is_convertible<T, Object>::value, bool>::type System::ObjectExt::Is(const Object &obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [Object](../../object/)\& | [Object](../../object/) 以測試 'is' 運算子。 |

### 傳回值

永遠傳回 false，因為型別不可轉換。

## ObjectExt::Is(const SmartPtr\<U\>\&) 方法


實作 'is' 運算子翻譯。針對指標型別的特殊化。

```cpp
template<class T,class U> static std::enable_if<IsSmartPtr<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) 以測試 'is' 運算子。 |

### 傳回值

如果 'is' 傳回 true，則回傳 true；否則回傳 false。

## ObjectExt::Is(const ExceptionWrapper\<U\>\&) 方法


實作 'is' 運算子翻譯。針對例外包裝型別的特殊化。

```cpp
template<class T,class U> static std::enable_if<IsExceptionWrapper<T>::value, bool>::type System::ObjectExt::Is(const ExceptionWrapper<U> &obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [ExceptionWrapper](../../exceptionwrapper/)\<U\>\& | [Object](../../object/) 以測試 'is' 運算子。 |

### 傳回值

如果 'is' 傳回 true，則回傳 true；否則回傳 false。

## ObjectExt::Is(const SmartPtr\<Object\>\&) 方法


實作 'is' 運算子翻譯。針對可空型別的特殊化。

```cpp
template<class T> static std::enable_if<IsNullable<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 以測試 'is' 運算子。 |

### 傳回值

如果 'is' 傳回 true，則回傳 true；否則回傳 false。

## ObjectExt::Is(const SmartPtr\<Object\>\&) 方法


實作 'is' 運算子翻譯。針對已定義 == 運算子的可箱裝型別的特殊化。

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 以測試 'is' 運算子。 |

### 傳回值

如果 'is' 傳回 true，則回傳 true；否則回傳 false。

## ObjectExt::Is(const SmartPtr\<Object\>\&) 方法


實作 'is' 運算子翻譯。針對未定義 == 運算子的可箱裝型別的特殊化。

```cpp
template<class T> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<Object> &obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 以測試 'is' 運算子。 |

### 傳回值

如果 'is' 傳回 true，則回傳 true；否則回傳 false。

## ObjectExt::Is(const SmartPtr\<V\>\&) 方法


實作 'is' 運算子翻譯。針對被箱裝為介面的值型別的特殊化。

```cpp
template<class T,class V> static std::enable_if<System::IsBoxable<T>::value &&!IsNullable<T>::value &&!std::is_enum<T>::value &&!std::is_same<V, Object>::value, bool>::type System::ObjectExt::Is(const SmartPtr<V> &obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標型別。 |
| V | 指向物件的型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<V\>\& | [Object](../../object/) 以測試 'is' 運算子。 |

### 傳回值

如果 'is' 傳回 true，則回傳 true；否則回傳 false。

## ObjectExt::Is(const SmartPtr\<U\>\&) 方法


實作 'is' 運算子翻譯。針對列舉型別的特殊化。

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const SmartPtr<U> &obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標型別。 |
| U | 指向物件的型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<U\>\& | [Object](../../object/) 以測試 'is' 運算子。 |

### 傳回值

如果 'is' 傳回 true，則回傳 true；否則回傳 false。

## ObjectExt::Is(const WeakPtr\<U\>\&) 方法


實作 'is' 運算子翻譯。針對列舉型別與弱指標的特殊化。

```cpp
template<class T,class U> static std::enable_if<std::is_enum<T>::value, bool>::type System::ObjectExt::Is(const WeakPtr<U> &obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標型別。 |
| U | 指向物件的型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [WeakPtr](../../weakptr/)\<U\>\& | [Object](../../object/) 以測試 'is' 運算子。 |

### 傳回值

如果 'is' 傳回 true，則回傳 true；否則回傳 false。

## ObjectExt::Is(const Nullable\<U\>\&) 方法


實作 'is' 運算子翻譯。針對 [Nullable](../../nullable/) 型別的特殊化。

```cpp
template<class T,class U> static bool System::ObjectExt::Is(const Nullable<U> &value)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [Nullable](../../nullable/)\<U\>\& | [Nullable](../../nullable/) 型別。 |

### 傳回值

如果 'is' 傳回 true，則回傳 true；否則回傳 false。

## ObjectExt::Is(const char16_t *) 方法


實作 'is' 運算子翻譯。針對字串文字的特殊化。

```cpp
template<class T> static bool System::ObjectExt::Is(const char16_t *str)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| str | const char16_t * | [String](../../string/) 常量。 |

### 傳回值

如果 'is' 傳回 true，則回傳 true；否則回傳 false。

## ObjectExt::Is(int32_t) 方法


實作 'is' 運算子翻譯。針對整數常量的特殊化。

```cpp
template<class T> static bool System::ObjectExt::Is(int32_t value)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | **int32_t** | 整數常量。 |

### 傳回值

如果 'is' 傳回 true，則回傳 true；否則回傳 false。

## 參見

* 類別 [ObjectExt](../)
* 類別 [Object](../../object/)
* 類別 [SmartPtr](../../smartptr/)
* 類別 [ExceptionWrapper](../../exceptionwrapper/)
* 類別 [WeakPtr](../../weakptr/)
* 類別 [Nullable](../../nullable/)
* 結構 [IsBoxable](../../isboxable/)
* 結構 [IsSmartPtr](../../issmartptr/)
* 結構 [IsExceptionWrapper](../../isexceptionwrapper/)
* 結構 [IsNullable](../../isnullable/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)