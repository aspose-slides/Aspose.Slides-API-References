---
title: MoveTo()
second_title: Riferimento API di Aspose.Slides per C++
description: Quando sovrascritto in una classe derivata, sposta l'XPathNavigator nella stessa posizione del XPathNavigator specificato.
type: docs
weight: 664
url: /it/system.xml.xpath/xpathnavigator/moveto/
---
## XPathNavigator::MoveTo(SharedPtr\<XPathNavigator\>) metodo


Quando sovrascritto in una classe derivata, sposta il [XPathNavigator](../) nella stessa posizione del [XPathNavigator](../) specificato.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveTo(SharedPtr<XPathNavigator> other)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| other | [SharedPtr](../../../system/sharedptr/)\<[XPathNavigator](../)\> | Il [XPathNavigator](../) posizionato sul nodo a cui si desidera spostarsi. |

### Valore di ritorno

**true** se il [XPathNavigator](../) riesce a spostarsi nella stessa posizione del [XPathNavigator](../) specificato; altrimenti, **false**. Se **false**, la posizione del [XPathNavigator](../) rimane invariata.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XPathNavigator](../)
* Spazio dei nomi [System::Xml::XPath](../../)
* Libreria [Aspose.Slides](../../../)