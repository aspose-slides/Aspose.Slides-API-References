---
title: XmlNodeType
second_title: Referência da API Aspose.Slides for C++
description: Especifica o tipo de nó.
type: docs
weight: 833
url: /pt/system.xml/xmlnodetype/
---
## XmlNodeType enum

Especifica o tipo de nó.

```cpp
enum class XmlNodeType
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| None | 0 | Isso é retornado pelo [XmlReader](../xmlreader/) se um método **Read** não foi chamado. |
| Element | 1 | Um elemento (por exemplo, **<item>**). |
| Attribute | 2 | Um atributo (por exemplo, **id='123'**). |
| Text | 3 | O conteúdo de texto de um nó. Um nó [XmlNodeType::Text](./) não pode ter nós filho. Ele pode aparecer como nó filho dos nós [XmlNodeType::Attribute](./), [XmlNodeType::DocumentFragment](./), [XmlNodeType::Element](./) e [XmlNodeType::EntityReference](./). |
| CDATA | 4 | Uma seção CDATA (por exemplo, **my escaped text**). |
| EntityReference | 5 | Uma referência a uma entidade (por exemplo, **&num;**). |
| Entity | 6 | Uma declaração de entidade (por exemplo, **<!ENTITY...>**). |
| ProcessingInstruction | 7 | Uma instrução de processamento (por exemplo, **<?pi test?>**). |
| Comment | 8 | Um comentário (por exemplo, ****). |
| Document | 9 | Um objeto documento que, como a raiz da árvore do documento, fornece acesso a todo o documento XML. |
| DocumentType | 10 | A declaração de tipo de documento, indicada pela seguinte tag (por exemplo, **<!DOCTYPE...>**). |
| DocumentFragment | 11 | Um fragmento de documento. |
| Notation | 12 | Uma notação na declaração de tipo de documento (por exemplo, **<!NOTATION...>**). |
| Whitespace | 13 | Espaço em branco entre marcações. |
| SignificantWhitespace | 14 | Espaço em branco entre marcações em um modelo de conteúdo misto ou espaço em branco dentro do escopo **xml:space=\"preserve\"**. |
| EndElement | 15 | Uma tag de fim de elemento (por exemplo, ****). |
| EndEntity | 16 | Retornado quando [XmlReader](../xmlreader/) chega ao fim da substituição de entidade como resultado de uma chamada a [XmlReader::ResolveEntity](../xmlreader/resolveentity/). |
| XmlDeclaration | 17 | A declaração XML (por exemplo, **<?xml version='1.0'?>**). O nó [XmlNodeType::XmlDeclaration](./) deve ser o primeiro nó no documento. Ele não pode ter filhos. É um filho do nó [XmlNodeType::Document](./). Pode ter atributos que fornecem informações de versão e codificação. |

## Ver também

* Espaço de nomes [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)