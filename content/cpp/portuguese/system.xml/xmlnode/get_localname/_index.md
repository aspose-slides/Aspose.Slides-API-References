---
title: get_LocalName()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o nome local do nó, quando sobrescrito em uma classe derivada.
type: docs
weight: 209
url: /pt/system.xml/xmlnode/get_localname/
---
## XmlNode::get_LocalName() método

Retorna o nome local do nó, quando sobrescrito em uma classe derivada.

```cpp
virtual String System::Xml::XmlNode::get_LocalName()=0
```

### Valor de Retorno

O nome do nó com o prefixo removido. Por exemplo, **LocalName** é **book** para o elemento **<bk:book>**.

## Observações

O nome retornado depende do [XmlNode::get_NodeType](../get_nodetype/) do nó:

| Tipo | Nome |
| --- | --- |
| [Attribute](../../../system/attribute/)| O nome local do atributo. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | O nome do tipo de documento. |
| Element | O nome local do elemento. |
| Entity | O nome da entidade. |
| EntityReference | O nome da entidade referenciada. |
| Notation | O nome da notação. |
| ProcessingInstruction | O alvo da instrução de processamento. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |

## Ver também

* Classe [String](../../../system/string/)
* Classe [XmlNode](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)