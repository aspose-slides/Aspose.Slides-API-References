---
title: ConformanceLevel
second_title: Referencia de la API de Aspose.Slides para C++
description: Especifica la cantidad de verificación de entrada o salida que realizan los objetos XmlReader y XmlWriter.
type: docs
weight: 625
url: /es/system.xml/conformancelevel/
---
## ConformanceLevel enum

Especifica la cantidad de verificación de entrada o salida que realizan los objetos [XmlReader](../xmlreader/) y [XmlWriter](../xmlwriter/).

```cpp
enum class ConformanceLevel
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| Auto | 0 | El objeto [XmlReader](../xmlreader/) o [XmlWriter](../xmlwriter/) detecta automáticamente si se debe realizar una verificación a nivel de documento o a nivel de fragmento, y lleva a cabo la verificación correspondiente. Si está encapsulando otro objeto [XmlReader](../xmlreader/) o [XmlWriter](../xmlwriter/), el objeto externo no realiza ninguna verificación de conformidad adicional. La verificación de conformidad se deja al objeto subyacente. |
| Fragment | 1 | Los datos XML son un [well-formed XML fragment](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities), según la definición de la W3C. Este nivel de conformidad representa un documento XML que podría no tener un elemento raíz pero que, de otro modo, está bien formado. Este nivel de verificación garantiza que la secuencia que se lee o escribe pueda ser consumida por cualquier procesador como un [XML 1.0 external parsed entity](https://www.w3.org/TR/2006/REC-xml-20060816/#wf-entities). |
| Document | 2 | Los datos XML cumplen con las reglas de un [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed) bien formado, según la definición de la W3C. Este nivel de verificación garantiza que la secuencia que se lee o escribe pueda ser consumida por cualquier procesador como un [XML 1.0 document](https://www.w3.org/TR/2006/REC-xml-20060816/#sec-well-formed). |

## Ver también

* Espacio de nombres [System::Xml](../)
* Biblioteca [Aspose.Slides](../../)