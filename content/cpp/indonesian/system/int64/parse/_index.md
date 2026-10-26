---
title: Parse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi integer bertanda 64-bit yang setara.
type: docs
weight: 1
url: /id/system/int64/parse/
---
## Int64::Parse(const String\&) metode

Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi integer bertanda 64-bit yang setara.

```cpp
static int64_t System::Int64::Parse(const String &value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |

### Nilai Kembali

Integer bertanda 64-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan.

## Int64::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi integer bertanda 64-bit yang setara menggunakan informasi format yang disediakan.

```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Pointer ke objek yang berisi informasi format string. |

### Nilai Kembali

Integer bertanda 64-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan.

## Int64::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static int64_t System::Int64::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, std::nullptr_t) metode




```cpp
static int64_t System::Int64::Parse(const String &value, std::nullptr_t)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metode

Mengonversi string yang ditentukan yang berisi representasi string dari sebuah angka menjadi integer bertanda 64-bit yang setara menggunakan informasi format dan gaya angka yang disediakan.

```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan dikonversi. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise dari nilai enum NumberStyles yang menentukan gaya yang diizinkan untuk representasi string dari sebuah angka. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Pointer ke objek yang berisi informasi format string. |

### Nilai Kembali

Integer bertanda 64-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan.

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int64::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metode




```cpp
static int64_t System::Int64::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Lihat Juga

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Kelas [String](../../string/)
* Kelas [Int64](../)
* Kelas [IFormatProvider](../../iformatprovider/)
* Kelas [CultureInfo](../../../system.globalization/cultureinfo/)
* Kelas [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)