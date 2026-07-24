---
title: InsertAfter()
second_title: Aspose.Slides için C++ API Referansı
description: Şu anda seçili düğümün ardından yeni bir kardeş düğüm oluşturmak için kullanılan bir XmlWriter nesnesi döndürür.
type: docs
weight: 898
url: /tr/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() metod

Şu anda seçili düğümün ardından yeni bir kardeş düğüm oluşturmak için kullanılan bir [XmlWriter](../../../system.xml/xmlwriter/) nesnesi döndürür.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```

### Dönüş Değeri

Şu anda seçili düğümün ardından yeni bir kardeş düğüm oluşturmak için kullanılan bir [XmlWriter](../../../system.xml/xmlwriter/) nesnesi.

## XPathNavigator::InsertAfter(String) metod

Belirtilen XML dizesini kullanarak şu anda seçili düğümün ardından yeni bir kardeş düğüm oluşturur.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | Yeni kardeş düğüm için XML veri dizesi. |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) metod

Belirtilen [XmlReader](../../../system.xml/xmlreader/) nesnesinin XML içeriğini kullanarak şu anda seçili düğümün ardından yeni bir kardeş düğüm oluşturur.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Yeni kardeş düğümün XML verileri üzerine konumlandırılmış bir [XmlReader](../../../system.xml/xmlreader/) nesnesi. |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) metod

Belirtilen [XPathNavigator](../) nesnesindeki düğümleri kullanarak şu anda seçili düğümün ardından yeni bir kardeş düğüm oluşturur.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Yeni kardeş düğüm olarak eklenecek düğüm üzerinde konumlandırılmış bir [XPathNavigator](../) nesnesi. |

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [XmlWriter](../../../system.xml/xmlwriter/)
* Sınıf [XPathNavigator](../)
* Sınıf [String](../../../system/string/)
* Sınıf [XmlReader](../../../system.xml/xmlreader/)
* Ad alanı [System::Xml::XPath](../../)
* Kütüphane [Aspose.Slides](../../../)