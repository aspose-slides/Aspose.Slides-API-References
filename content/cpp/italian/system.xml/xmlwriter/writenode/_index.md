---
title: WriteNode()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, copia tutto dal lettore allo scrittore e sposta il lettore all'inizio del fratello successivo.
type: docs
weight: 430
url: /it/system.xml/xmlwriter/writenode/
---
## XmlWriter::WriteNode(SharedPtr\<XmlReader\>, bool) metodo


When overridden in a derived class, copies everything from the reader to the writer and moves the reader to the start of the next sibling.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XmlReader> reader, bool defattr)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| reader | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../xmlreader/)\> | Il [XmlReader](../../xmlreader/) da cui leggere. |
| defattr | **bool** | **true** per copiare gli attributi predefiniti dal [XmlReader](../../xmlreader/); altrimenti, **false**. |

## XmlWriter::WriteNode(SharedPtr\<XPath::XPathNavigator\>, bool) metodo


Copia tutto dall'oggetto XPathNavigator allo scrittore. La posizione di XPathNavigator rimane invariata.

```cpp
virtual void System::Xml::XmlWriter::WriteNode(SharedPtr<XPath::XPathNavigator> navigator, bool defattr)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| navigator | [SharedPtr](../../../system/sharedptr/)\<[XPath::XPathNavigator](../../../system.xml.xpath/xpathnavigator/)\> | Il XPathNavigator da cui copiare. |
| defattr | **bool** | **true** per copiare gli attributi predefiniti; altrimenti, **false**. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlReader](../../xmlreader/)
* Classe [XmlWriter](../)
* Classe [XPathNavigator](../../../system.xml.xpath/xpathnavigator/)
* Spazio dei nomi [System::Xml](../../)
* Library [Aspose.Slides](../../../)