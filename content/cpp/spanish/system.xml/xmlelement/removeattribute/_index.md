---
title: RemoveAttribute()
second_title: Referencia de la API de Aspose.Slides para C++
description: Elimina un atributo por nombre.
type: docs
weight: 235
url: /es/system.xml/xmlelement/removeattribute/
---
## XmlElement::RemoveAttribute(String) método


Elimina un atributo por nombre.

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String name)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre del atributo a eliminar. Es un nombre calificado. Se compara con el valor **get_Name** del nodo coincidente. |

## XmlElement::RemoveAttribute(String, String) método


Elimina un atributo con el nombre local y el URI del espacio de nombres especificados. (Si el atributo eliminado tiene un valor predeterminado, se reemplaza inmediatamente).

```cpp
virtual void System::Xml::XmlElement::RemoveAttribute(String localName, String namespaceURI)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del atributo a eliminar. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del atributo a eliminar. |

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlElement](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)