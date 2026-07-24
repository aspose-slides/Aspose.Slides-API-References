---
title: PrependChildElement()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen değerle verilen ad alanı ön eki, yerel ad ve ad alanı URI'si kullanılarak, geçerli düğümün çocuk düğüm listesinin başına yeni bir çocuk eleman oluşturur.
type: docs
weight: 989
url: /tr/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement(String, String, String, String) metodu


Yeni bir çocuk elemanı, mevcut düğümün çocuk düğüm listesinin başına ekler; bu işlem, ad alanı ön eki, yerel ad ve belirtilen değerle verilen ad alanı URI'si kullanılarak yapılır.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Yeni çocuk elemanın ad alanı ön eki (varsa). |
| localName | [String](../../../system/string/) | Yeni çocuk elemanın yerel adı (varsa). |
| namespaceURI | [String](../../../system/string/) | Yeni çocuk elemanın ad alanı URI'si (varsa). [String::Empty](../../../system/string/empty/) ve **nullptr** eşdeğerdir. |
| value | [String](../../../system/string/) | Yeni çocuk elemanın değeri. [String::Empty](../../../system/string/empty/) veya **nullptr** geçirilirse, boş bir eleman oluşturulur. |

## Diğer Bağlantılar

* Sınıf [String](../../../system/string/)
* Sınıf [XPathNavigator](../)
* Ad alanı [System::Xml::XPath](../../)
* Kütüphane [Aspose.Slides](../../../)