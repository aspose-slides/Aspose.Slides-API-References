---
title: Fallback()
second_title: Referensi API Aspose.Slides untuk C++
description: Menangani kegagalan pengkodean.
type: docs
weight: 27
url: /id/system.text/encoderexceptionfallbackbuffer/fallback/
---
## EncoderExceptionFallbackBuffer::Fallback(char_t, int) metode

Menangani kegagalan pengkodean.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknown, int index) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| charUnknown | char_t | Karakter tidak dikenal; diabaikan. |
| index | int | Offset karakter tidak dikenal; diabaikan. |

### Nilai Kembali

Tidak pernah benar-benar mengembalikan, tetapi melempar pengecualian.

## EncoderExceptionFallbackBuffer::Fallback(char_t, char_t, int) metode

Menangani kegagalan pengkodean.

```cpp
virtual bool System::Text::EncoderExceptionFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| charUnknownHigh | char_t | Bagian tinggi pasangan surrogate yang memicu kesalahan. |
| charUnknownLow | char_t | Bagian rendah pasangan surrogate yang memicu kesalahan. |
| index | int | Offset karakter tidak dikenal; diabaikan. |

### Nilai Kembali

Tidak pernah benar-benar mengembalikan, tetapi melempar pengecualian.

## Lihat Juga

* Kelas [EncoderExceptionFallbackBuffer](../)
* Ruang Nama [System::Text](../../)
* Perpustakaan [Aspose.Slides](../../../)