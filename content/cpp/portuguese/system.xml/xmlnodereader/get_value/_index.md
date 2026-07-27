---
title: get_Value()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o valor de texto do nó atual.
type: docs
weight: 79
url: /pt/system.xml/xmlnodereader/get_value/
---
## XmlNodeReader::get_Value() método

Retorna o valor de texto do nó atual.

```cpp
String System::Xml::XmlNodeReader::get_Value() override
```

### Valor de Retorno

O valor retornado depende do [XmlNodeReader::get_NodeType](../get_nodetype/) do nó.

## Observações

A tabela a seguir lista os tipos de nó que têm um valor a ser retornado. Todos os demais tipos de nó retornam [String::Empty](../../../system/string/empty/).

| Tipo de Nó | Valor |
| --- | --- |
| [Attribute](../../../system/attribute/)| O valor do atributo. |
| CDATA| O conteúdo da seção CDATA. |
| Comment| O conteúdo do comentário. |
| DocumentType| O subconjunto interno. |
| ProcessingInstruction| Todo o conteúdo, excluindo o destino. |
| SignificantWhitespace| O espaço em branco entre marcações em um modelo de conteúdo misto. |
| [Text](../../../system.text/)| O conteúdo do nó de texto. |
| Whitespace| O espaço em branco entre marcações. |
| [XmlDeclaration](../../xmldeclaration/)| O conteúdo da declaração. |

## Ver Também

* Classe [String](../../../system/string/)
* Classe [XmlNodeReader](../)
* Espaço de nomes [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)