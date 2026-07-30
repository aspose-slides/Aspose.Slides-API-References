---
title: PrependChild()
second_title: Riferimento API Aspose.Slides per C++
description: Restituisce un oggetto XmlWriter utilizzato per creare un nuovo nodo figlio all'inizio dell'elenco dei nodi figlio del nodo corrente.
type: docs
weight: 872
url: /it/system.xml.xpath/xpathnavigator/prependchild/
---
## XPathNavigator::PrependChild() metodo

Restituisce un [XmlWriter](../../../system.xml/xmlwriter/) oggetto utilizzato per creare un nuovo nodo figlio all'inizio dell'elenco dei nodi figlio del nodo corrente.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::PrependChild()
```

### Valore di ritorno

Un [XmlWriter](../../../system.xml/xmlwriter/) oggetto utilizzato per creare un nuovo nodo figlio all'inizio dell'elenco dei nodi figlio del nodo corrente.

## XPathNavigator::PrependChild(String) metodo

Crea un nuovo nodo figlio all'inizio dell'elenco dei nodi figlio del nodo corrente utilizzando la stringa XML specificata.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(String newChild)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | La stringa dei dati XML per il nuovo nodo figlio. |

## XPathNavigator::PrependChild(SharedPtr\<XmlReader\>) metodo

Crea un nuovo nodo figlio all'inizio dell'elenco dei nodi figlio del nodo corrente utilizzando il contenuto XML dell'oggetto [XmlReader](../../../system.xml/xmlreader/) specificato.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XmlReader> newChild)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Un oggetto [XmlReader](../../../system.xml/xmlreader/) posizionato sui dati XML per il nuovo nodo figlio. |

## XPathNavigator::PrependChild(SharedPtr\<XPathNavigator\>) metodo

Crea un nuovo nodo figlio all'inizio dell'elenco dei nodi figlio del nodo corrente utilizzando i nodi nell'oggetto [XPathNavigator](../) specificato.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChild(SharedPtr<XPathNavigator> newChild)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Un oggetto [XPathNavigator](../) posizionato sul nodo da aggiungere come nuovo nodo figlio. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlWriter](../../../system.xml/xmlwriter/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Namespace [System::Xml::XPath](../../)
* Library [Aspose.Slides](../../../)