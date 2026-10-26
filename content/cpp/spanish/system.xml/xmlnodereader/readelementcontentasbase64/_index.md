---
title: ReadElementContentAsBase64()
second_title: Referencia de la API de Aspose.Slides para C++
description: Lee el elemento y decodifica el contenido Base64.
type: docs
weight: 469
url: /es/system.xml/xmlnodereader/readelementcontentasbase64/
---
## XmlNodeReader::ReadElementContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) método

Lee el elemento y decodifica el contenido Base64.

```cpp
int32_t System::Xml::XmlNodeReader::ReadElementContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | El búfer en el que copiar el texto resultante. Este valor no puede ser **nullptr**. |
| index | **int32_t** | El desplazamiento dentro del búfer donde comenzar a copiar el resultado. |
| count | **int32_t** | El número máximo de bytes a copiar en el búfer. El número real de bytes copiados se devuelve desde este método. |

### Valor devuelto

El número de bytes escritos en el búfer.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [XmlNodeReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)