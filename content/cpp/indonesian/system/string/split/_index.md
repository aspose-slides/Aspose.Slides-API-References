---
title: Split()
second_title: Referensi API Aspose.Slides untuk C++
description: Membagi string berdasarkan karakter.
type: docs
weight: 768
url: /id/system/string/split/
---
## String::Split(char_t, StringSplitOptions) const metode

Membagi string berdasarkan karakter.

```cpp
ArrayPtr<String> System::String::Split(char_t separator=u' ', StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separator | char_t | Karakter untuk membagi string. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opsi pemisahan. |

### Nilai Kembalian

[Array](../../array/) dari substring.

## String::Split(char_t, int32_t, StringSplitOptions) const metode

Membagi string berdasarkan karakter.

```cpp
ArrayPtr<String> System::String::Split(char_t separator, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separator | char_t | Karakter untuk membagi string. |
| count | **int32_t** | Jumlah maksimum substring yang dikembalikan. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opsi pemisahan. |

### Nilai Kembalian

[Array](../../array/) dari substring.

## String::Split(char_t, char_t, StringSplitOptions) const metode

Membagi string berdasarkan salah satu dari dua karakter.

```cpp
ArrayPtr<String> System::String::Split(char_t separatorA, char_t separatorB, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separatorA | char_t | Karakter pertama untuk membagi string. |
| separatorB | char_t | Karakter kedua untuk membagi string. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opsi pemisahan. |

### Nilai Kembalian

[Array](../../array/) dari substring.

## String::Split(const ArrayPtr\<char_t\>\&, StringSplitOptions) const metode

Membagi string berdasarkan salah satu karakter yang ditentukan.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) dari karakter pemisah. Jika kosong, semua karakter spasi dianggap sebagai pemisah. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opsi pemisahan. |

### Nilai Kembalian

[Array](../../array/) dari substring.

## String::Split(const ArrayPtr\<char_t\>\&, int32_t, StringSplitOptions) const metode

Membagi string berdasarkan salah satu karakter yang ditentukan.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<char_t> &separators, int32_t count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | [Array](../../array/) dari karakter pemisah. Jika kosong, semua karakter spasi dianggap sebagai pemisah. |
| count | **int32_t** | Jumlah maksimum substring yang dikembalikan. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opsi pemisahan. |

### Nilai Kembalian

[Array](../../array/) dari substring.

## String::Split(const String\&, StringSplitOptions) const metode

Membagi string berdasarkan substring.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separator | const [String](../)\& | Substring yang berfungsi sebagai pemisah. Jika kosong, karakter spasi berfungsi sebagai pemisah. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opsi pemisahan. |

### Nilai Kembalian

[Array](../../array/) dari substring.

## String::Split(const String\&, int, StringSplitOptions) const metode

Membagi string berdasarkan substring.

```cpp
ArrayPtr<String> System::String::Split(const String &separator, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separator | const [String](../)\& | Substring yang berfungsi sebagai pemisah. Jika kosong, karakter spasi berfungsi sebagai pemisah. |
| count | int | Jumlah maksimal elemen dalam array hasil pemisahan. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opsi pemisahan. |

### Nilai Kembalian

[Array](../../array/) dari substring.

## String::Split(const ArrayPtr\<String\>\&, StringSplitOptions) const metode

Membagi string berdasarkan substring.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) dari string pemisah. Jika kosong, tidak ada pemisahan yang dilakukan. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opsi pemisahan. |

### Nilai Kembalian

[Array](../../array/) dari substring.

## String::Split(const ArrayPtr\<String\>\&, int, StringSplitOptions) const metode

Membagi string berdasarkan substring. Saat ini, hanya mendukung array pemisah dengan nol atau satu elemen.

```cpp
ArrayPtr<String> System::String::Split(const ArrayPtr<String> &separators, int count, StringSplitOptions opt=StringSplitOptions::None) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| separators | const [ArrayPtr](../../arrayptr/)\<[String](../)\>\& | [Array](../../array/) dari string pemisah. Jika kosong, tidak ada pemisahan yang dilakukan. |
| count | int | Jumlah maksimal elemen dalam array hasil pemisahan. |
| opt | [StringSplitOptions](../../stringsplitoptions/) | Opsi pemisahan. |

### Nilai Kembalian

[Array](../../array/) dari substring.

## Lihat Juga

* Enum [StringSplitOptions](../../stringsplitoptions/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [String](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)