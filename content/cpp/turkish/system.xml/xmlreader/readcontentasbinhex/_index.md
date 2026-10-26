---
title: ReadContentAsBinHex()
second_title: Aspose.Slides için C++ API Referansı
description: İçeriği okur ve BinHex çözülen ikili baytları döndürür.
type: docs
weight: 781
url: /tr/system.xml/xmlreader/readcontentasbinhex/
---
## XmlReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) method

İçeriği okur ve **BinHex** çözülen ikili baytları döndürür.

```cpp
virtual int32_t System::Xml::XmlReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Sonuç metninin kopyalanacağı tampon. Bu değer **nullptr** olamaz. |
| index | **int32_t** | Tampon içinde sonucun kopyalanmaya başlanacağı ofset. |
| count | **int32_t** | Tampona kopyalanacak en fazla bayt sayısı. Aslında kopyalanan bayt sayısı bu yöntemden döndürülür. |

### Dönüş Değeri

Tampona yazılan bayt sayısı.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [XmlReader](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)