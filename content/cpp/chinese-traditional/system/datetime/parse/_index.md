---
title: Parse()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的日期和時間值字串表示轉換為等效的 DateTime 物件。
type: docs
weight: 859
url: /zh-hant/system/datetime/parse/
---
## DateTime::Parse(const String\&) 方法


將指定的日期和時間值字串表示轉換為等效的 [DateTime](../) 物件。

```cpp
static DateTime System::DateTime::Parse(const String &s)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要轉換的日期和時間值字串表示。 |

### 傳回值

一個新的 [DateTime](../) 類別實例，表示與指定字串所代表的日期和時間值等效的值。

## DateTime::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&, Globalization::DateTimeStyles) 方法


使用特定文化的格式資訊，將指定的日期和時間值字串表示轉換為等效的 [DateTime](../) 物件。

```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<IFormatProvider> &provider, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../string/)\& | 要轉換的日期和時間值字串表示。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供特定文化格式資訊的 [IFormatProvider](../../iformatprovider/) 物件。 |
| styles | [Globalization::DateTimeStyles](../../../system.globalization/datetimestyles/) | 一組列舉值的位元組合，提供有關 **s**、可能出現在 **s** 中的樣式元素，或 **s** 轉換為 [DateTime](../) 物件的其他資訊。 |

### 傳回值

一個新的 [DateTime](../) 類別實例，表示與指定字串所代表的日期和時間值等效的值。

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, Globalization::DateTimeStyles) 方法




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::CultureInfo> &culture, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, Globalization::DateTimeStyles) 方法




```cpp
static DateTime System::DateTime::Parse(const String &s, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## DateTime::Parse(const String\&, std::nullptr_t, Globalization::DateTimeStyles) 方法




```cpp
static DateTime System::DateTime::Parse(const String &s, std::nullptr_t, Globalization::DateTimeStyles styles=Globalization::DateTimeStyles::None)
```

## 另見

* 列舉 [DateTimeStyles](../../../system.globalization/datetimestyles/)
* 型別定義 [SharedPtr](../../sharedptr/)
* 類別 [DateTime](../)
* 類別 [String](../../string/)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)