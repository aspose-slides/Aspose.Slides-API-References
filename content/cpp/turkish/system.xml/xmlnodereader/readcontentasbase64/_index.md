---
title: ReadContentAsBase64()
second_title: Aspose.Slides for C++ API Referansı
description: İçeriği okur ve Base64 çözümlenmiş ikili baytları döndürür.
type: docs
weight: 443
url: /tr/system.xml/xmlnodereader/readcontentasbase64/
---
## XmlNodeReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metot


İçeriği okur ve Base64 çözümlenmiş ikili baytları döndürür.

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Sonuç metnin kopyalanacağı tampon. Bu değer **nullptr** olamaz. |
| index | **int32_t** | Sonucun kopyalanmaya başlanacağı tampon içindeki ofset. |
| count | **int32_t** | Tampona kopyalanacak azami bayt sayısı. Asıl kopyalanan bayt sayısı bu metottan döndürülür. |

### Dönüş Değeri

Tampona yazılan bayt sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [XmlNodeReader](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)