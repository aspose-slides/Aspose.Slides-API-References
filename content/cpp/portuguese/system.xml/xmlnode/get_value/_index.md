---
title: get_Value()
second_title: Referência da API Aspose.Slides for C++
description: Retorna o valor do nó.
type: docs
weight: 14
url: /pt/system.xml/xmlnode/get_value/
---
## XmlNode::get_Value() método

Retorna o valor do nó.

```cpp
virtual String System::Xml::XmlNode::get_Value()
```

### Valor retornado

O valor retornado depende do [XmlNode::get_NodeType](../get_nodetype/) do nó: 

| Tipo | Valor |
| --- | --- |
| [Attribute](../../../system/attribute/)| O valor do atributo. |
| CDATASection | O conteúdo da seção CDATA. |
| Comment | O conteúdo do comentário. |
| Document | `nullptr`. |
| DocumentFragment | `nullptr`. |
| DocumentType | `nullptr`. |
| Element | `nullptr`. Você pode usar XmlElement::InnerText ou valores [XmlElement::get_InnerXml](../../xmlelement/get_innerxml/) para acessar o valor do nó de elemento. |
| Entity | `nullptr`. |
| EntityReference | `nullptr`. |
| Notation | `nullptr`. |
| ProcessingInstruction | Todo o conteúdo excluindo o alvo. |
| [Text](../../../system.text/)| O conteúdo do nó de texto. |
| SignificantWhitespace | Os caracteres de espaço em branco. O espaço em branco pode consistir de um ou mais caracteres de espaço, retornos de carro, quebras de linha ou tabulações. |
| Whitespace | Os caracteres de espaço em branco. O espaço em branco pode consistir de um ou mais caracteres de espaço, retornos de carro, quebras de linha ou tabulações. |
| [XmlDeclaration](../../xmldeclaration/)| O conteúdo da declaração (isto é, tudo entre `<?xml e ?>`). |

## Ver também

* Classe [String](../../../system/string/)
* Classe [XmlNode](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)