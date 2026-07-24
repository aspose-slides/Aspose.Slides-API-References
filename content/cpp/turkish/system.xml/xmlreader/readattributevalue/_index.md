---
title: ReadAttributeValue()
second_title: Aspose.Slides for C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, öznitelik değerini bir veya daha fazla Text, EntityReference veya EndEntity düğümüne ayrıştırır.
type: docs
weight: 677
url: /tr/system.xml/xmlreader/readattributevalue/
---
## XmlReader::ReadAttributeValue() metod

Türetilmiş bir sınıfta geçersiz kılındığında, öznitelik değerini bir veya daha fazla **[Text](../../../system.text/)**, **EntityReference** veya **EndEntity** düğümüne ayrıştırır.

```cpp
virtual bool System::Xml::XmlReader::ReadAttributeValue()=0
```

### Dönüş Değeri

**true** eğer döndürülecek düğümler varsa. **false** eğer okuyucu ilk çağrı yapıldığında bir öznitelik düğümünde konumlanmamışsa veya tüm öznitelik değerleri okunmuşsa. Boş bir öznitelik, örneğin **misc=\"\"**, bir değeri [String::Empty](../../../system/string/empty/) olan tek bir düğümle **true** döndürür.

## Ayrıca Bakınız

* Sınıf [XmlReader](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)