---
title: AddNamespace()
second_title: Referência da API Aspose.Slides para C++
description: Adiciona o namespace fornecido à coleção.
type: docs
weight: 66
url: /pt/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) método

Adiciona o namespace fornecido à coleção.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | O prefixo a ser associado ao namespace que está sendo adicionado. Use [String::Empty](../../../system/string/empty/) para adicionar um namespace padrão. Se o [XmlNamespaceManager](../) for usado para resolver namespaces em uma expressão XML Path Language ([XPath](../../../system.xml.xpath/)), um prefixo deve ser especificado. Se uma expressão [XPath](../../../system.xml.xpath/) não incluir um prefixo, presume-se que o Identificador Uniforme de Recurso (URI) do namespace seja o namespace vazio. Para obter mais informações sobre expressões [XPath](../../../system.xml.xpath/) e [XmlNamespaceManager](../), consulte os métodos XmlNode::SelectNodes(String) e XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>) métodos. |
| uri | [String](../../../system/string/) | O namespace a ser adicionado. |

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlNamespaceManager](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)