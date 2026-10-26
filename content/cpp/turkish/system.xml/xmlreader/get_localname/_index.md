---
title: get_LocalName()
second_title: Aspose.Slides için C++ API Referansı
description: Türetilmiş bir sınıfta geçersiz kılındığında, geçerli düğümün yerel adını alır.
type: docs
weight: 40
url: /tr/system.xml/xmlreader/get_localname/
---
## XmlReader::get_LocalName() metodu


Türetilmiş bir sınıfta geçersiz kılındığında, geçerli düğümün yerel adını alır.

```cpp
virtual String System::Xml::XmlReader::get_LocalName()=0
```


### Dönüş Değeri

Önek kaldırılmış geçerli düğümün adıdır. Örneğin, **LocalName** **book** için **<bk:book>** öğesi vardır. Adı olmayan düğüm türleri için (örneğin **[Text](../../../system.text/)**, **Comment** ve benzeri), bu metod [String::Empty](../../../system/string/empty/) döndürür.

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XmlReader](../)
* Ad Alanı [System::Xml](../../)
* Kütüphane [Aspose.Slides](../../../)