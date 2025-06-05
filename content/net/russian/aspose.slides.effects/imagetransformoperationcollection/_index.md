---
title: ImageTransformOperationCollection
second_title: Aspose.Sildes для .NET API Reference
description: Представляет собой коллекцию эффектов, примененных к изображению.
type: docs
weight: 3460
url: /ru/aspose.slides.effects/imagetransformoperationcollection/
---

## ImageTransformOperationCollection class

Представляет собой коллекцию эффектов, примененных к изображению.

```csharp
public sealed class ImageTransformOperationCollection : PVIObject, 
    IImageTransformOperationCollection
```

## Properties

| Name | Description |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | Позволяет получить базовый интерфейс IPresentationComponent. Только для чтения [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent). |
| [Count](../../aspose.slides.effects/imagetransformoperationcollection/count) { get; } | Возвращает количество эффектов изображения в коллекции. Только для чтения Int32. |
| [IsReadOnly](../../aspose.slides.effects/imagetransformoperationcollection/isreadonly) { get; } | Получает значение, указывающее, является ли ICollection только для чтения. Только для чтения Boolean. |
| [Item](../../aspose.slides.effects/imagetransformoperationcollection/item) { get; } | Возвращает [`ImageTransformOperation`](../imagetransformoperation) из коллекции по его индексу. |

## Methods

| Name | Description |
| --- | --- |
| [Add](../../aspose.slides.effects/imagetransformoperationcollection/add)(IImageTransformOperation) | Добавляет новый эффект изображения в конец коллекции. |
| [AddAlphaBiLevelEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphabileveleffect)(float) | Добавляет новый эффект Alpha Bi-Level в конец коллекции. |
| [AddAlphaCeilingEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphaceilingeffect)() | Добавляет новый эффект Alpha Ceiling в конец коллекции. |
| [AddAlphaFloorEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphaflooreffect)() | Добавляет новый эффект Alpha Floor в конец коллекции. |
| [AddAlphaInverseEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphainverseeffect)() | Добавляет новый эффект Alpha Inverse в конец коллекции. |
| [AddAlphaModulateEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphamodulateeffect)() | Добавляет новый эффект Alpha Modulate в конец коллекции. |
| [AddAlphaModulateFixedEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphamodulatefixedeffect)(float) | Добавляет новый эффект Alpha Modulate Fixed в конец коллекции. |
| [AddAlphaReplaceEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphareplaceeffect)(float) | Добавляет новый эффект Alpha Replace в конец коллекции. |
| [AddBiLevelEffect](../../aspose.slides.effects/imagetransformoperationcollection/addbileveleffect)(float) | Добавляет новый эффект Bi-Level (черный/белый) в конец коллекции. |
| [AddBlurEffect](../../aspose.slides.effects/imagetransformoperationcollection/addblureffect)(double, bool) | Добавляет новый эффект размытия в конец коллекции. |
| [AddColorChangeEffect](../../aspose.slides.effects/imagetransformoperationcollection/addcolorchangeeffect)() | Добавляет новый эффект изменения цвета в конец коллекции. |
| [AddColorReplaceEffect](../../aspose.slides.effects/imagetransformoperationcollection/addcolorreplaceeffect)() | Добавляет новый эффект замены цвета в конец коллекции. |
| [AddDuotoneEffect](../../aspose.slides.effects/imagetransformoperationcollection/addduotoneeffect)() | Добавляет новый эффект дуотона в конец коллекции. |
| [AddFillOverlayEffect](../../aspose.slides.effects/imagetransformoperationcollection/addfilloverlayeffect)() | Добавляет новый эффект наложения заполнения в конец коллекции. |
| [AddGrayScaleEffect](../../aspose.slides.effects/imagetransformoperationcollection/addgrayscaleeffect)() | Добавляет новый эффект градации серого в конец коллекции. |
| [AddHSLEffect](../../aspose.slides.effects/imagetransformoperationcollection/addhsleffect)(float, float, float) | Добавляет новый эффект оттенка/насыщенности/яркости в конец коллекции. |
| [AddLuminanceEffect](../../aspose.slides.effects/imagetransformoperationcollection/addluminanceeffect)(float, float) | Добавляет новый эффект яркости в конец коллекции. |
| [AddTintEffect](../../aspose.slides.effects/imagetransformoperationcollection/addtinteffect)(float, float) | Добавляет новый эффект тонирования в конец коллекции. |
| [Clear](../../aspose.slides.effects/imagetransformoperationcollection/clear)() | Удаляет все эффекты изображения из коллекции. |
| [Contains](../../aspose.slides.effects/imagetransformoperationcollection/contains)(IImageTransformOperation) | Определяет, содержит ли ICollection определенное значение. |
| [CopyTo](../../aspose.slides.effects/imagetransformoperationcollection/copyto)(IImageTransformOperation[], int) | Копирует элементы ICollection в массив, начиная с определенного индекса массива. |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | Сравнивает с указанным объектом. |
| [GetEnumerator](../../aspose.slides.effects/imagetransformoperationcollection/getenumerator)() | Возвращает перечислитель, который перебирает коллекцию. |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | Возвращает хэш-код. |
| [Remove](../../aspose.slides.effects/imagetransformoperationcollection/remove)(IImageTransformOperation) | Удаляет первое вхождение определенного объекта из ICollection. |
| [RemoveAt](../../aspose.slides.effects/imagetransformoperationcollection/removeat)(int) | Удаляет эффект изображения из коллекции по указанному индексу. |

### See Also

* class [PVIObject](../../aspose.slides/pviobject)
* interface [IImageTransformOperationCollection](../iimagetransformoperationcollection)
* namespace [Aspose.Slides.Effects](../../aspose.slides.effects)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->