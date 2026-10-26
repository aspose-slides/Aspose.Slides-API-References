---
title: ReadElementContentAsBase64()
second_title: Aspose.Slides için C++ API Referansı
description: Elemanı okur ve Base64 içeriğini çözer.
type: docs
weight: 651
url: /tr/system.xml/xmltextreader/readelementcontentasbase64/
---
## XmlTextReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metodu

Elemanı okur ve Base64 içeriğini çözer.

```cpp
int32_t System::Xml::XmlTextReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Sonuç metnin kopyalanacağı tampon. Bu değer **nullptr** olamaz. |
| index | **int32_t** | Sonucun kopyalanmaya başlanacağı tampondaki ofset. |
| count | **int32_t** | Tampona kopyalanacak maksimum bayt sayısı. Gerçek kopyalanan bayt sayısı bu metoddan döndürülür. |

### Dönüş Değeri

Tampona yazılan bayt sayısı.

## Diğer Bağlantılar

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [XmlTextReader](../)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)