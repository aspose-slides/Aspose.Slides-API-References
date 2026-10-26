---
title: GetBytes()
second_title: Referensi API Aspose.Slides untuk C++
description: Dapatkan byte yang dihasilkan dari pengkodean buffer karakter.
type: docs
weight: 40
url: /id/system.text/icuencoding/getbytes/
---
## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) metode


Dapatkan byte yang dihasilkan dari pengkodean buffer karakter.

```cpp
int System::Text::ICUEncoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | const char_t * | Karakter untuk dienkode. |
| char_count | int | Jumlah karakter yang akan dikonversi. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) untuk menempatkan karakter. |
| byte_count | int | Ukuran buffer output. |

### Nilai Kembali

Jumlah byte yang ditulis.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) metode


Dapatkan byte yang dihasilkan dari pengkodean buffer karakter.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakter untuk dienkode. |
| char_index | int | Awal irisan karakter. |
| char_count | int | Jumlah karakter yang akan dikonversi. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) untuk menempatkan karakter. |
| byte_index | int | Offset buffer output. |

### Nilai Kembali

Jumlah byte yang ditulis.

## ICUEncoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) metode


Dapatkan byte yang dihasilkan dari pengkodean buffer karakter.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Karakter untuk dienkode. |
| char_index | int | Awal irisan karakter. |
| char_count | int | Jumlah karakter yang akan dikonversi. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) untuk menempatkan karakter. |
| byte_index | int | Offset buffer output. |

### Nilai Kembali

Jumlah byte yang ditulis.

## ICUEncoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) metode


Dapatkan byte yang dihasilkan dari pengkodean buffer karakter.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Karakter untuk dienkode. |
| char_index | int | Awal irisan karakter. |
| char_count | int | Jumlah karakter yang akan dikonversi. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) untuk menempatkan karakter. |
| byte_index | int | Offset buffer output. |

### Nilai Kembali

Jumlah byte yang ditulis.

## ICUEncoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) metode


Dapatkan byte yang dihasilkan dari pengkodean buffer karakter.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) untuk dienkode. |
| char_index | int | Awal irisan karakter. |
| char_count | int | Jumlah karakter yang akan dikonversi. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) untuk menempatkan karakter. |
| byte_index | int | Offset buffer output. |

### Nilai Kembali

Jumlah byte yang ditulis.

## ICUEncoding::GetBytes(const String\&) metode


Dapatkan byte yang dihasilkan dari pengkodean buffer karakter.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) untuk dienkode. |

### Nilai Kembali

[Buffer](../../../system/buffer/) yang menyimpan representasi karakter yang sedang dienkode.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>, int, int) metode


Dapatkan byte yang dihasilkan dari pengkodean buffer karakter.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakter untuk dienkode. |
| index | int | Awal irisan karakter. |
| count | int | Jumlah karakter yang akan dikonversi. |

### Nilai Kembali

[Buffer](../../../system/buffer/) yang menyimpan representasi karakter yang sedang dienkode.

## ICUEncoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) metode


Dapatkan byte yang dihasilkan dari pengkodean buffer karakter.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Karakter untuk dienkode. |
| index | int | Awal irisan karakter. |
| count | int | Jumlah karakter yang akan dikonversi. |

### Nilai Kembali

[Buffer](../../../system/buffer/) yang menyimpan representasi karakter yang sedang dienkode.

## ICUEncoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) metode


Dapatkan byte yang dihasilkan dari pengkodean buffer karakter.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Karakter untuk dienkode. |
| index | int | Awal irisan karakter. |
| count | int | Jumlah karakter yang akan dikonversi. |

### Nilai Kembali

[Buffer](../../../system/buffer/) yang menyimpan representasi karakter yang sedang dienkode.

## ICUEncoding::GetBytes(ArrayPtr\<char_t\>) metode


Dapatkan byte yang dihasilkan dari pengkodean buffer karakter.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakter untuk dienkode. |

### Nilai Kembali

[Buffer](../../../system/buffer/) yang menyimpan representasi karakter yang sedang dienkode.

## ICUEncoding::GetBytes(const char_t *, int, uint8_t *, int) metode


Dapatkan byte yang dihasilkan dari pengkodean buffer karakter.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | const char_t * | Karakter untuk dienkode. |
| char_count | int | Jumlah karakter yang akan dikonversi. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) untuk menempatkan karakter. |
| byte_count | int | Ukuran buffer output. |

### Nilai Kembali

Jumlah byte yang ditulis.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ICUEncoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)