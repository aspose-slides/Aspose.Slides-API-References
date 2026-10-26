---
title: ReadElementContentAsBinHex()
second_title: Aspose.Slides for C++ API Referansı
description: Elemanı okur ve BinHex içeriğini çözer.
type: docs
weight: 794
url: /tr/system.xml/xmlreader/readelementcontentasbinhex/
---
## XmlReader::ReadElementContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) metodu


Elemanı okur ve **BinHex** içeriğini çözer.

```cpp
virtual int32_t System::Xml::XmlReader::ReadElementContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Sonuç metni kopyalanacak tampon. Bu değer **nullptr** olamaz. |
| index | **int32_t** | Sonucun kopyalanmaya başlanacağı tampon içindeki kaydırma. |
| count | **int32_t** | Tampona kopyalanacak maksimum bayt sayısı. Gerçek kopyalanan bayt sayısı bu metoddan döndürülür. |

### Döndürme Değeri

Tampona yazılan bayt sayısı.

## Bkz

* TipTanımı [ArrayPtr](../../../system/arrayptr/)
* Sınıf [XmlReader](../)
* AdAlanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)