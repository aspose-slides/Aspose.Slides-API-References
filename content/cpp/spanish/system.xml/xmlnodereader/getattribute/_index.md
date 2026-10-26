---
title: GetAttribute()
second_title: Referencia de la API de Aspose.Slides para C++
description: Devuelve el valor del atributo con el nombre especificado.
type: docs
weight: 287
url: /es/system.xml/xmlnodereader/getattribute/
---
## XmlNodeReader::GetAttribute(String) método


Devuelve el valor del atributo con el nombre especificado.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre calificado del atributo. |

### Valor devuelto

El valor del atributo especificado. Si no se encuentra el atributo, **nullptr** se devuelve.

## XmlNodeReader::GetAttribute(String, String) método


Devuelve el valor del atributo con el nombre local y el URI del espacio de nombres especificados.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(String name, String namespaceURI) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre local del atributo. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del atributo. |

### Valor devuelto

El valor del atributo especificado. Si no se encuentra el atributo, **nullptr** se devuelve.

## XmlNodeReader::GetAttribute(int32_t) método


Devuelve el valor del atributo con el índice especificado.

```cpp
String System::Xml::XmlNodeReader::GetAttribute(int32_t attributeIndex) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| attributeIndex | **int32_t** | El índice del atributo. El índice es base cero. (El primer atributo tiene índice 0.) |

### Valor devuelto

El valor del atributo especificado.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlNodeReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)