---
title: LookupNamespace()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen önek için ad alanı URI'sını döndürür.
type: docs
weight: 404
url: /tr/system.xml.xpath/xpathnavigator/lookupnamespace/
---
## XPathNavigator::LookupNamespace(const String\&) metodu


Belirtilen önek için ad alanı URI'sını döndürür.

```cpp
String System::Xml::XPath::XPathNavigator::LookupNamespace(const String &prefix) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | Çözümlemek istediğiniz ad alanı URI'sına sahip önek. Varsayılan ad alanıyla eşleşmek için [String::Empty](../../../system/string/empty/) geçirin. |

### Dönüş Değeri

Belirtilen ad alanı önekine atanmış ad alanı URI'sını içeren bir [String](../../../system/string/); belirtilen önek için bir ad alanı URI'sı atanmadıysa **nullptr**. Döndürülen [String](../../../system/string/) atomik hâle getirilmiştir.

## Ayrıca Bakınız

* Sınıf [String](../../../system/string/)
* Sınıf [XPathNavigator](../)
* Ad Alanı [System::Xml::XPath](../../)
* Kütüphane [Aspose.Slides](../../../)