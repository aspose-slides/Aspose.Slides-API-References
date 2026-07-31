---
title: Double
second_title: Referensi API Aspose.Slides untuk C++
description: Berisi metode untuk bekerja dengan bilangan floating-point presisi ganda.
type: docs
weight: 1574
url: /id/system/double/
---
## Struct double

Contains methods to work with the double-precision floating-point number.

```cpp
class Double
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static **double** [Parse](./parse/)(const [String](../string/)\&) | Mengkonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi nilai floating-point double-precision yang setara. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengkonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi nilai floating-point double-precision yang setara menggunakan informasi format yang disediakan. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengkonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi nilai floating-point double-precision yang setara menggunakan informasi format dan gaya angka yang disediakan. |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **double** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **double**\&) | Mengkonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi nilai floating-point double-precision yang setara. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **double**\&) | Mengkonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi nilai floating-point double-precision yang setara menggunakan informasi format dan gaya angka yang disediakan. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **double**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **double**\&) |  |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Nilai positif terkecil yang lebih besar dari nol. |
| static constexpr [MaxValue](./maxvalue/) | Nilai terbesar yang mungkin. |
| static constexpr [MinValue](./minvalue/) | Nilai terkecil yang mungkin. |
| static constexpr [NaN](./nan/) | Nilai yang bukan angka. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Negatif tak terhingga. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Positif tak terhingga. |

## Lihat Juga

* Namespace [System](../)
* Library [Aspose.Slides](../../)