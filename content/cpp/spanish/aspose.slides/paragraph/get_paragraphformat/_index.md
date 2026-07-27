---
title: get_ParagraphFormat()
second_title: Referencia de API de Aspose.Slides para C++
description: Devuelve el objeto de formato para este párrafo. Solo lectura IParagraphFormat.
type: docs
weight: 14
url: /es/aspose.slides/paragraph/get_paragraphformat/
---
## Paragraph::get_ParagraphFormat() method

Devuelve el objeto de formato para este párrafo. Solo lectura [IParagraphFormat](../../iparagraphformat/).

```cpp
System::SharedPtr<IParagraphFormat> Aspose::Slides::Paragraph::get_ParagraphFormat() override
```

## Observaciones

El objeto de formato contiene los parámetros de formato definidos solo para el párrafo actual; los datos heredados no se aplican.

Para obtener los valores efectivos, incluidos los heredados, utilice el método [ParagraphFormat::GetEffective](../../paragraphformat/geteffective/).

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IParagraphFormat](../../iparagraphformat/)
* Clase [Paragraph](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)