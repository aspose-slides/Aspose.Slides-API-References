---
title: GetAttributeNode()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el XmlAttribute con el nombre especificado.
type: docs
weight: 248
url: /es/system.xml/xmlelement/getattributenode/
---
## XmlElement::GetAttributeNode(String) método

Devuelve el [XmlAttribute](../../xmlattribute/) con el nombre especificado.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String name)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre del atributo a recuperar. Este es un nombre calificado. Se compara con el valor **get_Name** del nodo coincidente. |

### Valor de retorno

El [XmlAttribute](../../xmlattribute/) especificado o **nullptr** si no se encontró un atributo coincidente.

## XmlElement::GetAttributeNode(String, String) método

Devuelve el [XmlAttribute](../../xmlattribute/) con el nombre local y el URI del espacio de nombres especificados.

```cpp
virtual SharedPtr<XmlAttribute> System::Xml::XmlElement::GetAttributeNode(String localName, String namespaceURI)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del atributo. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del atributo. |

### Valor de retorno

El [XmlAttribute](../../xmlattribute/) especificado o **nullptr** si no se encontró un atributo coincidente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [XmlAttribute](../../xmlattribute/)
* Clase [String](../../../system/string/)
* Clase [XmlElement](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)