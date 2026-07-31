---
title: SByte
second_title: Referensi API Aspose.Slides untuk C++
description: Berisi metode untuk bekerja dengan bilangan bulat 8-bit.
type: docs
weight: 1873
url: /id/system/sbyte/
---
## SByte struct

Berisi metode untuk bekerja dengan bilangan bulat 8-bit.

```cpp
class SByte
```

## Metode

| Metode | Deskripsi |
| --- | --- |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&) | Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka ke integer bertanda 8-bit yang setara. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka ke integer bertanda 8-bit yang setara menggunakan informasi pemformatan yang diberikan. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka ke integer bertanda 8-bit yang setara menggunakan informasi pemformatan dan gaya angka yang diberikan. |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **int8_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **int8_t**\&) | Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka ke integer bertanda 8-bit yang setara. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **int8_t**\&) | Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka ke integer bertanda 8-bit yang setara menggunakan informasi pemformatan dan gaya angka yang diberikan. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **int8_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **int8_t**\&) |  |

## Bidang

| Bidang | Deskripsi |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Nilai terbesar yang mungkin. |
| static constexpr [MinValue](./minvalue/) | Nilai terkecil yang mungkin. |

## Lihat Juga

* Ruang nama [System](../)
* Perpustakaan [Aspose.Slides](../../)