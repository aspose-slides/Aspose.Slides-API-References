---
title: CreateElement()
second_title: Referencia de API de Aspose.Slides para C++
description: Crea un elemento con el nombre especificado.
type: docs
weight: 339
url: /es/system.xml/xmldocument/createelement/
---
## XmlDocument::CreateElement(const String\&) método

Crea un elemento con el nombre especificado.

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &name)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | El nombre calificado del elemento. Si el nombre contiene dos puntos, entonces el valor [XmlNode::get_Prefix](../../xmlnode/get_prefix/) refleja la parte del nombre que precede a los dos puntos y el valor [XmlDocument::get_LocalName](../get_localname/) refleja la parte del nombre que sigue a los dos puntos. El nombre calificado no puede incluir un prefijo de **xmlns**. |

### Valor de retorno

El nuevo [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&) método

Crea un [XmlElement](../../xmlelement/) con el nombre calificado y [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/).

```cpp
SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &qualifiedName, const String &namespaceURI)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| qualifiedName | const [String](../../../system/string/)\& | El nombre calificado del elemento. Si el nombre contiene dos puntos, entonces el valor [XmlNode::get_Prefix](../../xmlnode/get_prefix/) reflejará la parte del nombre que precede a los dos puntos y el valor [XmlDocument::get_LocalName](../get_localname/) reflejará la parte del nombre que sigue a los dos puntos. El nombre calificado no puede incluir un prefijo de **xmlns**. |
| namespaceURI | const [String](../../../system/string/)\& | El URI del espacio de nombres del elemento. |

### Valor de retorno

El nuevo [XmlElement](../../xmlelement/).

## XmlDocument::CreateElement(const String\&, const String\&, const String\&) método

Crea un elemento con el [XmlNode::get_Prefix](../../xmlnode/get_prefix/), [XmlDocument::get_LocalName](../get_localname/) y [XmlNode::get_NamespaceURI](../../xmlnode/get_namespaceuri/) especificados.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlDocument::CreateElement(const String &prefix, const String &localName, const String &namespaceURI)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| prefix | const [String](../../../system/string/)\& | El prefijo del nuevo elemento (si lo hay). [String::Empty](../../../system/string/empty/) y **nullptr** son equivalentes. |
| localName | const [String](../../../system/string/)\& | El nombre local del nuevo elemento. |
| namespaceURI | const [String](../../../system/string/)\& | El URI del espacio de nombres del nuevo elemento (si lo hay). [String::Empty](../../../system/string/empty/) y **nullptr** son equivalentes. |

### Valor de retorno

El nuevo [XmlElement](../../xmlelement/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlElement](../../xmlelement/)
* Clase [String](../../../system/string/)
* Clase [XmlDocument](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)