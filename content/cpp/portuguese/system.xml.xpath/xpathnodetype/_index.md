---
title: XPathNodeType
second_title: Referência da API Aspose.Slides para C++
description: Define os tipos de nó XPath que podem ser retornados pela classe XPathNavigator.
type: docs
weight: 157
url: /pt/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum

Define os tipos de nó [XPath](../) que podem ser retornados pela classe [XPathNavigator](../xpathnavigator/).

```cpp
enum class XPathNodeType
```

### Valores

| Nome | Valor | Descrição |
| --- | --- | --- |
| Root | 0 | O nó raiz do documento XML ou da árvore de nós. |
| Element | 1 | Um elemento, como **<element>**. |
| Attribute | 2 | Um atributo, como **id='123'**. |
| Namespace | 3 | Um namespace, como **xmlns=\"namespace\"**. |
| Text | 4 | O conteúdo de texto de um nó. Equivalente ao Modelo de Documento [Object](../../system/object/) (DOM) [Text](../../system.text/) e tipos de nó CDATA. Contém pelo menos um caractere. |
| SignificantWhitespace | 5 | Um nó com caracteres de espaço em branco e **xml:space** definido como **preserve**. |
| Whitespace | 6 | Um nó contendo apenas caracteres de espaço em branco e sem espaço em branco significativo. Os caracteres de espaço em branco são **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**. |
| ProcessingInstruction | 7 | Uma instrução de processamento, como **<?pi test?>**. Isto não inclui declarações XML, que não são visíveis para a classe [XPathNavigator](../xpathnavigator/). |
| Comment | 8 | Um comentário, como ****. |
| All | 9 | Qualquer um dos tipos de nó XPathNodeType. |

## Veja Também

* Namespace [System::Xml::XPath](../)
* Biblioteca [Aspose.Slides](../../)