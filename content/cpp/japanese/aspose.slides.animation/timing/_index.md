---
title: Timing
second_title: Aspose.Slides for C++ API リファレンス
description: アニメーションのタイミングを表します。
type: docs
weight: 625
url: /ja/aspose.slides.animation/timing/
---
## Timing クラス

Represents animation timing.

```cpp
class Timing : public Aspose::Slides::Animation::ITiming,
               public Aspose::Slides::IDOMObject
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| **float** [get_Accelerate](./get_accelerate/)() override | 加速動作効果の継続時間のパーセンテージを示します。**float** を読み取ります。 |
| **bool** [get_AutoReverse](./get_autoreverse/)() override | 正方向に再生した後、アニメーションを自動的に逆再生するかどうかを示します。**bool** を読み取ります。 |
| **float** [get_Decelerate](./get_decelerate/)() override | 減速動作効果の継続時間のパーセンテージを示します。**float** を読み取ります。 |
| **float** [get_Duration](./get_duration/)() override | アニメーション効果の継続時間を示します。**float** を読み取ります。 |
| **float** [get_RepeatCount](./get_repeatcount/)() override | 効果が繰り返される回数を示します。**float** を読み取ります。 |
| **float** [get_RepeatDuration](./get_repeatduration/)() override | 効果が繰り返される回数を示します。**float** を読み取ります。 |
| **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() override | この属性は効果がスライドの最後まで繰り返されるかどうかを指定します。**bool** を読み取ります。 |
| **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() override | この属性は効果が次のクリックまで繰り返されるかどうかを指定します。**bool** を読み取ります。 |
| [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() override | 効果が完了後に再起動するかどうかを指定します。[EffectRestartType](../effectrestarttype/) を読み取ります。 |
| **bool** [get_Rewind](./get_rewind/)() override | この属性は効果が再生完了時に巻き戻されるかどうかを指定します。**bool** を読み取ります。 |
| **float** [get_Speed](./get_speed/)() override | タイミングを速め（または遅く）する割合のパーセンテージを指定します。**float** を読み取ります。 |
| **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() override | トリガー後の遅延時間を示します。**float** を読み取ります。 |
| [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() override | トリガータイプを示します。[EffectTriggerType](../effecttriggertype/) を読み取ります。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_Accelerate](./set_accelerate/)(**float**) override | 加速動作効果の継続時間のパーセンテージを示します。**float** を書き込みます。 |
| void [set_AutoReverse](./set_autoreverse/)(**bool**) override | 正方向に再生した後、アニメーションを自動的に逆再生するかどうかを示します。**bool** を書き込みます。 |
| void [set_Decelerate](./set_decelerate/)(**float**) override | 減速動作効果の継続時間のパーセンテージを示します。**float** を書き込みます。 |
| void [set_Duration](./set_duration/)(**float**) override | アニメーション効果の継続時間を示します。**float** を書き込みます。 |
| void [set_RepeatCount](./set_repeatcount/)(**float**) override | 効果が繰り返される回数を示します。**float** を書き込みます。 |
| void [set_RepeatDuration](./set_repeatduration/)(**float**) override | 効果が繰り返される回数を示します。**float** を書き込みます。 |
| void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) override | この属性は効果がスライドの最後まで繰り返されるかどうかを指定します。**bool** を書き込みます。 |
| void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) override | この属性は効果が次のクリックまで繰り返されるかどうかを指定します。**bool** を書き込みます。 |
| void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) override | 効果が完了後に再起動するかどうかを指定します。[EffectRestartType](../effectrestarttype/) を書き込みます。 |
| void [set_Rewind](./set_rewind/)(**bool**) override | この属性は効果が再生完了時に巻き戻されるかどうかを指定します。**bool** を書き込みます。 |
| void [set_Speed](./set_speed/)(**float**) override | タイミングを速め（または遅く）する割合のパーセンテージを指定します。**float** を書き込みます。 |
| void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) override | トリガー後の遅延時間を示します。**float** を書き込みます。 |
| void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) override | トリガータイプを示します。[EffectTriggerType](../effecttriggertype/) を書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、代わりにスマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換することができます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、代わりにスマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [ITiming](../itiming/)
* クラス [IDOMObject](../../aspose.slides/idomobject/)
* 名前空間 [Aspose::Slides::Animation](../)
* ライブラリ [Aspose.Slides](../../)