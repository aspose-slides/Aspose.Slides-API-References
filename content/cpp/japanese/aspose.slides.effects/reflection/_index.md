---
title: Reflection
second_title: Aspose.Slides for C++ API リファレンス
description: Reflection エフェクトを表します。
type: docs
weight: 1067
url: /ja/aspose.slides.effects/reflection/
---
## Reflection クラス

[Reflection](./) エフェクトを表します。

```cpp
class Reflection : public Aspose::Slides::Effects::IReflection,
                   public Aspose::Slides::Effects::IVisualEffect,
                   public Aspose::Slides::IPVIObject
```

## メソッド

| Method | Description |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 指定された [Reflection](./) が現在の [Reflection](./) と等しいかどうかを判断します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| **double** [get_BlurRadius](./get_blurradius/)() override | [Blur](../blur/) 半径。**double** を読み取ります。 |
| **float** [get_Direction](./get_direction/)() override | 反射の方向。**float** を読み取ります。 |
| **double** [get_Distance](./get_distance/)() override | 反射の距離。**double** を読み取ります。 |
| **float** [get_EndPosAlpha](./get_endposalpha/)() override | アルファ グラデーション ランプに沿った終端アルファ値（パーセント）の終端位置を指定します。**float** を読み取ります。 |
| **float** [get_EndReflectionOpacity](./get_endreflectionopacity/)() override | 終端反射不透明度（パーセント）。**float** を読み取ります。 |
| **float** [get_FadeDirection](./get_fadedirection/)() override | 反射をオフセットする方向（角度）を指定します。**float** を読み取ります。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../../aspose.slides/ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../../aspose.slides/ipviobject/get_parent_ipresentationcomponent/)() | 親 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/) を返します。読み取り専用 [IPresentationComponent](../../aspose.slides/ipresentationcomponent/)。 |
| [RectangleAlignment](../../aspose.slides/rectanglealignment/) [get_RectangleAlign](./get_rectanglealign/)() override | 矩形の配置。[RectangleAlignment](../../aspose.slides/rectanglealignment/) を読み取ります。 |
| **bool** [get_RotateShadowWithShape](./get_rotateshadowwithshape/)() override | シェイプが回転した場合に、反射がシェイプと共に回転すべきかどうかを指定します。**bool** を読み取ります。 |
| **double** [get_ScaleHorizontal](./get_scalehorizontal/)() override | 水平スケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセント）**double** を読み取ります。 |
| **double** [get_ScaleVertical](./get_scalevertical/)() override | 垂直スケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセント）**double** を読み取ります。 |
| **double** [get_SkewHorizontal](./get_skewhorizontal/)() override | 水平せん断角度を指定します。**double** を読み取ります。 |
| **double** [get_SkewVertical](./get_skewvertical/)() override | 垂直せん断角度を指定します。**double** を読み取ります。 |
| **float** [get_StartPosAlpha](./get_startposalpha/)() override | アルファ グラデーション ランプに沿った開始アルファ値（パーセント）の開始位置を指定します。**float** を読み取ります。 |
| **float** [get_StartReflectionOpacity](./get_startreflectionopacity/)() override | 開始反射不透明度（パーセント）。**float** を読み取ります。 |
| virtual ASPOSE_SLIDES_LOCAL_API **uint32_t** [get_Version](../../aspose.slides/ipviobject/get_version/)() | バージョン。読み取り専用 **uint32_t**。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IReflectionEffectiveData](../ireflectioneffectivedata/)\> [GetEffective](./geteffective/)() override | 継承が適用された有効な [Reflection](./) エフェクトデータを取得します。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 特定の型に対するハッシュ関数として機能します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネル オブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピー コンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースの特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_BlurRadius](./set_blurradius/)(**double**) override | [Blur](../blur/) 半径。**double** を書き込みます。 |
| void [set_Direction](./set_direction/)(**float**) override | 反射の方向。**float** を書き込みます。 |
| void [set_Distance](./set_distance/)(**double**) override | 反射の距離。**double** を書き込みます。 |
| void [set_EndPosAlpha](./set_endposalpha/)(**float**) override | アルファ グラデーション ランプに沿った終端アルファ値（パーセント）の終端位置を指定します。**float** を書き込みます。 |
| void [set_EndReflectionOpacity](./set_endreflectionopacity/)(**float**) override | 終端反射不透明度（パーセント）。**float** を書き込みます。 |
| void [set_FadeDirection](./set_fadedirection/)(**float**) override | 反射をオフセットする方向（角度）を指定します。**float** を書き込みます。 |
| void [set_RectangleAlign](./set_rectanglealign/)([RectangleAlignment](../../aspose.slides/rectanglealignment/)) override | 矩形の配置。[RectangleAlignment](../../aspose.slides/rectanglealignment/) に書き込みます。 |
| void [set_RotateShadowWithShape](./set_rotateshadowwithshape/)(**bool**) override | シェイプが回転した場合に、反射がシェイプと共に回転すべきかどうかを指定します。**bool** を書き込みます。 |
| void [set_ScaleHorizontal](./set_scalehorizontal/)(**double**) override | 水平スケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセント）**double** を書き込みます。 |
| void [set_ScaleVertical](./set_scalevertical/)(**double**) override | 垂直スケーリング係数を指定します。負のスケーリングは反転を引き起こします。（パーセント）**double** を書き込みます。 |
| void [set_SkewHorizontal](./set_skewhorizontal/)(**double**) override | 水平せん断角度を指定します。**double** を書き込みます。 |
| void [set_SkewVertical](./set_skewvertical/)(**double**) override | 垂直せん断角度を指定します。**double** を書き込みます。 |
| void [set_StartPosAlpha](./set_startposalpha/)(**float**) override | アルファ グラデーション ランプに沿った開始アルファ値（パーセント）の開始位置を指定します。**float** を書き込みます。 |
| void [set_StartReflectionOpacity](./set_startreflectionopacity/)(**float**) override | 開始反射不透明度（パーセント）。**float** を書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタに設定します（共有ではなく）。コンテナ内のポインタを弱いモードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマート ポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマート ポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネル オブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマート ポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマート ポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
## 参照

* クラス [IReflection](../ireflection/)
* クラス [IVisualEffect](../ivisualeffect/)
* クラス [IPVIObject](../../aspose.slides/ipviobject/)
* 名前空間 [Aspose::Slides::Effects](../)
* ライブラリ [Aspose.Slides](../../)