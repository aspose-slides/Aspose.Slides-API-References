---
title: InsertBefore()
second_title: Aspose.Slides için C++ API Referansı
description: Şu anda seçili düğümün önünde yeni bir kardeş düğüm oluşturmak için kullanılan bir XmlWriter nesnesi döndürür.
type: docs
weight: 911
url: /tr/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() metod

Şu anda seçili düğümün önünde yeni bir kardeş düğüm oluşturmak için kullanılan bir [XmlWriter](../../../system.xml/xmlwriter/) nesnesi döndürür.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```

### Dönüş Değeri

Şu anda seçili düğümün önünde yeni bir kardeş düğüm oluşturmak için kullanılan bir [XmlWriter](../../../system.xml/xmlwriter/) nesnesi döndürür.

## XPathNavigator::InsertBefore(String) metod

Belirtilen XML dizesini kullanarak şu anda seçili düğümün önünde yeni bir kardeş düğüm oluşturur.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | Yeni kardeş düğüm için XML veri dizesi. |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) metod

Belirtilen [XmlReader](../../../system.xml/xmlreader/) nesnesinin XML içeriğini kullanarak şu anda seçili düğümün önünde yeni bir kardeş düğüm oluşturur.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Yeni kardeş düğüm için XML verisine konumlandırılmış bir [XmlReader](../../../system.xml/xmlreader/) nesnesi. |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) metod

Belirtilen [XPathNavigator](../) içindeki düğümleri kullanarak şu anda seçili düğümün önünde yeni bir kardeş düğüm oluşturur.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Yeni kardeş düğüm olarak eklenecek düğüme konumlandırılmış bir [XPathNavigator](../) nesnesi. |

## Diğer Bilgiler

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlWriter](../../../system.xml/xmlwriter/)
* Sınıf [XPathNavigator](../)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlReader](../../../system.xml/xmlreader/)
* AdAlanı [System::Xml::XPath](../../)
* Kütüphane [Aspose.Slides](../../../)