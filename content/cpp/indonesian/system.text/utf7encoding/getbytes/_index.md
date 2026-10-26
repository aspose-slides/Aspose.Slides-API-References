---
title: GetBytes()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan byte yang dihasilkan dari pengkodean buffer karakter.
type: docs
weight: 66
url: /id/system.text/utf7encoding/getbytes/
---
## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) metode

Mendapatkan byte yang dihasilkan dari mengkodekan buffer karakter.

```cpp
int System::Text::UTF7Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakter yang akan dienkode. |
| char_index | int | Awal irisan karakter. |
| char_count | int | Jumlah karakter yang akan dikonversi. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) untuk menempatkan karakter ke. |
| byte_index | int | Offset buffer keluaran. |

### Nilai Kembali

Jumlah byte yang ditulis.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) metode

Mendapatkan byte yang dihasilkan dari mengkodekan buffer karakter.

```cpp
int System::Text::UTF7Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count) override
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Karakter yang akan dienkode. |
| char_count | int | Jumlah karakter yang akan dikonversi. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) untuk menempatkan karakter ke. |
| byte_count | int | Ukuran buffer keluaran. |

### Nilai Kembali

Jumlah byte yang ditulis.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) metode

Mendapatkan byte yang dihasilkan dari mengkodekan buffer karakter.

```cpp
int System::Text::UTF7Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index) override
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) untuk dienkode. |
| char_index | int | Awal irisan karakter. |
| char_count | int | Jumlah karakter yang akan dikonversi. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) untuk menempatkan karakter ke. |
| byte_index | int | Offset buffer keluaran. |

### Nilai Kembali

Jumlah byte yang ditulis.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int) metode

Mendapatkan byte yang dihasilkan dari mengkodekan buffer karakter.

```cpp
virtual int System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakter yang akan dienkode. |
| char_index | int | Awal irisan karakter. |
| char_count | int | Jumlah karakter yang akan dikonversi. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) untuk menempatkan karakter ke. |
| byte_index | int | Offset buffer keluaran. |

### Nilai Kembali

Jumlah byte yang ditulis.

## UTF7Encoding::GetBytes(System::Details::ArrayView\<char_t\>, int, int, System::Details::ArrayView\<uint8_t\>, int) metode

Mendapatkan byte yang dihasilkan dari mengkodekan buffer karakter.

```cpp
virtual int System::Text::Encoding::GetBytes(System::Details::ArrayView<char_t> chars, int char_index, int char_count, System::Details::ArrayView<uint8_t> bytes, int byte_index)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Karakter yang akan dienkode. |
| char_index | int | Awal irisan karakter. |
| char_count | int | Jumlah karakter yang akan dikonversi. |
| bytes | System::Details::ArrayView\<**uint8_t**\> | [Buffer](../../../system/buffer/) untuk menempatkan karakter ke. |
| byte_index | int | Offset buffer keluaran. |

### Nilai Kembali

Jumlah byte yang ditulis.

## UTF7Encoding::GetBytes(System::Details::StackArray\<char_t, SC\>\&, int, int, System::Details::StackArray\<uint8_t, SB\>\&, int) metode

Mendapatkan byte yang dihasilkan dari mengkodekan buffer karakter.

```cpp
template<std::size_t,std::size_t> int System::Text::Encoding::GetBytes(System::Details::StackArray<char_t, SC> &chars, int char_index, int char_count, System::Details::StackArray<uint8_t, SB> &bytes, int byte_index)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| chars | System::Details::StackArray\<char_t, SC\>\& | Karakter yang akan dienkode. |
| char_index | int | Awal irisan karakter. |
| char_count | int | Jumlah karakter yang akan dikonversi. |
| bytes | System::Details::StackArray\<**uint8_t**, SB\>\& | [Buffer](../../../system/buffer/) untuk menempatkan karakter ke. |
| byte_index | int | Offset buffer keluaran. |

### Nilai Kembali

Jumlah byte yang ditulis.

## UTF7Encoding::GetBytes(const String\&, int, int, ArrayPtr\<uint8_t\>, int) metode

Mendapatkan byte yang dihasilkan dari mengkodekan buffer karakter.

```cpp
virtual int System::Text::Encoding::GetBytes(const String &s, int char_index, int char_count, ArrayPtr<uint8_t> bytes, int byte_index)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) untuk dienkode. |
| char_index | int | Awal irisan karakter. |
| char_count | int | Jumlah karakter yang akan dikonversi. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Buffer](../../../system/buffer/) untuk menempatkan karakter ke. |
| byte_index | int | Offset buffer keluaran. |

### Nilai Kembali

Jumlah byte yang ditulis.

## UTF7Encoding::GetBytes(const String\&) metode

Mendapatkan byte yang dihasilkan dari mengkodekan buffer karakter.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const String &s)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) untuk dienkode. |

### Nilai Kembali

[Buffer](../../../system/buffer/) yang berisi representasi karakter yang sedang dienkode.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>, int, int) metode

Mendapatkan byte yang dihasilkan dari mengkodekan buffer karakter.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars, int index, int count)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakter yang akan dienkode. |
| index | int | Awal irisan karakter. |
| count | int | Jumlah karakter yang akan dikonversi. |

### Nilai Kembali

[Buffer](../../../system/buffer/) yang berisi representasi karakter yang sedang dienkode.

## UTF7Encoding::GetBytes(const System::Details::ArrayView\<char_t\>\&, int, int) metode

Mendapatkan byte yang dihasilkan dari mengkodekan buffer karakter.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::ArrayView<char_t> &chars, int index, int count)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::ArrayView\<char_t\>\& | Karakter yang akan dienkode. |
| index | int | Awal irisan karakter. |
| count | int | Jumlah karakter yang akan dikonversi. |

### Nilai Kembali

[Buffer](../../../system/buffer/) yang berisi representasi karakter yang sedang dienkode.

## UTF7Encoding::GetBytes(const System::Details::StackArray\<char_t, N\>\&, int, int) metode

Mendapatkan byte yang dihasilkan dari mengkodekan buffer karakter.

```cpp
template<std::size_t> ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Karakter yang akan dienkode. |
| index | int | Awal irisan karakter. |
| count | int | Jumlah karakter yang akan dikonversi. |

### Nilai Kembali

[Buffer](../../../system/buffer/) yang berisi representasi karakter yang sedang dienkode.

## UTF7Encoding::GetBytes(ArrayPtr\<char_t\>) metode

Mendapatkan byte yang dihasilkan dari mengkodekan buffer karakter.

```cpp
virtual ArrayPtr<uint8_t> System::Text::Encoding::GetBytes(ArrayPtr<char_t> chars)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakter yang akan dienkode. |

### Nilai Kembali

[Buffer](../../../system/buffer/) yang berisi representasi karakter yang sedang dienkode.

## UTF7Encoding::GetBytes(const char_t *, int, uint8_t *, int) metode

Mendapatkan byte yang dihasilkan dari mengkodekan buffer karakter.

```cpp
virtual int System::Text::Encoding::GetBytes(const char_t *chars, int char_count, uint8_t *bytes, int byte_count)
```

### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Karakter yang akan dienkode. |
| char_count | int | Jumlah karakter yang akan dikonversi. |
| bytes | **uint8_t** * | [Buffer](../../../system/buffer/) untuk menempatkan karakter ke. |
| byte_count | int | Ukuran buffer keluaran. |

### Nilai Kembali

Jumlah byte yang ditulis.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [UTF7Encoding](../)
* Kelas [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)