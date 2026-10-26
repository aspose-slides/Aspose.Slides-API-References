---
title: SelectSingleNode()
second_title: Referencia de la API de Aspose.Slides para C++
description: Selecciona el primer XmlNode que coincide con la expresión XPath.
type: docs
weight: 352
url: /es/system.xml/xmlnode/selectsinglenode/
---
## XmlNode::SelectSingleNode(const String\&) método


Selecciona el primer [XmlNode](../) que coincide con la expresión [XPath](../../../system.xml.xpath/).

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | La expresión [XPath](../../../system.xml.xpath/). |

### Valor devuelto

El primer [XmlNode](../) que coincide con la consulta [XPath](../../../system.xml.xpath/) o **nullptr** si no se encuentra ningún nodo coincidente.

## XmlNode::SelectSingleNode(const String\&, const SharedPtr\<XmlNamespaceManager\>\&) método


Selecciona el primer [XmlNode](../) que coincide con la expresión [XPath](../../../system.xml.xpath/). Cualquier prefijo encontrado en la expresión [XPath](../../../system.xml.xpath/) se resuelve utilizando el [XmlNamespaceManager](../../xmlnamespacemanager/) proporcionado.

```cpp
SharedPtr<XmlNode> System::Xml::XmlNode::SelectSingleNode(const String &xpath, const SharedPtr<XmlNamespaceManager> &nsmgr)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xpath | const [String](../../../system/string/)\& | La expresión [XPath](../../../system.xml.xpath/). |
| nsmgr | const [SharedPtr](../../../system/sharedptr/)\<[XmlNamespaceManager](../../xmlnamespacemanager/)\>\& | Un [XmlNamespaceManager](../../xmlnamespacemanager/) para usar al resolver espacios de nombres para los prefijos en la expresión [XPath](../../../system.xml.xpath/). |

### Valor devuelto

El primer [XmlNode](../) que coincide con la consulta [XPath](../../../system.xml.xpath/) o **nullptr** si no se encuentra ningún nodo coincidente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNode](../)
* Clase [String](../../../system/string/)
* Clase [XmlNamespaceManager](../../xmlnamespacemanager/)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)