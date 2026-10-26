---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考
description: 將包含數字字串表示的指定字串轉換為等效的 64 位元有號整數。
type: docs
weight: 14
url: /zh-hant/system/int64/tryparse/
---
## Int64::TryParse(const String\&, int64_t\&) 方法

將包含數字字串表示的指定字串轉換為等效的 64 位元有號整數。

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| result | **int64_t**\& | 用於放置轉換結果的 64 位元有號整數變數的參照。 |

### 回傳值

若轉換成功則回傳 true，否則回傳 false。

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) 方法

使用提供的格式資訊與數字樣式，將包含數字字串表示的指定字串轉換為等效的 64 位元有號整數。

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列舉值的位元組合，指定允許的數字字串表示樣式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 指向包含字串格式資訊之物件的指標。 |
| result | **int64_t**\& | 用於放置轉換結果的 64 位元有號整數變數的參照。 |

### 回傳值

若轉換成功則回傳 true，否則回傳 false。

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) 方法




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) 方法




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) 方法




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## 另請參閱

* 列舉 [NumberStyles](../../../system.globalization/numberstyles/)
* 型別別名 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [Int64](../)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)