---
title: ReadChars()
second_title: Referencia de API de Aspose.Slides para C++
description: Lee el contenido de texto de un elemento en un búfer de caracteres. Este método está diseñado para leer flujos grandes de texto incrustado llamándolo sucesivamente.
type: docs
weight: 755
url: /es/system.xml/xmltextreader/readchars/
---
## XmlTextReader::ReadChars(const ArrayPtr\<char16_t\>\&, int32_t, int32_t) método


Lee el contenido de texto de un elemento en un búfer de caracteres. Este método está diseñado para leer flujos grandes de texto incrustado llamándolo sucesivamente.

```cpp
int32_t System::Xml::XmlTextReader::ReadChars(const ArrayPtr<char16_t> &buffer, int32_t index, int32_t count)
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char16_t\>\& | La matriz de caracteres que sirve como búfer al que se escribe el contenido de texto. |
| index | **int32_t** | La posición dentro de **buffer** donde el método puede comenzar a escribir el contenido de texto. |
| count | **int32_t** | El número de caracteres que se escribirán en **buffer**. |

### Valor devuelto

El número de caracteres leídos. Puede ser 0 si el lector no está posicionado sobre un elemento o si no hay más contenido de texto que devolver en el contexto actual.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [XmlTextReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)