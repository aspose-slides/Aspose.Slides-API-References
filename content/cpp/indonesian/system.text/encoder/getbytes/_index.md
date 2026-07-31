---
title: GetBytes()
second_title: Referensi API Aspose.Slides untuk C++
description: Dapatkan byte yang dihasilkan dari penyandian sebuah buffer.
type: docs
weight: 53
url: /id/system.text/encoder/getbytes/
---
## Encoder::GetBytes(ArrayPtr\<char_t\>, int, int, ArrayPtr\<uint8_t\>, int, bool) method


Dapatkan byte yang dihasilkan dari penyandian buffer.

```cpp
virtual int System::Text::Encoder::GetBytes(ArrayPtr<char_t> chars, int charIndex, int charCount, ArrayPtr<uint8_t> bytes, int byteIndex, bool flush)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Karakter yang akan disandikan. |
| charIndex | int | Offset array sumber. |
| charCount | int | Panjang subarray sumber. |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Buffer byte tujuan. |
| byteIndex | int | Offset buffer tujuan. |
| flush | **bool** | Jika true, membersihkan keadaan encoder internal setelah perhitungan. |

### Nilai Kembalian

Jumlah byte yang ditulis.

## Encoder::GetBytes(const char_t *, int, uint8_t *, int, bool) method


Dapatkan byte yang dihasilkan dari penyandian buffer.

```cpp
virtual int System::Text::Encoder::GetBytes(const char_t *chars, int charCount, uint8_t *bytes, int byteCount, bool flush)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| chars | const char_t * | Karakter yang akan disandikan. |
| charCount | int | Panjang array sumber. |
| bytes | **uint8_t** * | Buffer byte tujuan. |
| byteCount | int | Ukuran buffer tujuan. |
| flush | **bool** | Jika true, membersihkan keadaan encoder internal setelah perhitungan. |

### Nilai Kembalian

Jumlah byte yang ditulis.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [Encoder](../)
* Ruang Nama [System::Text](../../)
* Library [Aspose.Slides](../../../)