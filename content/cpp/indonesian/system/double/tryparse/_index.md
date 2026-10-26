---
title: TryParse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string yang diberikan yang berisi representasi string dari sebuah angka menjadi nilai floating-point double-precision yang setara.
type: docs
weight: 14
url: /id/system/double/tryparse/
---
## Double::TryParse(const String\&, double\&) method


Mengonversi string yang diberikan yang berisi representasi string dari sebuah angka menjadi nilai floating-point double-precision yang setara.

```cpp
static bool System::Double::TryParse(const String &value, double &result)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| result | **double**\& | Referensi ke variabel floating-point double-precision tempat hasil konversi disimpan. |

### Nilai Kembali

True jika konversi berhasil, jika tidak - false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&, double\&) method


Mengonversi string yang diberikan yang berisi representasi string dari sebuah angka menjadi nilai floating-point double-precision yang setara menggunakan informasi format dan gaya angka yang disediakan.

```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider, double &result)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise dari nilai enum NumberStyles yang menentukan gaya representasi string angka yang diizinkan. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Pointer ke objek yang berisi informasi format string. |
| result | **double**\& | Referensi ke variabel floating-point double-precision tempat hasil konversi disimpan. |

### Nilai Kembali

True jika konversi berhasil, jika tidak - false.

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&, double\&) method




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&, double\&) method




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi, double &result)
```

## Double::TryParse(const String\&, Globalization::NumberStyles, std::nullptr_t, double\&) method




```cpp
static bool System::Double::TryParse(const String &value, Globalization::NumberStyles styles, std::nullptr_t, double &result)
```

## Lihat Juga

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [Double](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)