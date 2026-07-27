---
title: ReadStartElement()
second_title: Aspose.Slides para la referencia de la API de C++
description: Comprueba que el nodo actual sea un elemento y avanza el lector al siguiente nodo.
type: docs
weight: 846
url: /es/system.xml/xmlreader/readstartelement/
---
## XmlReader::ReadStartElement() método

Checks that the current node is an element and advances the reader to the next node.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement()
```

## XmlReader::ReadStartElement(String) método

Checks that the current content node is an element with the given [XmlReader::get_Name](../get_name/) value and advances the reader to the next node.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String name)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre calificado del elemento. |

## XmlReader::ReadStartElement(String, String) método

Checks that the current content node is an element with the given [XmlReader::get_LocalName](../get_localname/) and [XmlReader::get_NamespaceURI](../get_namespaceuri/) values and advances the reader to the next node.

```cpp
virtual void System::Xml::XmlReader::ReadStartElement(String localname, String ns)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localname | [String](../../../system/string/) | El nombre local del elemento. |
| ns | [String](../../../system/string/) | El URI del espacio de nombres del elemento. |

## Ver también

* Clase [XmlReader](../)
* Clase [String](../../../system/string/)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)