---
title: CreateAttribute()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un XmlAttribute con el nombre especificado.
type: docs
weight: 274
url: /es/system.xml/xmldocument/createattribute/
---
## XmlDocument::CreateAttribute(const String\&) método


Crea un [XmlAttribute](../../xmlattribute/) con el nombre especificado.

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &name)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | El nombre calificado del atributo. Si el nombre contiene dos puntos, el valor [XmlNode::get_Prefix](../../xmlnode/get_prefix/) refleja la parte del nombre que precede al primer dos puntos y el valor [XmlDocument::get_LocalName](../get_localname/) refleja la parte del nombre que sigue al primer dos puntos. El [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) permanece vacío a menos que el prefijo sea un prefijo incorporado reconocido, como **xmlns**. En este caso, get_NamespaceURI tiene un valor de [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Valor de retorno

El nuevo [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&) método


Crea un [XmlAttribute](../../xmlattribute/) con el nombre calificado especificado y [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &qualifiedName, const String &namespaceURI)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | El nombre calificado del atributo. Si el nombre contiene dos puntos, el valor [XmlNode::get_Prefix](../../xmlnode/get_prefix/) reflejará la parte del nombre que precede al dos puntos y el valor [XmlDocument::get_LocalName](../get_localname/) reflejará la parte del nombre que sigue al dos puntos. |
| namespaceURI | const [String](../../../system/string/)\& | El namespaceURI del atributo. Si el nombre calificado incluye un prefijo **xmlns**, entonces este parámetro debe ser [http://www.w3.org/2000/xmlns/](http://www.w3.org/2000/xmlns/). |

### Valor de retorno

El nuevo [XmlAttribute](../../xmlattribute/).

## XmlDocument::CreateAttribute(const String\&, const String\&, const String\&) método


Crea un [XmlAttribute](../../xmlattribute/) con el [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) y [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) especificados.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlDocument::CreateAttribute(const String &prefix, const String &localName, const String &namespaceURI)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | El prefijo del atributo (si lo hay). [String::Empty](../../../system/string/empty/) y **nullptr** son equivalentes. |
| localName | const [String](../../../system/string/)\& | El nombre local del atributo. |
| namespaceURI | const [String](../../../system/string/)\& | El URI del espacio de nombres del atributo (si lo hay). [String::Empty](../../../system/string/empty/) y **nullptr** son equivalentes. Si **prefix** es **xmlns**, entonces este parámetro debe ser [http://www.w3.org/2000/xmlns/;](http://www.w3.org/2000/xmlns/;); de lo contrario se lanza una excepción. |

### Valor de retorno

El nuevo [XmlAttribute](../../xmlattribute/).

## Ver también

* Definición de tipo [SharedPtr](../../../system/sharedptr/)
* Clase [XmlAttribute](../../xmlattribute/)
* Clase [String](../../../system/string/)
* Clase [XmlDocument](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)