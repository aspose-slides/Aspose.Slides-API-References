---
title: get_ParentNode()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o pai deste nó (para nós que podem ter pais).
type: docs
weight: 53
url: /pt/system.xml/xmlnode/get_parentnode/
---
## XmlNode::get_ParentNode() método

Retorna o pai deste nó (para nós que podem ter pais).

```cpp
virtual SharedPtr<XmlNode> System::Xml::XmlNode::get_ParentNode() final
```

### Valor de Retorno

O [XmlNode](../) que é o pai do nó atual.

## Observações

Se um nó acabou de ser criado e ainda não foi adicionado à árvore, ou se foi removido da árvore, o pai é **nullptr**. Para todos os outros nós, o valor retornado depende do [XmlNode::get_NodeType](../get_nodetype/) do nó. A tabela a seguir descreve os possíveis valores de retorno para o método **get_NodeType**.

| NodeType | Valor de Retorno de ParentNode |
| --- | --- |
| [Attribute](../../../system/attribute/), Document, DocumentFragment, Entity, Notation | Retorna `nullptr`; esses nós não têm pais. |
| CDATA | Retorna o elemento ou referência de entidade que contém a seção CDATA. |
| Comment | Retorna o elemento, referência de entidade, tipo de documento ou documento que contém o comentário. |
| DocumentType | Retorna o nó do documento. |
| Element | Retorna o nó pai do elemento. Se o elemento for o nó raiz na árvore, o pai é o nó do documento. |
| EntityReference | Retorna o elemento, atributo ou referência de entidade que contém a referência de entidade. |
| ProcessingInstruction | Retorna o documento, elemento, tipo de documento ou referência de entidade que contém a instrução de processamento. |
| [Text](../../../system.text/) | Retorna o elemento pai, atributo ou referência de entidade que contém o nó de texto. |

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [XmlNode](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)