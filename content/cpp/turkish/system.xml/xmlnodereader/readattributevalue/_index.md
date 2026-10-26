---
title: ReadAttributeValue()
second_title: Aspose.Slides C++ için API Referansı
description: Öznitelik değerini bir veya daha fazla Text, EntityReference veya EndEntity düğümüne ayrıştırır.
type: docs
weight: 430
url: /tr/system.xml/xmlnodereader/readattributevalue/
---
## XmlNodeReader::ReadAttributeValue() yöntemi


Öznitelik değerini bir veya daha fazla **[Text](../../../system.text/)**, **EntityReference** veya **EndEntity** düğümüne ayrıştırır.

```cpp
bool System::Xml::XmlNodeReader::ReadAttributeValue() override
```


### Dönüş Değeri

**true** eğer döndürülecek düğümler varsa. **false** eğer okuyucu ilk çağrı yapıldığında bir öznitelik düğümünde konumlandırılmamışsa veya tüm öznitelik değerleri okunmuşsa. **misc=\"\"** gibi boş bir öznitelik, **true** döndürür ve değeri [String::Empty](../../../system/string/empty/) olan tek bir düğümle.

## İlgili

* Sınıf [XmlNodeReader](../)
* Ad alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)