---
title: Aspose.Slides.Effects
second_title: Aspose.Sildes の .NET API リファレンス
description: Microsoft PowerPoint プレゼンテーションでさまざまなエフェクトを処理するためのクラスを含みます。
type: docs
weight: 60
url: /ja/aspose.slides.effects/
---
Microsoft PowerPoint プレゼンテーションでさまざまなエフェクトを処理するためのクラスを含みます。

## クラス

| クラス | 説明 |
| --- | --- |
| [AlphaBiLevel](./alphabilevel) | Alpha Bi-Level エフェクトを表します。しきい値未満の Alpha (Opacity) 値は 0 (完全に透明) に、しきい値以上の Alpha 値は 100% (完全に不透明) に変換されます。 |
| [AlphaCeiling](./alphaceiling) | Alpha Ceiling エフェクトを表します。0 より大きい Alpha (opacity) 値は 100% に変換されます。つまり、部分的に不透明なものはすべて完全に不透明になります。 |
| [AlphaFloor](./alphafloor) | Alpha Floor エフェクトを表します。100% 未満の Alpha (opacity) 値は 0 に変換されます。つまり、部分的に透明なものはすべて完全に透明になります。 |
| [AlphaInverse](./alphainverse) | Alpha Inverse エフェクトを表します。Alpha (opacity) 値は 100% から減算して反転されます。 |
| [AlphaModulate](./alphamodulate) | Alpha Modulate エフェクトを表します。エフェクトの Alpha (opacity) 値は固定パーセンテージで乗算されます。エフェクト コンテナは、調整対象となる Alpha 値を含むエフェクトを指定します。 |
| [AlphaModulateFixed](./alphamodulatefixed) | Alpha Modulate Fixed エフェクトを表します。エフェクトの Alpha (opacity) 値は固定パーセンテージで乗算されます。 |
| [AlphaReplace](./alphareplace) | Alpha Replace エフェクトを表します。エフェクトの Alpha (opacity) 値は固定の Alpha に置き換えられます。 |
| [BiLevel](./bilevel) | Bi-Level (黒/白) エフェクトを表します。指定されたしきい値より低い輝度の入力色は黒に、しきい値以上の輝度の入力色は白に変換されます。Alpha エフェクト値はこのエフェクトの影響を受けません。 |
| [Blur](./blur) | 形状全体（塗りつぶしを含む）に適用される Blur エフェクトを表します。すべてのカラーチャネル（Alpha を含む）が影響を受けます。 |
| [BrightnessContrast](./brightnesscontrast) | BrightnessContrast エフェクトを表します。明るさとコントラストを調整します。 |
| [ColorChange](./colorchange) | Color Change エフェクトを表します。FromColor のインスタンスが ToColor のインスタンスに置き換えられます。 |
| [ColorReplace](./colorreplace) | Color Replacement エフェクトを表します。すべてのエフェクトカラーが固定カラーに変更されます。Alpha 値は影響を受けません。 |
| [Duotone](./duotone) | Duotone エフェクトを表します。各ピクセルについて、Color1 と Color2 を線形補間して新しいピクセル色を決定します。 |
| [EffectFactory](./effectfactory) | エフェクトの作成を可能にします。 |
| [FillOverlay](./filloverlay) | Fill Overlay エフェクトを表します。フィル オーバーレイはオブジェクトに追加の塗りを指定し、2 つの塗りを合成するために使用できます。 |
| [Glow](./glow) | Glow エフェクトを表します。オブジェクトのエッジ外側にカラー ブラー輪郭が追加されます。 |
| [GrayScale](./grayscale) | Gray Scale エフェクトを表します。すべてのエフェクトカラー値を、輝度に対応したグレイスケールに変換します。Alpha (opacity) 値は影響を受けません。 |
| [HSL](./hsl) | Hue/Saturation/Luminance エフェクトを表します。色相、彩度、輝度はそれぞれ現在の値に対して相対的に調整できます。 |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata) | 効果的な画像変換エフェクトの読み取り専用コレクションを表す不変オブジェクトです。 |
| [ImageTransformOperation](./imagetransformoperation) | 抽象的な画像変換エフェクトを表します。 |
| [ImageTransformOperationCollection](./imagetransformoperationcollection) | 画像に適用されるエフェクトのコレクションを表します。 |
| [ImageTransformOperationFactory](./imagetransformoperationfactory) | 画像変換操作の作成を可能にします。 |
| [InnerShadow](./innershadow) | Inner Shadow エフェクトを表します。 |
| [Luminance](./luminance) | Luminance エフェクトを表します。明るさはすべての色を白または黒に線形にシフトし、コントラストは色同士の距離を拡大または縮小します。 |
| [OuterShadow](./outershadow) | Outer Shadow エフェクトを表します。 |
| [PresetShadow](./presetshadow) | Preset Shadow エフェクトを表します。 |
| [Reflection](./reflection) | Reflection エフェクトを表します。 |
| [SoftEdge](./softedge) | ソフトエッジ エフェクトを表します。形状のエッジはぼかされますが、塗りは影響を受けません。 |
| [Tint](./tint) | Tint エフェクトを表します。指定された量だけ、エフェクトカラーを色相方向または反対方向にシフトします。 |

## インターフェイス

| インターフェイス | 説明 |
| --- | --- |
| [IAlphaBiLevel](./ialphabilevel) | Alpha Bi-Level エフェクトを表します。しきい値未満の Alpha (Opacity) 値は 0 (完全に透明) に、しきい値以上の Alpha 値は 100% (完全に不透明) に変換されます。 |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata) | Alpha Bi-Level エフェクトを表す不変オブジェクトです。しきい値未満の Alpha (Opacity) 値は 0 (完全に透明) に、しきい値以上の Alpha 値は 100% (完全に不透明) に変換されます。 |
| [IAlphaCeiling](./ialphaceiling) | Alpha Ceiling エフェクトを表します。0 より大きい Alpha (opacity) 値は 100% に変換されます。つまり、部分的に不透明なものはすべて完全に不透明になります。 |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata) | Alpha Ceiling エフェクトを表す不変オブジェクトです。0 より大きい Alpha (opacity) 値は 100% に変換されます。つまり、部分的に不透明なものはすべて完全に不透明になります。 |
| [IAlphaFloor](./ialphafloor) | Alpha Floor エフェクトを表します。100% 未満の Alpha (opacity) 値は 0 に変換されます。つまり、部分的に透明なものはすべて完全に透明になります。 |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata) | Alpha Floor エフェクトを表す不変オブジェクトです。100% 未満の Alpha (opacity) 値は 0 に変換されます。つまり、部分的に透明なものはすべて完全に透明になります。 |
| [IAlphaInverse](./ialphainverse) | Alpha Inverse エフェクトを表します。Alpha (opacity) 値は 100% から減算して反転されます。 |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata) | Alpha Inverse エフェクトを表す不変オブジェクトです。Alpha (opacity) 値は 100% から減算して反転されます。 |
| [IAlphaModulate](./ialphamodulate) | Alpha Modulate エフェクトを表します。エフェクトの Alpha (opacity) 値は固定パーセンテージで乗算されます。エフェクト コンテナは、調整対象となる Alpha 値を含むエフェクトを指定します。 |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata) | Alpha Modulate エフェクトを表す不変オブジェクトです。エフェクトの Alpha (opacity) 値は固定パーセンテージで乗算されます。エフェクト コンテナは、調整対象となる Alpha 値を含むエフェクトを指定します。 |
| [IAlphaModulateFixed](./ialphamodulatefixed) | Alpha Modulate Fixed エフェクトを表します。エフェクトの Alpha (opacity) 値は固定パーセンテージで乗算されます。 |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata) | Alpha Modulate Fixed エフェクトを表す不変オブジェクトです。エフェクトの Alpha (opacity) 値は固定パーセンテージで乗算されます。 |
| [IAlphaReplace](./ialphareplace) | 基底 IImageTransformOperation インターフェイスを表します。 |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata) | Alpha Replace エフェクトを表す不変オブジェクトです。エフェクトの Alpha (opacity) 値は固定の Alpha に置き換えられます。 |
| [IBiLevel](./ibilevel) | 基底 IImageTransformOperation インターフェイスを表します。 |
| [IBiLevelEffectiveData](./ibileveleffectivedata) | Bi-Level (黒/白) エフェクトを表す不変オブジェクトです。指定されたしきい値より低い輝度の入力色は黒に、しきい値以上の輝度の入力色は白に変換されます。Alpha エフェクト値は影響を受けません。 |
| [IBlur](./iblur) | 形状全体（塗りつぶしを含む）に適用される Blur エフェクトを表します。すべてのカラーチャネル（Alpha を含む）が影響を受けます。 |
| [IBlurEffectiveData](./iblureffectivedata) | Blur エフェクトを表す不変オブジェクトです。形状全体（塗りつぶしを含む）に適用され、すべてのカラーチャネル（Alpha を含む）が影響を受けます。 |
| [IBrightnessContrast](./ibrightnesscontrast) | BrightnessContrast エフェクトを表します。明るさとコントラストを調整します。 |
| [IBrightnessContrastEffectiveData](./ibrightnesscontrasteffectivedata) | BrightnessContrast エフェクトを表す不変オブジェクトです。明るさとコントラストを調整します。 |
| [IColorChange](./icolorchange) | Color Change エフェクトを表します。FromColor のインスタンスが ToColor のインスタンスに置き換えられます。 |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata) | Color Change エフェクトを表す不変オブジェクトです。FromColor のインスタンスが ToColor のインスタンスに置き換えられます。 |
| [IColorReplace](./icolorreplace) | Color Replacement エフェクトを表します。 |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata) | Color Replacement エフェクトを表す不変オブジェクトです。すべてのエフェクトカラーが固定カラーに変更され、Alpha 値は影響を受けません。 |
| [IDuotone](./iduotone) | Duotone エフェクトを表します。 |
| [IDuotoneEffectiveData](./iduotoneeffectivedata) | Duotone エフェクトを表す不変オブジェクトです。各ピクセルについて、clr1 と clr2 を線形補間して新しいピクセル色を決定します。 |
| [IEffectEffectiveData](./ieffecteffectivedata) | エフェクトを表す不変オブジェクトの基底クラスです。 |
| [IEffectFactory](./ieffectfactory) | エフェクト インスタンスの作成を可能にします。 |
| [IFillOverlay](./ifilloverlay) | Fill Overlay エフェクトを表します。フィル オーバーレイはオブジェクトに追加の塗りを指定し、2 つの塗りを合成するために使用できます。 |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata) | Fill Overlay エフェクトを表す不変オブジェクトです。フィル オーバーレイはオブジェクトに追加の塗りを指定し、2 つの塗りを合成するために使用できます。 |
| [IGlow](./iglow) | Glow エフェクトを表します。オブジェクトのエッジ外側にカラー ブラー輪郭が追加されます。 |
| [IGlowEffectiveData](./igloweffectivedata) | Glow エフェクトを表す不変オブジェクトです。オブジェクトのエッジ外側にカラー ブラー輪郭が追加されます。 |
| [IGrayScale](./igrayscale) | IImageTransformOperation インターフェイスを表します。 |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata) | Gray Scale エフェクトを表す不変オブジェクトです。すべてのエフェクトカラー値を、輝度に対応したグレイスケールに変換します。Alpha (opacity) 値は影響を受けません。 |
| [IHSL](./ihsl) | Hue/Saturation/Luminance エフェクトを表します。色相、彩度、輝度はそれぞれ現在の値に対して相対的に調整できます。 |
| [IHSLEffectiveData](./ihsleffectivedata) | Hue/Saturation/Luminance エフェクトを表します。色相、彩度、輝度はそれぞれ現在の値に対して相対的に調整できます。 |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata) | 効果的な画像変換エフェクトの読み取り専用コレクションを表す不変オブジェクトです。 |
| [IImageTransformOperation](./iimagetransformoperation) | 抽象的な画像変換エフェクトを表します。 |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection) | 画像に適用されるエフェクトのコレクションを表します。 |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory) | 画像エフェクト インスタンスの作成を可能にします。 |
| [IInnerShadow](./iinnershadow) | 内部シャドウ エフェクトを表します。 |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata) | 内部シャドウ エフェクトを表す不変オブジェクトです。 |
| [ILuminance](./iluminance) | Luminance エフェクトを表します。明るさはすべての色を白または黒に線形にシフトし、コントラストは色同士の距離を拡大または縮小します。 |
| [ILuminanceEffectiveData](./iluminanceeffectivedata) | Luminance エフェクトを表します。明るさはすべての色を白または黒に線形にシフトし、コントラストは色同士の距離を拡大または縮小します。 |
| [IOuterShadow](./ioutershadow) | Outer Shadow エフェクトを表します。 |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata) | Outer Shadow エフェクトを表す不変オブジェクトです。 |
| [IPresetShadow](./ipresetshadow) | Preset Shadow エフェクトを表します。 |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata) | Preset Shadow エフェクトを表す不変オブジェクトです。 |
| [IReflection](./ireflection) | Reflection エフェクトを表します。 |
| [IReflectionEffectiveData](./ireflectioneffectivedata) | Reflection エフェクトを表す不変オブジェクトです。 |
| [ISoftEdge](./isoftedge) | Soft Edge エフェクトを表します。形状のエッジはぼかされますが、塗りは影響を受けません。 |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata) | Soft Edge エフェクトを表す不変オブジェクトです。形状のエッジはぼかされますが、塗りは影響を受けません。 |
| [ITint](./itint) | Tint エフェクトを表します。指定された量だけ、エフェクトカラーを色相方向または反対方向にシフトします。 |
| [ITintEffectiveData](./itinteffectivedata) | Tint エフェクトを表す不変オブジェクトです。指定された量だけ、エフェクトカラーを色相方向または反対方向にシフトします。 |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->