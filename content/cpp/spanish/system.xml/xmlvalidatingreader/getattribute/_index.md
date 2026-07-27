---
title: GetAttribute()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el valor del atributo con el nombre especificado.
type: docs
weight: 443
url: /es/system.xml/xmlvalidatingreader/getattribute/
---
## XmlValidatingReader::GetAttribute(String) método

Devuelve el valor del atributo con el nombre especificado.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String name) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre calificado del atributo. |

### Valor de retorno

El valor del atributo especificado. Si no se encuentra el atributo, **nullptr** se devuelve.

## XmlValidatingReader::GetAttribute(String, String) método

Devuelve el valor del atributo con el nombre local y el Identificador Uniforme de Recurso (URI) de espacio de nombres especificados.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(String localName, String namespaceURI) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localName | [String](../../../system/string/) | El nombre local del atributo. |
| namespaceURI | [String](../../../system/string/) | El URI del espacio de nombres del atributo. |

### Valor de retorno

El valor del atributo especificado. Si no se encuentra el atributo, **nullptr** se devuelve. Este método no mueve al lector.

## XmlValidatingReader::GetAttribute(int32_t) método

Devuelve el valor del atributo con el índice especificado.

```cpp
String System::Xml::XmlValidatingReader::GetAttribute(int32_t i) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| i | **int32_t** | El índice del atributo. El índice es basado en cero. (El primer atributo tiene índice 0.) |

### Valor de retorno

El valor del atributo especificado.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlValidatingReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)