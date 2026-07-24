---
title: Convert()
second_title: Aspose.Slides için C++ API Referansı
description: İki kodlama arasında baytları dönüştürür.
type: docs
weight: 378
url: /tr/system.text/encoding/convert/
---
## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&) metodu


İki kodlama arasında baytları dönüştürür.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kaynak kodlama. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Hedef kodlama. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Dönüştürülecek baytlar. |

### Dönüş Değeri

Dönüştürülmüş baytlar.

## Encoding::Convert(const EncodingPtr\&, const EncodingPtr\&, const ArrayPtr\<uint8_t\>\&, int, int) metodu


İki kodlama arasında baytları dönüştürür.

```cpp
static ArrayPtr<uint8_t> System::Text::Encoding::Convert(const EncodingPtr &src_encoding, const EncodingPtr &dst_encoding, const ArrayPtr<uint8_t> &bytes, int index, int count)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| src_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Kaynak kodlama. |
| dst_encoding | const [EncodingPtr](../../../system/encodingptr/)\& | Hedef kodlama. |
| bytes | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Dönüştürülecek baytlar. |
| index | int | Dilim başlangıcı. |
| count | int | Dilim boyutu. |

### Dönüş Değeri

Dönüştürülmüş baytlar.

## Ayrıca Bakınız

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Tip Tanımı [EncodingPtr](../../../system/encodingptr/)
* Sınıf [Encoding](../)
* Ad Alanı [System::Text](../../)
* Kütüphane [Aspose.Slides](../../../)