---
title: String()
second_title: Aspose.Slides for C++ API 參考
description: 預設建構函式。建立被視為 null 的字串物件。
type: docs
weight: 14
url: /zh-hant/system/string/string/
---
## String::String() 建構函式

預設建構函式。建立被視為 null 的字串物件。

```cpp
System::String::String()
```

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char16_t\>::value\>::type *) 建構函式

根據字串常值建構字串。將常值視為以 null 結尾的字串，根據常值大小計算目標字串長度。

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char16_t>::value>::type *=nullptr)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | T\& | [String](../) 文字指標。 |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char16_t\>::value\>::type *) 建構函式

根據字元字串指標建構字串。將指向的字串視為以 null 結尾，根據 null 字元計算目標字串長度。

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char16_t>::value>::type *=nullptr)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | const T\& | 字元字串指標。 |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, char\>::value\>::type *) 建構函式

根據字串常值建構字串。將常值視為 UTF8 中以 null 結尾的字串，根據常值大小計算目標字串長度。

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, char>::value>::type *=nullptr)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | T\& | [String](../) 文字指標。 |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, char\>::value\>::type *) 建構函式

根據字元字串指標建構字串。將指向的字串視為 UTF8 中以 null 結尾，根據 null 字元計算目標字串長度。

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, char>::value>::type *=nullptr)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | const T\& | 字元字串指標。 |

## String::String(const char16_t *, int) 建構函式

根據字元字串指標與明確長度建構字串。

```cpp
System::String::String(const char16_t *str, int length)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| str | const char16_t * | [String](../) 指標，可為常值或陣列。 |
| length | int | 明確的字串長度 |

## String::String(const ReadOnlySpan\<char16_t\>\&) 建構函式

將 [System.String](../) 類別的新實例初始化為指定唯讀 span 中的 Unicode 字元。

```cpp
System::String::String(const ReadOnlySpan<char16_t> &value)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | const [ReadOnlySpan](../../readonlyspan/)\<char16_t\>\& | 唯讀的 Unicode 字元 span。 |

## String::String(const char *, int) 建構函式

根據字元字串指標與明確長度建構字串。

```cpp
System::String::String(const char *str, int length)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| str | const char * | [String](../) 指向 UTF8 資料的指標，可為常值或陣列。 |
| length | int | 明確的字串長度 |

## String::String(const char16_t *, int, int) 建構函式

根據字元字串指標、起始位置與長度建構字串。

```cpp
System::String::String(const char16_t *str, int start, int length)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| str | const char16_t * | [String](../) 指標，可為常值或陣列。 |
| start | int | 起始位置。 |
| length | int | [String](../) 長度。 |

## String::String(const char16_t, int) 建構函式

填充建構函式。

```cpp
System::String::String(const char16_t ch, int count)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| ch | const char16_t | 填充字元。 |
| count | int | 目標長度。 |

## String::String(const T\&, typename std::enable_if\<std::is_same\<T, std::nullptr_t\>::value\>::type *) 建構函式

nullptr 建構函式。宣告為模板以解決與其他模板建構函式的優先權。

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<std::is_same<T, std::nullptr_t>::value>::type *=nullptr)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 應為 nullptr_t |

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | const T\& | nullptr |

## String::String(T\&, typename std::enable_if\<IsStringLiteral\<T, wchar_t\>::value\>::type *) 建構函式

根據寬字串常值建構字串。將常值視為以 null 結尾的字串，根據常值大小計算目標字串長度。某些平台上從 **wchar_t** 的轉換耗時較長，因而不允許隱式轉換。

```cpp
template<typename T> System::String::String(T &value, typename std::enable_if<IsStringLiteral<T, wchar_t>::value>::type *=nullptr)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | T\& | [String](../) 文字指標。 |

## String::String(const T\&, typename std::enable_if\<IsStringPointer\<T, wchar_t\>::value\>::type *) 建構函式

根據寬字元字串指標建構字串。將指向的字串視為以 null 結尾，根據 null 字元計算目標字串長度。某些平台上從 **wchar_t** 的轉換耗時較長，因而不允許隱式轉換。

```cpp
template<typename T> System::String::String(const T &value, typename std::enable_if<IsStringPointer<T, wchar_t>::value>::type *=nullptr)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| value | const T\& | 字元字串指標。 |

## String::String(const wchar_t *, int) 建構函式

根據寬字元字串指標與明確長度建構字串。某些平台上從 **wchar_t** 的轉換耗時較長，因而不允許隱式轉換。

```cpp
System::String::String(const wchar_t *str, int length)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| str | const **wchar_t** * | [String](../) 指標，可為常值或陣列。 |
| length | int | 明確的字串長度 |

## String::String(const wchar_t, int) 建構函式

填充建構函式。某些平台上從 **wchar_t** 的轉換耗時較長，因而不允許隱式轉換。

```cpp
System::String::String(const wchar_t ch, int count=1)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| ch | const **wchar_t** | 填充字元。 |
| count | int | 目標長度。 |

## String::String(const String\&) 建構函式

拷貝建構函式。

```cpp
System::String::String(const String &str)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| str | const [String](../)\& | [String](../) 用於拷貝。 |

## String::String(String\&&) 建構函式

移動建構函式。

```cpp
System::String::String(String &&str) noexcept
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| str | [String](../)\&& | [String](../) 用於移動資料來源。 |

## String::String(const ArrayPtr\<char16_t\>\&) 建構函式

將整個字元陣列轉換為字串。

```cpp
System::String::String(const ArrayPtr<char16_t> &arr)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | [Array](../../array/) 用於轉換為字串。 |

## String::String(const ArrayPtr\<char16_t\>\&, int, int) 建構函式

將字元陣列子範圍轉換為字串。若參數超出陣列範圍，則會建構空字串。

```cpp
System::String::String(const ArrayPtr<char16_t> &arr, int offset, int len)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| arr | const [ArrayPtr](../../arrayptr/)\<char16_t\>\& | 字元陣列。 |
| offset | int | 子陣列起始索引。 |
| len | int | 子陣列長度。 |

## String::String(const codeporting_icu::UnicodeString\&) 建構函式

將 UnicodeString 包裝到 [String](../) 中。

```cpp
System::String::String(const codeporting_icu::UnicodeString &str)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| str | const codeporting_icu::UnicodeString\& | UnicodeString 用於包裝到 [String](../)。 |

## String::String(codeporting_icu::UnicodeString\&&) 建構函式

移動建構函式。

```cpp
System::String::String(codeporting_icu::UnicodeString &&str) noexcept
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| str | codeporting_icu::UnicodeString\&& | UnicodeString 用於包裝到 [String](../)。 |

## String::String(const std::wstring\&) 建構函式

從寬字串建立 [String](../)。

```cpp
System::String::String(const std::wstring &str)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| str | const std::wstring\& | 寬字串用於轉換成 [String](../)。 |

## String::String(const std::u16string\&) 建構函式

從 UTF-16 字串建立 [String](../)。

```cpp
System::String::String(const std::u16string &str)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| str | const std::u16string\& | UTF-16 字串用於轉換成 [String](../)。 |

## String::String(const std::string\&) 建構函式

從以 UTF-8 格式呈現的 std::string 字串建立 [String](../)。

```cpp
System::String::String(const std::string &utf8str)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| utf8str | const std::string\& | std::string 字串用於轉換成 [String](../)。 |

## String::String(const std::u32string\&) 建構函式

從 std::u32string 字串建立 [String](../)。

```cpp
System::String::String(const std::u32string &u32str)
```

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| u32str | const std::u32string\& | std::u32string 字串用於轉換成 [String](../)。 |

## 另請參閱

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Class [ReadOnlySpan](../../readonlyspan/)
* Struct [IsStringLiteral](../../isstringliteral/)
* Struct [IsStringPointer](../../isstringpointer/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)