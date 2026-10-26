---
title: MoveToChild()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen yerel ad ve ad alanı URI'sine sahip alt düğüme XPathNavigator'ı taşır.
type: docs
weight: 690
url: /tr/system.xml.xpath/xpathnavigator/movetochild/
---
## XPathNavigator::MoveToChild(String, String) metodu

Belirtilen yerel ad ve ad alanı URI'sine sahip alt düğüme [XPathNavigator](../)'ı taşır.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(String localName, String namespaceURI)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Taşınacak alt düğümün yerel adı. |
| namespaceURI | [String](../../../system/string/) | Taşınacak alt düğümün ad alanı URI'si. |

### Dönüş Değeri

**true** eğer [XPathNavigator](../) alt düğüme başarılı bir şekilde hareket ederse; aksi takdirde **false**. **false** ise [XPathNavigator](../)'in konumu değişmez.

## XPathNavigator::MoveToChild(XPathNodeType) metodu

Belirtilen XPathNodeType'ın alt düğümüne [XPathNavigator](../)'ı taşır.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToChild(XPathNodeType type)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| type | [XPathNodeType](../../xpathnodetype/) | Taşınacak alt düğümün XPathNodeType'ı. |

### Dönüş Değeri

**true** eğer [XPathNavigator](../) alt düğüme başarılı bir şekilde hareket ederse; aksi takdirde **false**. **false** ise [XPathNavigator](../)'in konumu değişmez.

## Ayrıca Bakınız

* Enum [XPathNodeType](../../xpathnodetype/)
* Sınıf [String](../../../system/string/)
* Sınıf [XPathNavigator](../)
* Ad alanı [System::Xml::XPath](../../)
* Kütüphane [Aspose.Slides](../../../)