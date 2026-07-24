---
title: ReadContentAsBase64()
second_title: Aspose.Slides for C++ API Referansı
description: İçeriği okur ve Base64 kodu çözülmüş ikili baytları döndürür.
type: docs
weight: 573
url: /tr/system.xml/xmlvalidatingreader/readcontentasbase64/
---
## XmlValidatingReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) metot


İçeriği okuyup Base64 kodu çözülmüş ikili baytları döndürür.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Elde edilen metni kopyalamak için kullanılacak tampon. Bu değer **nullptr** olamaz. |
| index | **int32_t** | Tampon içinde sonuç kopyalanmaya başlanacak ofset. |
| count | **int32_t** | Tampona kopyalanacak en fazla bayt sayısı. Aslında kopyalanan bayt sayısı bu yöntemden döndürülür. |

### Dönüş Değeri

Tampona yazılan bayt sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [XmlValidatingReader](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)