---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides for C++ API Referansı
description: Elemanı okur ve BinHex içeriğini çözer.
type: docs
weight: 482
url: /tr/system.xml/xmlnodereader/readelementcontentasbinhex/
---
## XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metodu

Elemanı okur ve BinHex içeriğini çözer.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Sonuç metni kopyalanacak tampon. Bu değer **nullptr** olamaz. |
| index | **int32_t** | Sonucun kopyalanmaya başlanacağı tampon içindeki ofset. |
| count | **int32_t** | Tampona kopyalanacak en fazla bayt sayısı. Gerçek kopyalanan bayt sayısı bu yöntemden döndürülür. |

### Dönüş Değeri

Tampona yazılan bayt sayısı.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [XmlNodeReader](../)
* AdAlanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)