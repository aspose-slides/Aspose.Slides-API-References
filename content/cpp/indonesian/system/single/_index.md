---
title: Single
second_title: Referensi API Aspose.Slides untuk C++
description: Berisi metode untuk bekerja dengan bilangan floating-point presisi tunggal.
type: docs
weight: 1899
url: /id/system/single/
---
## Struct Tunggal

Berisi metode untuk bekerja dengan bilangan floating-point presisi tunggal.

```cpp
class Single
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static **float** [Parse](./parse/)(const [String](../string/)\&) | Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi nilai floating-point presisi tunggal yang setara. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi nilai floating-point presisi tunggal yang setara menggunakan informasi pemformatan yang diberikan. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi nilai floating-point presisi tunggal yang setara menggunakan informasi pemformatan dan gaya angka yang diberikan. |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **float** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **float**\&) | Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi nilai floating-point presisi tunggal yang setara. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **float**\&) | Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi nilai floating-point presisi tunggal yang setara menggunakan informasi pemformatan dan gaya angka yang diberikan. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **float**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **float**\&) |  |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static constexpr [Epsilon](./epsilon/) | Nilai positif terkecil yang lebih besar dari nol. |
| static constexpr [MaxValue](./maxvalue/) | Nilai terbesar yang mungkin. |
| static constexpr [MinValue](./minvalue/) | Nilai terkecil yang mungkin. |
| static constexpr [NaN](./nan/) | Nilai yang bukan angka. |
| static constexpr [NegativeInfinity](./negativeinfinity/) | Tak terhingga negatif. |
| static constexpr [PositiveInfinity](./positiveinfinity/) | Tak terhingga positif. |

## Lihat Juga

* Namespace [System](../)
* Perpustakaan [Aspose.Slides](../../)