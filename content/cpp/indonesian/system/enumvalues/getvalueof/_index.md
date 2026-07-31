---
title: GetValueOf()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan nilai yang dibungkus dari konstan enum dengan nama yang ditentukan.
type: docs
weight: 53
url: /id/system/enumvalues/getvalueof/
---
## EnumValues::GetValueOf(const String\&, bool) const metode


Mengembalikan nilai yang dibungkus dari konstan enum dengan nama yang ditentukan.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(const String &str, bool ignoreCase) const override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../../string/)\& | Nama konstan enum |
| ignoreCase | **bool** | Menentukan apakah huruf besar/kecil harus diabaikan saat menginterpretasikan nama konstan enum |

### Nilai Kembalian

Sebuah nilai yang dibungkus dari konstan enum yang namanya ditentukan dalam **str**.

## EnumValues::GetValueOf(long) const metode


Mengembalikan nilai yang dibungkus dari konstan enum dengan nilai yang ditentukan.

```cpp
virtual SharedPtr<Object> System::EnumValues<E, Guard>::GetValueOf(long val) const override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| val | long | Nilai konstan enum |

### Nilai Kembalian

Sebuah nilai yang dibungkus dari konstan enum yang nilainya ditentukan dalam **str**.

## Lihat Juga

* Typedef [SharedPtr](../../sharedptr/)
* Kelas [Object](../../object/)
* Kelas [String](../../string/)
* Kelas [EnumValues](../)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)