---
title: PrependChildElement()
second_title: Riferimento API di Aspose.Slides per C++
description: Crea un nuovo elemento figlio all'inizio dell'elenco dei nodi figlio del nodo corrente utilizzando il prefisso di spazio dei nomi, il nome locale e l'URI di spazio dei nomi specificati con il valore indicato.
type: docs
weight: 989
url: /it/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement(String, String, String, String) metodo

Crea un nuovo elemento figlio all'inizio dell'elenco dei nodi figlio del nodo corrente utilizzando il prefisso di spazio dei nomi, il nome locale e l'URI di spazio dei nomi specificati con il valore indicato.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Il prefisso di spazio dei nomi del nuovo elemento figlio (se presente). |
| localName | [String](../../../system/string/) | Il nome locale del nuovo elemento figlio (se presente). |
| namespaceURI | [String](../../../system/string/) | L'URI di spazio dei nomi del nuovo elemento figlio (se presente). [String::Empty](../../../system/string/empty/) e **nullptr** sono equivalenti. |
| value | [String](../../../system/string/) | Il valore del nuovo elemento figlio. Se [String::Empty](../../../system/string/empty/) o **nullptr** vengono passati, viene creato un elemento vuoto. |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Spazio dei nomi [System::Xml::XPath](../../)
* Libreria [Aspose.Slides](../../../)