---
title: GetByteCount()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan jumlah byte yang diperlukan untuk mengodekan sebuah buffer.
type: docs
weight: 40
url: /id/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) metode

Mendapatkan jumlah byte yang diperlukan untuk mengodekan sebuah buffer.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakter yang akan dienkode. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Jumlah karakter yang akan dienkode. |
| flush | **bool** | Jika true, membersihkan status internal enkoder setelah perhitungan. |

### Nilai Kembali

Jumlah byte yang diperlukan untuk mengodekan buffer.

## Encoder::GetByteCount(const char_t *, int, bool) metode

Mendapatkan jumlah byte yang diperlukan untuk mengodekan sebuah buffer.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | const char_t * | Karakter yang akan dienkode. |
| count | int | Jumlah karakter yang akan dienkode. |
| flush | **bool** | Jika true, membersihkan status internal enkoder setelah perhitungan. |

### Nilai Kembali

Jumlah byte yang diperlukan untuk mengodekan buffer.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Encoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)