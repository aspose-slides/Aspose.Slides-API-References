---
title: AddNamespace()
second_title: Referencia de la API de Aspose.Slides para C++
description: Agrega el espacio de nombres especificado a la colección.
type: docs
weight: 66
url: /es/system.xml/xmlnamespacemanager/addnamespace/
---
## XmlNamespaceManager::AddNamespace(String, String) método

Agrega el espacio de nombres especificado a la colección.

```cpp
virtual void System::Xml::XmlNamespaceManager::AddNamespace(String prefix, String uri)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | [String](../../../system/string/) | El prefijo para asociar con el espacio de nombres que se agrega. Use [String::Empty](../../../system/string/empty/) para agregar un espacio de nombres predeterminado. Si el [XmlNamespaceManager](../) se utilizará para resolver espacios de nombres en una expresión de XML Path Language ([XPath](../../../system.xml.xpath/)), se debe especificar un prefijo. Si una expresión [XPath](../../../system.xml.xpath/) no incluye un prefijo, se asume que el Identificador Uniforme de Recursos (URI) del espacio de nombres está vacío. Para obtener más información sobre expresiones [XPath](../../../system.xml.xpath/) y el [XmlNamespaceManager](../), consulte los métodos XmlNode::SelectNodes(String) y XPathExpression::SetContext(SharedPtr<XmlNamespaceManager>). |
| uri | [String](../../../system/string/) | El espacio de nombres que se agrega. |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlNamespaceManager](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)