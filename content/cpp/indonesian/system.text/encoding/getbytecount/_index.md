---
title: GetByteCount()
second_title: Referensi API Aspose.Slides untuk C++
description: Dapatkan jumlah karakter yang diperlukan untuk mengenkode buffer karakter.
type: docs
weight: 235
url: /id/system.text/encoding/getbytecount/
---
## Encoding::GetByteCount(ArrayPtr\<char_t\>, int, int) metode

Dapatkan jumlah karakter yang diperlukan untuk mengenkode buffer karakter.

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

## Encoding::GetByteCount(System::Details::ArrayView\<char_t\>, int, int) metode

Dapatkan jumlah karakter yang diperlukan untuk mengenkode buffer karakter.

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

## Encoding::GetByteCount(const System::Details::StackArray\<char_t, N\>\&, int, int) metode

Dapatkan jumlah karakter yang diperlukan untuk mengenkode buffer karakter.

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

## Encoding::GetByteCount(const String\&) metode

Dapatkan jumlah karakter yang diperlukan untuk mengenkode string.

```cpp
virtual int System::Text::Encoding::GetByteCount(const String &s)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| s | const [String](../../../system/string/)\& | [String](../../../system/string/) untuk dienkode. |

### Nilai Kembali

Ukuran buffer yang diperlukan.

## Encoding::GetByteCount(ArrayPtr\<char_t\>) metode

Dapatkan jumlah karakter yang diperlukan untuk mengenkode buffer karakter.

```cpp
virtual int System::Text::Encoding::GetByteCount(ArrayPtr<char_t> chars)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer karakter. |

### Nilai Kembali

Ukuran buffer yang diperlukan.

## Encoding::GetByteCount(const char_t *, int) metode

Dapatkan jumlah karakter yang diperlukan untuk mengenkode buffer karakter.

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
* Class [Encoding](../)
* Class [String](../../../system/string/)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)