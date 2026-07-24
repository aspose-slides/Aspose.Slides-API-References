---
title: AppendChildElement()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen değerle sağlanan ad alan öneki, yerel ad ve ad alan URI'si kullanarak, mevcut düğümün alt düğüm listesinin sonuna yeni bir alt öğe düğümü oluşturur.
type: docs
weight: 1002
url: /tr/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement(String, String, String, String) metodu


Yeni bir alt öğe düğümünü, belirtilen ad alan öneki, yerel adı ve ad alan URI'si ile, mevcut düğümün alt düğüm listesi sonuna ekler.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Yeni alt öğe düğümünün ad alan ön eki (varsa). |
| localName | [String](../../../system/string/) | Yeni alt öğe düğümünün yerel adı (varsa). |
| namespaceURI | [String](../../../system/string/) | Yeni alt öğe düğümünün ad alan URI'si (varsa). [String::Empty](../../../system/string/empty/) ve **nullptr** eşdeğerdir. |
| value | [String](../../../system/string/) | Yeni alt öğe düğümünün değeri. [String::Empty](../../../system/string/empty/) veya **nullptr** geçilirse, boş bir öğe oluşturulur. |

## Diğer Bağlantılar

* Sınıf [String](../../../system/string/)
* Sınıf [XPathNavigator](../)
* İsim Alanı [System::Xml::XPath](../../)
* Kütüphane [Aspose.Slides](../../../)