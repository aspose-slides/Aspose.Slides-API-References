---
title: WriteNode()
second_title: Référence de l'API Aspose.Slides pour C++
description: Lorsqu'elle est remplacée dans une classe dérivée, copie tout du lecteur vers l'écrivain et déplace le lecteur au début du frère suivant.
type: docs
weight: 430
url: /fr/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) méthode


Lorsqu’elle est remplacée dans une classe dérivée, copie tout du reader vers le writer et déplace le reader au début du prochain sibling.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Le [XmlReader](../../xmlreader/) à lire. |
| defattr | **bool** | **true** pour copier les attributs par défaut depuis le [XmlReader](../../xmlreader/) ; sinon, **false**. |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) méthode


Copie tout depuis l'objet XPathNavigator vers le writer. La position du XPathNavigator reste inchangée.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```


### Paramètres

| Paramètre | Type | Description |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Le XPathNavigator à copier. |
| defattr | **bool** | **true** pour copier les attributs par défaut ; sinon, **false**. |

## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlReader](../../xmlreader/)
* Class [XmlWriter](../)
* Class [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Namespace [System::Xml](../../)
* Library [Aspose.Slides](../../../)