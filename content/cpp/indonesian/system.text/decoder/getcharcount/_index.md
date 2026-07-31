---
title: GetCharCount()
second_title: Aspose.Slides untuk Referensi API C++
description: Mendapatkan jumlah karakter yang diperlukan untuk mendekode sebuah buffer.
type: docs
weight: 40
url: /id/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metode

Mendapatkan jumlah karakter yang diperlukan untuk mendekode sebuah buffer.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte yang akan didekode. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Jumlah byte yang akan didekode. |

### Nilai Kembalian

Jumlah karakter yang diperlukan untuk mendekode buffer.

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) metode

Mendapatkan jumlah karakter yang diperlukan untuk mendekode sebuah buffer.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte yang akan didekode. |
| index | int | [Buffer](../../../system/buffer/) offset. |
| count | int | Jumlah byte yang akan didekode. |
| flush | **bool** | Jika true, membersihkan keadaan internal decoder setelah perhitungan. |

### Nilai Kembalian

Jumlah karakter yang diperlukan untuk mendekode buffer.

## Decoder::GetCharCount(const uint8_t *, int, bool) metode

Mendapatkan jumlah karakter yang diperlukan untuk mendekode sebuah buffer.

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byte yang akan didekode. |
| count | int | Jumlah byte yang akan didekode. |
| flush | **bool** | Jika true, membersihkan keadaan internal decoder setelah perhitungan. |

### Nilai Kembalian

Jumlah karakter yang diperlukan untuk mendekode buffer.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [Decoder](../)
* Ruang Nama [System::Text](../../)
* Perpustakaan [Aspose.Slides](../../../)