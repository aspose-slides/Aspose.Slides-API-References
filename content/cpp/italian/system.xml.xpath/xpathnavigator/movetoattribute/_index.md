---
title: MoveToAttribute()
second_title: Riferimento API Aspose.Slides per C++
description: Sposta lo XPathNavigator sull'attributo con il nome locale e l'URI dello spazio dei nomi corrispondenti.
type: docs
weight: 495
url: /it/system.xml.xpath/xpathnavigator/movetoattribute/
---
## XPathNavigator::MoveToAttribute(String, String) metodo

Sposta il [XPathNavigator](../) sull'attributo con il nome locale e l'URI dello spazio dei nomi corrispondenti.

```cpp
virtual bool System::Xml::XPath::XPathNavigator::MoveToAttribute(String localName, String namespaceURI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale dell'attributo. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'attributo; **nullptr** per uno spazio dei nomi vuoto. |

### Valore di ritorno

**true** se il [XPathNavigator](../) è stato spostato con successo sull'attributo; altrimenti, **false**. Se **false**, la posizione del [XPathNavigator](../) rimane invariata.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Spazio dei nomi [System::Xml::XPath](../../)
* Libreria [Aspose.Slides](../../../)