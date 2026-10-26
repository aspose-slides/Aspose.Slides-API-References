---
title: Parse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi nilai floating-point presisi tunggal yang setara.
type: docs
weight: 1
url: /id/system/single/parse/
---
## Single::Parse(const String\&) metode

Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi nilai floating-point presisi tunggal yang setara.

```cpp
static float System::Single::Parse(const String &value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |

### Nilai Kembalian

Nilai floating-point presisi tunggal yang sama dengan angka yang direpresentasikan oleh string yang ditentukan.

## Single::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi nilai floating-point presisi tunggal yang setara dengan menggunakan informasi format yang disediakan.

```cpp
static float System::Single::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Pointer ke objek yang berisi informasi format string. |

### Nilai Kembalian

Nilai floating-point presisi tunggal yang sama dengan angka yang direpresentasikan oleh string yang ditentukan.

## Single::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static float System::Single::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, std::nullptr_t) metode




```cpp
static float System::Single::Parse(const String &value, std::nullptr_t)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi nilai floating-point presisi tunggal yang setara dengan menggunakan informasi format dan gaya angka yang disediakan.

```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise dari nilai-nilai enum NumberStyles yang menentukan gaya yang diizinkan untuk representasi string dari sebuah angka. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Pointer ke objek yang berisi informasi format string. |

### Nilai Kembalian

Nilai floating-point presisi tunggal yang sama dengan angka yang direpresentasikan oleh string yang ditentukan.

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Single::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Single::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metode




```cpp
static float System::Single::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
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