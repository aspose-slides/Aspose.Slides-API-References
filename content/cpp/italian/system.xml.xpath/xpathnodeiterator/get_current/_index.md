---
title: get_Current()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, ottiene l'oggetto XPathNavigator per questo XPathNodeIterator, posizionato sul nodo di contesto corrente.
type: docs
weight: 1
url: /it/system.xml.xpath/xpathnodeiterator/get_current/
---
## XPathNodeIterator::get_Current() metodo

When overridden in a derived class, gets the [XPathNavigator](../../xpathnavigator/) object for this [XPathNodeIterator](../), positioned on the current context node.

```cpp
virtual const SharedPtr<XPathNavigator> & System::Xml::XPath::XPathNodeIterator::get_Current()=0
```

### Valore di ritorno

An [XPathNavigator](../../xpathnavigator/) object positioned on the context node from which the node set was selected. The [XPathNodeIterator::MoveNext](../movenext/) method must be called to move the [XPathNodeIterator](../) to the first node in the selected set.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathNavigator](../../xpathnavigator/)
* Classe [XPathNodeIterator](../)
* Namespace [System::Xml::XPath](../../)
* Libreria [Aspose.Slides](../../../)