---
title: GetDateTimeFormats()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan array string di mana setiap elemen adalah representasi string dari objek saat ini yang diformat dengan salah satu spesifikator format tanggal dan waktu standar.
type: docs
weight: 547
url: /id/system/datetime/getdatetimeformats/
---
## DateTime::GetDateTimeFormats() const metode

Mengembalikan array string di mana setiap elemen adalah representasi string dari objek saat ini yang diformat dengan salah satu spesifikator format tanggal dan waktu standar.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats() const
```

## DateTime::GetDateTimeFormats(char_t) const metode

Mengembalikan array string di mana setiap elemen adalah representasi string dari objek saat ini yang diformat dengan spesifikator format tanggal dan waktu standar yang ditentukan.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | char_t | Spesifikator format tanggal dan waktu standar. |

## DateTime::GetDateTimeFormats(const SharedPtr\<IFormatProvider\>\&) const metode

Mengembalikan array string di mana setiap elemen adalah representasi string dari objek saat ini yang diformat dengan salah satu spesifikator format tanggal dan waktu standar serta penyedia format yang ditentukan.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(const SharedPtr<IFormatProvider> &provider) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penyedia format. |

## DateTime::GetDateTimeFormats(char_t, const SharedPtr\<IFormatProvider\>\&) const metode

Mengembalikan array string di mana setiap elemen adalah representasi string dari objek saat ini yang diformat dengan spesifikator format tanggal dan waktu standar yang ditentukan serta penyedia format.

```cpp
ArrayPtr<String> System::DateTime::GetDateTimeFormats(char_t format, const SharedPtr<IFormatProvider> &provider) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| format | char_t | Spesifikator format tanggal dan waktu standar. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Penyedia format. |

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Kelas [String](../../string/)
* Kelas [DateTime](../)
* Kelas [IFormatProvider](../../iformatprovider/)
* Namespace [System](../../)
* Pustaka [Aspose.Slides](../../../)