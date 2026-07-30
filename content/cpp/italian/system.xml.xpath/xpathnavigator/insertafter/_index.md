---
title: InsertAfter()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce un oggetto XmlWriter usato per creare un nuovo nodo fratello dopo il nodo attualmente selezionato.
type: docs
weight: 898
url: /it/system.xml.xpath/xpathnavigator/insertafter/
---
## XPathNavigator::InsertAfter() metodo

Restituisce un [XmlWriter](../../../system.xml/xmlwriter/) oggetto usato per creare un nuovo nodo fratello dopo il nodo attualmente selezionato.

```cpp
virtual SharedPtr<XmlWriter> System::Xml::XPath::XPathNavigator::InsertAfter()
```

### Valore di ritorno

Un [XmlWriter](../../../system.xml/xmlwriter/) oggetto usato per creare un nuovo nodo fratello dopo il nodo attualmente selezionato.

## XPathNavigator::InsertAfter(String) metodo

Crea un nuovo nodo fratello dopo il nodo attualmente selezionato usando la stringa XML specificata.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(String newSibling)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newSibling | [String](../../../system/string/) | La stringa dei dati XML per il nuovo nodo fratello. |

## XPathNavigator::InsertAfter(SharedPtr\<XmlReader\>) metodo

Crea un nuovo nodo fratello dopo il nodo attualmente selezionato usando il contenuto XML dell'oggetto [XmlReader](../../../system.xml/xmlreader/) specificato.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XmlReader> newSibling)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XmlReader](../../../system.xml/xmlreader/)\> | Un oggetto [XmlReader](../../../system.xml/xmlreader/) posizionato sui dati XML per il nuovo nodo fratello. |

## XPathNavigator::InsertAfter(SharedPtr\<XPathNavigator\>) metodo

Crea un nuovo nodo fratello dopo il nodo attualmente selezionato usando i nodi nell'oggetto [XPathNavigator](../) specificato.

```cpp
virtual void System::Xml::XPath::XPathNavigator::InsertAfter(SharedPtr<XPathNavigator> newSibling)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| newSibling | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Un oggetto [XPathNavigator](../) posizionato sul nodo da aggiungere come nuovo nodo fratello. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlWriter](../../../system.xml/xmlwriter/)
* Classe [XPathNavigator](../)
* Classe [String](../../../system/string/)
* Classe [XmlReader](../../../system.xml/xmlreader/)
* Spazio dei nomi [System::Xml::XPath](../../)
* Libreria [Aspose.Slides](../../../)