---
title: WriteFont()
second_title: Referencia de la API de Aspose.Slides para C++
description: Escribe datos como base64 dentro del propio documento HTML
type: docs
weight: 105
url: /es/aspose.slides.export/embedallfontshtmlcontroller/writefont/
---
## EmbedAllFontsHtmlController::WriteFont(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IFontData\>, System::SharedPtr\<IFontData\>, System::String, System::String, System::ArrayPtr\<uint8_t\>) método

Escribe datos como base64 dentro del propio documento HTML

```cpp
virtual void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteFont(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IFontData> originalFont, System::SharedPtr<IFontData> substitutedFont, System::String fontStyle, System::String fontWeight, System::ArrayPtr<uint8_t> fontData)
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | generador HTML |
| originalFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Fuente a serializar |
| substitutedFont | [System::SharedPtr](../../../system/sharedptr/)\<[IFontData](../../../aspose.slides/ifontdata/)\> | Fuente sustituida (si ocurrió la sustitución de fuente), null de lo contrario |
| fontStyle | [System::String](../../../system/string/) | Estilo de fuente |
| fontWeight | [System::String](../../../system/string/) | Peso de fuente |
| fontData | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Datos de fuente |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Clase [IHtmlGenerator](../../ihtmlgenerator/)
* Clase [IFontData](../../../aspose.slides/ifontdata/)
* Clase [String](../../../system/string/)
* Clase [EmbedAllFontsHtmlController](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)