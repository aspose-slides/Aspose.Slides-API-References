---
title: GetElementsByTagName()
second_title: Aspose.Slides para la referencia de la API de C++
description: Devuelve un XmlNodeList que contiene una lista de todos los elementos descendientes que coinciden con el nombre especificado.
type: docs
weight: 443
url: /es/system.xml/xmldocument/getelementsbytagname/
---
## XmlDocument::GetElementsByTagName(String) método


Devuelve un [XmlNodeList](../../xmlnodelist/) que contiene una lista de todos los elementos descendientes que coinciden con el nombre especificado.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String name)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre calificado a coincidir. Se compara con el valor **get_Name** del nodo coincidente. El valor especial **"*"`** coincide con todas las etiquetas. |

### Valor devuelto

Un [XmlNodeList](../../xmlnodelist/) que contiene una lista de todos los nodos coincidentes. Si ningún nodo coincide con **name**, la colección devuelta estará vacía.

## XmlDocument::GetElementsByTagName(String, String) método


Devuelve un [XmlNodeList](../../xmlnodelist/) que contiene una lista de todos los elementos descendientes que coinciden con el [XmlDocument::get_LocalName](../get_localname/) y [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) especificados.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlDocument::GetElementsByTagName(String localName, String namespaceURI)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El LocalName a coincidir. El valor especial **"*"`** coincide con todas las etiquetas. |
| namespaceURI | [String](../../../system/string/) | NamespaceURI a coincidir. |

### Valor devuelto

Un [XmlNodeList](../../xmlnodelist/) que contiene una lista de todos los nodos coincidentes. Si ningún nodo coincide con el **localName** y **namespaceURI** especificados, la colección devuelta estará vacía.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNodeList](../../xmlnodelist/)
* Clase [String](../../../system/string/)
* Clase [XmlDocument](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)