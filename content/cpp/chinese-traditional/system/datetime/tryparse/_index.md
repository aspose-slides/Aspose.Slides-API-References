---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的日期和時間值的字串表示形式轉換為等效的 DateTime 物件。
type: docs
weight: 885
url: /zh-hant/system/datetime/tryparse/
---
## DateTime::TryParse(const String&, DateTime&) 方法


將指定的日期和時間值的字串表示形式轉換為等效的 [DateTime](../) 物件。

```cpp
static bool System::DateTime::TryParse(const String &s, DateTime &result)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要轉換的日期和時間值的字串表示形式。 |
| result | [DateTime](../)\& | 輸出參數，若轉換成功，則包含轉換結果。 |

### 返回值

若轉換成功則為 true，否則為 false。

## DateTime::TryParse(const String&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles, DateTime&) 方法


將指定的日期和時間值的字串表示形式轉換為等效的 [DateTime](../) 物件，使用指定的特定文化格式資訊與樣式。

```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles, DateTime &result)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要轉換的日期和時間值的字串表示形式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供特定文化格式資訊的 [IFormatProvider](../../iformatprovider/) 物件。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 提供關於 **s**、可能出現在 **s** 中的樣式元素，或關於從 **s** 轉換為 [DateTime](../) 物件的其他資訊的列舉值的位元組合。 |
| result | [DateTime](../)\& | 輸出參數，若轉換成功，則包含轉換結果。 |

### 返回值

若轉換成功則為 true，否則為 false。

## DateTime::TryParse(const String&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles, DateTime&) 方法




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles, DateTime&) 方法




```cpp
static bool System::DateTime::TryParse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles, DateTime &result)
```

## DateTime::TryParse(const String&, std::nullptr_t, Globalization::DateTimeStyles, DateTime&) 方法




```cpp
static bool System::DateTime::TryParse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles, DateTime &result)
```

## 另請參閱

* 列舉 [DateTimeStyles](../../../system.globalization/datetimestyles/)
* 類型定義 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [DateTime](../)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)