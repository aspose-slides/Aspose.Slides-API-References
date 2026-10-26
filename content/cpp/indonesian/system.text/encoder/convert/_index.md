---
title: Convert()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi karakter menjadi byte.
type: docs
weight: 79
url: /id/system.text/encoder/convert/
---
## Encoder::Convert(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, int, bool, int\&, int\&, bool\&) method

Mengonversi karakter menjadi byte.

```cpp
virtual void System::Text::Encoder::Convert(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakter yang akan dienkode. |
| charIndex | int | Offset buffer masukan. |
| charCount | int | Ukuran buffer masukan. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer byte tujuan. |
| byteIndex | int | Offset array tujuan. |
| byteCount | int | Ukuran array tujuan. |
| flush | **bool** | Jika true, membersihkan status encoder internal setelah perhitungan. |
| charsUsed | int\& | Referensi ke variabel untuk menyimpan jumlah karakter yang dibaca. |
| bytesUsed | int\& | Referensi ke variabel untuk menyimpan jumlah byte yang ditulis. |
| completed | **bool**\& | Referensi ke variabel yang akan diatur true jika buffer masukan habis dan false bila tidak. |

## Encoder::Convert(const char_t *, int, uint8_t *, int, bool, int\&, int\&, bool\&) method

Mengonversi karakter menjadi byte.

```cpp
virtual void System::Text::Encoder::Convert(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush, int &charsUsed, int &bytesUsed, bool &completed)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| chars | const char_t * | Karakter yang akan dienkode. |
| charCount | int | Ukuran buffer masukan. |
| bytes | **uint8_t** * | Buffer byte tujuan. |
| byteCount | int | Ukuran array tujuan. |
| flush | **bool** | Jika true, membersihkan status encoder internal setelah perhitungan. |
| charsUsed | int\& | Referensi ke variabel untuk menyimpan jumlah karakter yang dibaca. |
| bytesUsed | int\& | Referensi ke variabel untuk menyimpan jumlah byte yang ditulis. |
| completed | **bool**\& | Referensi ke variabel yang akan diatur true jika buffer masukan habis dan false bila tidak. |

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [Encoder](../)
* Ruang Nama [System::Text](../../)
* Library [Aspose.Slides](../../../)