---
title: Unbox()
second_title: Aspose.Slides for C++ API 參考
description: 在轉換為 Object 後解除值類型的裝箱。針對列舉型別的實作。
type: docs
weight: 53
url: /zh-hant/system/objectext/unbox/
---
## ObjectExt::Unbox(const SmartPtr\<Object\>\&) 方法

在轉換為[Object](../../object/)之後解除裝箱值類型。針對列舉型別的實作。

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Enum](../../enum/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 以解除裝箱。 |

### 回傳值

[Enum](../../enum/) 值。

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) 方法

在轉換為[Object](../../object/)之後解除裝箱值類型。針對非列舉且非可為 null 的型別之實作。

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 值類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 以解除裝箱。 |

### 回傳值

解除裝箱後的值。

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) 方法

在轉換為[Object](../../object/)之後解除裝箱值類型。針對非列舉且非可為 null 的型別之實作。

```cpp
template<class T> static std::enable_if<!std::is_enum<T>::value &&!detail::has_operator_equal<T>::value, T>::type System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 值類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 以解除裝箱。 |

### 回傳值

解除裝箱後的值。

## ObjectExt::Unbox(E) 方法

將列舉型別解除裝箱為整數。

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::numeric_limits<T>::is_integer, T>::type System::ObjectExt::Unbox(E e)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標整數型別。 |
| E | 來源列舉型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| e | E | 要解除裝箱的值。 |

### 回傳值

列舉的整數表示。

## ObjectExt::Unbox(E) 方法

轉換列舉型別。

```cpp
template<class T,class E> static std::enable_if<std::is_enum<E>::value &&std::is_enum<T>::value, T>::type System::ObjectExt::Unbox(E e)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 目標列舉型別。 |
| E | 來源列舉型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| e | E | 要解除裝箱的值。 |

### 回傳值

已轉換的列舉值。

## ObjectExt::Unbox(const SmartPtr\<Object\>\&) 方法

解除字串值的裝箱。

```cpp
String System::ObjectExt::Unbox(const SmartPtr<Object> &obj)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SmartPtr](../../smartptr/)\<[Object](../../object/)\>\& | [Object](../../object/) 以解除裝箱 |

### 回傳值

[String](../../string/) 已裝箱字串的表示形式，如果已裝箱的字串為 null，則可能為 null。

## 參考資訊

* 類別 [SmartPtr](../../smartptr/)
* 類別 [Object](../../object/)
* 類別 [ObjectExt](../)
* 類別 [String](../../string/)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)