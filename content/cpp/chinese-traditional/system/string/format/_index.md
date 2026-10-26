---
title: Format()
second_title: Aspose.Slides for C++ API 參考文件
description: 以 C# 風格格式化字串。
type: docs
weight: 885
url: /zh-hant/system/string/format/
---
## String::Format(const SharedPtr\<IFormatProvider\>\&, const String\&, const Args\&...) method

以 C# 風格格式化字串。

```cpp
template<class...> String System::String::Format(const SharedPtr<IFormatProvider> &fp, const String &format, const Args &... args)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| Args | 用於格式化字串的參數。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| fp | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 用於將參數轉換為字串的格式提供者。 |
| format | const [String](../)\& | 格式字串。 |
| args | const Args\&... | 用於格式化字串的參數。 |

## String::Format(std::nullptr_t, const String\&, const Args\&...) method

以 C# 風格格式化字串。

```cpp
template<class...> String System::String::Format(std::nullptr_t, const String &format, const Args &... args)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| Args | 用於格式化字串的參數。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| format | std::nullptr_t | 格式字串。 |
| args | const [String](../)\& | 用於格式化字串的參數。 |

## String::Format(std::nullptr_t, const char16_t(&), const Args\&...) method

以 C# 風格格式化字串。

```cpp
template<std::size_t,class...> String System::String::Format(std::nullptr_t, const char16_t(&format)[N], const Args &... args)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| Args | 用於格式化字串的參數。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| format | std::nullptr_t | 格式字串。 |
| args | const char16_t(&) | 用於格式化字串的參數。 |

## String::Format(const String\&, const Args\&...) method

以 C# 風格格式化字串。

```cpp
template<class...> String System::String::Format(const String &format, const Args &... args)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| Args | 用於格式化字串的參數。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| format | const [String](../)\& | 格式字串。 |
| args | const Args\&... | 用於格式化字串的參數。 |

## String::Format(const String\&, const System::ArrayPtr\<T\>\&) method

以 C# 風格格式化字串。

```cpp
template<class T> String System::String::Format(const String &format, const System::ArrayPtr<T> &args)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 用於格式化字串的參數。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| format | const [String](../)\& | 格式字串。 |
| args | const [System::ArrayPtr](../../arrayptr/)\<T\>\& | 用於格式化字串的參數。 |

## 參見

* 型別別名 [SharedPtr](../../sharedptr/)
* 型別別名 [ArrayPtr](../../arrayptr/)
* 類別 [String](../)
* 類別 [IFormatProvider](../../iformatprovider/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)