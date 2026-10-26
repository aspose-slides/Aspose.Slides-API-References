---
title: ColorFormat
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションで使用される色を表します。
type: docs
weight: 339
url: /ja/aspose.slides/colorformat/
---
## ColorFormat クラス

プレゼンテーションで使用される色を表します。

```cpp
class ColorFormat : public Aspose::Slides::PVIObject,
                    public Aspose::Slides::IColorFormat
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../icolorformat/)\>) override | \"color\" からカラー形式をコピーします。 |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 指定されたオブジェクトと等価かどうかをチェックします。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用です。 |
| **uint8_t** [get_B](./get_b/)() override | 色の青成分を返します。すべての色変換は無視されます。**uint8_t** を読み取ります。 |
| [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() override | すべての色変換が適用された結果の色を返します。RGB 色を設定し、すべての色変換をクリアします。[System::Drawing::Color](../../system.drawing/color/) を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) override | 指定したインデックスの色に適用された色変換操作を返します。読み取り/書き込み [Aspose::Slides::IColorOperation](../icoloroperation/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() override | 色に適用された色変換のコレクションを返します。読み取り専用 [IColorOperationCollection](../icoloroperationcollection/)。 |
| [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() override | 色定義方法を返します。[Slides::ColorType](../colortype/) を読み取ります。 |
| **float** [get_FloatB](./get_floatb/)() override | 色の青成分を返します。すべての色変換は無視されます。**float** を読み取ります。 |
| **float** [get_FloatG](./get_floatg/)() override | 色の緑成分を返します。すべての色変換は無視されます。**float** を読み取ります。 |
| **float** [get_FloatR](./get_floatr/)() override | 色の赤成分を返します。すべての色変換は無視されます。**float** を読み取ります。 |
| **uint8_t** [get_G](./get_g/)() override | 色の緑成分を返します。すべての色変換は無視されます。 |
| **float** [get_Hue](./get_hue/)() override | HSL 表現の色の色相成分を返します。すべての色変換は無視されます。**float** を読み取ります。 |
| **float** [get_Luminance](./get_luminance/)() override | HSL 表現の色の輝度成分を返します。すべての色変換は無視されます。**float** を読み取ります。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IDOMObject](../idomobject/)\> [get_Parent_Immediate](../idomobject/get_parent_immediate/)() | Parent_Immediate オブジェクトを返します。読み取り専用 [IDOMObject](../idomobject/)。 |
| virtual ASPOSE_SLIDES_LOCAL_API [System::SharedPtr](../../system/sharedptr/)\<[IPresentationComponent](../ipresentationcomponent/)\> [get_Parent_IPresentationComponent](../ipviobject/get_parent_ipresentationcomponent/)() | 親 [IPresentationComponent](../ipresentationcomponent/) を返します。読み取り専用 [IPresentationComponent](../ipresentationcomponent/)。 |
| [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() override | 色プリセットを返します。[Slides::PresetColor](../presetcolor/) を読み取ります。 |
| **uint8_t** [get_R](./get_r/)() override | 色の赤成分を返します。すべての色変換は無視されます。**uint8_t** を読み取ります。 |
| **float** [get_Saturation](./get_saturation/)() override | HSL 表現の色の彩度成分を返します。すべての色変換は無視されます。**float** を読み取ります。 |
| [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() override | カラースキームで識別された色を返します。[Slides::SchemeColor](../schemecolor/) を読み取ります。 |
| [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() override | システムカラーテーブルで識別された色を返します。[Slides::SystemColor](../systemcolor/) を読み取ります。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | ハッシュコードを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値で共有参照カウントを減少させます。 |
| void [set_B](./set_b/)(**uint8_t**) override | 色の青成分を設定します。すべての色変換は無視されます。**uint8_t** に書き込みます。 |
| void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) override | すべての色変換が適用された結果の色を返します。RGB 色を設定し、すべての色変換をクリアします。[System::Drawing::Color](../../system.drawing/color/) に書き込みます。 |
| void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) override | 指定したインデックスの色に適用された色変換操作を設定します。読み取り/書き込み [Aspose::Slides::IColorOperation](../icoloroperation/) |
| void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) override | 色定義方法を設定します。[Slides::ColorType](../colortype/) に書き込みます。 |
| void [set_FloatB](./set_floatb/)(**float**) override | 色の青成分を設定します。すべての色変換は無視されます。**float** に書き込みます。 |
| void [set_FloatG](./set_floatg/)(**float**) override | 色の緑成分を設定します。すべての色変換は無視されます。**float** に書き込みます。 |
| void [set_FloatR](./set_floatr/)(**float**) override | 色の赤成分を設定します。すべての色変換は無視されます。**float** に書き込みます。 |
| void [set_G](./set_g/)(**uint8_t**) override | 色の緑成分を設定します。すべての色変換は無視されます。 |
| void [set_Hue](./set_hue/)(**float**) override | HSL 表現の色相成分を設定します。すべての色変換は無視されます。**float** に書き込みます。 |
| void [set_Luminance](./set_luminance/)(**float**) override | HSL 表現の輝度成分を設定します。すべての色変換は無視されます。**float** に書き込みます。 |
| void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) override | 色プリセットを設定します。[Slides::PresetColor](../presetcolor/) に書き込みます。 |
| void [set_R](./set_r/)(**uint8_t**) override | 色の赤成分を設定します。すべての色変換は無視されます。**uint8_t** に書き込みます。 |
| void [set_Saturation](./set_saturation/)(**float**) override | HSL 表現の彩度成分を設定します。すべての色変換は無視されます。**float** に書き込みます。 |
| void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) override | カラースキームで識別された色を設定します。[Slides::SchemeColor](../schemecolor/) に書き込みます。 |
| void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) override | システムカラーテーブルで識別された色を設定します。[Slides::SystemColor](../systemcolor/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることが可能です。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) override | 現在のカラー形式を表す [System::String](../../system/string/) を返します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| ASPOSE_SLIDES_LOCAL_API void [WrapperLazyInitialization](../pviobject/wrapperlazyinitialization/)() const |  |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [PVIObject](../pviobject/)
* クラス [IColorFormat](../icolorformat/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)