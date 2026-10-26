---
title: ReadToFollowing()
second_title: Referencia de la API de Aspose.Slides para C++
description: Lee hasta que se encuentra un elemento con el nombre calificado especificado.
type: docs
weight: 898
url: /es/system.xml/xmlreader/readtofollowing/
---
## XmlReader::ReadToFollowing(String) método

Lee hasta que se encuentra un elemento con el nombre calificado especificado.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String name)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre calificado del elemento. |

### Valor devuelto

**true** si se encuentra un elemento coincidente; de lo contrario **false** y el [XmlReader](../) está en un estado de fin de archivo.

## XmlReader::ReadToFollowing(String, String) método

Lee hasta que se encuentra un elemento con el nombre local y el URI del espacio de nombres especificados.

```cpp
virtual bool System::Xml::XmlReader::ReadToFollowing(String localName, String namespaceURI)
```

### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del elemento. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del elemento. |

### Valor devuelto

**true** si se encuentra un elemento coincidente; de lo contrario **false** y el [XmlReader](../) está en un estado de fin de archivo.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)