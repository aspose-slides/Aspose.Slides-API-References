---
title: GetElementsByTagName()
second_title: Referencia de la API de Aspose.Slides para C++
description: "Devuelve un XmlNodeList que contiene una lista de todos los elementos descendientes que coinciden con el XmlElement::get_Name especificado."
type: docs
weight: 287
url: /es/system.xml/xmlelement/getelementsbytagname/
---
## XmlElement::GetElementsByTagName(String) método

Devuelve un [XmlNodeList](../../xmlnodelist/) que contiene una lista de todos los elementos descendientes que coinciden con el [XmlElement::get_Name](../get_name/) especificado.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String name)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre de la etiqueta a coincidir. Este es un nombre calificado. Se compara con el valor **get_Name** del nodo coincidente. El asterisco (*) es un valor especial que coincide con todas las etiquetas. |

### Valor devuelto

Un [XmlNodeList](../../xmlnodelist/) que contiene una lista de todos los nodos coincidentes. La lista está vacía si no hay nodos coincidentes.

## XmlElement::GetElementsByTagName(String, String) método

Devuelve un [XmlNodeList](../../xmlnodelist/) que contiene una lista de todos los elementos descendientes que coinciden con los valores [XmlElement::get_LocalName](../get_localname/) y [XmlElement::get_NamespaceURI](../get_namespaceuri/) especificados.

```cpp
virtual SharedPtr<XmlNodeList> System::Xml::XmlElement::GetElementsByTagName(String localName, String namespaceURI)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local a coincidir. El asterisco (*) es un valor especial que coincide con todas las etiquetas. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres a coincidir. |

### Valor devuelto

Un [XmlNodeList](../../xmlnodelist/) que contiene una lista de todos los nodos coincidentes. La lista está vacía si no hay nodos coincidentes.

## Véase también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlNodeList](../../xmlnodelist/)
* Clase [String](../../../system/string/)
* Clase [XmlElement](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)