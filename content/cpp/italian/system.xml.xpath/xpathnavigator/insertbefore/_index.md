---
title: InsertBefore()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce un oggetto XmlWriter utilizzato per creare un nuovo nodo fratello prima del nodo attualmente selezionato.
type: docs
weight: 911
url: /it/system.xml.xpath/xpathnavigator/insertbefore/
---
## XPathNavigator::InsertBefore() metodo


Restituisce un oggetto [XmlWriter](../../../system.xml/xmlwriter/) utilizzato per creare un nuovo nodo fratello prima del nodo attualmente selezionato.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertBefore()
```


### Valore restituito

Un oggetto [XmlWriter](../../../system.xml/xmlwriter/) utilizzato per creare un nuovo nodo fratello prima del nodo attualmente selezionato.

## XPathNavigator::InsertBefore(String) metodo


Crea un nuovo nodo fratello prima del nodo attualmente selezionato utilizzando la stringa XML specificata.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(String newSibling)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | La stringa di dati XML per il nuovo nodo fratello. |

## XPathNavigator::InsertBefore(SharedPtr\<XmlReader\>) metodo


Crea un nuovo nodo fratello prima del nodo attualmente selezionato utilizzando il contenuto XML dell'oggetto [XmlReader](../../../system.xml/xmlreader/) specificato.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XmlReader> newSibling)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Un oggetto [XmlReader](../../../system.xml/xmlreader/) posizionato sui dati XML per il nuovo nodo fratello. |

## XPathNavigator::InsertBefore(SharedPtr\<XPathNavigator\>) metodo


Crea un nuovo nodo fratello prima del nodo attualmente selezionato utilizzando i nodi nel [XPathNavigator](../) specificato.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertBefore(SharedPtr<XPathNavigator> newSibling)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Un oggetto [XPathNavigator](../) posizionato sul nodo da aggiungere come nuovo nodo fratello. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [XmlWriter](../../../system.xml/xmlwriter/)
* Class [XPathNavigator](../)
* Class [String](../../../system/string/)
* Class [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)