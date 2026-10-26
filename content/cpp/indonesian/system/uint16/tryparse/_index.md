---
title: TryParse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi bilangan bulat tidak bertanda 16-bit yang setara.
type: docs
weight: 14
url: /id/system/uint16/tryparse/
---
## UInt16::TryParse(const String\&, uint16_t\&) method

Mengonversi string yang diberikan yang berisi representasi string dari sebuah angka menjadi bilangan bulat tidak bertanda 16-bit yang setara.

```cpp
static bool System::UInt16::TryParse(const String &value, uint16_t &result)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| result | **uint16_t**\& | Referensi ke variabel bilangan bulat tidak bertanda 16-bit tempat hasil konversi disimpan. |

### Nilai Kembali

True jika konversi berhasil, jika tidak - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, uint16_t\&) method

Mengonversi string yang diberikan yang berisi representasi string dari sebuah angka menjadi bilangan bulat tidak bertanda 16-bit yang setara menggunakan informasi format dan gaya angka yang disediakan.

```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, uint16_t &result)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise nilai enum NumberStyles yang menentukan gaya representasi string angka yang diizinkan. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Pointer ke objek yang berisi informasi format string. |
| result | **uint16_t**\& | Referensi ke variabel bilangan bulat tidak bertanda 16-bit tempat hasil konversi disimpan. |

### Nilai Kembali

True jika konversi berhasil, jika tidak - false.

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, uint16_t\&) method




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, uint16_t\&) method




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, uint16_t &result)
```

## UInt16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, uint16_t\&) method




```cpp
static bool System::UInt16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, uint16_t &result)
```

## Lihat Juga

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [UInt16](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)