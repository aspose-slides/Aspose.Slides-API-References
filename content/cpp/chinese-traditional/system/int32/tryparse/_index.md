---
title: TryParse()
second_title: Aspose.Slides for C++ API 參考文件
description: 將指定的字串（其內容為數字的字串表示）轉換為等效的 32 位元有號整數。
type: docs
weight: 14
url: /zh-hant/system/int32/tryparse/
---
## Int32::TryParse(const String\&, int32_t\&) 方法

將指定的字串（其內容為數字的字串表示）轉換為等效的 32 位元有號整數。

```cpp
static bool System::Int32::TryParse(const String &value, int32_t &result)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| result | **int32_t**\& | 用於存放轉換結果的 32 位元有號整數變數的參考。 |

### 回傳值

轉換成功則回傳 True，否則回傳 false。

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int32_t\&) 方法

將指定的字串（其內容為數字的字串表示）使用提供的格式資訊和數字樣式，轉換為等效的 32 位元有號整數。

```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int32_t &result)
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | 要轉換的字串。 |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | 指定允許的數字字串表示樣式之 NumberStyles 列舉值的位元組合。 |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | 包含字串格式資訊之物件的指標。 |
| result | **int32_t**\& | 用於存放轉換結果的 32 位元有號整數變數的參考。 |

### 回傳值

轉換成功則回傳 True，否則回傳 false。

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int32_t\&) 方法




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int32_t\&) 方法




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int32_t &result)
```

## Int32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int32_t\&) 方法




```cpp
static bool System::Int32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int32_t &result)
```

## 相關參考

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int32](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)