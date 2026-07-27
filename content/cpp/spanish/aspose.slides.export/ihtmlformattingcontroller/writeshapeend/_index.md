---
title: WriteShapeEnd()
second_title: Referencia de API de Aspose.Slides para C++
description: Se llama antes del renderizado de la forma. Se llama una vez por cada forma. Si esta función escribe algo en el generador, la generación de la imagen de la diapositiva actual se finalizará, se insertará el fragmento HTML añadido y se iniciará una nueva imagen sobre la anterior.
type: docs
weight: 66
url: /es/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) método

Se llama antes del renderizado de la forma. Se llama una vez por cada forma. Si esta función escribe algo en el generador, la generación de la imagen de la diapositiva actual se finalizará, se insertará el fragmento HTML añadido y se iniciará una nueva imagen sobre la anterior.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Objeto de salida. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) que se renderiza al final. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IHtmlGenerator](../../ihtmlgenerator/)
* Clase [IShape](../../../aspose.slides/ishape/)
* Clase [IHtmlFormattingController](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)