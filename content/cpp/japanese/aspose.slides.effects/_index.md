---
title: "Aspose::Slides::Effects"
second_title: Aspose.Slides for C++ API リファレンス
description: 
type: docs
weight: 66
url: /ja/aspose.slides.effects/
---
## クラス

| クラス | 説明 |
| --- | --- |
| [AlphaBiLevel](./alphabilevel/) | Alpha Bi-Level エフェクトを表します。しきい値未満の Alpha（Opacity）値は 0（完全に透明）に変更され、しきい値以上の Alpha 値は 100%（完全に不透明）に変更されます。 |
| [AlphaCeiling](./alphaceiling/) | Alpha Ceiling エフェクトを表します。Alpha（opacity）値が 0 より大きい場合は 100% に変更されます。言い換えると、部分的に不透明なものはすべて完全に不透明になります。 |
| [AlphaFloor](./alphafloor/) | Alpha Floor エフェクトを表します。Alpha（opacity）値が 100% 未満の場合は 0 に変更されます。言い換えると、部分的に透明なものはすべて完全に透明になります。 |
| [AlphaInverse](./alphainverse/) | Alpha Inverse エフェクトを表します。Alpha（opacity）値は 100% から減算することで反転されます。 |
| [AlphaModulate](./alphamodulate/) | Alpha Modulate エフェクトを表します。エフェクトの Alpha（opacity）値は固定パーセンテージで乗算されます。エフェクト コンテナは、変調する Alpha 値を含むエフェクトを指定します。 |
| [AlphaModulateFixed](./alphamodulatefixed/) | Alpha Modulate Fixed エフェクトを表します。エフェクトの Alpha（opacity）値は固定パーセンテージで乗算されます。 |
| [AlphaReplace](./alphareplace/) | Alpha Replace エフェクトを表します。エフェクトの Alpha（opacity）値は固定の Alpha に置き換えられます。 |
| [BiLevel](./bilevel/) | Bi-Level（黒/白）エフェクトを表します。指定されたしきい値未満の輝度を持つ入力色は黒に変更され、しきい値以上の輝度を持つ入力色は白に設定されます。このエフェクトは Alpha のエフェクト値には影響しません。 |
| [Blur](./blur/) | [Blur](./blur/) エフェクトを表します。これは形状全体（塗りつぶしを含む）に適用されます。Alpha を含むすべてのカラーチャンネルが影響を受けます。 |
| [BrightnessContrast](./brightnesscontrast/) | [BrightnessContrast](./brightnesscontrast/) エフェクトを表します。明るさとコントラストを調整します。 |
| [ColorChange](./colorchange/) | Color Change エフェクトを表します。FromColor のインスタンスは ToColor のインスタンスに置き換えられます。 |
| [ColorReplace](./colorreplace/) | Color Replacement エフェクトを表します。すべてのエフェクトカラーは固定色に変更され、Alpha 値は影響を受けません。 |
| [Duotone](./duotone/) | [Duotone](./duotone/) エフェクトを表します。各ピクセルについて、線形補間により Color1 と Color2 を組み合わせ、新しいピクセルカラーを決定します。 |
| [EffectFactory](./effectfactory/) | エフェクトの作成が可能です。 |
| [FillOverlay](./filloverlay/) | Fill Overlay エフェクトを表します。フィル オーバーレイはオブジェクトに追加の塗りを指定し、2 つの塗りをブレンドするために使用できます。 |
| [Glow](./glow/) | [Glow](./glow/) エフェクトを表します。オブジェクトのエッジの外側にカラーのぼかしアウトラインが追加されます。 |
| [GrayScale](./grayscale/) | Gray Scale エフェクトを表します。すべてのエフェクトカラー値を輝度に対応したグレイの色調に変換します。エフェクトの Alpha（opacity）値は影響を受けません。 |
| [HSL](./hsl/) | Hue/Saturation/Luminance エフェクトを表します。色相、彩度、輝度はそれぞれ現在の値に対して調整できます。 |
| [IAlphaBiLevel](./ialphabilevel/) | Alpha Bi-Level エフェクトを表します。しきい値未満の Alpha（Opacity）値は 0（完全に透明）に変更され、しきい値以上の Alpha 値は 100%（完全に不透明）に変更されます。 |
| [IAlphaBiLevelEffectiveData](./ialphabileveleffectivedata/) | Alpha Bi-Level エフェクトを表す不変オブジェクトです。しきい値未満の Alpha（Opacity）値は 0（完全に透明）に変更され、しきい値以上の Alpha 値は 100%（完全に不透明）に変更されます。 |
| [IAlphaCeiling](./ialphaceiling/) | Alpha Ceiling エフェクトを表します。Alpha（opacity）値が 0 より大きい場合は 100% に変更されます。言い換えると、部分的に不透明なものはすべて完全に不透明になります。 |
| [IAlphaCeilingEffectiveData](./ialphaceilingeffectivedata/) | Alpha Ceiling エフェクトを表す不変オブジェクトです。Alpha（opacity）値が 0 より大きい場合は 100% に変更されます。言い換えると、部分的に不透明なものはすべて完全に不透明になります。 |
| [IAlphaFloor](./ialphafloor/) | Alpha Floor エフェクトを表します。Alpha（opacity）値が 100% 未満の場合は 0 に変更されます。言い換えると、部分的に透明なものはすべて完全に透明になります。 |
| [IAlphaFloorEffectiveData](./ialphaflooreffectivedata/) | Alpha Floor エフェクトを表す不変オブジェクトです。Alpha（opacity）値が 100% 未満の場合は 0 に変更されます。言い換えると、部分的に透明なものはすべて完全に透明になります。 |
| [IAlphaInverse](./ialphainverse/) | Alpha Inverse エフェクトを表します。Alpha（opacity）値は 100% から減算することで反転されます。 |
| [IAlphaInverseEffectiveData](./ialphainverseeffectivedata/) | Alpha Inverse エフェクトを表す不変オブジェクトです。Alpha（opacity）値は 100% から減算することで反転されます。 |
| [IAlphaModulate](./ialphamodulate/) | Alpha Modulate エフェクトを表します。エフェクトの Alpha（opacity）値は固定パーセンテージで乗算されます。エフェクト コンテナは、変調する Alpha 値を含むエフェクトを指定します。 |
| [IAlphaModulateEffectiveData](./ialphamodulateeffectivedata/) | Alpha Modulate エフェクトを表す不変オブジェクトです。エフェクトの Alpha（opacity）値は固定パーセンテージで乗算されます。エフェクト コンテナは、変調する Alpha 値を含むエフェクトを指定します。 |
| [IAlphaModulateFixed](./ialphamodulatefixed/) | Alpha Modulate Fixed エフェクトを表します。エフェクトの Alpha（opacity）値は固定パーセンテージで乗算されます。 |
| [IAlphaModulateFixedEffectiveData](./ialphamodulatefixedeffectivedata/) | Alpha Modulate Fixed エフェクトを表す不変オブジェクトです。エフェクトの Alpha（opacity）値は固定パーセンテージで乗算されます。 |
| [IAlphaReplace](./ialphareplace/) | [IImageTransformOperation](./iimagetransformoperation/) インターフェイスの基底を表します。 |
| [IAlphaReplaceEffectiveData](./ialphareplaceeffectivedata/) | Alpha Replace エフェクトを表す不変オブジェクトです。エフェクトの Alpha（opacity）値は固定の Alpha に置き換えられます。 |
| [IApplicableEffect](./iapplicableeffect/) |  |
| [IBiLevel](./ibilevel/) | [IImageTransformOperation](./iimagetransformoperation/) インターフェイスの基底を表します。 |
| [IBiLevelEffectiveData](./ibileveleffectivedata/) | Bi-Level（黒/白）エフェクトを表す不変オブジェクトです。指定されたしきい値未満の輝度を持つ入力色は黒に変更され、しきい値以上の輝度を持つ入力色は白に設定されます。このエフェクトは Alpha のエフェクト値には影響しません。 |
| [IBlur](./iblur/) | [Blur](./blur/) エフェクトを表します。これは形状全体（塗りつぶしを含む）に適用され、Alpha を含むすべてのカラーチャンネルが影響を受けます。 |
| [IBlurEffectiveData](./iblureffectivedata/) | [Blur](./blur/) エフェクトを表す不変オブジェクトです。これは形状全体（塗りつぶしを含む）に適用され、Alpha を含むすべてのカラーチャンネルが影響を受けます。 |
| [IBrightnessContrast](./ibrightnesscontrast/) | [BrightnessContrast](./brightnesscontrast/) エフェクトを表します。明るさとコントラストを調整します。 |
| [IBrightnessContrastEffectiveData](./ibrightnesscontrasteffectivedata/) | [BrightnessContrast](./brightnesscontrast/) エフェクトを表す不変オブジェクトです。明るさとコントラストを調整します。 |
| [IColorChange](./icolorchange/) | Color Change エフェクトを表します。FromColor のインスタンスは ToColor のインスタンスに置き換えられます。 |
| [IColorChangeEffectiveData](./icolorchangeeffectivedata/) | Color Change エフェクトを表す不変オブジェクトです。FromColor のインスタンスは ToColor のインスタンスに置き換えられます。 |
| [IColorReplace](./icolorreplace/) | Color Replacement エフェクトを表します。 |
| [IColorReplaceEffectiveData](./icolorreplaceeffectivedata/) | Color Replacement エフェクトを表す不変オブジェクトです。すべてのエフェクトカラーは固定色に変更され、Alpha 値は影響を受けません。 |
| [IDuotone](./iduotone/) | [Duotone](./duotone/) エフェクトを表します。 |
| [IDuotoneEffectiveData](./iduotoneeffectivedata/) | [Duotone](./duotone/) エフェクトを表す不変オブジェクトです。各ピクセルについて、線形補間により clr1 と clr2 を組み合わせ、新しいピクセルカラーを決定します。 |
| [IEffectEffectiveData](./ieffecteffectivedata/) | エフェクトを表す不変オブジェクトの基底クラスです。 |
| [IEffectFactory](./ieffectfactory/) | エフェクトのインスタンス作成が可能です。 |
| [IFillOverlay](./ifilloverlay/) | Fill Overlay エフェクトを表します。フィル オーバーレイはオブジェクトに追加の塗りを指定し、2 つの塗りをブレンドするために使用できます。 |
| [IFillOverlayEffectiveData](./ifilloverlayeffectivedata/) | Fill Overlay エフェクトを表す不変オブジェクトです。フィル オーバーレイはオブジェクトに追加の塗りを指定し、2 つの塗りをブレンドするために使用できます。 |
| [IGlow](./iglow/) | [Glow](./glow/) エフェクトを表します。オブジェクトのエッジの外側にカラーのぼかしアウトラインが追加されます。 |
| [IGlowEffectiveData](./igloweffectivedata/) | [Glow](./glow/) エフェクトを表す不変オブジェクトです。オブジェクトのエッジの外側にカラーのぼかしアウトラインが追加されます。 |
| [IGrayScale](./igrayscale/) | [IImageTransformOperation](./iimagetransformoperation/) インターフェイスを表します。 |
| [IGrayScaleEffectiveData](./igrayscaleeffectivedata/) | Gray Scale エフェクトを表す不変オブジェクトです。すべてのエフェクトカラー値を輝度に対応したグレイの色調に変換し、エフェクトの Alpha（opacity）値は影響を受けません。 |
| [IHSL](./ihsl/) | Hue/Saturation/Luminance エフェクトを表します。色相、彩度、輝度はそれぞれ現在の値に対して調整できます。 |
| [IHSLEffectiveData](./ihsleffectivedata/) | Hue/Saturation/Luminance エフェクトを表します。色相、彩度、輝度はそれぞれ現在の値に対して調整できます。 |
| [IImageTransformOCollectionEffectiveData](./iimagetransformocollectioneffectivedata/) | 効果的な画像変換エフェクトの読み取り専用コレクションを表す不変オブジェクトです。 |
| [IImageTransformOperation](./iimagetransformoperation/) | 抽象的な画像変換エフェクトを表します。 |
| [IImageTransformOperationCollection](./iimagetransformoperationcollection/) | 画像に適用されるエフェクトのコレクションを表します。 |
| [IImageTransformOperationFactory](./iimagetransformoperationfactory/) | 画像エフェクトのインスタンス作成が可能です。 |
| [IInnerShadow](./iinnershadow/) | 内側シャドウ エフェクトを表します。 |
| [IInnerShadowEffectiveData](./iinnershadoweffectivedata/) | 内側シャドウ エフェクトを表す不変オブジェクトです。 |
| [ILuminance](./iluminance/) | [Luminance](./luminance/) エフェクトを表します。明るさはすべての色を白または黒に線形にシフトさせ、コントラストはすべての色をより近くまたは遠くなるようにスケーリングします。 |
| [ILuminanceEffectiveData](./iluminanceeffectivedata/) | [Luminance](./luminance/) エフェクトを表します。明るさはすべての色を白または黒に線形にシフトさせ、コントラストはすべての色をより近くまたは遠くなるようにスケーリングします。 |
| [ImageTransformOCollectionEffectiveData](./imagetransformocollectioneffectivedata/) | 効果的な画像変換エフェクトの読み取り専用コレクションを表す不変オブジェクトです。 |
| [ImageTransformOperation](./imagetransformoperation/) | 抽象的な画像変換エフェクトを表します。 |
| [ImageTransformOperationCollection](./imagetransformoperationcollection/) | 画像に適用されるエフェクトのコレクションを表します。 |
| [ImageTransformOperationFactory](./imagetransformoperationfactory/) | 画像変換操作の作成が可能です。 |
| [InnerShadow](./innershadow/) | Inner Shadow エフェクトを表します。 |
| [IOuterShadow](./ioutershadow/) | Outer Shadow エフェクトを表します。 |
| [IOuterShadowEffectiveData](./ioutershadoweffectivedata/) | Outer Shadow エフェクトを表す不変オブジェクトです。 |
| [IPresetShadow](./ipresetshadow/) | Preset Shadow エフェクトを表します。 |
| [IPresetShadowEffectiveData](./ipresetshadoweffectivedata/) | Preset Shadow エフェクトを表す不変オブジェクトです。 |
| [IReflection](./ireflection/) | Reflection エフェクトを表します。 |
| [IReflectionEffectiveData](./ireflectioneffectivedata/) | [Reflection](./reflection/) エフェクトを表す不変オブジェクトです。 |
| [ISoftEdge](./isoftedge/) | Soft Edge エフェクトを表します。形状のエッジはぼかされますが、塗りは影響を受けません。 |
| [ISoftEdgeEffectiveData](./isoftedgeeffectivedata/) | Soft Edge エフェクトを表す不変オブジェクトです。形状のエッジはぼかされますが、塗りは影響を受けません。 |
| [ITint](./itint/) | [Tint](./tint/) エフェクトを表します。指定された量だけエフェクトのカラー値を色相へ/からシフトさせます。 |
| [ITintEffectiveData](./itinteffectivedata/) | [Tint](./tint/) エフェクトを表す不変オブジェクトです。指定された量だけエフェクトのカラー値を色相へ/からシフトさせます。 |
| [IVisualEffect](./ivisualeffect/) |  |
| [Luminance](./luminance/) | [Luminance](./luminance/) エフェクトを表します。明るさはすべての色を白または黒に線形にシフトさせ、コントラストはすべての色をより近くまたは遠くなるようにスケーリングします。 |
| [OuterShadow](./outershadow/) | Outer Shadow エフェクトを表します。 |
| [PresetShadow](./presetshadow/) | Preset Shadow エフェクトを表します。 |
| [Reflection](./reflection/) | [Reflection](./reflection/) エフェクトを表します。 |
| [SoftEdge](./softedge/) | Soft Edge エフェクトを表します。形状のエッジはぼかされますが、塗りは影響を受けません。 |
| [Tint](./tint/) | [Tint](./tint/) エフェクトを表します。指定された量だけエフェクトのカラー値を色相へ/からシフトさせます。 |