---
title: Parse()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengubah string yang ditentukan yang berisi representasi string dari sebuah angka menjadi bilangan bulat bertanda 16-bit yang setara.
type: docs
weight: 1
url: /id/system/int16/parse/
---
## Int16::Parse(const String\&) metode


Mengubah string yang ditentukan yang berisi representasi string dari sebuah angka menjadi bilangan bulat bertanda 16-bit yang setara.

```cpp
static int16_t System::Int16::Parse(const String &value)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan diubah. |

### Nilai Kembali

Bilangan bulat bertanda 16-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan.

## Int16::Parse(const String\&, const SharedPtr\<IFormatProvider\>\&) metode


Mengubah string yang ditentukan yang berisi representasi string dari sebuah angka menjadi bilangan bulat bertanda 16-bit yang setara menggunakan informasi pemformatan yang disediakan.

```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<IFormatProvider> &provider)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan diubah. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Pointer ke objek yang berisi informasi format string. |

### Nilai Kembali

Bilangan bulat bertanda 16-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan.

## Int16::Parse(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static int16_t System::Int16::Parse(const String &value, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, std::nullptr_t) metode




```cpp
static int16_t System::Int16::Parse(const String &value, std::nullptr_t)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<IFormatProvider\>\&) metode


Mengubah string yang ditentukan yang berisi representasi string dari sebuah angka menjadi bilangan bulat bertanda 16-bit yang setara menggunakan informasi pemformatan yang disediakan dan gaya nomor.

```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<IFormatProvider> &provider)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | const [String](../../string/)\& | String yang akan diubah. |
| styles | [Globalization::NumberStyles](../../../system.globalization/numberstyles/) | Kombinasi bitwise nilai-nilai enum NumberStyles yang menentukan gaya yang diizinkan untuk representasi string sebuah angka. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Pointer ke objek yang berisi informasi format string. |

### Nilai Kembali

Bilangan bulat bertanda 16-bit yang sama dengan angka yang direpresentasikan oleh string yang ditentukan.

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::CultureInfo\>\&) metode




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::CultureInfo> &culture)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, const SharedPtr\<Globalization::NumberFormatInfo\>\&) metode




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, const SharedPtr<Globalization::NumberFormatInfo> &nfi)
```

## Int16::Parse(const String\&, Globalization::NumberStyles, std::nullptr_t) metode




```cpp
static int16_t System::Int16::Parse(const String &value, Globalization::NumberStyles styles, std::nullptr_t=nullptr)
```

## Lihat Juga

* Enum [NumberStyles](../../../system.globalization/numberstyles/)
* Typedef [SharedPtr](../../sharedptr/)
* Kelas [String](../../string/)
* Kelas [Int16](../)
* Kelas [IFormatProvider](../../iformatprovider/)
* Kelas [CultureInfo](../../../system.globalization/cultureinfo/)
* Kelas [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Ruang nama [System](../../)
* Perpustakaan [Aspose.Slides](../../../)