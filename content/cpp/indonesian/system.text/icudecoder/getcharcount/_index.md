---
title: GetCharCount()
second_title: Aspose.Slides untuk C++ Referensi API
description: Mendapatkan jumlah karakter yang diperlukan untuk mendekode sebuah buffer.
type: docs
weight: 40
url: /id/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metode

Mendapatkan jumlah karakter yang diperlukan untuk mendekode buffer.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Number of bytes to decode. |

### Nilai Kembali

Jumlah karakter yang diperlukan untuk mendekode buffer.

## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) metode

Mendapatkan jumlah karakter yang diperlukan untuk mendekode buffer.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Bytes to decode. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Number of bytes to decode. |
| flush | **bool** | If true, cleans internal decoder state after calculation. |

### Nilai Kembali

Jumlah karakter yang diperlukan untuk mendekode buffer.

## ICUDecoder::GetCharCount(const uint8_t *, int, bool) metode

Mendapatkan jumlah karakter yang diperlukan untuk mendekode buffer.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | const **uint8_t** * | Bytes to decode. |
| count | int | Number of bytes to decode. |
| flush | **bool** | If true, cleans internal decoder state after calculation. |

### Nilai Kembali

Jumlah karakter yang diperlukan untuk mendekode buffer.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [ICUDecoder](../)
* Namespace [System::Text](../../)
* Pustaka [Aspose.Slides](../../../)