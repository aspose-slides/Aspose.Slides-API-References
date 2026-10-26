---
title: GetBytes()
second_title: Referensi API Aspose.Slides untuk C++
description: Dapatkan byte yang dihasilkan dari enkoding sebuah buffer.
type: docs
weight: 53
url: /id/system.text/icuencoder/getbytes/
---
## ICUEncoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) metode

Dapatkan byte yang dihasilkan dari enkoding buffer.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakter untuk dienkode. |
| charIndex | int | Offset array sumber. |
| charCount | int | Panjang subarray sumber. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer byte tujuan. |
| byteIndex | int | Offset buffer tujuan. |
| flush | **bool** | Jika true, membersihkan status enkoder internal setelah perhitungan. |

### Nilai Kembalian

Jumlah byte yang ditulis.

## ICUEncoder::GetBytes(const char_t *, int, uint8_t *, int, bool) metode

Dapatkan byte yang dihasilkan dari enkoding buffer.

```cpp
virtual int System::Text::ICUEncoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | const char_t * | Karakter untuk dienkode. |
| charCount | int | Panjang array sumber. |
| bytes | **uint8_t** * | Buffer byte tujuan. |
| byteCount | int | Ukuran buffer tujuan. |
| flush | **bool** | Jika true, membersihkan status enkoder internal setelah perhitungan. |

### Nilai Kembalian

Jumlah byte yang ditulis.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [ICUEncoder](../)
* Ruang nama [System::Text](../../)
* Perpustakaan [Aspose.Slides](../../../)