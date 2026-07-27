---
title: PrependChildElement()
second_title: Referência da API Aspose.Slides para C++
description: Cria um novo elemento filho no início da lista de nós filhos do nó atual usando o prefixo de namespace, o nome local e o URI de namespace especificados com o valor especificado.
type: docs
weight: 989
url: /pt/system.xml.xpath/xpathnavigator/prependchildelement/
---
## XPathNavigator::PrependChildElement(String, String, String, String) método


Cria um novo elemento filho no início da lista de nós filhos do nó atual usando o prefixo de namespace, o nome local e o URI de namespace especificados com o valor especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::PrependChildElement(String prefix, String localName, String namespaceURI, String value)
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | O prefixo de namespace do novo elemento filho (se houver). |
| localName | [String](../../../system/string/) | O nome local do novo elemento filho (se houver). |
| namespaceURI | [String](../../../system/string/) | O URI de namespace do novo elemento filho (se houver). [String::Empty](../../../system/string/empty/) e **nullptr** são equivalentes. |
| value | [String](../../../system/string/) | O valor do novo elemento filho. Se [String::Empty](../../../system/string/empty/) ou **nullptr** forem passados, um elemento vazio é criado. |

## Ver Também

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)