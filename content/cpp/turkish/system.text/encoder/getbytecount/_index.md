---
title: GetByteCount()
second_title: Aspose.Slides için C++ API Referansı
description: Bir tamponu kodlamak için gereken bayt sayısını alır.
type: docs
weight: 40
url: /tr/system.text/encoder/getbytecount/
---
## Encoder::GetByteCount(ArrayPtr\<char_t\>, int, int, bool) method

Bir tamponu kodlamak için gereken bayt sayısını alır.

```cpp
virtual int System::Text::Encoder::GetByteCount(ArrayPtr<char_t> chars, int index, int count, bool flush)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Kodlanacak karakterler. |
| index | int | [Buffer](../../../system/buffer/) ofset. |
| count | int | Kodlanacak karakter sayısı. |
| flush | **bool** | Doğru ise, hesaplamadan sonra iç kodlayıcı durumunu temizler. |

### Return Value

Tamponu kodlamak için gereken bayt sayısı.

## Encoder::GetByteCount(const char_t *, int, bool) method

Bir tamponu kodlamak için gereken bayt sayısını alır.

```cpp
virtual int System::Text::Encoder::GetByteCount(const char_t *chars, int count, bool flush)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| chars | const char_t * | Kodlanacak karakterler. |
| count | int | Kodlanacak karakter sayısı. |
| flush | **bool** | Doğru ise, hesaplamadan sonra iç kodlayıcı durumunu temizler. |

### Return Value

Tamponu kodlamak için gereken bayt sayısı.

## İlgili

* Tip tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [Encoder](../)
* Ad alanı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)