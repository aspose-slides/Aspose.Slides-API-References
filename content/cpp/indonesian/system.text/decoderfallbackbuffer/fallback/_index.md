---
title: Fallback()
second_title: Referensi API Aspose.Slides untuk C++
description: Menerapkan prosedur fallback aktual.
type: docs
weight: 14
url: /id/system.text/decoderfallbackbuffer/fallback/
---
## DecoderFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) metode

Menerapkan prosedur fallback aktual.

```cpp
virtual bool System::Text::DecoderFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) dari byte termasuk yang gagal didekode oleh decoder. |
| index | int | [Index](../../../system/index/) dari byte yang memicu kesalahan. |

### Nilai Kembalian

True jika buffer memproses byte yang tidak diketahui, false jika mengabaikannya.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [DecoderFallbackBuffer](../)
* Ruang Nama [System::Text](../../)
* Library [Aspose.Slides](../../../)