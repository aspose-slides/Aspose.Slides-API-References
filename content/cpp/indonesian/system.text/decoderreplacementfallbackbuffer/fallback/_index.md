---
title: Fallback()
second_title: Referensi API Aspose.Slides untuk C++
description: Menangani kegagalan decoding.
type: docs
weight: 27
url: /id/system.text/decoderreplacementfallbackbuffer/fallback/
---
## DecoderReplacementFallbackBuffer::Fallback(ArrayPtr\<uint8_t\>, int) metode

Menangani kegagalan decoding.

```cpp
virtual bool System::Text::DecoderReplacementFallbackBuffer::Fallback(ArrayPtr<uint8_t> bytesUnknown, int index) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bytesUnknown | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | [Array](../../../system/array/) dari byte yang tidak dikenal; diabaikan. |
| index | int | Offset byte yang tidak dikenal; diabaikan. |

### Nilai Kembali

True jika string pengganti disediakan dan tidak kosong, false sebaliknya.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [DecoderReplacementFallbackBuffer](../)
* Namespace [System::Text](../../)
* Pustaka [Aspose.Slides](../../../)