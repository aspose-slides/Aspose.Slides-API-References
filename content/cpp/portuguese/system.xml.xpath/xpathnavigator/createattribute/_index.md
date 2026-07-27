---
title: CreateAttribute()
second_title: Referência da API Aspose.Slides para C++
description: Cria um nó de atributo no nó de elemento atual usando o prefixo de namespace, o nome local e o URI de namespace especificados com o valor especificado.
type: docs
weight: 1041
url: /pt/system.xml.xpath/xpathnavigator/createattribute/
---
## XPathNavigator::CreateAttribute(String, String, String, String) método

Cria um nó de atributo no nó de elemento atual usando o prefixo de namespace, o nome local e o URI de namespace especificados, com o valor especificado.

```cpp
virtual void System::Xml::XPath::XPathNavigator::CreateAttribute(String prefix, String localName, String namespaceURI, String value)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | O prefixo de namespace do novo nó de atributo (se houver). |
| localName | [String](../../../system/string/) | O nome local do novo nó de atributo que não pode [String::Empty](../../../system/string/empty/) ou **nullptr**. |
| namespaceURI | [String](../../../system/string/) | O URI de namespace para o novo nó de atributo (se houver). |
| value | [String](../../../system/string/) | O valor do novo nó de atributo. Se [String::Empty](../../../system/string/empty/) ou **nullptr** forem passados, um nó de atributo vazio será criado. |

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XPathNavigator](../)
* Namespace [System::Xml::XPath](../../)
* Biblioteca [Aspose.Slides](../../../)