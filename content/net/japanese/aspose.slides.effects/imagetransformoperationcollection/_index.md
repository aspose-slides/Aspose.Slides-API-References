---
title: ImageTransformOperationCollection
second_title: Aspose.Sildes の .NET API リファレンス
description: 画像に適用されたエフェクトのコレクションを表します。
type: docs
weight: 3580
url: /ja/aspose.slides.effects/imagetransformoperationcollection/
---
## ImageTransformOperationCollection クラス

画像に適用されたエフェクトのコレクションを表します。

```csharp
public sealed class ImageTransformOperationCollection : PVIObject, 
    IImageTransformOperationCollection
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AsIPresentationComponent](../../aspose.slides/pviobject/asipresentationcomponent) { get; } | ベースの IPresentationComponent インターフェイスを取得できます。読み取り専用 [`IPresentationComponent`](../../aspose.slides/ipresentationcomponent)。 |
| [Count](../../aspose.slides.effects/imagetransformoperationcollection/count) { get; } | コレクション内の画像エフェクトの数を返します。読み取り専用 Int32。 |
| [IsReadOnly](../../aspose.slides.effects/imagetransformoperationcollection/isreadonly) { get; } | ICollection が読み取り専用かどうかを示す値を取得します。読み取り専用 Boolean。 |
| [Item](../../aspose.slides.effects/imagetransformoperationcollection/item) { get; } | インデックスでコレクションから [`ImageTransformOperation`](../imagetransformoperation) を返します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.slides.effects/imagetransformoperationcollection/add)(IImageTransformOperation) | 新しい画像エフェクトをコレクションの末尾に追加します。 |
| [AddAlphaBiLevelEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphabileveleffect)(float) | 新しい Alpha Bi-Level エフェクトをコレクションの末尾に追加します。 |
| [AddAlphaCeilingEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphaceilingeffect)() | 新しい Alpha Ceiling エフェクトをコレクションの末尾に追加します。 |
| [AddAlphaFloorEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphaflooreffect)() | 新しい Alpha Floor エフェクトをコレクションの末尾に追加します。 |
| [AddAlphaInverseEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphainverseeffect)() | 新しい Alpha Inverse エフェクトをコレクションの末尾に追加します。 |
| [AddAlphaModulateEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphamodulateeffect)() | 新しい Alpha Modulate エフェクトをコレクションの末尾に追加します。 |
| [AddAlphaModulateFixedEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphamodulatefixedeffect)(float) | 新しい Alpha Modulate Fixed エフェクトをコレクションの末尾に追加します。 |
| [AddAlphaReplaceEffect](../../aspose.slides.effects/imagetransformoperationcollection/addalphareplaceeffect)(float) | 新しい Alpha Replace エフェクトをコレクションの末尾に追加します。 |
| [AddBiLevelEffect](../../aspose.slides.effects/imagetransformoperationcollection/addbileveleffect)(float) | 新しい Bi-Level (black/white) エフェクトをコレクションの末尾に追加します。 |
| [AddBlurEffect](../../aspose.slides.effects/imagetransformoperationcollection/addblureffect)(double, bool) | 新しい Blur エフェクトをコレクションの末尾に追加します。 |
| [AddBrightnessContrastEffect](../../aspose.slides.effects/imagetransformoperationcollection/addbrightnesscontrasteffect)(float, float) | 新しい BrightnessContrast エフェクトをコレクションの末尾に追加します。 |
| [AddColorChangeEffect](../../aspose.slides.effects/imagetransformoperationcollection/addcolorchangeeffect)() | 新しい Color Change エフェクトをコレクションの末尾に追加します。 |
| [AddColorReplaceEffect](../../aspose.slides.effects/imagetransformoperationcollection/addcolorreplaceeffect)() | 新しい Color Replacement エフェクトをコレクションの末尾に追加します。 |
| [AddDuotoneEffect](../../aspose.slides.effects/imagetransformoperationcollection/addduotoneeffect)() | 新しい Duotone エフェクトをコレクションの末尾に追加します。 |
| [AddFillOverlayEffect](../../aspose.slides.effects/imagetransformoperationcollection/addfilloverlayeffect)() | 新しい Fill Overlay エフェクトをコレクションの末尾に追加します。 |
| [AddGrayScaleEffect](../../aspose.slides.effects/imagetransformoperationcollection/addgrayscaleeffect)() | 新しい Gray Scale エフェクトをコレクションの末尾に追加します。 |
| [AddHSLEffect](../../aspose.slides.effects/imagetransformoperationcollection/addhsleffect)(float, float, float) | 新しい Hue/Saturation/Luminance エフェクトをコレクションの末尾に追加します。 |
| [AddLuminanceEffect](../../aspose.slides.effects/imagetransformoperationcollection/addluminanceeffect)(float, float) | 新しい Luminance エフェクトをコレクションの末尾に追加します。 |
| [AddTintEffect](../../aspose.slides.effects/imagetransformoperationcollection/addtinteffect)(float, float) | 新しい Tint エフェクトをコレクションの末尾に追加します。 |
| [Clear](../../aspose.slides.effects/imagetransformoperationcollection/clear)() | コレクションからすべての画像エフェクトを削除します。 |
| [Contains](../../aspose.slides.effects/imagetransformoperationcollection/contains)(IImageTransformOperation) | ICollection が特定の値を含むかどうかを判定します。 |
| [CopyTo](../../aspose.slides.effects/imagetransformoperationcollection/copyto)(IImageTransformOperation[], int) | ICollection の要素を特定の配列インデックスから始めて Array にコピーします。 |
| override [Equals](../../aspose.slides/pviobject/equals)(object) | 指定されたオブジェクトと比較します。 |
| [GetEnumerator](../../aspose.slides.effects/imagetransformoperationcollection/getenumerator)() | コレクションを反復処理する列挙子を返します。 |
| override [GetHashCode](../../aspose.slides/pviobject/gethashcode)() | ハッシュコードを返します。 |
| [Remove](../../aspose.slides.effects/imagetransformoperationcollection/remove)(IImageTransformOperation) | ICollection から特定のオブジェクトの最初の出現を削除します。 |
| [RemoveAt](../../aspose.slides.effects/imagetransformoperationcollection/removeat)(int) | 指定されたインデックスのコレクションから画像エフェクトを削除します。 |

### 参照

* クラス [PVIObject](../../aspose.slides/pviobject)
* インターフェース [IImageTransformOperationCollection](../iimagetransformoperationcollection)
* 名前空間 [Aspose.Slides.Effects](../../aspose.slides.effects)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->