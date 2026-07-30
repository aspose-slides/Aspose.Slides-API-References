---
title: AppendChildElement()
second_title: Aspose.Slides per C++ API Reference
description: Crea un nuovo nodo elemento figlio alla fine dell'elenco dei nodi figlio del nodo corrente usando il prefisso di namespace, il nome locale e l'URI di namespace specificati con il valore specificato.
type: docs
weight: 1002
url: /it/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement(String, String, String, String) metodo

Crea un nuovo nodo elemento figlio alla fine dell'elenco dei nodi figlio del nodo corrente utilizzando il prefisso di namespace, il nome locale e l'URI di namespace specificati con il valore indicato.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | Il prefisso di namespace del nuovo nodo elemento figlio (se presente). |
| localName | [String](../../../system/string/) | Il nome locale del nuovo nodo elemento figlio (se presente). |
| namespaceURI | [String](../../../system/string/) | L'URI di namespace del nuovo nodo elemento figlio (se presente). [String::Empty](../../../system/string/empty/) e **nullptr** sono equivalenti. |
| value | [String](../../../system/string/) | Il valore del nuovo nodo elemento figlio. Se [String::Empty](../../../system/string/empty/) o **nullptr** vengono passati, viene creato un elemento vuoto. |

## Vedi anche

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Libreria [Aspose.Slides](../../../)