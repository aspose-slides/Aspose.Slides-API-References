---
title: MoveToContent()
second_title: Referência da API Aspose.Slides para C++
description: "Verifica se o nó atual é um nó de conteúdo (texto que não seja espaço em branco, CDATA, Element, EndElement, EntityReference ou EndEntity). Se o nó não for um nó de conteúdo, o leitor avança até o próximo nó de conteúdo ou ao final do arquivo. Ele ignora nós do seguinte tipo: ProcessingInstruction, DocumentType, Comment, Whitespace ou SignificantWhitespace."
type: docs
weight: 833
url: /pt/system.xml/xmlreader/movetocontent/
---
## XmlReader::MoveToContent() método

Verifica se o nó atual é um nó de conteúdo (texto que não seja espaço em branco, **CDATA**, **Element**, **EndElement**, **EntityReference**, ou **EndEntity**). Se o nó não for um nó de conteúdo, o leitor avança até o próximo nó de conteúdo ou o fim do arquivo. Ele ignora nós do seguinte tipo: **ProcessingInstruction**, **DocumentType**, **Comment**, **Whitespace**, ou **SignificantWhitespace**.

```cpp
virtual XmlNodeType System::Xml::XmlReader::MoveToContent()
```

### Valor de Retorno

O valor [XmlReader::get_NodeType](../get_nodetype/) do nó atual encontrado pelo método ou [XmlNodeType::None](../../xmlnodetype/) se o leitor atingiu o fim do fluxo de entrada.

## Veja Também

* Enum [XmlNodeType](../../xmlnodetype/)
* Classe [XmlReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)