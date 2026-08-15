---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考
description: 將字串轉換為等價的 TimeSpan 物件並傳回轉換結果。
type: docs
weight: 560
url: /zh-hant/system/timespan/tryparse/
---
## TimeSpan::TryParse(const String\&, TimeSpan\&) 方法


將字串轉換為等價的 [TimeSpan](../) 物件並傳回轉換結果。

```cpp
static bool System::TimeSpan::TryParse(const String &input, TimeSpan &result)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | 輸入字串。 |
| result | [TimeSpan](../)\& | 對應於字串的時間間隔。 |

### 傳回值

True if string was converted successfully; otherwise, false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<IFormatProvider\>\&, TimeSpan\&) 方法


將字串使用指定的格式提供者轉換為等價的 [TimeSpan](../) 物件並傳回轉換結果。

```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<IFormatProvider> &provider, TimeSpan &result)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| input | const [String](../../string/)\& | 輸入字串。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 提供特定文化格式資訊的格式提供者。 |
| result | [TimeSpan](../)\& | 對應於字串的時間間隔。 |

### 傳回值

True if string was converted successfully; otherwise, false.

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&, TimeSpan\&) 方法




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::CultureInfo> &culture, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&, TimeSpan\&) 方法




```cpp
static bool System::TimeSpan::TryParse(const String &input, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi, TimeSpan &result)
```

## TimeSpan::TryParse(const String\&, std::nullptr_t, TimeSpan\&) 方法




```cpp
static bool System::TimeSpan::TryParse(const String &input, std::nullptr_t, TimeSpan &result)
```

## 另請參閱

* Typedef [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [TimeSpan](../)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)