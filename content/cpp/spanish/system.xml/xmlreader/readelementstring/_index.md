---
title: ReadElementString()
second_title: Referencia de API de Aspose.Slides para C++
description: "Lee un elemento de solo texto. Sin embargo, se recomienda usar el método XmlReader::ReadElementContentAsString en su lugar, porque proporciona una forma más directa de manejar esta operación."
type: docs
weight: 859
url: /es/system.xml/xmlreader/readelementstring/
---
## XmlReader::ReadElementString() método

Lee un elemento solo de texto. Sin embargo, se recomienda usar el método [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) en su lugar, porque proporciona una forma más directa de manejar esta operación.

```cpp
virtual String System::Xml::XmlReader::ReadElementString()
```

### Valor devuelto

El texto contenido en el elemento leído. Una cadena vacía si el elemento está vacío.

## XmlReader::ReadElementString(String) método

Comprueba que el valor [XmlReader::get_Name](../get_name/) del elemento encontrado coincida con la cadena proporcionada antes de leer un elemento solo de texto. Sin embargo, se recomienda usar el método [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) en su lugar, porque proporciona una forma más directa de manejar esta operación.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String name)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| name | [String](../../../system/string/) | El nombre a comprobar. |

### Valor devuelto

El texto contenido en el elemento leído. Una cadena vacía si el elemento está vacío.

## XmlReader::ReadElementString(String, String) método

Comprueba que los valores [XmlReader::get_LocalName](../get_localname/) y [XmlReader::get_NamespaceURI](../get_namespaceuri/) del elemento encontrado coincidan con las cadenas proporcionadas antes de leer un elemento solo de texto. Sin embargo, se recomienda usar el método [XmlReader::ReadElementContentAsString](../readelementcontentasstring/) en su lugar, porque proporciona una forma más directa de manejar esta operación.

```cpp
virtual String System::Xml::XmlReader::ReadElementString(String localname, String ns)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| localname | [String](../../../system/string/) | El nombre local a comprobar. |
| ns | [String](../../../system/string/) | El URI del espacio de nombres a comprobar. |

### Valor devuelto

El texto contenido en el elemento leído. Una cadena vacía si el elemento está vacío.

## Ver también

* Clase [String](../../../system/string/)
* Clase [XmlReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)