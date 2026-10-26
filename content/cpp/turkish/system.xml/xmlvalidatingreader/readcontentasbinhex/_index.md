---
title: ReadContentAsBinHex()
second_title: Aspose.Slides C++ için API Referansı
description: İçeriği okur ve BinHex çözümlenmiş ikili baytları döndürür.
type: docs
weight: 599
url: /tr/system.xml/xmlvalidatingreader/readcontentasbinhex/
---
## XmlValidatingReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) yöntemi

İçeriği okur ve BinHex çözülmüş ikili baytları döndürür.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Sonuç metnin kopyalanacağı tampon. Bu değer **nullptr** olamaz. |
| index | **int32_t** | Sonucun kopyalanmaya başlanacağı tampon içindeki ofset. |
| count | **int32_t** | Tampona kopyalanacak azami bayt sayısı. Gerçek kopyalanan bayt sayısı bu yöntemden döndürülür. |

### Dönüş Değeri

Tampona yazılan bayt sayısı.

## İlgili

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [XmlValidatingReader](../)
* AdAlanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)