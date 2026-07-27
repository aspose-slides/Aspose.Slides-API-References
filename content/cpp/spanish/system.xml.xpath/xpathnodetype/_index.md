---
title: XPathNodeType
second_title: Referencia de la API de Aspose.Slides para C++
description: Define los tipos de nodo XPath que pueden ser devueltos por la clase XPathNavigator.
type: docs
weight: 157
url: /es/system.xml.xpath/xpathnodetype/
---
## XPathNodeType enum

Define los tipos de nodo [XPath](../) que pueden ser devueltos por la clase [XPathNavigator](../xpathnavigator/).

```cpp
enum class XPathNodeType
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Root | 0 | El nodo raíz del documento XML o del árbol de nodos. |
| Element | 1 | Un elemento, como **<element>**. |
| Attribute | 2 | Un atributo, como **id='123'**. |
| Namespace | 3 | Un espacio de nombres, como **xmlns=\"namespace\"**. |
| Text | 4 | El contenido de texto de un nodo. Equivalente al Documento [Object](../../system/object/) Modelo (DOM) [Text](../../system.text/) y a los tipos de nodo CDATA. Contiene al menos un carácter. |
| SignificantWhitespace | 5 | Un nodo con caracteres de espacio en blanco y **xml:space** configurado a **preserve**. |
| Whitespace | 6 | Un nodo con solo caracteres de espacio en blanco y sin espacio en blanco significativo. Los caracteres de espacio en blanco son **'\x20'**, **'\x0d'**, **'\x0a'**, **'\x09'**. |
| ProcessingInstruction | 7 | Una instrucción de procesamiento, como **<?pi test?>**. Esto no incluye declaraciones XML, que no son visibles para la clase [XPathNavigator](../xpathnavigator/). |
| Comment | 8 | Un comentario, como ****. |
| All | 9 | Cualquiera de los tipos de nodo XPathNodeType. |

## Véase también

* Namespace [System::Xml::XPath](../)
* Library [Aspose.Slides](../../)