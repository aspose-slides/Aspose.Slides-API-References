---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides for C++ API Referansı
description: Elemanı okur ve Base64 içeriğini çözer.
type: docs
weight: 586
url: /tr/system.xml/xmlvalidatingreader/readelementcontentasbase64/
---
## XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metot


Element'i okur ve Base64 içeriğini çözer.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Sonuç metni kopyalanacak tampon. Bu değer **nullptr** olamaz. |
| index | **int32_t** | Tampon içinde sonucun kopyalanmaya başlanacağı ofset. |
| count | **int32_t** | Tampona kopyalanacak azami bayt sayısı. Gerçek kopyalanan bayt sayısı bu metottan döndürülür. |

### Dönüş Değeri

Tampona yazılan bayt sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [XmlValidatingReader](../)
* AdAlanı [System::Xml](../../)
* Library [Aspose.Slides](../../../)