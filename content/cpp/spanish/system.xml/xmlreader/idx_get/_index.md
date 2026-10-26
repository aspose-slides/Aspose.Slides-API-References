---
title: idx_get()
second_title: Referencia de la API de Aspose.Slides para C++
description: Cuando se sobrescribe en una clase derivada, obtiene el valor del atributo con el índice especificado.
type: docs
weight: 612
url: /es/system.xml/xmlreader/idx_get/
---
## XmlReader::idx_get(int32_t) método


Cuando se sobrescribe en una clase derivada, obtiene el valor del atributo con el índice especificado.

```cpp
virtual String System::Xml::XmlReader::idx_get(int32_t i)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | **int32_t** | El índice del atributo. |

### Valor devuelto

El valor del atributo especificado.

## XmlReader::idx_get(String) método


Cuando se sobrescribe en una clase derivada, obtiene el valor del atributo con el valor [XmlReader::get_Name](../get_name/) especificado.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre calificado del atributo. |

### Valor devuelto

El valor del atributo especificado. Si no se encuentra el atributo, se devuelve **nullptr**.

## XmlReader::idx_get(String, String) método


Cuando se sobrescribe en una clase derivada, obtiene el valor del atributo con los valores [XmlReader::get_LocalName](../get_localname/) y [XmlReader::get_NamespaceURI](../get_namespaceuri/) especificados.

```cpp
virtual String System::Xml::XmlReader::idx_get(String name, String namespaceURI)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre local del atributo. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del atributo. |

### Valor devuelto

El valor del atributo especificado. Si no se encuentra el atributo, se devuelve **nullptr**.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)