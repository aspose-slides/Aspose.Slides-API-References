---
title: idx_get()
second_title: Referencia de API de Aspose.Slides para C++
description: "Devuelve el primer elemento hijo con el XmlNode::get_Name especificado."
type: docs
weight: 586
url: /es/system.xml/xmlnode/idx_get/
---
## XmlNode::idx_get(String) método

Devuelve el primer elemento hijo con el [XmlNode::get_Name](../get_name/) especificado.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String name)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre calificado del elemento a recuperar. |

### Valor devuelto

El primer [XmlElement](../../xmlelement/) que coincide con el nombre especificado. Devuelve **nullptr** si no hay coincidencia.

## XmlNode::idx_get(String, String) método

Devuelve el primer elemento hijo con los valores [XmlNode::get_LocalName](../get_localname/) y [XmlNode::get_NamespaceURI](../get_namespaceuri/) especificados.

```cpp
virtual SharedPtr<XmlElement> System::Xml::XmlNode::idx_get(String localname, String ns)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localname | [String](../../../system/string/) | El nombre local del elemento. |
| ns | [String](../../../system/string/) | El URI del espacio de nombres del elemento. |

### Valor devuelto

El primer [XmlElement](../../xmlelement/) con **localname** y **ns** coincidentes. Devuelve **nullptr** si no hay coincidencia.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlElement](../../xmlelement/)
* Clase [String](../../../system/string/)
* Clase [XmlNode](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)