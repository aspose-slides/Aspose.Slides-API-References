---
title: GetChars()
second_title: Aspose.Slides for C++ API Referansı
description: Bir tamponun kod çözülmesinden elde edilen karakterleri alır.
type: docs
weight: 53
url: /tr/system.text/icudecoder/getchars/
---
## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int) metot

Bir tamponun kod çözülmesinden elde edilen karakterleri alır.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kod çözülmesi gereken baytlar. |
| byteIndex | int | Girdi tamponu ofseti. |
| byteCount | int | Girdi tamponu boyutu. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Hedef karakter tamponu. |
| charIndex | int | Hedef dizi ofseti. |

### Dönüş Değeri

Yazılan karakter sayısı.

## ICUDecoder::GetChars(ArrayPtr\<uint8_t\>, int, int, ArrayPtr\<char_t\>, int, bool) metot

Bir tamponun kod çözülmesinden elde edilen karakterleri alır.

```cpp
virtual int System::Text::ICUDecoder::GetChars(ArrayPtr<uint8_t> bytes, int byteIndex, int byteCount, ArrayPtr<char_t> chars, int charIndex, bool flush)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kod çözülmesi gereken baytlar. |
| byteIndex | int | Girdi tamponu ofseti. |
| byteCount | int | Girdi tamponu boyutu. |
| chars | [ArrayPtr](../../../system/arrayptr/)\<char_t\> | Hedef karakter tamponu. |
| charIndex | int | Hedef dizi ofseti. |
| flush | **bool** | Doğru ise, hesaplamadan sonra iç kod çözücü durumunu temizler. |

### Dönüş Değeri

Yazılan karakter sayısı.

## ICUDecoder::GetChars(const uint8_t *, int, char_t *, int, bool) metot

Bir tamponun kod çözülmesinden elde edilen karakterleri alır.

```cpp
virtual int System::Text::ICUDecoder::GetChars(const uint8_t *bytes, int byteCount, char_t *chars, int charCount, bool flush)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const **uint8_t** * | Kod çözülmesi gereken baytlar. |
| byteCount | int | Girdi tamponu boyutu. |
| chars | char_t * | Hedef karakter tamponu. |
| charCount | int | Hedef dizi boyutu. |
| flush | **bool** | Doğru ise, hesaplamadan sonra iç kod çözücü durumunu temizler. |

### Dönüş Değeri

Yazılan karakter sayısı.

## Ayrıca

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [ICUDecoder](../)
* Ad alanı [System::Text](../../)
* Library [Aspose.Slides](../../../)