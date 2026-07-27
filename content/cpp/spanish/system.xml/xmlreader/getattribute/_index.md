---
title: GetAttribute()
second_title: Referencia de API de Aspose.Slides para C++
description: "Cuando se anula en una clase derivada, obtiene el valor del atributo con el valor especificado de XmlReader::get_Name."
type: docs
weight: 599
url: /es/system.xml/xmlreader/getattribute/
---
## XmlReader::GetAttribute(String) método

Cuando se anula en una clase derivada, obtiene el valor del atributo con el valor [XmlReader::get_Name](../get_name/) especificado.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre calificado del atributo. |

### Valor devuelto

El valor del atributo especificado. Si el atributo no se encuentra o el valor es [String::Empty](../../../system/string/empty/), **nullptr** se devuelve.

## XmlReader::GetAttribute(String, String) método

Cuando se anula en una clase derivada, obtiene el valor del atributo con los valores [XmlReader::get_LocalName](../get_localname/) y [XmlReader::get_NamespaceURI](../get_namespaceuri/) especificados.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(String name, String namespaceURI)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre local del atributo. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del atributo. |

### Valor devuelto

El valor del atributo especificado. Si el atributo no se encuentra o el valor es [String::Empty](../../../system/string/empty/), **nullptr** se devuelve. Este método no mueve al lector.

## XmlReader::GetAttribute(int32_t) método

Cuando se anula en una clase derivada, obtiene el valor del atributo con el índice especificado.

```cpp
virtual String System::Xml::XmlReader::GetAttribute(int32_t i)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | **int32_t** | El índice del atributo. El índice comienza en cero. (El primer atributo tiene índice 0.) |

### Valor devuelto

El valor del atributo especificado. Este método no mueve al lector.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)