---
title: Convert()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengonversi byte menjadi karakter.
type: docs
weight: 1
url: /id/system.text/encodingdecoder/convert/
---
## EncodingDecoder::Convert(const uint8_t *, int, char_t *, int, bool, int\&, int\&, bool\&) method

Mengonversi byte menjadi karakter.

```cpp
void System::Text::EncodingDecoder::Convert(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byte untuk didekodekan. |
| byteCount | int | Ukuran buffer masukan. |
| chars | char_t * | Buffer karakter tujuan. |
| charCount | int | Ukuran array tujuan. |
| flush | **bool** | Jika true, membersihkan keadaan dekoder internal setelah perhitungan. |
| bytesUsed | int\& | Referensi ke variabel untuk menyimpan jumlah byte yang dibaca. |
| charsUsed | int\& | Referensi ke variabel untuk menyimpan jumlah karakter yang ditulis. |
| completed | **bool**\& | Referensi ke variabel yang diatur ke true jika buffer masukan habis dan ke false jika tidak. |

## EncodingDecoder::Convert(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, int, bool, int\&, int\&, bool\&) method

Mengonversi byte menjadi karakter.

```cpp
void System::Text::EncodingDecoder::Convert(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, int charCount, bool flush, int &bytesUsed, int &charsUsed, bool &completed) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte untuk didekodekan. |
| byteIndex | int | Offset buffer masukan. |
| byteCount | int | Ukuran buffer masukan. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer karakter tujuan. |
| charIndex | int | Offset array tujuan. |
| charCount | int | Ukuran array tujuan. |
| flush | **bool** | Jika true, membersihkan keadaan dekoder internal setelah perhitungan. |
| bytesUsed | int\& | Referensi ke variabel untuk menyimpan jumlah byte yang dibaca. |
| charsUsed | int\& | Referensi ke variabel untuk menyimpan jumlah karakter yang ditulis. |
| completed | **bool**\& | Referensi ke variabel yang diatur ke true jika buffer masukan habis dan ke false jika tidak. |

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [EncodingDecoder](../)
* Namespace [System::Text](../../)
* Library [Aspose.Slides](../../../)