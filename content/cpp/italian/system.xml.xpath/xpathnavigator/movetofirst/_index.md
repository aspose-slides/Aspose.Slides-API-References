---
title: MoveToFirst()
second_title: Riferimento API di Aspose.Slides per C++
description: Sposta l'XPathNavigator al primo nodo fratello del nodo corrente.
type: docs
weight: 612
url: /it/system.xml.xpath/xpathnavigator/movetofirst/
---
## XPathNavigator::MoveToFirst() metodo


Sposta il [XPathNavigator](../) al primo nodo fratello del nodo corrente.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToFirst()
```


### Valore di ritorno

**true** se il [XPathNavigator](../) riesce a spostarsi al primo nodo fratello del nodo corrente; **false** se non esiste un primo fratello, o se il [XPathNavigator](../) è attualmente posizionato su un nodo attributo. Se il [XPathNavigator](../) è già posizionato sul primo fratello, [XPathNavigator](../) restituirà **true** e non sposterà la sua posizione. Se [XPathNavigator::MoveToFirst](./) restituisce **false** perché non esiste un primo fratello, o se [XPathNavigator](../) è attualmente posizionato su un attributo, la posizione del [XPathNavigator](../) rimane invariata.

## Vedere anche

* Classe [XPathNavigator](../)
* Spazio dei nomi [System::Xml::XPath](../../)
* Libreria [Aspose.Slides](../../../)