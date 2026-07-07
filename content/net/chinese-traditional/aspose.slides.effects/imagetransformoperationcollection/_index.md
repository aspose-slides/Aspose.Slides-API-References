---
title: ImageTransformOperationCollection
second_title: Aspose.Sildes for .NET API 參考
description: 表示套用於影像的效果集合。
type: docs
weight: 3580
url: /zh-hant/aspose.slides.effects/imagetransformoperationcollection/
---
## ImageTransformOperationCollection 類別

表示套用於影像的效果集合。

```csharp
public sealed class ImageTransformOperationCollection : PVIObject, 
    IImageTransformOperationCollection
```

## 屬性

| 名稱 | 說明 |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | 允許取得基礎 IPresentationComponent 介面。唯讀 [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent)。 |
| [Count](../../aspose.slides.effects/imagetransformoperationcollection/count) { get; } | 傳回集合中影像效果的數量。唯讀 Int32。 |
| [IsReadOnly](../../aspose.slides.effects/imagetransformoperationcollection/isreadonly) { get; } | 取得指示 ICollection 是否唯讀的值。唯讀 Boolean。 |
| [Item](../../aspose.slides.effects/imagetransformoperationcollection/item) { get; } | 依索引從集合中傳回 [`ImageTransformOperation`](../imagetransformoperation)。 |

## 方法

| 名稱 | 說明 |
| --- | --- |
| [Add](../../aspose.slides.effects/imagetransformoperationcollection/add)(IImageTransformOperation) | 將新影像效果新增至集合的末端。 |
| [AddAlphaBiLevelEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphabileveleffect)(float) | 將新的 Alpha Bi-Level 效果新增至集合的末端。 |
| [AddAlphaCeilingEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphaceilingeffect)() | 將新的 Alpha Ceiling 效果新增至集合的末端。 |
| [AddAlphaFloorEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphaflooreffect)() | 將新的 Alpha Floor 效果新增至集合的末端。 |
| [AddAlphaInverseEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphainverseeffect)() | 將新的 Alpha Inverse 效果新增至集合的末端。 |
| [AddAlphaModulateEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphamodulateeffect)() | 將新的 Alpha Modulate 效果新增至集合的末端。 |
| [AddAlphaModulateFixedEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphamodulatefixedeffect)(float) | 將新的 Alpha Modulate Fixed 效果新增至集合的末端。 |
| [AddAlphaReplaceEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphareplaceeffect)(float) | 將新的 Alpha Replace 效果新增至集合的末端。 |
| [AddBiLevelEffect](../../aspose.slides.effects/imagetransformoperationcollection/addbileveleffect)(float) | 將新的 Bi-Level（黑/白）效果新增至集合的末端。 |
| [AddBlurEffect](../../aspose.slides.effects/imagetransformoperationcollection/addblureffect)(double, bool) | 將新的 Blur 效果新增至集合的末端。 |
| [AddBrightnessContrastEffect](../../aspose.slides.effects/imagetransformoperationcollection/addbrightnesscontrasteffect)(float, float) | 將新的 BrightnessContrast 效果新增至集合的末端。 |
| [AddColorChangeEffect](../../aspose.slides.effects/imagetransformoperationcollection/addcolorchangeeffect)() | 將新的 Color Change 效果新增至集合的末端。 |
| [AddColorReplaceEffect](../../aspose.slides.effects/imagetransformoperationcollection/addcolorreplaceeffect)() | 將新的 Color Replacement 效果新增至集合的末端。 |
| [AddDuotoneEffect](../../aspose.slides.effects/imagetransformoperationcollection/addduotoneeffect)() | 將新的 Duotone 效果新增至集合的末端。 |
| [AddFillOverlayEffect](../../aspose.slides.effects/imagetransformoperationcollection/addfilloverlayeffect)() | 將新的 Fill Overlay 效果新增至集合的末端。 |
| [AddGrayScaleEffect](../../aspose.slides.effects/imagetransformoperationcollection/addgrayscaleeffect)() | 將新的 Gray Scale 效果新增至集合的末端。 |
| [AddHSLEffect](../../aspose.slides.effects/imagetransformoperationcollection/addhsleffect)(float, float, float) | 將新的 Hue/Saturation/Luminance 效果新增至集合的末端。 |
| [AddLuminanceEffect](../../aspose.slides.effects/imagetransformoperationcollection/addluminanceeffect)(float, float) | 將新的 Luminance 效果新增至集合的末端。 |
| [AddTintEffect](../../aspose.slides.effects/imagetransformoperationcollection/addtinteffect)(float, float) | 將新的 Tint 效果新增至集合的末端。 |
| [Clear](../../aspose.slides.effects/imagetransformoperationcollection/clear)() | 從集合中移除所有影像效果。 |
| [Contains](../../aspose.slides.effects/imagetransformoperationcollection/contains)(IImageTransformOperation) | 判斷 ICollection 是否包含特定值。 |
| [CopyTo](../../aspose.slides.effects/imagetransformoperationcollection/copyto)(IImageTransformOperation[], int) | 將 ICollection 的元素複製到陣列，從特定的陣列索引開始。 |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 與指定的物件比較。 |
| [GetEnumerator](../../aspose.slides.effects/imagetransformoperationcollection/getenumerator)() | 傳回可遍歷集合的列舉器。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | 傳回雜湊碼。 |
| [Remove](../../aspose.slides.effects/imagetransformoperationcollection/remove)(IImageTransformOperation) | 從 ICollection 中移除第一個出現的特定物件。 |
| [RemoveAt](../../aspose.slides.effects/imagetransformoperationcollection/removeat)(int) | 在指定索引處從集合中移除影像效果。 |

### 參見

* 類別 [PVIObject](../../aspose.slides/pviobject)
* 介面 [IImageTransformOperationCollection](../iimagetransformoperationcollection)
* 命名空間 [Aspose.Slides.Effects](../../aspose.slides.effects)
* 組件 [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->