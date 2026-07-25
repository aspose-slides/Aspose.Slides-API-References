---
title: IOuterShadow
second_title: Aspose.Slides for C++ API リファレンス
description: 外部シャドウ効果を表します。
type: docs
weight: 885
url: /ja/aspose.slides.effects/ioutershadow/
---
## IOuterShadow クラス

外部シャドウ効果を表します。

```cpp
class IOuterShadow : public virtual Aspose::Slides::Effects::IImageTransformOperation,
                     public Aspose::Slides::IAccessiblePVIObject<System::SharedPtr<Aspose::Slides::Effects::IOuterShadowEffectiveData>>
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）に等しくないにもかかわらず、2 つの NaN を等しいと見なす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）に等しくないにもかかわらず、2 つの NaN を等しいと見なす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的専用です。 |
| virtual **double** [get_BlurRadius](./get_blurradius/)() | [Blur](../blur/) 半径（ポイント単位）。デフォルト値 \u2013 0 pt。読み取り **double**。 |
| virtual **float** [get_Direction](./get_direction/)() | シャドウの方向（度単位）。デフォルト値 \u2013 0 \u00B0（左から右）。読み取り **float**。 |
| virtual **double** [get_Distance](./get_distance/)() | オブジェクトからのシャドウの距離（ポイント単位）。デフォルト値 \u2013 0 pt。読み取り **double**。 |
| virtual [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() | 矩形の配置。デフォルト値 \u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/)。読み取り [RectangleAlignment](../../aspose.slides/rectanglealignment/)。 |
| virtual **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() | シャドウがシェイプと共に回転するかどうかを示します。デフォルト値 \u2013 true。読み取り **bool**。 |
| virtual **double** [get_ScaleHorizontal](./get_scalehorizontal/)() | 元サイズのパーセンテージで表した水平スケーリング係数。負のスケーリングは反転を引き起こします。デフォルト値 \u2013 100%。読み取り **double**。 |
| virtual **double** [get_ScaleVertical](./get_scalevertical/)() | 元サイズのパーセンテージで表した垂直スケーリング係数。負のスケーリングは反転を引き起こします。デフォルト値 \u2013 100%。読み取り **double**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() | シャドウの色。デフォルト値 \u2013 自動黒（テーマ依存）。読み取り専用 [IColorFormat](../../aspose.slides/icolorformat/)。 |
| virtual **double** [get_SkewHorizontal](./get_skewhorizontal/)() | 水平せん断角度（度単位）。デフォルト値 \u2013 0 \u00B0。読み取り **double**。 |
| virtual **double** [get_SkewVertical](./get_skewvertical/)() | 垂直せん断角度（度単位）。デフォルト値 \u2013 0 \u00B0。読み取り **double**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual T [GetEffective](../../aspose.slides/iaccessiblepviobject/geteffective/)() | 継承を適用した有効なデータを取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_BlurRadius](./set_blurradius/)(**double**) | [Blur](../blur/) 半径（ポイント単位）。デフォルト値 \u2013 0 pt。書き込み **double**。 |
| virtual void [set_Direction](./set_direction/)(**float**) | シャドウの方向（度単位）。デフォルト値 \u2013 0 \u00B0（左から右）。書き込み **float**。 |
| virtual void [set_Distance](./set_distance/)(**double**) | オブジェクトからのシャドウの距離（ポイント単位）。デフォルト値 \u2013 0 pt。書き込み **double**。 |
| virtual void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) | 矩形の配置。デフォルト値 \u2013 [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/)。書き込み [RectangleAlignment](../../aspose.slides/rectanglealignment/)。 |
| virtual void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) | シャドウがシェイプと共に回転するかどうかを示します。デフォルト値 \u2013 true。書き込み **bool**。 |
| virtual void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) | 元サイズのパーセンテージで表した水平スケーリング係数。負のスケーリングは反転を引き起こします。デフォルト値 \u2013 100%。書き込み **double**。 |
| virtual void [set_ScaleVertical](./set_scalevertical/)(**double**) | 元サイズのパーセンテージで表した垂直スケーリング係数。負のスケーリングは反転を引き起こします。デフォルト値 \u2013 100%。書き込み **double**。 |
| virtual void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) | 水平せん断角度（度単位）。デフォルト値 \u2013 0 \u00B0。書き込み **double**。 |
| virtual void [set_SkewVertical](./set_skewvertical/)(**double**) | 垂直せん断角度（度単位）。デフォルト値 \u2013 0 \u00B0。書き込み **double**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n'th テンプレート引数を弱ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることが可能です。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IImageTransformOperation](../iimagetransformoperation/)
* クラス [IAccessiblePVIObject](../../aspose.slides/iaccessiblepviobject/)
* 名前空間 [Aspose::Slides::Effects](../)
* ライブラリ [Aspose.Slides](../../)