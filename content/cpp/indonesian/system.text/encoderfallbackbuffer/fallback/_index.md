---
title: Fallback()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengimplementasikan prosedur fallback aktual.
type: docs
weight: 14
url: /id/system.text/encoderfallbackbuffer/fallback/
---
## EncoderFallbackBuffer::Fallback(char_t, int) metode

Mengimplementasikan prosedur fallback aktual.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknown, int index)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| charUnknown | char_t | Pengode karakter gagal mengkode. |
| index | int | [Index](../../../system/index/) dari karakter yang memicu kesalahan. |

### Nilai Kembali

True jika buffer memproses karakter yang tidak dikenal, false jika mengabaikannya.

## EncoderFallbackBuffer::Fallback(char_t, char_t, int) metode


Mengimplementasikan prosedur fallback aktual.

```cpp
virtual bool System::Text::EncoderFallbackBuffer::Fallback(char_t charUnknownHigh, char_t charUnknownLow, int index)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| charUnknownHigh | char_t | Bagian tinggi dari pasangan surrogate yang memicu kesalahan. |
| charUnknownLow | char_t | Bagian rendah dari pasangan surrogate yang memicu kesalahan. |
| index | int | [Index](../../../system/index/) dari karakter yang memicu kesalahan. |

### Nilai Kembali

True jika buffer memproses karakter yang tidak dikenal, false jika mengabaikannya.

## Lihat Juga

* Kelas [EncoderFallbackBuffer](../)
* Ruang Nama [System::Text](../../)
* Pustaka [Aspose.Slides](../../../)