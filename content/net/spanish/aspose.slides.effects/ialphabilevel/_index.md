---
title: IAlphaBiLevel
second_title: Referencia de la API de Aspose.Slides para .NET
description: Representa un efecto Alpha Bi-Level. Los valores de opacidad alfa menores que el umbral se cambian a 0 totalmente transparente y los valores de alfa mayores o iguales al umbral se cambian a 100 totalmente opaco.
type: docs
weight: 2920
url: /es/aspose.slides.effects/ialphabilevel/
---

## Interfaz IAlphaBiLevel

Representa un efecto Alpha Bi-Level. Los valores de Alpha (Opacidad) menores que el umbral se cambian a 0 (totalmente transparente) y los valores de alfa mayores o iguales al umbral se cambian a 100% (totalmente opaco).

```csharp
public interface IAlphaBiLevel : IAccessiblePVIObject<IAlphaBiLevelEffectiveData>, 
    IImageTransformOperation
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AsIAccessiblePVIObject](../../aspose.slides.effects/ialphabilevel/asiaccessiblepviobject) { get; } | Permite obtener la interfaz base IAccessiblePVIObject. Solo lectura [`IAccessiblePVIObject`](../../aspose.slides/iaccessiblepviobject-1). |
| [AsIImageTransformOperation](../../aspose.slides.effects/ialphabilevel/asiimagetransformoperation) { get; } | Permite obtener la interfaz base IImageTransformOperation. Solo lectura [`IImageTransformOperation`](../iimagetransformoperation). |
| [Threshold](../../aspose.slides.effects/ialphabilevel/threshold) { get; set; } | Devuelve el umbral del efecto. Lectura/escritura Single. |

### Observaciones

Utilice ImageTransformOperationFactory para crear instancias en COM.

### Véase También

* interfaz [IAccessiblePVIObject&lt;T&gt;](../../aspose.slides/iaccessiblepviobject-1)
* interfaz [IAlphaBiLevelEffectiveData](../ialphabileveleffectivedata)
* interfaz [IImageTransformOperation](../iimagetransformoperation)
* espacio de nombres [Aspose.Slides.Effects](../../aspose.slides.effects)
* ensamblado [Aspose.Slides](../../)

<!-- NO EDITAR: generado por xmldocmd para Aspose.Slides.dll -->