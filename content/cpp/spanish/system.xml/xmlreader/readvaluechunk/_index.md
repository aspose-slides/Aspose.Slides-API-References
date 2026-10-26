---
title: ReadValueChunk()
second_title: Referencia de la API de Aspose.Slides para C++
description: Lee flujos grandes de texto incrustados en un documento XML.
type: docs
weight: 807
url: /es/system.xml/xmlreader/readvaluechunk/
---
## XmlReader::ReadValueChunk(ArrayPtr\<char16_t\>, int32_t, int32_t) método

Lee flujos grandes de texto incrustados en un documento XML.

```cpp
virtual int32_t System::Xml::XmlReader::ReadValueChunk(ArrayPtr<char16_t> buffer, int32_t index, int32_t count)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<char16_t\> | La matriz de caracteres que sirve como búfer al que se escribe el contenido de texto. Este valor no puede ser **nullptr**. |
| index | **int32_t** | El desplazamiento dentro del búfer donde [XmlReader](../) puede comenzar a copiar los resultados. |
| count | **int32_t** | El número máximo de caracteres a copiar al búfer. El número real de caracteres copiados se devuelve desde este método. |

### Valor de retorno

El número de caracteres leídos en el búfer. Se devuelve el valor cero cuando no hay más contenido de texto.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [XmlReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)