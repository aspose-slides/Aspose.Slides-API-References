---
title: ReadContentAsBinHex()
second_title: Referencia de API de Aspose.Slides para C++
description: Lee el contenido y devuelve los bytes binarios decodificados en BinHex.
type: docs
weight: 599
url: /es/system.xml/xmlvalidatingreader/readcontentasbinhex/
---
## XmlValidatingReader::ReadContentAsBinHex(ArrayPtr\<uint8_t\>, int32_t, int32_t) método

Lee el contenido y devuelve los bytes binarios decodificados en BinHex.

```cpp
int32_t System::Xml::XmlValidatingReader::ReadContentAsBinHex(ArrayPtr<uint8_t> buffer, int32_t index, int32_t count) override
```

### Parámetros

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| buffer | [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | El buffer en el que copiar el texto resultante. Este valor no puede ser **nullptr**. |
| index | **int32_t** | El desplazamiento en el buffer donde comenzar a copiar el resultado. |
| count | **int32_t** | El número máximo de bytes a copiar en el buffer. El número real de bytes copiados se devuelve desde este método. |

### Valor de retorno

El número de bytes escritos en el buffer.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [XmlValidatingReader](../)
* Espacio de nombres [System::Xml](../../)
* Biblioteca [Aspose.Slides](../../../)