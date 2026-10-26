---
title: ToString()
second_title: Aspose.Slides C++ API 參考
description: 用於取代 C# ToString 方法，使其可在任何 C++ 類型上使用。
type: docs
weight: 27
url: /zh-hant/system/objectext/tostring/
---
## ObjectExt::ToString(const char_t *) 方法

用於取代 C# ToString 方法，使其可用於任何 C++ 類型。

```cpp
static String System::ObjectExt::ToString(const char_t *obj)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const char_t * | [String](../../string/) 文字常數，將其轉換為字串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## ObjectExt::ToString(const Nullable\<T\>\&) 方法

用於取代 C# ToString 方法，使其可用於任何 C++ 類型。

```cpp
template<typename T> static String System::ObjectExt::ToString(const Nullable<T> &obj)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | [Nullable](../../nullable/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [Nullable](../../nullable/)\<T\>\& | [Nullable](../../nullable/) 物件，將其轉換為字串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## ObjectExt::ToString(const T\&) 方法

用於取代 C# ToString 方法，使其可用於任何 C++ 類型。

```cpp
template<typename T> static std::enable_if<std::is_enum<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | [Enum](../../enum/) 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const T\& | [Enum](../../enum/) 值，將其轉換為字串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## ObjectExt::ToString(const T\&) 方法

用於取代 C# ToString 方法，使其可用於任何 C++ 類型。

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 智能指標類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const T\& | [SmartPtr](../../smartptr/) 值，將其轉換為字串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## ObjectExt::ToString(T\&) 方法

用於取代 C# ToString 方法，使其可用於任何 C++ 類型。

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value||std::is_pointer<T>::value||IsExceptionWrapper<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 智能指標類型或 [ExceptionWrapper](../../exceptionwrapper/)。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | T\& | 智能指標或 [ExceptionWrapper](../../exceptionwrapper/)，將其轉換為字串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## ObjectExt::ToString(T\&) 方法

用於取代 C# ToString 方法，使其可用於任何 C++ 類型。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 標量類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | T\& | 標量值，將其轉換為字串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## ObjectExt::ToString(T\&&) 方法

用於取代 C# ToString 方法，使其可用於任何 C++ 類型。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&std::is_scalar<T>::value &&!std::is_enum<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 標量類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | T\&& | 標量值，將其轉換為字串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## ObjectExt::ToString(T\&) 方法

用於取代 C# ToString 方法，使其可用於任何 C++ 類型。

```cpp
template<typename T> static std::enable_if<!IsExceptionWrapper<T>::value &&!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(T &obj)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 結構類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | T\& | 結構值，將其轉換為字串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## ObjectExt::ToString(const T\&) 方法

用於取代 C# ToString 方法，使其可用於任何 C++ 類型。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value, String>::type System::ObjectExt::ToString(const T &obj)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 結構類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const T\& | 結構值，將其轉換為字串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## ObjectExt::ToString(T\&&) 方法

用於取代 C# ToString 方法，使其可用於任何 C++ 類型。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value &&!std::is_scalar<T>::value &&!IsNullable<T>::value &&!std::is_reference<T>::value, String>::type System::ObjectExt::ToString(T &&obj)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 標量類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | T\&& | 標量值，將其轉換為字串。 |

### 返回值

[String](../../string/) **obj** 的表示形式。

## 另請參見

* 類別 [String](../../string/)
* 類別 [ObjectExt](../)
* 類別 [Nullable](../../nullable/)
* 結構 [IsSmartPtr](../../issmartptr/)
* 結構 [IsExceptionWrapper](../../isexceptionwrapper/)
* 結構 [IsNullable](../../isnullable/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)