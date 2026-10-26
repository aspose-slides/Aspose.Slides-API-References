---
title: FoundResult()
second_title: Referencia de la API de Aspose.Slides para C++
description: Método de devolución de llamada que recibe datos sobre el texto encontrado.
type: docs
weight: 1
url: /es/aspose.slides/ifindresultcallback/foundresult/
---
## IFindResultCallback::FoundResult(System::SharedPtr\<ITextFrame\>, System::String, System::String, int32_t) método

Método de devolución de llamada que recibe datos sobre el texto encontrado.

```cpp
virtual void Aspose::Slides::IFindResultCallback::FoundResult(System::SharedPtr<ITextFrame> textFrame, System::String sourceText, System::String foundText, int32_t textPosition)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../itextframe/)\> | El [ITextFrame](../../itextframe/) en el que se encontró el texto. |
| sourceText | [System::String](../../../system/string/) | El texto fuente en el que se encontró el texto. |
| foundText | [System::String](../../../system/string/) | El texto encontrado. |
| textPosition | **int32_t** | La posición del texto encontrado. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [ITextFrame](../../itextframe/)
* Clase [String](../../../system/string/)
* Clase [IFindResultCallback](../)
* Espacio de nombres [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)