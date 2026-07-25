---
title: IEffect
second_title: Aspose.Slides for C++ API リファレンス
description: アニメーション効果を表します。
type: docs
weight: 248
url: /ja/aspose.slides.animation/ieffect/
---
## IEffect クラス

Represents animation effect.

```cpp
class IEffect : public virtual System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部使用のみです。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\> [get_AfterAnimationColor](./get_afteranimationcolor/)() | エフェクトの後のアニメーションカラーが定義されています。[IColorFormat](../../aspose.slides/icolorformat/) を読み取ります。 |
| virtual [Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/) [get_AfterAnimationType](./get_afteranimationtype/)() | エフェクトの後のアニメーションタイプが定義されています。[AfterAnimationType](../afteranimationtype/) を読み取ります。 |
| virtual [Aspose::Slides::Animation::AnimateTextType](../animatetexttype/) [get_AnimateTextType](./get_animatetexttype/)() | エフェクトのテキストアニメーションタイプを定義します。シェイプのテキストは文字単位、単語単位、または全体でアニメーション化できます。[AnimateTextType](../animatetexttype/) を読み取ります。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\> [get_Behavior](./get_behavior/)(**int32_t**) | 指定されたインデックスのアニメーションビヘイビアを返します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\> [get_Behaviors](./get_behaviors/)() | エフェクトのビヘイビアコレクションを返します。[IBehaviorCollection](../ibehaviorcollection/) を読み取ります。 |
| virtual **float** [get_DelayBetweenTextParts](./get_delaybetweentextparts/)() | アニメーションされたテキスト部分（単語または文字）の間の遅延を定義します。正の値はエフェクト期間の割合を指定し、負の値は秒単位の遅延を指定します。**float** を読み取ります。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffect](./)\> [get_Effect](./get_effect/)(**int32_t**) | 指定されたインデックスのシーケンスの影響を返します。 |
| virtual [EffectPresetClassType](../effectpresetclasstype/) [get_PresetClassType](./get_presetclasstype/)() | エフェクトのクラスを定義します。[EffectPresetClassType](../effectpresetclasstype/) を読み取ります。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISequence](../isequence/)\> [get_Sequence](./get_sequence/)() | エフェクトのシーケンスを返します。読み取り専用 [ISequence](../isequence/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() | エフェクトに埋め込まれたサウンドが定義されています。[IAudio](../../aspose.slides/iaudio/) を読み取ります。 |
| virtual **bool** [get_StopPreviousSound](./get_stopprevioussound/)() | この属性はアニメーションエフェクトが前のサウンドを停止するかどうかを指定します。**bool** を読み取ります。 |
| virtual [EffectSubtype](../effectsubtype/) [get_Subtype](./get_subtype/)() | エフェクトのサブタイプを定義します。[EffectSubtype](../effectsubtype/) を読み取ります。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [get_TargetShape](./get_targetshape/)() | エフェクトの対象シェイプを返します。読み取り専用 [IShape](../../aspose.slides/ishape/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextAnimation](../itextanimation/)\> [get_TextAnimation](./get_textanimation/)() | テキストアニメーションを返します。読み取り専用 [ITextAnimation](../itextanimation/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\> [get_Timing](./get_timing/)() | エフェクトのタイミング値を定義します。[ITiming](../itiming/) を読み取ります。 |
| virtual [EffectType](../effecttype/) [get_Type](./get_type/)() | エフェクトのタイプを定義します。[EffectType](../effecttype/) を読み取ります。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_AfterAnimationColor](./set_afteranimationcolor/)([System::SharedPtr](../../system/sharedptr/)\<[IColorFormat](../../aspose.slides/icolorformat/)\>) | エフェクトの後のアニメーションカラーが定義されています。[IColorFormat](../../aspose.slides/icolorformat/) に書き込みます。 |
| virtual void [set_AfterAnimationType](./set_afteranimationtype/)([Aspose::Slides::Animation::AfterAnimationType](../afteranimationtype/)) | エフェクトの後のアニメーションタイプが定義されています。[AfterAnimationType](../afteranimationtype/) に書き込みます。 |
| virtual void [set_AnimateTextType](./set_animatetexttype/)([Aspose::Slides::Animation::AnimateTextType](../animatetexttype/)) | エフェクトのテキストアニメーションタイプを定義します。シェイプのテキストは文字単位、単語単位、または全体でアニメーション化できます。[AnimateTextType](../animatetexttype/) に書き込みます。 |
| virtual void [set_Behavior](./set_behavior/)(**int32_t**, [System::SharedPtr](../../system/sharedptr/)\<[IBehavior](../ibehavior/)\>) | 指定されたインデックスのアニメーションビヘイビアを設定します。 |
| virtual void [set_Behaviors](./set_behaviors/)([System::SharedPtr](../../system/sharedptr/)\<[IBehaviorCollection](../ibehaviorcollection/)\>) | エフェクトのビヘイビアコレクションを返します。[IBehaviorCollection](../ibehaviorcollection/) に書き込みます。 |
| virtual void [set_DelayBetweenTextParts](./set_delaybetweentextparts/)(**float**) | アニメーションされたテキスト部分（単語または文字）の間の遅延を定義します。正の値はエフェクト期間の割合を指定し、負の値は秒単位の遅延を指定します。**float** に書き込みます。 |
| virtual void [set_PresetClassType](./set_presetclasstype/)([EffectPresetClassType](../effectpresetclasstype/)) | エフェクトのクラスを定義します。[EffectPresetClassType](../effectpresetclasstype/) に書き込みます。 |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) | エフェクトに埋め込まれたサウンドが定義されています。[IAudio](../../aspose.slides/iaudio/) に書き込みます。 |
| virtual void [set_StopPreviousSound](./set_stopprevioussound/)(**bool**) | この属性はアニメーションエフェクトが前のサウンドを停止するかどうかを指定します。**bool** に書き込みます。 |
| virtual void [set_Subtype](./set_subtype/)([EffectSubtype](../effectsubtype/)) | エフェクトのサブタイプを定義します。[EffectSubtype](../effectsubtype/) に書き込みます。 |
| virtual void [set_Timing](./set_timing/)([System::SharedPtr](../../system/sharedptr/)\<[ITiming](../itiming/)\>) | エフェクトのタイミング値を定義します。[ITiming](../itiming/) に書き込みます。 |
| virtual void [set_Type](./set_type/)([EffectType](../effecttype/)) | エフェクトのタイプを定義します。[EffectType](../effecttype/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を共有ポインタではなく弱ポインタに設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [Aspose::Slides::Animation](../)
* ライブラリ [Aspose.Slides](../../)