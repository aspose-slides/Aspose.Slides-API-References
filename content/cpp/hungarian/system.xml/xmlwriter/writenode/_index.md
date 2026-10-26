---
title: WriteNode()
second_title: Aspose.Slides C++ API Referencia
description: Ha egy leszármazott osztályban felülírják, mindent átmásol a olvasóból az íróba, és az olvasót a következő testvér elejére helyezi.
type: docs
weight: 430
url: /hu/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) metódus


Ha egy leszármazott osztályban felülírják, akkor mindent átmásol a olvasóból az íróba, és az olvasót a következő testvér elejére helyezi.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | A [XmlReader](../../xmlreader/), amelyből olvas. |
| defattr | **bool** | **true** az alapértelmezett attribútumok másolásához a [XmlReader](../../xmlreader/)-ből; egyébként **false**. |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) metódus


Mindet átmásol az XPathNavigator objektumból az íróba. Az XPathNavigator pozíciója változatlan marad.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Az XPathNavigator, amelyből másolni kell. |
| defattr | **bool** | **true** az alapértelmezett attribútumok másolásához; egyébként **false**. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [XmlReader](../../xmlreader/)
* Osztály [XmlWriter](../)
* Osztály [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Névtér [System::Xml](../../)
* Könyvtár [Aspose.Slides](../../../)