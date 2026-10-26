---
title: TryParse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi integer tak bertanda 64-bit yang setara.
type: docs
weight: 14
url: /id/system/uint64/tryparse/
---
## UInt64::TryParse(const String\&, uint64_t\&) metode


Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi integer tak bertanda 64-bit yang setara.

```cpp
static bool System::UInt64::TryParse(const String &value, uint64_t &result)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| result | **uint64_t**\& | Referensi ke variabel integer tak bertanda 64-bit tempat hasil konversi disimpan. |

### Nilai Kembali

True jika konversi berhasil, jika tidak - false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint64_t\&) metode


Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi integer tak bertanda 64-bit yang setara menggunakan informasi format dan gaya angka yang disediakan.

```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint64_t &result)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise dari nilai enum NumberStyles yang menentukan gaya representasi string angka yang diizinkan. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string. |
| result | **uint64_t**\& | Referensi ke variabel integer tak bertanda 64-bit tempat hasil konversi disimpan. |

### Nilai Kembali

True jika konversi berhasil, jika tidak - false.

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint64_t\&) metode




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint64_t\&) metode




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint64_t &result)
```

## UInt64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint64_t\&) metode




```cpp
static bool System::UInt64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint64_t &result)
```

## Lihat Juga

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Kelas [String](../../string/)
* Kelas [IFormatProvider](../../iformatprovider/)
* Kelas [CultureInfo](../../../system.globalization/cultureinfo/)
* Kelas [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt64](../)
* Namespace [System](../../)
* Pustaka [Aspose.Slides](../../../)