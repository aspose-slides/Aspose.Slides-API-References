---
title: GetCharCount()
second_title: Aspose.Slides for C++ API Referansı
description: Bir tamponu çözmek için gerekli karakter sayısını alır.
type: docs
weight: 40
url: /tr/system.text/decoder/getcharcount/
---
## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int) metodu


Bir tamponu çözmek için gereken karakter sayısını alır.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kod çözülecek baytlar. |
| index | int | [Buffer](../../../system/buffer/) ofset. |
| count | int | Kod çözülecek bayt sayısı. |

### Dönüş Değeri

Kod çözmek için gereken karakter sayısı.

## Decoder::GetCharCount(ArrayPtr\<uint8_t\>, int, int, bool) metodu


Bir tamponu çözmek için gereken karakter sayısını alır.

```cpp
virtual int System::Text::Decoder::GetCharCount(ArrayPtr<uint8_t> bytes, int index, int count, bool flush)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Kod çözülecek baytlar. |
| index | int | [Buffer](../../../system/buffer/) ofset. |
| count | int | Kod çözülecek bayt sayısı. |
| flush | **bool** | Doğru ise, hesaplamadan sonra iç decoder durumunu temizler. |

### Dönüş Değeri

Kod çözmek için gereken karakter sayısı.

## Decoder::GetCharCount(const uint8_t *, int, bool) metodu


Bir tamponu çözmek için gereken karakter sayısını alır.

```cpp
virtual int System::Text::Decoder::GetCharCount(const uint8_t *bytes, int count, bool flush)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| bytes | const **uint8_t** * | Kod çözülecek baytlar. |
| count | int | Kod çözülecek bayt sayısı. |
| flush | **bool** | Doğru ise, hesaplamadan sonra iç decoder durumunu temizler. |

### Dönüş Değeri

Kod çözmek için gereken karakter sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [Decoder](../)
* Ad Alanı [System::Text](../../)
* Library [Aspose.Slides](../../../)