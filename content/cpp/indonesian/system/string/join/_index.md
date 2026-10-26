---
title: Join()
second_title: Aspose.Slides untuk Referensi API C++
description: Menggabungkan array menggunakan string sebagai pemisah.
type: docs
weight: 846
url: /id/system/string/join/
---
## String::Join(const String\&, const ArrayPtr\<String\>\&, int, int) metode

Menggabungkan array menggunakan string sebagai pemisah.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<String> &parts, int startIndex=0, int count=-1)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) untuk diletakkan di antara elemen array saat menggabungkannya. |
| parts | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) bagian untuk digabungkan. |
| startIndex | int | Indeks pertama dalam array untuk memulai penggabungan. |
| count | int | Jumlah elemen array yang akan digabungkan. -1 berarti 'sampai akhir array'. |

### Nilai Kembalian

[String](../) yang mewakili elemen array yang digabungkan.

## String::Join(const String\&, const System::Details::ArrayView\<String\>\&, int, int) metode

Menggabungkan array menggunakan string sebagai pemisah.

```cpp
static String System::String::Join(const String &separator, const System::Details::ArrayView<String> &parts, int startIndex=0, int count=-1)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) untuk diletakkan di antara elemen array saat menggabungkannya. |
| parts | const System::Details::ArrayView\<[String](../)\>\& | ArrayView bagian untuk digabungkan. |
| startIndex | int | Indeks pertama dalam array untuk memulai penggabungan. |
| count | int | Jumlah elemen array yang akan digabungkan. -1 berarti 'sampai akhir array'. |

### Nilai Kembalian

[String](../) yang mewakili elemen array yang digabungkan.

## String::Join(const String\&, const SharedPtr\<System::Collections::Generic::IEnumerable\<String\>\>\&) metode

Menggabungkan array menggunakan string sebagai pemisah.

```cpp
static String System::String::Join(const String &separator, const SharedPtr<System::Collections::Generic::IEnumerable<String>> &parts)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) untuk diletakkan di antara elemen array saat menggabungkannya. |
| parts | const [SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<[String](../)\>\>\& | - objek enumerable bagian |

### Nilai Kembalian

[String](../) yang mewakili elemen yang digabungkan.

## String::Join(const String\&, const ArrayPtr\<SharedPtr\<Object\>\>\&) metode

Menggabungkan array menggunakan string sebagai pemisah.

```cpp
static String System::String::Join(const String &separator, const ArrayPtr<SharedPtr<Object>> &parts)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separator | const [String](../)\& | [String](../) untuk diletakkan di antara elemen array saat menggabungkannya. |
| parts | const [ArrayPtr](../../arrayptr/)\<[SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\>\& | [Array](../../array/) bagian untuk digabungkan. |

### Nilai Kembalian

[String](../) yang mewakili elemen yang digabungkan.

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Typedef [SharedPtr](../../sharedptr/)
* Kelas [String](../)
* Kelas [IEnumerable](../../../system.collections.generic/ienumerable/)
* Kelas [Object](../../object/)
* Ruang Nama [System](../../)
* Library [Aspose.Slides](../../../)