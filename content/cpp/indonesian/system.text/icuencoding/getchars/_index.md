---
title: GetChars()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan karakter yang dihasilkan dari decoding sebuah buffer byte.
type: docs
weight: 66
url: /id/system.text/icuencoding/getchars/
---
## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) metode

Mendapatkan karakter yang dihasilkan dari decoding sebuah buffer byte.

```cpp
int System::Text::ICUEncoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) untuk membaca byte. |
| byte_count | int | Ukuran buffer masukan. |
| chars | char_t * | [Buffer](../../../system/buffer/) untuk menempatkan karakter. |
| char_count | int | Ukuran buffer keluaran. |

### Nilai Kembalian

Jumlah karakter yang ditulis.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metode

Mendapatkan karakter yang dihasilkan dari decoding sebuah buffer byte.

```cpp
virtual int System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int byte_index, int byte_count, ArrayPtr<char_t> chars, int char_index)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) untuk membaca byte. |
| byte_index | int | Offset buffer masukan. |
| byte_count | int | Ukuran buffer masukan. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | [Buffer](../../../system/buffer/) untuk menempatkan karakter. |
| char_index | int | Offset buffer keluaran. |

### Nilai Kembalian

Jumlah karakter yang ditulis.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>, int, int) metode

Mendapatkan karakter yang dihasilkan dari decoding sebuah buffer byte.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) untuk membaca byte. |
| index | int | Offset buffer masukan. |
| count | int | Ukuran buffer masukan. |

### Nilai Kembalian

[Buffer](../../../system/buffer/) dari karakter yang didecode.

## ICUEncoding::GetChars(ArrayPtr\<uint8_t\>) metode

Mendapatkan karakter yang dihasilkan dari decoding sebuah buffer byte.

```cpp
virtual ArrayPtr<char_t> System::Text::Encoding::GetChars(ArrayPtr<uint8_t> bytes)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) untuk membaca byte. |

### Nilai Kembalian

[Buffer](../../../system/buffer/) dari karakter yang didecode.

## ICUEncoding::GetChars(const uint8_t *, int, char_t *, int) metode

Mendapatkan karakter yang dihasilkan dari decoding sebuah buffer byte.

```cpp
virtual int System::Text::Encoding::GetChars(const uint8_t *bytes, int byte_count, char_t *chars, int char_count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | const **uint8_t** * | [Buffer](../../../system/buffer/) untuk membaca byte. |
| byte_count | int | Ukuran buffer masukan. |
| chars | char_t * | [Buffer](../../../system/buffer/) untuk menempatkan karakter. |
| char_count | int | Ukuran buffer keluaran. |

### Nilai Kembalian

Jumlah karakter yang ditulis.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [ICUEncoding](../)
* Ruang Nama [System::Text](../../)
* Pustaka [Aspose.Slides](../../../)