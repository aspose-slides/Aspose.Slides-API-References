---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考
description: 將包含數字字串表示的指定字串轉換為等效的單精度浮點值。
type: docs
weight: 14
url: /zh-hant/system/single/tryparse/
---
## Single::TryParse(const String\&, float\&) 方法


將包含數字字串表示的指定字串轉換為等效的單精度浮點值。

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| result | **float**\& | 轉換結果會放入的單精度浮點變數的參考。 |

### 回傳值

True if the conversion succeeded, otherwise - false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, float\&) 方法


使用提供的格式資訊與數字樣式，將包含數字字串表示的指定字串轉換為等效的單精度浮點值。

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | NumberStyles 列舉值的位元組合，指定允許的字串表示樣式。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字串格式資訊之物件的指標。 |
| result | **float**\& | 轉換結果會放入的單精度浮點變數的參考。 |

### 回傳值

True if the conversion succeeded, otherwise - false.

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, float\&) 方法




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, float\&) 方法




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## Single::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, float\&) 方法




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
```

## 參見

* 列舉 [NumberStyles](../../../system.globalization/numberstyles/)
* 型別定義 [SharedPtr](../../sharedptr/)
* 類別 [String](../../string/)
* 類別 [IFormatProvider](../../iformatprovider/)
* 類別 [CultureInfo](../../../system.globalization/cultureinfo/)
* 類別 [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* 結構 [Single](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)