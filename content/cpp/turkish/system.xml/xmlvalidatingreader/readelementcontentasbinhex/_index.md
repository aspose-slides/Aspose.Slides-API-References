---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides for C++ API Referansı
description: Elemanı okur ve BinHex içeriğini çözer.
type: docs
weight: 612
url: /tr/system.xml/xmlvalidatingreader/readelementcontentasbinhex/
---
## XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) yöntemi

Elemanı okur ve BinHex içeriğini çözer.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Sonuç metnin kopyalanacağı buffer. Bu değer **nullptr** olamaz. |
| index | **int32_t** | Sonucun kopyalanmaya başlanacağı buffer içindeki offset. |
| count | **int32_t** | Tampona kopyalanacak maksimum bayt sayısı. Kopyalanan gerçek bayt sayısı bu yöntemden döndürülür. |

### Dönüş Değeri

Tampona yazılan bayt sayısı.

## Ayrıca Bakınız

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [XmlValidatingReader](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)