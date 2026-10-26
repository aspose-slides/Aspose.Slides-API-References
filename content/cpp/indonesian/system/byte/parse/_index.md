---
title: Parse()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengonversi string yang ditentukan yang berisi representasi string dari suatu angka menjadi bilangan bulat tak bertanda 8-bit yang setara.
type: docs
weight: 1
url: /id/system/byte/parse/
---
## Byte::Parse(const String\&) metode

Mengonversi string yang ditentukan yang berisi representasi string dari suatu angka menjadi bilangan bulat tak bertanda 8-bit yang setara.

```cpp
static uint8_t System::Byte::Parse(const String &value)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |

### Nilai Kembalian

Bilangan bulat tak bertanda 8-bit yang sama dengan angka yang diwakili oleh string yang ditentukan.

## Byte::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi string yang ditentukan yang berisi representasi string dari suatu angka menjadi bilangan bulat tak bertanda 8-bit yang setara dengan menggunakan informasi format yang disediakan.

```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string. |

### Nilai Kembalian

Bilangan bulat tak bertanda 8-bit yang sama dengan angka yang diwakili oleh string yang ditentukan.

## Byte::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static uint8_t System::Byte::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, std::nullptr_t) metode




```cpp
static uint8_t System::Byte::Parse(const String &value, std::nullptr_t)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi string yang ditentukan yang berisi representasi string dari suatu angka menjadi bilangan bulat tak bertanda 8-bit yang setara dengan menggunakan informasi format dan gaya angka yang disediakan.

```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise dari nilai enum NumberStyles yang menentukan gaya yang diizinkan untuk representasi string dari suatu angka. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penunjuk ke objek yang berisi informasi format string. |

### Nilai Kembalian

Bilangan bulat tak bertanda 8-bit yang sama dengan angka yang diwakili oleh string yang ditentukan.

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Byte::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metode




```cpp
static uint8_t System::Byte::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Lihat Juga

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Byte](../)
* Class [IFormatProvider](../../iformatprovider/)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Class [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)