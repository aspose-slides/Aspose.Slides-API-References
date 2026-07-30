---
title: GetAttribute()
second_title: Riferimento API di Aspose.Slides per C++
description: Restituisce il valore dell'attributo con il nome locale e l'URI dello spazio dei nomi specificati.
type: docs
weight: 482
url: /it/system.xml.xpath/xpathnavigator/getattribute/
---
## XPathNavigator::GetAttribute(String, String) metodo

Restituisce il valore dell'attributo con il nome locale e l'URI dello spazio dei nomi specificati.

```cpp
virtual String System::Xml::XPath::XPathNavigator::GetAttribute(String localName, String namespaceURI)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| localName | [String](../../../system/string/) | Il nome locale dell'attributo. **localName** è sensibile al maiuscole/minuscole. |
| namespaceURI | [String](../../../system/string/) | L'URI dello spazio dei nomi dell'attributo. |

### Valore di ritorno

Un [String](../../../system/string/) che contiene il valore dell'attributo specificato; [String::Empty](../../../system/string/empty/) se non viene trovato un attributo corrispondente, o se il [XPathNavigator](../) non è posizionato su un nodo elemento.

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Spazio dei nomi [System::Xml::XPath](../../)
* Libreria [Aspose.Slides](../../../)