---
title: UInt32
second_title: Aspose.Slides for C++ API 參考
description: 包含用於處理無號 32 位元整數的方法。
type: docs
weight: 1977
url: /zh-hant/system/uint32/
---
## UInt32 結構

包含用於處理無號 32 位元整數的方法。

```cpp
class UInt32
```

## 方法

| Method | Description |
| --- | --- |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&) | 將指定的字串（其內容為數字的字串表示形式）轉換為等效的 32 位元無號整數。 |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式資訊，將指定的字串（其內容為數字的字串表示形式）轉換為等效的 32 位元無號整數。 |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式資訊和數字樣式，將指定的字串（其內容為數字的字串表示形式）轉換為等效的 32 位元無號整數。 |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint32_t**\&) | 將指定的字串（其內容為數字的字串表示形式）轉換為等效的 32 位元無號整數。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint32_t**\&) | 使用提供的格式資訊和數字樣式，將指定的字串（其內容為數字的字串表示形式）轉換為等效的 32 位元無號整數。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint32_t**\&) |  |

## 欄位

| Field | Description |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | 可能的最大值。 |
| static constexpr [MinValue](./minvalue/) | 可能的最小值。 |

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)