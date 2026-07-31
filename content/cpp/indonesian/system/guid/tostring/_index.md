---
title: ToString()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi GUID yang diwakili oleh objek saat ini ke representasi stringnya.
type: docs
weight: 79
url: /id/system/guid/tostring/
---
## Guid::ToString() const metode

Mengonversi GUID yang diwakili oleh objek saat ini ke representasi stringnya.

```cpp
String System::Guid::ToString() const
```

## Guid::ToString(const String\&) const metode

Mengonversi GUID yang diwakili oleh objek saat ini ke representasi stringnya menggunakan format string yang ditentukan.

```cpp
String System::Guid::ToString(const String &format) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | const [String](../../string/)\& | Format yang digunakan |

### Nilai Kembalian

Representasi string dari nilai GUID yang diwakili oleh objek saat ini

## Guid::ToString(const String\&, const SharedPtr\<Globalization::CultureInfo\>\&) const metode

Mengonversi GUID yang diwakili oleh objek saat ini ke representasi stringnya menggunakan format string dan kultur yang ditentukan.

```cpp
String System::Guid::ToString(const String &format, const SharedPtr<Globalization::CultureInfo> &culture) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | const [String](../../string/)\& | Format yang digunakan |
| culture | const [SharedPtr](../../sharedptr/)\<[Globalization::CultureInfo](../../../system.globalization/cultureinfo/)\>\& | Kultur yang digunakan |

### Nilai Kembalian

Representasi string dari nilai GUID yang diwakili oleh objek saat ini

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Class [Guid](../)
* Class [CultureInfo](../../../system.globalization/cultureinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)