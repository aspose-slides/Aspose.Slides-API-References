---
title: TryParse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi nilai floating-point presisi tunggal yang setara.
type: docs
weight: 14
url: /id/system/single/tryparse/
---
## Single::TryParse(const String&, float&) method


Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi nilai floating-point presisi tunggal yang setara.

```cpp
static bool System::Single::TryParse(const String &value, float &result)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)& | String yang akan dikonversi. |
| result | **float**& | Referensi ke variabel floating-point presisi tunggal tempat hasil konversi disimpan. |

### Nilai Kembalian

True if the conversion succeeded, otherwise - false.

## Single::TryParse(const String&, Globalization::NumberStyles, const SharedPtr<IFormatProvider>&, float&) method


Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi nilai floating-point presisi tunggal yang setara menggunakan informasi format dan gaya angka yang disediakan.

```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, float &result)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)& | String yang akan dikonversi. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise dari nilai-nilai enum NumberStyles yang menentukan gaya representasi string angka yang diizinkan. |
| provider | const [SharedPtr](../../sharedptr/)<[IFormatProvider](../../iformatprovider/)>& | Pointer ke objek yang berisi informasi format string. |
| result | **float**& | Referensi ke variabel floating-point presisi tunggal tempat hasil konversi disimpan. |

### Nilai Kembalian

True if the conversion succeeded, otherwise - false.

## Single::TryParse(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::CultureInfo>&, float&) method




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, float &result)
```

## Single::TryParse(const String&, Globalization::NumberStyles, const SharedPtr<Globalization::NumberFormatInfo>&, float&) method




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, float &result)
```

## Single::TryParse(const String&, Globalization::NumberStyles, std::nullptr_t, float&) method




```cpp
static bool System::Single::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, float &result)
```

## Lihat Juga

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Kelas [String](../../string/)
* Kelas [IFormatProvider](../../iformatprovider/)
* Kelas [CultureInfo](../../../system.globalization/cultureinfo/)
* Kelas [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Single](../)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)