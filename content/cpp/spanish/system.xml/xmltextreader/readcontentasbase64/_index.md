---
title: ReadContentAsBase64()
second_title: Referencia de API de Aspose.Slides para C++
description: Lee el contenido y devuelve los bytes binarios decodificados en Base64.
type: docs
weight: 638
url: /es/system.xml/xmltextreader/readcontentasbase64/
---
## XmlTextReader::ReadContentAsBase64(ArrayPtr\<uint8_t\>, int32_t, int32_t) método


Lee el contenido y devuelve los bytes binarios decodificados en **Base64**.

```cpp
int32_t System::Xml::XmlTextReader::ReadContentAsBase64(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```


### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | El búfer en el que copiar el texto resultante. Este valor no puede ser **nullptr**. |
| index | **int32_t** | El desplazamiento en el búfer donde comenzar a copiar el resultado. |
| count | **int32_t** | El número máximo de bytes a copiar al búfer. El número real de bytes copiados se devuelve desde este método. |

### Valor de retorno

El número de bytes escritos en el búfer.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [XmlTextReader](../)
* Espacio de nombres [System::Xml](../../)
* Library [Aspose.Slides](../../../)