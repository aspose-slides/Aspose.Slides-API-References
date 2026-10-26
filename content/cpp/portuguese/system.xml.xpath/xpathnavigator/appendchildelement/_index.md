---
title: AppendChildElement()
second_title: Referência da API Aspose.Slides for C++
description: Cria um novo nó de elemento filho ao final da lista de nós filhos do nó atual usando o prefixo de namespace, o nome local e o URI de namespace especificados com o valor indicado.
type: docs
weight: 1002
url: /pt/system.xml.xpath/xpathnavigator/appendchildelement/
---
## XPathNavigator::AppendChildElement(String, String, String, String) método

Cria um novo nó de elemento filho no final da lista de nós filhos do nó atual usando o prefixo de namespace, o nome local e o URI de namespace especificados com o valor indicado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::AppendChildElement(String prefix, String localName, String namespaceURI, String value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | O prefixo de namespace do novo nó de elemento filho (se houver). |
| localName | [String](../../../system/string/) | O nome local do novo nó de elemento filho (se houver). |
| namespaceURI | [String](../../../system/string/) | O URI de namespace do novo nó de elemento filho (se houver). [String::Empty](../../../system/string/empty/) e **nullptr** são equivalentes. |
| value | [String](../../../system/string/) | O valor do novo nó de elemento filho. Se [String::Empty](../../../system/string/empty/) ou **nullptr** forem passados, um elemento vazio é criado. |

## Ver também

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)