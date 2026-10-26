---
title: HasAttribute()
second_title: Referencia de la API de Aspose.Slides para C++
description: Determina si el nodo actual tiene un atributo con el nombre especificado.
type: docs
weight: 300
url: /es/system.xml/xmlelement/hasattribute/
---
## XmlElement::HasAttribute(String) método

Determina si el nodo actual tiene un atributo con el nombre especificado.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String name)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre del atributo a buscar. Este es un nombre calificado. Se compara con el valor **get_Name** del nodo correspondiente. |

### Valor devuelto

**true** si el nodo actual tiene el atributo especificado; de lo contrario, **false**.

## XmlElement::HasAttribute(String, String) método

Determina si el nodo actual tiene un atributo con el nombre local y el URI del espacio de nombres especificados.

```cpp
virtual bool System::Xml::XmlElement::HasAttribute(String localName, String namespaceURI)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del atributo a buscar. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del atributo a buscar. |

### Valor devuelto

**true** si el nodo actual tiene el atributo especificado; de lo contrario, **false**.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlElement](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)