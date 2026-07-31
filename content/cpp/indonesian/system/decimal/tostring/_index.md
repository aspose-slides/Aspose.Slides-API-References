---
title: ToString()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan representasi string dari nilai yang diwakili oleh objek.
type: docs
weight: 352
url: /id/system/decimal/tostring/
---
## Decimal::ToString() const method

Mengembalikan representasi string dari nilai yang diwakili oleh objek.

```cpp
String System::Decimal::ToString() const
```

## Decimal::ToString(const SharedPtr\<IFormatProvider\>\&) const method

Mengonversi objek saat ini menjadi string menggunakan informasi format khusus budaya.

```cpp
String System::Decimal::ToString(const SharedPtr<IFormatProvider> &provider) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objek [IFormatProvider](../../iformatprovider/) yang menyediakan informasi format khusus budaya. |

### Nilai Kembalian

Representasi string dari objek saat ini.

## Decimal::ToString(const SharedPtr\<Globalization::CultureInfo\>\&) const method

```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const SharedPtr\<Globalization::NumberFormatInfo\>\&) const method

```cpp
String System::Decimal::ToString(const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const Decimal\&, std::nullptr_t) const method

```cpp
String System::Decimal::ToString(const Decimal &value, std::nullptr_t) const
```

## Decimal::ToString(const String\&, const SharedPtr\<IFormatProvider\>\&) const method

Mengonversi objek saat ini menjadi representasi stringnya menggunakan format string yang ditentukan dan informasi format khusus budaya yang disediakan oleh objek [IFormatProvider](../../iformatprovider/) yang ditentukan.

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<IFormatProvider> &provider) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | const [String](../../string/)\& | Format string. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Objek [IFormatProvider](../../iformatprovider/) yang menyediakan informasi format khusus budaya. |

### Nilai Kembalian

Representasi string dari objek saat ini.

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const method

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

## Decimal::ToString(const String\&, const SharedPtr\<Globalization::NumberFormatInfo\>\&) const method

```cpp
String System::Decimal::ToString(const String &format, const SharedPtr<Globalization::NumberFormatInfo> &nfi) const
```

## Decimal::ToString(const String\&, std::nullptr_t) const method

```cpp
String System::Decimal::ToString(const String &format, std::nullptr_t=nullptr) const
```

## Lihat Juga

* Kelas [SharedPtr](../../sharedptr/)
* Kelas [String](../../string/)
* Kelas [Decimal](../)
* Kelas [IFormatProvider](../../iformatprovider/)
* Kelas [CultureInfo](../../../system.globalization/cultureinfo/)
* Kelas [NumberFormatInfo](../../../system.globalization/numberformatinfo/)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)