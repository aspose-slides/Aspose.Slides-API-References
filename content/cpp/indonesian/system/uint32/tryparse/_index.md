---
title: TryParse()
second_title: Aspose.Slides untuk C++ API Referensi
description: Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi integer tak bertanda 32-bit yang setara.
type: docs
weight: 14
url: /id/system/uint32/tryparse/
---
## UInt32::TryParse(const String\&, uint32_t\&) method

Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi integer tak bertanda 32-bit yang setara.

```cpp
static bool System::UInt32::TryParse(const String &value, uint32_t &result)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| result | **uint32_t**\& | Referensi ke variabel integer tak bertanda 32-bit tempat hasil konversi ditempatkan. |

### Nilai Kembalian

True jika konversi berhasil, sebaliknya - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint32_t\&) method

Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi integer tak bertanda 32-bit yang setara menggunakan informasi format dan gaya angka yang disediakan.

```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint32_t &result)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise dari nilai-nilai enum NumberStyles yang menentukan gaya representasi string dari sebuah angka yang diizinkan. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Pointer ke objek yang berisi informasi format string. |
| result | **uint32_t**\& | Referensi ke variabel integer tak bertanda 32-bit tempat hasil konversi ditempatkan. |

### Nilai Kembalian

True jika konversi berhasil, sebaliknya - false.

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint32_t\&) method




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint32_t\&) method




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint32_t &result)
```

## UInt32::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint32_t\&) method




```cpp
static bool System::UInt32::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint32_t &result)
```

## Lihat Juga

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt32](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)