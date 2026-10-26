---
title: PrependChild()
second_title: Aspose.Slides for C++ API Referansı
description: Geçerli düğümün alt düğüm listesinin başına yeni bir alt düğüm oluşturmak için kullanılan bir XmlWriter nesnesi döndürür.
type: docs
weight: 872
url: /tr/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() yöntemi

Geçerli düğümün alt düğüm listelerinin başına yeni bir alt düğüm oluşturmak için kullanılan bir [XmlWriter](../../../system.xml/xmlwriter/) nesnesi döndürür.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```

### Dönüş Değeri

Geçerli düğümün alt düğüm listelerinin başına yeni bir alt düğüm oluşturmak için kullanılan bir [XmlWriter](../../../system.xml/xmlwriter/) nesnesi.

## XPathNavigator::PrependChild(String) yöntemi

Belirtilen XML dizesini kullanarak geçerli düğümün alt düğüm listelerinin başına yeni bir alt düğüm oluşturur.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | Yeni alt düğüm için XML veri dizesi. |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) yöntemi

Belirtilen [XmlReader](../../../system.xml/xmlreader/) nesnesinin XML içeriğini kullanarak geçerli düğümün alt düğüm listelerinin başına yeni bir alt düğüm oluşturur.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Yeni alt düğüm için XML verileri üzerinde konumlandırılmış bir [XmlReader](../../../system.xml/xmlreader/) nesnesi. |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) yöntemi

Belirtilen [XPathNavigator](../) nesnesindeki düğümleri kullanarak geçerli düğümün alt düğüm listelerinin başına yeni bir alt düğüm oluşturur.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Yeni alt düğüm olarak eklenecek düğüm üzerine konumlandırılmış bir [XPathNavigator](../) nesnesi. |

## Ayrıca

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlWriter](../../../system.xml/xmlwriter/)
* Sınıf [XPathNavigator](../)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlReader](../../../system.xml/xmlreader/)
* Ad Alanı [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)