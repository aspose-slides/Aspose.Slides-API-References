---
title: ReadValueChunk()
second_title: Aspose.Slides for C++ API Referansı
description: XML belgesine gömülü büyük metin akışlarını okur.
type: docs
weight: 807
url: /tr/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) yöntemi


XML belgesine gömülü büyük metin akışlarını okur.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | Metin içeriğinin yazıldığı tampon görevi gören karakter dizisi. Bu değer **nullptr** olamaz. |
| index | **int32_t** | Tampon içinde [XmlReader](../)'nin sonuçları kopyalamaya başlayabileceği ofset. |
| count | **int32_t** | Tampona kopyalanacak en fazla karakter sayısı. Gerçek kopyalanan karakter sayısı bu yöntemden döndürülür. |

### Dönüş Değeri

Tampona okunan karakter sayısı. Daha fazla metin içeriği olmadığında değer **sıfır** döndürülür.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [XmlReader](../)
* Ad alanı [System::Xml](../../)
* Library [Aspose.Slides](../../../)