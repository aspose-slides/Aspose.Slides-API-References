---
title: GetCharCount()
second_title: Aspose.Slides for C++ API Referansı
description: Bir tamponu çözmek için gereken karakter sayısını alır.
type: docs
weight: 40
url: /tr/system.text/icudecoder/getcharcount/
---
## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metodu

Bir tamponu çözmek için gereken karakter sayısını alır.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Çözümlemesi gereken baytlar. |
| index | int | [Buffer](../../../system/buffer/) ofset. |
| count | int | Çözümlemesi gereken bayt sayısı. |

### Dönüş Değeri

Tamponu çözmek için gereken karakter sayısı.

## ICUDecoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) metodu

Bir tamponu çözmek için gereken karakter sayısını alır.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Çözümlemesi gereken baytlar. |
| index | int | [Buffer](../../../system/buffer/) ofset. |
| count | int | Çözümlemesi gereken bayt sayısı. |
| flush | **bool** | Doğruysa, hesaplamadan sonra iç çözücü durumunu temizler. |

### Dönüş Değeri

Tamponu çözmek için gereken karakter sayısı.

## ICUDecoder::GetCharCount(const uint8_t *, int, bool) metodu

Bir tamponu çözmek için gereken karakter sayısını alır.

```cpp
virtual int System::Text::ICUDecoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const **uint8_t** * | Çözümlemesi gereken baytlar. |
| count | int | Çözümlemesi gereken bayt sayısı. |
| flush | **bool** | Doğruysa, hesaplamadan sonra iç çözücü durumunu temizler. |

### Dönüş Değeri

Tamponu çözmek için gereken karakter sayısı.

## İlgili

* Tip tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [ICUDecoder](../)
* Ad alanı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)