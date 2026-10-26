---
title: Double
second_title: Aspose.Slides for C++ API 參考文件
description: 包含用於處理雙精度浮點數的方法。
type: docs
weight: 1574
url: /zh-hant/system/double/
---
## 雙精度結構

包含用於處理雙精度浮點數的方法。

```cpp
class Double
```

## 方法

| 方法 | 說明 |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | 將指定的字串（其內容為數字的字串表示）轉換為等效的雙精度浮點值。 |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式資訊，將指定的字串（其內容為數字的字串表示）轉換為等效的雙精度浮點值。 |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | 使用提供的格式資訊和數字樣式，將指定的字串（其內容為數字的字串表示）轉換為等效的雙精度浮點值。 |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | 將指定的字串（其內容為數字的字串表示）轉換為等效的雙精度浮點值。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | 使用提供的格式資訊和數字樣式，將指定的字串（其內容為數字的字串表示）轉換為等效的雙精度浮點值。 |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

## 欄位

| 欄位 | 說明 |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | 大於零的最小正值。 |
| static constexpr [MaxValue](./maxvalue/) | 可能的最大值。 |
| static constexpr [MinValue](./minvalue/) | 可能的最小值。 |
| static constexpr [NaN](./nan/) | 非數字的值。 |
| static constexpr [NegativeInfinity](./negativeinfinity/) | 負無限大。 |
| static constexpr [PositiveInfinity](./positiveinfinity/) | 正無限大。 |

## 另請參閱

* Namespace [System](../)
* Library [Aspose.Slides](../../)