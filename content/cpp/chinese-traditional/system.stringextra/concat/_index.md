---
title: Concat()
second_title: Aspose.Slides for C++ API 參考
description: 將字串陣列串接起來。
type: docs
weight: 1
url: /zh-hant/system.stringextra/concat/
---
## System::StringExtra::Concat(const ArrayPtr\<String\>\&) 函式


將字串陣列串接起來。

```cpp
String System::StringExtra::Concat(const ArrayPtr<String> &parts)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| parts | const [ArrayPtr](../../system/arrayptr/)\<[String](../../system/string/)\>\& | 要合併的字串 [Array](../../system/array/)。 |

### 返回值

合併後的字串。

## System::StringExtra::Concat(const String\&, const String\&) 函式


將字串串接起來。

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | 第一個要串接的字串。 |
| str1 | const [String](../../system/string/)\& | 第二個要串接的字串。 |

### 返回值

合併後的參數字串。

## System::StringExtra::Concat(const String\&, const String\&, const String\&) 函式


將字串串接起來。

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | 第一個要串接的字串。 |
| str1 | const [String](../../system/string/)\& | 第二個要串接的字串。 |
| str2 | const [String](../../system/string/)\& | 第三個要串接的字串。 |

### 返回值

合併後的參數字串。

## System::StringExtra::Concat(const String\&, const String\&, const String\&, const String\&) 函式


將字串串接起來。

```cpp
String System::StringExtra::Concat(const String &str0, const String &str1, const String &str2, const String &str3)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| str0 | const [String](../../system/string/)\& | 第一個要串接的字串。 |
| str1 | const [String](../../system/string/)\& | 第二個要串接的字串。 |
| str2 | const [String](../../system/string/)\& | 第三個要串接的字串。 |
| str3 | const [String](../../system/string/)\& | 第四個要串接的字串。 |

### 返回值

合併後的參數字串。

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) 函式


將多個物件轉為字串並串接結果字串。適用於 [SmartPtr](../../system/smartptr/) 類型的特化。

```cpp
template<typename T> std::enable_if_t<IsSmartPtr<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | 要轉換並合併的 [Object](../../system/object/)。 |

### 返回值

從所有傳入物件的字串表示合併而成的 [String](../../system/string/) 值。

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) 函式


將多個物件轉為字串並串接結果字串。適用於算術類型的特化。

```cpp
template<typename T> std::enable_if_t<std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | 要轉換並合併的 [Object](../../system/object/)。 |

### 返回值

從所有傳入物件的字串表示合併而成的 [String](../../system/string/) 值。

## System::StringExtra::Concat(const ArrayPtr\<T\>\&) 函式


將多個物件轉為字串並串接結果字串。適用於結構和其他值類型的特化。

```cpp
template<typename T> std::enable_if_t<!IsSmartPtr<T>::value &&!std::is_arithmetic<T>::value, String> System::StringExtra::Concat(const ArrayPtr<T> &args)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| args | const [ArrayPtr](../../system/arrayptr/)\<T\>\& | 要轉換並合併的 [Object](../../system/object/)。 |

### 返回值

從所有傳入物件的字串表示合併而成的 [String](../../system/string/) 值。

## 另見

* Typedef [ArrayPtr](../../system/arrayptr/)
* Class [String](../../system/string/)
* Struct [IsSmartPtr](../../system/issmartptr/)
* Namespace [System::StringExtra](../)
* Library [Aspose.Slides](../../)