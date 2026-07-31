---
title: TryParse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengubah string yang ditentukan yang berisi representasi string dari sebuah angka menjadi bilangan bulat bertanda 16-bit yang setara.
type: docs
weight: 14
url: /id/system/int16/tryparse/
---
## Int16::TryParse(const String\&, int16_t\&) metode


Mengubah string yang ditentukan yang berisi representasi string dari sebuah angka menjadi bilangan bulat bertanda 16-bit yang setara.

```cpp
static bool System::Int16::TryParse(const String &value, int16_t &result)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan diubah. |
| result | **int16_t**\& | Referensi ke variabel bilangan bulat bertanda 16-bit tempat hasil konversi disimpan. |

### Nilai Kembali

True if the conversion succeeded, otherwise - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, int16_t\&) metode


Mengubah string yang ditentukan yang berisi representasi string dari sebuah angka menjadi bilangan bulat bertanda 16-bit yang setara menggunakan informasi format dan gaya angka yang disediakan.

```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, int16_t &result)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan diubah. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise dari nilai enum NumberStyles yang menentukan gaya yang diizinkan untuk representasi string sebuah angka. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Pointer ke objek yang berisi informasi format string. |
| result | **int16_t**\& | Referensi ke variabel bilangan bulat bertanda 16-bit tempat hasil konversi disimpan. |

### Nilai Kembali

True if the conversion succeeded, otherwise - false.

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, int16_t\&) metode




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, int16_t\&) metode




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, int16_t &result)
```

## Int16::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, int16_t\&) metode




```cpp
static bool System::Int16::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, int16_t &result)
```

## Lihat Juga

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Int16](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)