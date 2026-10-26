---
title: Trim()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghapus semua karakter spasi dari awal hingga akhir string.
type: docs
weight: 677
url: /id/system/string/trim/
---
## String::Trim() const method


Menghapus semua karakter spasi baik di awal maupun di akhir string.

```cpp
String System::String::Trim() const
```


### Nilai Kembalian

[String](../) tanpa spasi di awal atau akhir.

## String::Trim(char_t) const method


Menghapus semua kemunculan karakter yang diberikan dari awal maupun akhir string.

```cpp
String System::String::Trim(char_t ch) const
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ch | char_t | Simbol yang akan dihapus. |

### Nilai Kembalian

Hasil penghapusan.

## String::Trim(const String\&) const method


Menghapus semua kemunculan karakter yang diberikan dari awal maupun akhir string.

```cpp
String System::String::Trim(const String &anyOf) const
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| anyOf | const [String](../)\& | [String](../) karakter untuk dihapus. |

### Nilai Kembalian

[String](../) tanpa karakter yang dihapus.

## String::Trim(const ArrayPtr\<char_t\>\&) const method


Menghapus semua kemunculan karakter yang diberikan dari awal maupun akhir string.

```cpp
String System::String::Trim(const ArrayPtr<char_t> &anyOf) const
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| anyOf | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) karakter untuk dihapus. |

### Nilai Kembalian

[String](../) tanpa karakter yang dihapus.

## Lihat Juga

* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)