---
title: AppendChild()
second_title: Aspose.Slides for C++ API Referansı
description: Mevcut düğümün alt düğüm listesinin sonunda bir veya daha fazla yeni alt düğüm oluşturmak için kullanılan bir XmlWriter nesnesini döndürür.
type: docs
weight: 885
url: /tr/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() metodu


Mevcut düğümün alt düğüm listesinin sonunda bir veya daha fazla yeni alt düğüm oluşturmak için kullanılan bir [XmlWriter](../../../system.xml/xmlwriter/) nesnesini döndürür.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```


### Dönüş Değeri

Mevcut düğümün alt düğüm listesinin sonunda yeni alt düğümler oluşturmak için kullanılan bir [XmlWriter](../../../system.xml/xmlwriter/) nesnesi.

## XPathNavigator::AppendChild(String) metodu


Belirtilen XML veri dizesi kullanılarak mevcut düğümün alt düğüm listesinin sonunda yeni bir alt düğüm oluşturur.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | Yeni alt düğüm için XML veri dizesi. |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) metodu


Belirtilen [XmlReader](../../../system.xml/xmlreader/) nesnesinin XML içeriği kullanılarak mevcut düğümün alt düğüm listesinin sonunda yeni bir alt düğüm oluşturur.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Yeni alt düğüm için XML verisine konumlanmış bir [XmlReader](../../../system.xml/xmlreader/) nesnesi. |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) metodu


Belirtilen [XPathNavigator](../) içindeki düğümler kullanılarak mevcut düğümün alt düğüm listesinin sonunda yeni bir alt düğüm oluşturur.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Yeni alt düğüm olarak eklenecek düğüme konumlanmış bir [XPathNavigator](../) nesnesi. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlWriter](../../../system.xml/xmlwriter/)
* Sınıf [XPathNavigator](../)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlReader](../../../system.xml/xmlreader/)
* Ad alanı [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)