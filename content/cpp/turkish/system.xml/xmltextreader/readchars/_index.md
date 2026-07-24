---
title: ReadChars()
second_title: Aspose.Slides for C++ API Referansı
description: Bir öğenin metin içeriğini bir karakter tamponuna okur. Bu metod, gömülü metnin büyük akışlarını art arda çağırarak okumak için tasarlanmıştır.
type: docs
weight: 755
url: /tr/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) metod

Bir öğenin metin içeriğini bir karakter tamponuna okur. Bu metod, gömülü metnin büyük akışlarını art arda çağırarak okumak için tasarlanmıştır.

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | Metin içeriğinin yazıldığı tampon görevini gören karakter dizisi. |
| index | **int32_t** | **buffer** içindeki metin içeriğinin yazılmaya başlanacağı konum. |
| count | **int32_t** | **buffer** içine yazılacak karakter sayısı. |

### Dönüş Değeri

Okunan karakter sayısı. Okuyucu bir öğe üzerinde konumlandırılmamışsa veya mevcut bağlamda geri verilecek daha fazla metin içeriği kalmamışsa bu değer 0 olabilir.

## Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [XmlTextReader](../)
* İsim alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)