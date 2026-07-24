---
title: CreateAttribute()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen değerle birlikte belirtilen ad alanı öneki, yerel ad ve ad alanı URI'si kullanılarak mevcut eleman düğümünde bir öznitelik düğümü oluşturur.
type: docs
weight: 1041
url: /tr/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) metot

Mevcut eleman düğümünde, belirtilen ad alanı öneki, yerel ad ve ad alanı URI'si ile verilen değeri kullanarak bir öznitelik düğümü oluşturur.

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Yeni öznitelik düğümünün ad alanı öneki (varsa). |
| localName | [String](../../../system/string/) | Yeni öznitelik düğümünün yerel adı, [String::Empty](../../../system/string/empty/) veya **nullptr** olamaz. |
| namespaceURI | [String](../../../system/string/) | Yeni öznitelik düğümünün ad alanı URI'si (varsa). |
| value | [String](../../../system/string/) | Yeni öznitelik düğümünün değeri. [String::Empty](../../../system/string/empty/) veya **nullptr** geçirilirse, boş bir öznitelik düğümü oluşturulur. |

## İlgili

* Sınıf [String](../../../system/string/)
* Sınıf [XPathNavigator](../)
* Ad alanı [System::Xml::XPath](../../)
* Kütüphane [Aspose.Slides](../../../)