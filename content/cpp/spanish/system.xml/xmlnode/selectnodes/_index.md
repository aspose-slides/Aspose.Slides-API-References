---
title: SelectNodes()
second_title: Referencia de la API de Aspose.Slides para C++
description: Selecciona una lista de nodos que coinciden con la expresión XPath.
type: docs
weight: 365
url: /es/system.xml/xmlnode/selectnodes/
---
## XmlNode::SelectNodes(const String\&) método

Selecciona una lista de nodos que coinciden con la expresión [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | La expresión [XPath](../../../system.xml.xpath/). |

### Valor devuelto

Un [XmlNodeList](../../xmlnodelist/) que contiene una colección de nodos que coinciden con la consulta [XPath](../../../system.xml.xpath/).

## XmlNode::SelectNodes(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) método

Selecciona una lista de nodos que coinciden con la expresión [XPath](../../../system.xml.xpath/). Cualquier prefijo encontrado en la expresión [XPath](../../../system.xml.xpath/) se resuelve usando el [XmlNamespaceManager](../../xmlnamespacemanager/) proporcionado.

```cpp
SharedPtr<XmlNodeList> System::Xml::XmlNode::SelectNodes(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | La expresión [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Un [XmlNamespaceManager](../../xmlnamespacemanager/) para usar al resolver espacios de nombres para los prefijos en la expresión [XPath](../../../system.xml.xpath/). |

### Valor devuelto

Un [XmlNodeList](../../xmlnodelist/) que contiene una colección de nodos que coinciden con la consulta [XPath](../../../system.xml.xpath/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNodeList](../../xmlnodelist/)
* Clase [String](../../../system/string/)
* Clase [XmlNode](../)
* Clase [XmlNamespaceManager](../../xmlnamespacemanager/)
* Espacio de nombres [System::Xml](../../)
* Library [Aspose.Slides](../../../)