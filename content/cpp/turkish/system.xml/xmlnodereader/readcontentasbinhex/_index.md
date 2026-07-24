---
title: ReadContentAsBinHex()
second_title: Aspose.Slides for C++ API Referansı
description: İçeriği okur ve BinHex çözümlenmiş ikili baytları döndürür.
type: docs
weight: 456
url: /tr/system.xml/xmlnodereader/readcontentasbinhex/
---
## XmlNodeReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) yöntemi

İçeriği okur ve BinHex çözümlenmiş ikili baytları döndürür.

```cpp
int32_t System::Xml::XmlNodeReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Sonuç metnin kopyalanacağı tampon. Bu değer **nullptr** olamaz. |
| index | **int32_t** | Sonucun kopyalanmaya başlanacağı tampon içindeki ofset. |
| count | **int32_t** | Tampona kopyalanacak maksimum bayt sayısı. Gerçek kopyalanan bayt sayısı bu yöntemden döndürülür. |

### Dönüş Değeri

Tampona yazılan bayt sayısı.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [XmlNodeReader](../)
* İsim Uzayı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)