---
title: Parse()
second_title: Referensi API Aspose.Slides untuk C++
description: Membungkus nilai konstan enumerasi dari enumerasi yang ditentukan dengan nama yang ditentukan. Sebuah parameter menentukan apakah huruf besar/kecil harus diabaikan saat menginterpretasikan string yang menentukan nama konstan enumerasi.
type: docs
weight: 53
url: /id/system/boxedvaluebase/parse/
---
## BoxedValueBase::Parse(const TypeInfo\&, const String\&, bool) metode

Membungkus nilai konstan enumerasi dari enumerasi yang ditentukan dengan nama yang ditentukan. Sebuah parameter menentukan apakah huruf besar/kecil harus diabaikan saat menginterpretasikan string yang menentukan nama konstan enumerasi.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str, bool ignoreCase)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Menentukan tipe enumerasi |
| str | const [String](../../string/)\& | Nama konstan enumerasi, nilai yang akan dibungkus |
| ignoreCase | **bool** | Menentukan apakah huruf besar/kecil harus diabaikan saat menginterpretasikan string yang mewakili nama konstan enumerasi |

### Nilai Kembali

Pointer bersama ke objek yang mewakili nilai terbungkus dari konstan enumerasi yang ditentukan

## BoxedValueBase::Parse(const TypeInfo\&, const String\&) metode

Membungkus nilai konstan enumerasi dari enumerasi yang ditentukan dengan nama yang ditentukan.

```cpp
static SharedPtr<Object> System::BoxedValueBase::Parse(const TypeInfo &type, const String &str)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | const [TypeInfo](../../typeinfo/)\& | Menentukan tipe enumerasi |
| str | const [String](../../string/)\& | Nama konstan enumerasi, nilai yang akan dibungkus |

### Nilai Kembali

Pointer bersama ke objek yang mewakili nilai terbungkus dari konstan enumerasi yang ditentukan

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [Object](../../object/)
* Kelas [TypeInfo](../../typeinfo/)
* Kelas [String](../../string/)
* Kelas [BoxedValueBase](../)
* Ruang Nama [System](../../)
* Pustaka [Aspose.Slides](../../../)