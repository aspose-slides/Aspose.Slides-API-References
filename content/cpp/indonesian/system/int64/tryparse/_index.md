---
title: TryParse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi integer bertanda 64-bit yang setara.
type: docs
weight: 14
url: /id/system/int64/tryparse/
---
## Int64::TryParse(const String\&, int64_t\&) metode


Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi integer bertanda 64-bit yang setara.

```cpp
static bool System::Int64::TryParse(const String &value, int64_t &result)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| result | **int64_t**\& | Referensi ke variabel integer bertanda 64-bit tempat hasil konversi disimpan. |

### Nilai Kembali

True jika konversi berhasil, jika tidak - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int64_t\&) metode


Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi integer bertanda 64-bit yang setara menggunakan informasi format dan gaya angka yang disediakan.

```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int64_t &result)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise dari nilai enum NumberStyles yang menentukan gaya representasi string dari sebuah angka yang diizinkan. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Pointer ke objek yang berisi informasi format string. |
| result | **int64_t**\& | Referensi ke variabel integer bertanda 64-bit tempat hasil konversi disimpan. |

### Nilai Kembali

True jika konversi berhasil, jika tidak - false.

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int64_t\&) metode




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int64_t\&) metode




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int64_t &result)
```

## Int64::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int64_t\&) metode 




```cpp
static bool System::Int64::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int64_t &result)
```

## Lihat Juga

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int64](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)