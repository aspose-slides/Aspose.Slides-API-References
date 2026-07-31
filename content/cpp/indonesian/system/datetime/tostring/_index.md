---
title: ToString()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan representasi string dari nilai tanggal dan waktu yang direpresentasikan oleh objek saat ini menggunakan konvensi format yang ditentukan oleh budaya saat ini.
type: docs
weight: 482
url: /id/system/datetime/tostring/
---
## DateTime::ToString() const metode

Mengembalikan representasi string dari nilai tanggal dan waktu yang direpresentasikan oleh objek saat ini menggunakan konvensi format yang ditentukan oleh budaya saat ini.

```cpp
String System::DateTime::ToString() const
```

### Nilai Kembali

Representasi string dari nilai yang direpresentasikan oleh objek saat ini

## DateTime::ToString(const String\&) const metode

Mengembalikan representasi string dari nilai tanggal dan waktu yang direpresentasikan oleh objek saat ini menggunakan format yang ditentukan serta konvensi format yang ditetapkan oleh budaya saat ini.

```cpp
String System::DateTime::ToString(const String &format) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | const [String](../../string/)\& | String format |

### Nilai Kembali

Representasi string dari nilai yang direpresentasikan oleh objek saat ini diformat menurut format yang didefinisikan oleh **format** dan budaya saat ini.

## DateTime::ToString(const SharedPtr\<IFormatProvider\>\&) const metode

Mengembalikan representasi string dari nilai tanggal dan waktu yang direpresentasikan oleh objek saat ini menggunakan informasi format yang ditentukan.

```cpp
String System::DateTime::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objek yang mewakili informasi format |

### Nilai Kembali

Representasi string dari nilai yang direpresentasikan oleh objek saat ini diformat menurut informasi format yang disediakan oleh **formatProvider**.

## DateTime::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const metode




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const metode




```cpp
String System::DateTime::ToString(const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(std::nullptr_t) const metode




```cpp
String System::DateTime::ToString(std::nullptr_t) const
```

## DateTime::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const metode

Mengembalikan representasi string dari nilai tanggal dan waktu yang direpresentasikan oleh objek saat ini menggunakan informasi format yang ditentukan.

```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | const [String](../../string/)\& | String format |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objek yang mewakili informasi format |

### Nilai Kembali

Representasi string dari nilai yang direpresentasikan oleh objek saat ini diformat menurut informasi format yang disediakan oleh **provider** dan string format **format**.

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metode




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## DateTime::ToString(const String\&, const SharedPtr\<Globalization::DateTimeFormatInfo\>\&) const metode




```cpp
String System::DateTime::ToString(const String &format, const SharedPtr<Globalization::DateTimeFormatInfo> &dtfi) const
```

## DateTime::ToString(const String\&, std::nullptr_t) const metode




```cpp
String System::DateTime::ToString(const String &format, std::nullptr_t) const
```

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [String](../../string/)
* Kelas [DateTime](../)
* Kelas [IFormatProvider](../../iformatprovider/)
* Kelas [CultureInfo](../../../system.globalization/cultureinfo/)
* Kelas [DateTimeFormatInfo](../../../system.globalization/datetimeformatinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)