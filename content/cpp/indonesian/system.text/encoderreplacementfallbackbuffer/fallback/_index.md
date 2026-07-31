---
title: Fallback()
second_title: Referensi API Aspose.Slides untuk C++
description: Menangani kegagalan encoding.
type: docs
weight: 27
url: /id/system.text/encoderreplacementfallbackbuffer/fallback/
---
## EncoderReplacementFallbackBuffer::Fallback(char_t, int) metode


Menangani kegagalan encoding.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknown, int index) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| charUnknown | char_t | Karakter tidak dikenal; diabaikan. |
| index | int | Posisi karakter tidak dikenal; diabaikan. |

### Nilai Kembali

True jika string pengganti disediakan dan tidak kosong, false jika tidak.

## EncoderReplacementFallbackBuffer::Fallback(char_t, char_t, int) metode


Menangani kegagalan encoding.

```cpp
virtual bool System::Text::EncoderReplacementFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| charUnknownHigh | char_t | Bagian tinggi pasangan surrogate yang memicu kesalahan. |
| charUnknownLow | char_t | Bagian rendah pasangan surrogate yang memicu kesalahan. |
| index | int | Posisi karakter tidak dikenal; diabaikan. |

### Nilai Kembali

True jika string pengganti disediakan dan tidak kosong, false jika tidak.

## Lihat Juga

* Kelas [EncoderReplacementFallbackBuffer](../)
* Ruang Nama [System::Text](../../)
* Perpustakaan [Aspose.Slides](../../../)