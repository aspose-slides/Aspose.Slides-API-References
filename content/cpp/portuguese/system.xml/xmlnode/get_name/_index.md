---
title: get_Name()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o nome qualificado do nó, quando sobrescrito em uma classe derivada.
type: docs
weight: 1
url: /pt/system.xml/xmlnode/get_name/
---
## XmlNode::get_Name() método

Retorna o nome qualificado do nó, quando sobrescrito em uma classe derivada.

```cpp
virtual String System::Xml::XmlNode::get_Name()=0
```

### Valor de Retorno

O nome qualificado do nó.

## Observações

O nome retornado depende do [XmlNode::get_NodeType](../get_nodetype/) do nó: 

| Tipo | Nome |
| --- | --- |
| [Attribute](../../../system/attribute/)| O nome qualificado do atributo. |
| CDATA | #cdata-section |
| Comment | #comment |
| Document | #document |
| DocumentFragment | #document-fragment |
| DocumentType | O nome do tipo de documento. |
| Element | O nome qualificado do elemento. |
| Entity | O nome da entidade. |
| EntityReference | O nome da entidade referenciada. |
| Notation | O nome da notação. |
| ProcessingInstruction | O alvo da instrução de processamento. |
| [Text](../../../system.text/)| #text |
| Whitespace | #whitespace |
| SignificantWhitespace | #significant-whitespace |
| [XmlDeclaration](../../xmldeclaration/)| #xml-declaration |

## Ver Também

* Classe [String](../../../system/string/)
* Classe [XmlNode](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)