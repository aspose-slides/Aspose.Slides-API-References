---
title: get_Value()
second_title: Referência da API Aspose.Slides para C++
description: Quando sobrescrito em uma classe derivada, obtém o valor de texto do nó atual.
type: docs
weight: 92
url: /pt/system.xml/xmlreader/get_value/
---
## XmlReader::get_Value() método

Quando sobrescrito em uma classe derivada, obtém o valor de texto do nó atual.

```cpp
virtual String System::Xml::XmlReader::get_Value()=0
```

### Valor de Retorno

O valor retornado depende do valor [XmlReader::get_NodeType](../get_nodetype/) do nó.

## Observações

A tabela a seguir lista os tipos de nó que têm um valor a ser retornado. Todos os demais tipos de nó retornam [String::Empty](../../../system/string/empty/).

| Tipo de Nó | Valor |
| --- | --- |
| `[Attribute](../../../system/attribute/)`| O valor do atributo. |
| `CDATA`| O conteúdo da seção CDATA. |
| `Comment`| O conteúdo do comentário. |
| `DocumentType`| O subconjunto interno. |
| `ProcessingInstruction`| Todo o conteúdo, excluindo o alvo. |
| `SignificantWhitespace`| O espaço em branco entre marcas em um modelo de conteúdo misto. |
| `[Text](../../../system.text/)`| O conteúdo do nó de texto. |
| `Whitespace`| O espaço em branco entre marcas. |
| [XmlDeclaration](../../xmldeclaration/)| O conteúdo da declaração. |

## Veja Também

* Classe [String](../../../system/string/)
* Classe [XmlReader](../)
* Namespace [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)