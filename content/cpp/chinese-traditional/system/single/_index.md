---
title: Single
second_title: Aspose.Slides for C++ API 參考
description: 包含用於處理單精度浮點數的方法。
type: docs
weight: 1899
url: /zh-hant/system/single/
---
## 單一結構

包含用於處理單精度浮點數的方法。

```cpp
class Single
```

## 方法

| Method | Description |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | 將包含數字字串表示的指定字串轉換為等效的單精度浮點值。 |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將包含數字字串表示的指定字串，使用提供的格式資訊，轉換為等效的單精度浮點值。 |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 將包含數字字串表示的指定字串，使用提供的格式資訊和數字樣式，轉換為等效的單精度浮點值。 |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | 將包含數字字串表示的指定字串轉換為等效的單精度浮點值。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | 將包含數字字串表示的指定字串，使用提供的格式資訊和數字樣式，轉換為等效的單精度浮點值。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## 欄位

| Field | Description |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | 大於零的最小正值。 |
| static constexpr [MaxValue](./maxvalue/) | 可能的最大值。 |
| static constexpr [MinValue](./minvalue/) | 可能的最小值。 |
| static constexpr [NaN](./nan/) | 不是數字的值。 |
| static constexpr [NegativeInfinity](./negativeinfinity/) | 負無限大。 |
| static constexpr [PositiveInfinity](./positiveinfinity/) | 正無限大。 |

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)