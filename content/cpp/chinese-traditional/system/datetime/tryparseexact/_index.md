---
title: TryParseExact()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的日期時間值字串表示轉換為相等的 DateTime 物件，使用指定的格式、文化特定的格式資訊和樣式。字串表示的格式必須完全符合指定的格式。
type: docs
weight: 898
url: /zh-hant/system/datetime/tryparseexact/
---
## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method

將指定的日期時間值字串表示轉換為相等的 [DateTime](../) 物件，使用指定的格式、文化特定的格式資訊和樣式。字串表示的格式必須完全符合指定的格式。

```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要轉換的日期時間值的字串表示。 |
| format | const [String](../../string/)\& | 字串格式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供文化特定格式資訊的 [IFormatProvider](../../iformatprovider/) 物件。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 列舉值的位元組合，提供有關 **s**、可能出現在 **s** 中的樣式元素，或 **s** 轉換為 [DateTime](../) 物件的其他資訊。 |
| result | [DateTime](../)\& | 輸出參數；如果轉換成功，則其中包含轉換結果。 |

### 返回值

如果轉換成功則返回 True，否則返回 false.

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const String\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const String &format, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime\&) method

將指定的日期時間值字串表示轉換為相等的 [DateTime](../) 物件，使用指定的格式、文化特定的格式資訊和樣式。字串表示的格式必須完全符合一個或多個指定的格式。

```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要轉換的日期時間值的字串表示。 |
| formats | const [ArrayPtr](../../arrayptr/)\<[String](../../string/)\>\& | 字串格式的陣列。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供文化特定格式資訊的 [IFormatProvider](../../iformatprovider/) 物件。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 列舉值的位元組合，提供有關 **s**、可能出現在 **s** 中的樣式元素，或 **s** 轉換為 [DateTime](../) 物件的其他資訊。 |
| result | [DateTime](../)\& | 輸出參數；如果轉換成功，則其中包含轉換結果。 |

### 返回值

如果轉換成功則返回 True，否則返回 false.

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParseExact(const String\&, const ArrayPtr\<String\>\&, std::nullptr_t, Globalization::DateTimeStyles, DateTime\&) method




```cpp
static bool System::DateTime::TryParseExact(const String &s, const ArrayPtr<String> &formats, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## 相關參見

* 列舉 [DateTimeStyles](../../../system.globalization/datetimestyles/)
* 型別別名 [SharedPtr](../../sharedptr/)
* 型別別名 [ArrayPtr](../../arrayptr/)
* 類別 [String](../../string/)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [DateTime](../)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)