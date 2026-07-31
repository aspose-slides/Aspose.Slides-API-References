---
title: UInt32
second_title: Referensi API Aspose.Slides untuk C++
description: Berisi metode untuk bekerja dengan bilangan bulat tak bertanda 32-bit.
type: docs
weight: 1977
url: /id/system/uint32/
---
## UInt32 struct

Berisi metode untuk bekerja dengan bilangan bulat tak bertanda 32-bit.

```cpp
class UInt32
```

## Metode

| Method | Description |
| --- | --- |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&) | Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi bilangan bulat tak bertanda 32-bit yang ekuivalen. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi bilangan bulat tak bertanda 32-bit yang ekuivalen dengan menggunakan informasi format yang diberikan. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, std::nullptr_t) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&) | Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi bilangan bulat tak bertanda 32-bit yang ekuivalen dengan menggunakan informasi format dan gaya angka yang diberikan. |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&) |  |
| static **uint32_t** [Parse](./parse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **uint32_t**\&) | Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi bilangan bulat tak bertanda 32-bit yang ekuivalen. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[IFormatProvider](../iformatprovider/)\>\&, **uint32_t**\&) | Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi bilangan bulat tak bertanda 32-bit yang ekuivalen dengan menggunakan informasi format dan gaya angka yang diberikan. |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::CultureInfo](../../system.globalization/cultureinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), const [SharedPtr](../sharedptr/)\<[Globalization::NumberFormatInfo](../../system.globalization/numberformatinfo/)\>\&, **uint32_t**\&) |  |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, [Globalization::NumberStyles](../../system.globalization/numberstyles/), std::nullptr_t, **uint32_t**\&) |  |

## Bidang

| Field | Description |
| --- | --- |
| static constexpr [MaxValue](./maxvalue/) | Nilai terbesar yang mungkin. |
| static constexpr [MinValue](./minvalue/) | Nilai terkecil yang mungkin. |

## Lihat Juga

* Namespace [System](../)
* Library [Aspose.Slides](../../)