---
title: ReadContentAsBase64()
second_title: Aspose.Slides için C++ API Referansı
description: İçeriği okur ve Base64 çözülen ikili baytları döndürür.
type: docs
weight: 638
url: /tr/system.xml/xmltextreader/readcontentasbase64/
---
## XmlTextReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) yöntemi

İçeriği okur ve **Base64** çözülen ikili baytları döndürür.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Sonuç metni kopyalanacak tampon. Bu değer **nullptr** olamaz. |
| index | **int32_t** | Sonucun kopyalanmaya başlanacağı tampon içindeki ofset. |
| count | **int32_t** | Tampona kopyalanacak en fazla bayt sayısı. Gerçek kopyalanan bayt sayısı bu yöntemden döndürülür. |

### Dönüş Değeri

Tampona yazılan bayt sayısı.

## Ayrıca

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [XmlTextReader](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)