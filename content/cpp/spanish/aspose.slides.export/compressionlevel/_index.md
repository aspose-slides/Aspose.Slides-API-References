---
title: CompressionLevel
second_title: Referencia de API de Aspose.Slides para C++
description: Especifica los niveles de compresión ZIP para archivos OpenXML. Los niveles superiores ofrecen una mejor compresión a costa de un procesamiento más lento.
type: docs
weight: 846
url: /es/aspose.slides.export/compressionlevel/
---
## CompressionLevel enum

Especifica los niveles de compresión ZIP para archivos OpenXML. Los niveles superiores ofrecen una mejor compresión a costa de un procesamiento más lento.

```cpp
enum class CompressionLevel
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| None | 0 | No se aplica compresión. Los archivos se almacenan tal cual. |
| Level1 | 1 | Compresión más rápida con la menor relación de compresión. |
| Level2 | 2 | Compresión más rápida con una relación de compresión ligeramente mejor que [CompressionLevel::Level1](./). |
| Level3 | 3 | Proporciona mejor compresión que [CompressionLevel::Level2](./) con un impacto moderado en el rendimiento. |
| Level4 | 4 | Proporciona mejor compresión que [CompressionLevel::Level3](./). |
| Level5 | 5 | Proporciona compresión mejorada respecto a [CompressionLevel::Level4](./) con tiempo de procesamiento adicional. |
| Level6 | 6 | Compresión estándar, ofreciendo un buen equilibrio entre velocidad de compresión y tamaño del archivo. El nivel de compresión predeterminado. |
| Level7 | 7 | Proporciona mayor compresión que [CompressionLevel::Level6](./) con un procesamiento más lento. |
| Level8 | 8 | Proporciona mayor compresión que [CompressionLevel::Level7](./). |
| Level9 | 9 | Compresión máxima. Produce el archivo de menor tamaño con la velocidad de procesamiento más lenta. |

## Ver también

* Namespace [Aspose::Slides::Export](../)
* Library [Aspose.Slides](../../)