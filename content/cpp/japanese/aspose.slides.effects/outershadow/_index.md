---
title: OuterShadow
second_title: Aspose.Slides for C++ API リファレンス
description: Outer Shadow エフェクトを表します。
type: docs
weight: 1041
url: /ja/aspose.slides.effects/outershadow/
---
## OuterShadow クラス

Outer Shadow エフェクトを表します。

```cpp
class OuterShadow : public Aspose::Slides::Effects::IOuterShadow,
                    public Aspose::Slides::Effects::IVisualEffect,
                    public Aspose::Slides::IPVIObject
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 指定された [OuterShadow](./) が現在の [OuterShadow](./) と等しいかどうかを判断します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) 半径（ポイント単位）。デフォルト値 – 0 pt。読み取り **double**。 |
| **float** [get_Direction](./get_direction/)() override | 影の方向（度単位）。デフォルト値 – 0 °（左から右）。読み取り **float**。 |
| **double** [get_Distance](./get_distance/)() override | 影がオブジェクトから離れる距離（ポイント単位）。デフォルト値 – 0 pt。読み取り **double**。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | 親 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) を返します。読み取り専用 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)。 |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | 矩形の配置。デフォルト値 – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/)。読み取り [RectangleAlignment](../../aspose.slides/rectanglealignment/)。 |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | 影がシェイプと共に回転するかどうかを示します。デフォルト値 – true。読み取り **bool**。 |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | 元のサイズに対するパーセンテージで表した水平スケーリング係数。負のスケーリングは反転を引き起こします。デフォルト値 – 100%。読み取り **double**。 |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | 元のサイズに対するパーセンテージで表した垂直スケーリング係数。負のスケーリングは反転を引き起こします。デフォルト値 – 100%。読み取り **double**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_ShadowColor](./get_shadowcolor/)() override | 影の色。デフォルト値 – 自動黒（テーマ依存）。読み取り専用 [IColorFormat](../../aspose.slides/icolorformat/)。 |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | 水平せん断角度（度単位）。デフォルト値 – 0 °。読み取り **double**。 |
| **double** [get_SkewVertical](./get_skewvertical/)() override | 垂直せん断角度（度単位）。デフォルト値 – 0 °。読み取り **double**。 |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | バージョン。読み取り専用 **uint32_t**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IOuterShadowEffectiveData](../ioutershadoweffectivedata/)\> [GetEffective](./geteffective/)() override | 継承が適用された有効な Outer Shadow エフェクトデータを取得します。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 特定の型に対するハッシュ関数として機能します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合に対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合に対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウンタを減少させます。 |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) 半径（ポイント単位）。デフォルト値 – 0 pt。書き込み **double**。 |
| void [set_Direction](./set_direction/)(**float**) override | 影の方向（度単位）。デフォルト値 – 0 °（左から右）。書き込み **float**。 |
| void [set_Distance](./set_distance/)(**double**) override | 影がオブジェクトから離れる距離（ポイント単位）。デフォルト値 – 0 pt。書き込み **double**。 |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | 矩形の配置。デフォルト値 – [RectangleAlignment::Bottom](../../aspose.slides/rectanglealignment/)。書き込み [RectangleAlignment](../../aspose.slides/rectanglealignment/)。 |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | 影がシェイプと共に回転するかどうかを示します。デフォルト値 – true。書き込み **bool**。 |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | 水平スケーリング係数（元のサイズに対するパーセンテージ）。負のスケーリングは反転を引き起こします。デフォルト値 – 100%。書き込み **double**。 |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | 垂直スケーリング係数（元のサイズに対するパーセンテージ）。負のスケーリングは反転を引き起こします。デフォルト値 – 100%。書き込み **double**。 |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | 水平せん断角度（度単位）。デフォルト値 – 0 °。書き込み **double**。 |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | 垂直せん断角度（度単位）。デフォルト値 – 0 °。書き込み **double**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウンタをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウンタをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウンタをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウンタをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IOuterShadow](../ioutershadow/)
* クラス [IVisualEffect](../ivisualeffect/)
* クラス [IPVIObject](../../aspose.slides/ipviobject/)
* 名前空間 [Aspose::Slides::Effects](../)
* ライブラリ [Aspose.Slides](../../)