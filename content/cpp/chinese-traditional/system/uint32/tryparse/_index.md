---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考手冊
description: 將包含數字字串表示形式的指定字串轉換為等效的 32 位元無號整數。
type: docs
weight: 14
url: /zh-hant/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) 方法


將包含數字字串表示形式的指定字串轉換為等效的 32 位元無號整數。

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| result | **uint32_t**\& | 參考的 32 位元無號整數變數，放置轉換結果。 |

### 返回值

若轉換成功則傳回 true，否則傳回 false。

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) 方法


使用提供的格式資訊與數字樣式，將包含數字字串表示形式的指定字串轉換為等效的 32 位元無號整數。

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 指定允許的數字字串表示樣式之 NumberStyles 列舉值的位元組合。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字串格式資訊之物件的指標。 |
| result | **uint32_t**\& | 參考的 32 位元無號整數變數，放置轉換結果。 |

### 返回值

若轉換成功則傳回 true，否則傳回 false。

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) 方法




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) 方法




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) 方法




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## 另見

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)