---
title: ITiming
second_title: Aspose.Slides for C++ API リファレンス
description: アニメーションのタイミングを表します。
type: docs
weight: 443
url: /ja/aspose.slides.animation/itiming/
---
## ITiming クラス

アニメーションのタイミングを表します。

```cpp
class ITiming : public virtual System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual **float** [get_Accelerate](./get_accelerate/)() | 加速動作効果の期間のパーセンテージを表します。**float** を読み取ります。 |
| virtual **bool** [get_AutoReverse](./get_autoreverse/)() | 前方向に再生した後、アニメーションを自動的に逆再生するかどうかを表します。**bool** を読み取ります。 |
| virtual **float** [get_Decelerate](./get_decelerate/)() | 減速動作効果の期間のパーセンテージを表します。**float** を読み取ります。 |
| virtual **float** [get_Duration](./get_duration/)() | アニメーション効果の期間を表します。**float** を読み取ります。 |
| virtual **float** [get_RepeatCount](./get_repeatcount/)() | 効果を繰り返す回数を表します。**float** を読み取ります。 |
| virtual **float** [get_RepeatDuration](./get_repeatduration/)() | 効果を繰り返す回数を表します。**float** を読み取ります。 |
| virtual **bool** [get_RepeatUntilEndSlide](./get_repeatuntilendslide/)() | この属性は、効果がスライドの最後まで繰り返されるかどうかを指定します。**bool** を読み取ります。 |
| virtual **bool** [get_RepeatUntilNextClick](./get_repeatuntilnextclick/)() | この属性は、効果が次のクリックまで繰り返されるかどうかを指定します。**bool** を読み取ります。 |
| virtual [EffectRestartType](../effectrestarttype/) [get_Restart](./get_restart/)() | 効果が完了した後に再開するかどうかを指定します。[EffectRestartType](../effectrestarttype/) を読み取ります。 |
| virtual **bool** [get_Rewind](./get_rewind/)() | この属性は、再生が終了したときに効果を巻き戻すかどうかを指定します。**bool** を読み取ります。 |
| virtual **float** [get_Speed](./get_speed/)() | タイミングを加速（または減速）させるパーセンテージを指定します。**float** を読み取ります。 |
| virtual **float** [get_TriggerDelayTime](./get_triggerdelaytime/)() | トリガー後の遅延時間を表します。**float** を読み取ります。 |
| virtual [EffectTriggerType](../effecttriggertype/) [get_TriggerType](./get_triggertype/)() | トリガーの種類を表します。[EffectTriggerType](../effecttriggertype/) を読み取ります。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_Accelerate](./set_accelerate/)(**float**) | 加速動作効果の期間のパーセンテージを記述します。**float** に書き込みます。 |
| virtual void [set_AutoReverse](./set_autoreverse/)(**bool**) | 前方向に再生した後、アニメーションを自動的に逆再生するかどうかを記述します。**bool** に書き込みます。 |
| virtual void [set_Decelerate](./set_decelerate/)(**float**) | 減速動作効果の期間のパーセンテージを記述します。**float** に書き込みます。 |
| virtual void [set_Duration](./set_duration/)(**float**) | アニメーション効果の期間を記述します。**float** に書き込みます。 |
| virtual void [set_RepeatCount](./set_repeatcount/)(**float**) | 効果を繰り返す回数を記述します。**float** に書き込みます。 |
| virtual void [set_RepeatDuration](./set_repeatduration/)(**float**) | 効果を繰り返す回数を記述します。**float** に書き込みます。 |
| virtual void [set_RepeatUntilEndSlide](./set_repeatuntilendslide/)(**bool**) | この属性は、効果がスライドの最後まで繰り返されるかどうかを指定します。**bool** に書き込みます。 |
| virtual void [set_RepeatUntilNextClick](./set_repeatuntilnextclick/)(**bool**) | この属性は、効果が次のクリックまで繰り返されるかどうかを指定します。**bool** に書き込みます。 |
| virtual void [set_Restart](./set_restart/)([EffectRestartType](../effectrestarttype/)) | 効果が完了した後に再開するかどうかを指定します。[EffectRestartType](../effectrestarttype/) に書き込みます。 |
| virtual void [set_Rewind](./set_rewind/)(**bool**) | この属性は、再生が終了したときに効果を巻き戻すかどうかを指定します。**bool** に書き込みます。 |
| virtual void [set_Speed](./set_speed/)(**float**) | タイミングを加速（または減速）させるパーセンテージを指定します。**float** に書き込みます。 |
| virtual void [set_TriggerDelayTime](./set_triggerdelaytime/)(**float**) | トリガー後の遅延時間を記述します。**float** に書き込みます。 |
| virtual void [set_TriggerType](./set_triggertype/)([EffectTriggerType](../effecttriggertype/)) | トリガーの種類を記述します。[EffectTriggerType](../effecttriggertype/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
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

* クラス [Object](../../system/object/)
* 名前空間 [Aspose::Slides::Animation](../)
* ライブラリ [Aspose.Slides](../../)