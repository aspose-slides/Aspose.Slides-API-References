---
title: ReadContentAsBinHex()
second_title: Aspose.Slides için C++ API Referansı
description: İçeriği okur ve BinHex kodu çözülmüş ikili baytları döndürür.
type: docs
weight: 664
url: /tr/system.xml/xmltextreader/readcontentasbinhex/
---
## XmlTextReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metot


İçeriği okur ve **BinHex** kodu çözülmüş ikili baytları döndürür.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Sonuç metnin kopyalanacağı tampon. Bu değer **nullptr** olamaz. |
| index | **int32_t** | Sonucun kopyalanmaya başlanacağı tampondaki ofset. |
| count | **int32_t** | Tampona kopyalanacak en fazla bayt sayısı. Gerçek kopyalanan bayt sayısı bu metottan döndürülür. |

### Dönüş Değeri

Tampona yazılan bayt sayısı.

## İlgili

* Tip Tanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [XmlTextReader](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)