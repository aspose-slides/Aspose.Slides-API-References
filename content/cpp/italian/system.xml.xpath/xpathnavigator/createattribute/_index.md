---
title: CreateAttribute()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nodo attributo sul nodo elemento corrente utilizzando il prefisso di spazio dei nomi, il nome locale e l'URI di spazio dei nomi specificati con il valore specificato.
type: docs
weight: 1041
url: /it/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) metodo

Crea un nodo attributo sul nodo elemento corrente utilizzando il prefisso di spazio dei nomi, il nome locale e l'URI dello spazio dei nomi specificati con il valore specificato.

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Il prefisso di spazio dei nomi del nuovo nodo attributo (se presente). |
| localName | [String](../../../system/string/) | Il nome locale del nuovo nodo attributo che non può [String::Empty](../../../system/string/empty/) o **nullptr**. |
| namespaceURI | [String](../../../system/string/) | L'URI di spazio dei nomi per il nuovo nodo attributo (se presente). |
| value | [String](../../../system/string/) | Il valore del nuovo nodo attributo. Se [String::Empty](../../../system/string/empty/) o **nullptr** vengono passati, viene creato un nodo attributo vuoto. |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Spazio dei nomi [System::Xml::XPath](../../)
* Libreria [Aspose.Slides](../../../)