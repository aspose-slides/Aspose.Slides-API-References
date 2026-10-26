---
title: Parse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string yang ditentukan yang berisi representasi string dari suatu angka menjadi nilai floating-point double-precision yang setara.
type: docs
weight: 1
url: /id/system/double/parse/
---
## Double::Parse(const String\&) metode

Mengonversi string yang ditentukan yang berisi representasi string dari suatu angka menjadi nilai floating-point double-precision yang setara.

```cpp
static double System::Double::Parse(const String &value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |

### Nilai Kembalian

Nilai floating-point double-precision yang setara dengan angka yang direpresentasikan oleh string yang ditentukan.

## Double::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi string yang ditentukan yang berisi representasi string dari suatu angka menjadi nilai floating-point double-precision yang setara dengan menggunakan informasi format yang disediakan.

```cpp
static double System::Double::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string. |

### Nilai Kembalian

Nilai floating-point double-precision yang setara dengan angka yang direpresentasikan oleh string yang ditentukan.

## Double::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static double System::Double::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, std::nullptr_t) metode




```cpp
static double System::Double::Parse(const String &value, std::nullptr_t)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi string yang ditentukan yang berisi representasi string dari suatu angka menjadi nilai floating-point double-precision yang setara dengan menggunakan informasi format dan gaya angka yang disediakan.

```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise nilai enum NumberStyles yang menentukan gaya yang diizinkan untuk representasi string angka. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string. |

### Nilai Kembalian

Nilai floating-point double-precision yang setara dengan angka yang direpresentasikan oleh string yang ditentukan.

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Double::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Double::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metode




```cpp
static double System::Double::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
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