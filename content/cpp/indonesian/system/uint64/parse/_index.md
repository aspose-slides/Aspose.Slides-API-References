---
title: Parse()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi bilangan bulat tak bertanda 64-bit yang ekuivalen.
type: docs
weight: 1
url: /id/system/uint64/parse/
---
## UInt64::Parse(const String\&) metode


Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi bilangan bulat tak bertanda 64-bit yang ekuivalen.

```cpp
static uint64_t System::UInt64::Parse(const String &value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |

### Nilai Kembalian

Bilangan bulat tak bertanda 64-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan.

## UInt64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metode


Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi bilangan bulat tak bertanda 64-bit yang ekuivalen menggunakan informasi format yang diberikan.

```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Pointer ke objek yang berisi informasi format string. |

### Nilai Kembalian

Bilangan bulat tak bertanda 64-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan.

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static uint64_t System::UInt64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, std::nullptr_t) metode




```cpp
static uint64_t System::UInt64::Parse(const String &value, std::nullptr_t)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metode


Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi bilangan bulat tak bertanda 64-bit yang ekuivalen menggunakan informasi format dan gaya angka yang diberikan.

```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise dari nilai-nilai enum NumberStyles yang menentukan gaya representasi string angka yang diizinkan. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Pointer ke objek yang berisi informasi format string. |

### Nilai Kembalian

Bilangan bulat tak bertanda 64-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan.

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## UInt64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metode




```cpp
static uint64_t System::UInt64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Lihat Juga

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Kelas [String](../../string/)
* Kelas [IFormatProvider](../../iformatprovider/)
* Kelas [CultureInfo](../../../system.globalization/cultureinfo/)
* Kelas [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Struktur [UInt64](../)
* Ruang nama [System](../../)
* Library [Aspose.Slides](../../../)