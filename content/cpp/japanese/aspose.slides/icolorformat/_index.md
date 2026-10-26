---
title: IColorFormat
second_title: Aspose.Slides for C++ APIリファレンス
description: プレゼンテーションで使用される色を表します。
type: docs
weight: 1691
url: /ja/aspose.slides/icolorformat/
---
## IColorFormat クラス


プレゼンテーションで使用される色を表します。

```cpp
class IColorFormat : public Aspose::Slides::IFillParamSource
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual void [CopyFrom](./copyfrom/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](./)\>) | \"color\" からカラー形式をコピーします。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| virtual **uint8_t** [get_B](./get_b/)() | 色の青成分を返します。すべての色変換は無視されます。読み取り **uint8_t**。 |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_Color](./get_color/)() | すべての色変換が適用された結果の色を返します。RGB 色を設定し、すべての色変換をクリアします。読み取り [System::Drawing::Color](../../system.drawing/color/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\> [get_ColorOperation](./get_coloroperation/)(**int32_t**) | 指定されたインデックスの色に適用された色変換操作を返します。読み取り/書き込み [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorOperationCollection](../icoloroperationcollection/)\> [get_ColorTransform](./get_colortransform/)() | 色に適用された色変換のコレクションを返します。読み取り専用 [IColorOperationCollection](../icoloroperationcollection/)。 |
| virtual [Aspose::Slides::ColorType](../colortype/) [get_ColorType](./get_colortype/)() | 色定義方法を返します。読み取り [Slides::ColorType](../colortype/)。 |
| virtual **float** [get_FloatB](./get_floatb/)() | 色の青成分を返します。すべての色変換は無視されます。読み取り **float**。 |
| virtual **float** [get_FloatG](./get_floatg/)() | 色の緑成分を返します。すべての色変換は無視されます。読み取り **float**。 |
| virtual **float** [get_FloatR](./get_floatr/)() | 色の赤成分を返します。すべての色変換は無視されます。読み取り **float**。 |
| virtual **uint8_t** [get_G](./get_g/)() | 色の緑成分を返します。すべての色変換は無視されます。読み取り **uint8_t**。 |
| virtual **float** [get_Hue](./get_hue/)() | HSL 表現における色相成分を返します。すべての色変換は無視されます。読み取り **float**。 |
| virtual **float** [get_Luminance](./get_luminance/)() | HSL 表現における輝度成分を返します。すべての色変換は無視されます。読み取り **float**。 |
| virtual [Aspose::Slides::PresetColor](../presetcolor/) [get_PresetColor](./get_presetcolor/)() | カラープリセットを返します。読み取り [Slides::PresetColor](../presetcolor/)。 |
| virtual **uint8_t** [get_R](./get_r/)() | 色の赤成分を返します。すべての色変換は無視されます。読み取り **uint8_t**。 |
| virtual **float** [get_Saturation](./get_saturation/)() | HSL 表現における彩度成分を返します。すべての色変換は無視されます。読み取り **float**。 |
| virtual [Aspose::Slides::SchemeColor](../schemecolor/) [get_SchemeColor](./get_schemecolor/)() | カラースキームで識別された色を返します。読み取り [Slides::SchemeColor](../schemecolor/)。 |
| virtual [Aspose::Slides::SystemColor](../systemcolor/) [get_SystemColor](./get_systemcolor/)() | システムカラー表で識別された色を返します。読み取り [Slides::SystemColor](../systemcolor/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_B](./set_b/)(**uint8_t**) | 色の青成分を設定します。すべての色変換は無視されます。書き込み **uint8_t**。 |
| virtual void [set_Color](./set_color/)([System::Drawing::Color](../../system.drawing/color/)) | すべての色変換が適用された結果の色を返します。RGB 色を設定し、すべての色変換をクリアします。書き込み [System::Drawing::Color](../../system.drawing/color/)。 |
| virtual void [set_ColorOperation](./set_coloroperation/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IColorOperation](../icoloroperation/)\>) | 指定されたインデックスの色に適用する色変換操作を設定します。読み取り/書き込み [Aspose::Slides::IColorOperation](../icoloroperation/) |
| virtual void [set_ColorType](./set_colortype/)([Aspose::Slides::ColorType](../colortype/)) | 色定義方法を設定します。書き込み [Slides::ColorType](../colortype/)。 |
| virtual void [set_FloatB](./set_floatb/)(**float**) | 色の青成分を設定します。すべての色変換は無視されます。書き込み **float**。 |
| virtual void [set_FloatG](./set_floatg/)(**float**) | 色の緑成分を設定します。すべての色変換は無視されます。書き込み **float**。 |
| virtual void [set_FloatR](./set_floatr/)(**float**) | 色の赤成分を設定します。すべての色変換は無視されます。書き込み **float**。 |
| virtual void [set_G](./set_g/)(**uint8_t**) | 色の緑成分を設定します。すべての色変換は無視されます。書き込み **uint8_t**。 |
| virtual void [set_Hue](./set_hue/)(**float**) | HSL 表現における色相成分を設定します。すべての色変換は無視されます。書き込み **float**。 |
| virtual void [set_Luminance](./set_luminance/)(**float**) | HSL 表現における輝度成分を設定します。すべての色変換は無視されます。書き込み **float**。 |
| virtual void [set_PresetColor](./set_presetcolor/)([Aspose::Slides::PresetColor](../presetcolor/)) | カラープリセットを設定します。書き込み [Slides::PresetColor](../presetcolor/)。 |
| virtual void [set_R](./set_r/)(**uint8_t**) | 色の赤成分を設定します。すべての色変換は無視されます。書き込み **uint8_t**。 |
| virtual void [set_Saturation](./set_saturation/)(**float**) | HSL 表現における彩度成分を設定します。すべての色変換は無視されます。書き込み **float**。 |
| virtual void [set_SchemeColor](./set_schemecolor/)([Aspose::Slides::SchemeColor](../schemecolor/)) | カラースキームで識別された色を設定します。書き込み [Slides::SchemeColor](../schemecolor/)。 |
| virtual void [set_SystemColor](./set_systemcolor/)([Aspose::Slides::SystemColor](../systemcolor/)) | システムカラー表で識別された色を設定します。書き込み [Slides::SystemColor](../systemcolor/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [System::String](../../system/string/) [ToString](./tostring/)([ColorStringFormat](../colorstringformat/)) | 現在のカラー形式を表す [System::String](../../system/string/) を返します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換することができます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IFillParamSource](../ifillparamsource/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)