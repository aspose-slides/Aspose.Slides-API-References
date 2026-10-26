---
title: GetAttribute()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el valor del atributo con el nombre especificado.
type: docs
weight: 495
url: /es/system.xml/xmltextreader/getattribute/
---
## XmlTextReader::GetAttribute(String) método


Devuelve el valor del atributo con el nombre especificado.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String name) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre calificado del atributo. |

### Valor devuelto

El valor del atributo especificado. Si no se encuentra el atributo, se devuelve **nullptr**.

## XmlTextReader::GetAttribute(String, String) método


Devuelve el valor del atributo con el nombre local y el URI del espacio de nombres especificados.

```cpp
String System::Xml::XmlTextReader::GetAttribute(String localName, String namespaceURI) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del atributo. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del atributo. |

### Valor devuelto

El valor del atributo especificado. Si no se encuentra el atributo, se devuelve **nullptr**. Este método no mueve al lector.

## XmlTextReader::GetAttribute(int32_t) método


Devuelve el valor del atributo con el índice especificado.

```cpp
String System::Xml::XmlTextReader::GetAttribute(int32_t i) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | **int32_t** | El índice del atributo. El índice comienza en cero. (El primer atributo tiene el índice 0.) |

### Valor devuelto

El valor del atributo especificado.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlTextReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)