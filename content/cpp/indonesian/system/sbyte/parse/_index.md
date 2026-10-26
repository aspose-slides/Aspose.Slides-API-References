---
title: Parse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string yang ditentukan, yang berisi representasi string dari sebuah angka, menjadi integer bertanda 8-bit yang setara.
type: docs
weight: 1
url: /id/system/sbyte/parse/
---
## SByte::Parse(const String\&) metode

Mengonversi string yang ditentukan, yang berisi representasi string dari sebuah angka, menjadi integer bertanda 8-bit yang setara.

```cpp
static int8_t System::SByte::Parse(const String &value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |

### Nilai Kembali

Integer bertanda 8-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan.

## SByte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi string yang ditentukan, yang berisi representasi string dari sebuah angka, menjadi integer bertanda 8-bit yang setara menggunakan informasi format yang disediakan.

```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Pointer ke objek yang berisi informasi format string. |

### Nilai Kembali

Integer bertanda 8-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan.

## SByte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metode

```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode

```cpp
static int8_t System::SByte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, std::nullptr_t) metode

```cpp
static int8_t System::SByte::Parse(const String &value, std::nullptr_t)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi string yang ditentukan, yang berisi representasi string dari sebuah angka, menjadi integer bertanda 8-bit yang setara menggunakan informasi format dan gaya angka yang disediakan.

```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise dari nilai enum NumberStyles yang menentukan gaya representasi string angka yang diizinkan. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Pointer ke objek yang berisi informasi format string. |

### Nilai Kembali

Integer bertanda 8-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan.

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metode

```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode

```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## SByte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metode

```cpp
static int8_t System::SByte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Lihat Juga

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struct [SByte](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)