---
title: GetByteCount()
second_title: Referensi API Aspose.Slides untuk C++
description: Dapatkan jumlah karakter yang diperlukan untuk mengkodekan buffer karakter.
type: docs
weight: 157
url: /id/system.text/utf7encoding/getbytecount/
---
## UTF7Encoding::GetByteCount(const char_t *, int) metode

Mendapatkan jumlah karakter yang diperlukan untuk mengkodekan buffer karakter.

```cpp
int System::Text::UTF7Encoding::GetByteCount(const char_t *chars, int count) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | const char_t * | Buffer karakter. |
| count | int | [Buffer](../../../system/buffer/) ukuran. |

### Nilai Kembali

Ukuran buffer yang diperlukan.

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) metode

Mendapatkan jumlah karakter yang diperlukan untuk mengkodekan buffer karakter.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars, int index, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer karakter. |
| index | int | Awal irisan. |
| count | int | Ukuran irisan. |

### Nilai Kembali

Ukuran buffer yang diperlukan.

## UTF7Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) metode

Mendapatkan jumlah karakter yang diperlukan untuk mengkodekan buffer karakter.

```cpp
virtual int System::Text::Encoding::GetByteCount(System::Details::ArrayView<char_t> chars, int index, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | System::Details::ArrayView\<char_t\> | Buffer karakter. |
| index | int | Awal irisan. |
| count | int | Ukuran irisan. |

### Nilai Kembali

Ukuran buffer yang diperlukan.

## UTF7Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) metode

Mendapatkan jumlah karakter yang diperlukan untuk mengkodekan buffer karakter.

```cpp
template<std::size_t> int System::Text::Encoding::GetByteCount(const System::Details::StackArray<char_t, N> &chars, int index, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | const System::Details::StackArray\<char_t, N\>\& | Buffer karakter. |
| index | int | Awal irisan. |
| count | int | Ukuran irisan. |

### Nilai Kembali

Ukuran buffer yang diperlukan.

## UTF7Encoding::GetByteCount(const String\&) metode

Mendapatkan jumlah karakter yang diperlukan untuk mengkodekan string.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) untuk dikodekan. |

### Nilai Kembali

Ukuran buffer yang diperlukan.

## UTF7Encoding::GetByteCount(ArrayPtr\<char_t\>) metode

Mendapatkan jumlah karakter yang diperlukan untuk mengkodekan buffer karakter.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer karakter. |

### Nilai Kembali

Ukuran buffer yang diperlukan.

## UTF7Encoding::GetByteCount(const char_t *, int) metode

Mendapatkan jumlah karakter yang diperlukan untuk mengkodekan buffer karakter.

```cpp
virtual int System::Text::Encoding::GetByteCount(const char_t *chars, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | const char_t * | Buffer karakter. |
| count | int | [Buffer](../../../system/buffer/) ukuran. |

### Nilai Kembali

Ukuran buffer yang diperlukan.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [UTF7Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)