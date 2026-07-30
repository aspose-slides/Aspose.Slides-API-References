---
title: AppendChild()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un oggetto XmlWriter utilizzato per creare uno o più nuovi nodi figlio alla fine dell'elenco dei nodi figlio del nodo corrente.
type: docs
weight: 885
url: /it/system.xml.xpath/xpathnavigator/appendchild/
---
## XPathNavigator::AppendChild() metodo

Restituisce un oggetto [XmlWriter](../../../system.xml/xmlwriter/) utilizzato per creare uno o più nuovi nodi figlio alla fine dell'elenco dei nodi figlio del nodo corrente.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::AppendChild()
```

### Valore restituito

Un oggetto [XmlWriter](../../../system.xml/xmlwriter/) utilizzato per creare nuovi nodi figlio alla fine dell'elenco dei nodi figlio del nodo corrente.

## XPathNavigator::AppendChild(String) metodo

Crea un nuovo nodo figlio alla fine dell'elenco dei nodi figlio del nodo corrente utilizzando la stringa di dati XML specificata.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(String newChild)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newChild | [String](../../../system/string/) | La stringa di dati XML per il nuovo nodo figlio. |

## XPathNavigator::AppendChild(SharedPtr\<XmlReader\>) metodo

Crea un nuovo nodo figlio alla fine dell'elenco dei nodi figlio del nodo corrente utilizzando il contenuto XML dell'oggetto [XmlReader](../../../system.xml/xmlreader/) specificato.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XmlReader> newChild)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newChild | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Un oggetto [XmlReader](../../../system.xml/xmlreader/) posizionato sui dati XML per il nuovo nodo figlio. |

## XPathNavigator::AppendChild(SharedPtr\<XPathNavigator\>) metodo

Crea un nuovo nodo figlio alla fine dell'elenco dei nodi figlio del nodo corrente utilizzando i nodi nel [XPathNavigator](../) specificato.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChild(SharedPtr<XPathNavigator> newChild)
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
* Libreria [Aspose.Slides](../../../)