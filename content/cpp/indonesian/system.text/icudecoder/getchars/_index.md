---
title: GetChars()
second_title: Referensi API Aspose.Slides untuk C++
description: Dapatkan karakter yang dihasilkan dari mendekode buffer.
type: docs
weight: 53
url: /id/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) method

Dapatkan karakter yang dihasilkan dari mendekode buffer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte yang akan didekode. |
| byteIndex | int | Offset buffer masukan. |
| byteCount | int | Ukuran buffer masukan. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer karakter tujuan. |
| charIndex | int | Offset array tujuan. |

### Nilai Kembali

Jumlah karakter yang ditulis.

## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) method

Dapatkan karakter yang dihasilkan dari mendekode buffer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Byte yang akan didekode. |
| byteIndex | int | Offset buffer masukan. |
| byteCount | int | Ukuran buffer masukan. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Buffer karakter tujuan. |
| charIndex | int | Offset array tujuan. |
| flush | **bool** | Jika true, membersihkan status decoder internal setelah perhitungan. |

### Nilai Kembali

Jumlah karakter yang ditulis.

## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) method

Dapatkan karakter yang dihasilkan dari mendekode buffer.

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytes | const **uint8_t** * | Byte yang akan didekode. |
| byteCount | int | Ukuran buffer masukan. |
| chars | char_t * | Buffer karakter tujuan. |
| charCount | int | Ukuran array tujuan. |
| flush | **bool** | Jika true, membersihkan status decoder internal setelah perhitungan. |

### Nilai Kembali

Jumlah karakter yang ditulis.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [ICUDecoder](../)
* Ruang Nama [System::Text](../../)
* Pustaka [Aspose.Slides](../../../)