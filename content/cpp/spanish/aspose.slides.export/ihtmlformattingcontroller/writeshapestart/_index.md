---
title: WriteShapeStart()
second_title: Referencia de la API de Aspose.Slides para C++
description: Llamado antes de la renderización del shape. Llamado una vez por cada shape. Si esta función escribe algo en generator, la generación de la imagen de la diapositiva actual se finalizará, se insertará el fragmento HTML añadido y se iniciará una nueva imagen encima de la anterior.
type: docs
weight: 53
url: /es/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) método

Llamado antes de la renderización del shape. Llamado una vez por cada shape. Si esta función escribe algo en generator, la generación de la imagen de la diapositiva actual se finalizará, se insertará el fragmento html añadido y se iniciará una nueva imagen encima de la anterior.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### Argumentos

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Objeto de salida. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) que está a punto de renderizarse. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Clase [IHtmlGenerator](../../ihtmlgenerator/)
* Clase [IShape](../../../aspose.slides/ishape/)
* Clase [IHtmlFormattingController](../)
* Espacio de nombres [Aspose::Slides::Export](../../)
* Biblioteca [Aspose.Slides](../../../)