---
title: SlideShowTransition
second_title: Aspose.Slides for C++ API リファレンス
description: スライドショー遷移を表します。
type: docs
weight: 404
url: /ja/aspose.slides.slideshow/slideshowtransition/
---
## SlideShowTransition クラス

Represents slide show transition.

```cpp
class SlideShowTransition : public Aspose::Slides::DomObject<System::SharedPtr<Aspose::Slides::BaseSlide>>,
                            public Aspose::Slides::ISlideShowTransition
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| **bool** [Equals](./equals/)([System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | [SlideShowTransition](./) の 2 つのインスタンスが等しいかどうかを判定します。読み書き **bool**。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| **bool** [get_AdvanceAfter](./get_advanceafter/)() override | この属性は、スライドショーが一定時間後に次のスライドに移動するかどうかを指定します。読み取り **bool**。 |
| **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() override | 遷移が開始するまでの時間（ミリ秒）を指定します。この設定は advClick 属性と組み合わせて使用できます。この属性が指定されていない場合、自動進行は行われないとみなされます。読み取り **uint32_t**。 |
| **bool** [get_AdvanceOnClick](./get_advanceonclick/)() override | マウスクリックでスライドを進めるかどうかを指定します。この属性が指定されていない場合、true が設定されているとみなされます。読み取り **bool**。 |
| **int32_t** [get_Duration](./get_duration/)() override | スライド遷移効果の期間（ミリ秒）を取得します。読み取り **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\> [get_Sound](./get_sound/)() override | 埋め込みオーディオデータを返します。読み取り [IAudio](../../aspose.slides/iaudio/)。 |
| **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() override | このサウンドが組み込みサウンドかどうかを指定します。この属性が true に設定されている場合、生成アプリケーションは組み込みサウンドのリストでこのサウンドに指定された name 属性を確認し、必要に応じてカスタム名や UI を表示できます。読み取り **bool**。 |
| **bool** [get_SoundLoop](./get_soundloop/)() override | この属性は、サウンドが次のサウンドイベントがスライドショーで発生するまでループするかどうかを指定します。読み取り **bool**。 |
| [TransitionSoundMode](../transitionsoundmode/) [get_SoundMode](./get_soundmode/)() override | スライド遷移のサウンドモードを設定または取得します。読み取り [TransitionSoundMode](../transitionsoundmode/)。 |
| [System::String](../../system/string/) [get_SoundName](./get_soundname/)() override | 遷移サウンドの人が読める名前を指定します。[ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) を設定してサウンド名を取得または設定する必要があります。読み取り [System::String](../../system/string/)。 |
| [TransitionSpeed](../transitionspeed/) [get_Speed](./get_speed/)() override | 現在のスライドから次へ遷移する際に使用される遷移速度を指定します。読み取り [TransitionSpeed](../transitionspeed/)。 |
| [TransitionType](../transitiontype/) [get_Type](./get_type/)() override | 遷移の種類です。読み取り [TransitionType](../transitiontype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITransitionValueBase](../itransitionvaluebase/)\> [get_Value](./get_value/)() override | [Slide](../../aspose.slides/slide/) の遷移値を示します。読み取り専用 [ITransitionValueBase](../itransitionvaluebase/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| **int32_t** [GetHashCode](./gethashcode/)() const override | 特定の型のハッシュ関数として機能し、ハッシュアルゴリズムやハッシュテーブルなどのデータ構造での使用に適しています。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [set_AdvanceAfter](./set_advanceafter/)(**bool**) override | この属性は、スライドショーが一定時間後に次のスライドに移動するかどうかを指定します。書き込み **bool**。 |
| void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) override | 遷移が開始するまでの時間（ミリ秒）を指定します。この設定は advClick 属性と組み合わせて使用できます。この属性が指定されていない場合、自動進行は行われないとみなされます。書き込み **uint32_t**。 |
| void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) override | マウスクリックでスライドを進めるかどうかを指定します。この属性が指定されていない場合、true が設定されているとみなされます。書き込み **bool**。 |
| void [set_Duration](./set_duration/)(**int32_t**) override | スライド遷移効果の期間（ミリ秒）を設定します。書き込み **int32_t**。 |
| void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../../aspose.slides/iaudio/)\>) override | 埋め込みオーディオデータを設定します。書き込み [IAudio](../../aspose.slides/iaudio/)。 |
| void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) override | このサウンドが組み込みサウンドかどうかを指定します。この属性が true に設定されている場合、生成アプリケーションは組み込みサウンドのリストでこのサウンドに指定された name 属性を確認し、必要に応じてカスタム名や UI を表示できます。書き込み **bool**。 |
| void [set_SoundLoop](./set_soundloop/)(**bool**) override | この属性は、サウンドが次のサウンドイベントがスライドショーで発生するまでループするかどうかを指定します。書き込み **bool**。 |
| void [set_SoundMode](./set_soundmode/)([TransitionSoundMode](../transitionsoundmode/)) override | スライド遷移のサウンドモードを設定または取得します。書き込み [TransitionSoundMode](../transitionsoundmode/)。 |
| void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) override | 遷移サウンドの人が読める名前を指定します。[ISlideShowTransition::set_Sound](../../aspose.slides/islideshowtransition/set_sound/) を設定してサウンド名を取得または設定する必要があります。書き込み [System::String](../../system/string/)。 |
| void [set_Speed](./set_speed/)([TransitionSpeed](../transitionspeed/)) override | 現在のスライドから次へ遷移する際に使用される遷移速度を指定します。書き込み [TransitionSpeed](../transitionspeed/)。 |
| void [set_Type](./set_type/)([TransitionType](../transitiontype/)) override | 遷移の種類です。書き込み [TransitionType](../transitiontype/)。 |
| void [SetTemplateWeakPtr](./settemplateweakptr/)(**uint32_t**) override | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [DomObject](../../aspose.slides/domobject/)
* クラス [ISlideShowTransition](../../aspose.slides/islideshowtransition/)
* 名前空間 [Aspose::Slides::SlideShow](../)
* ライブラリ [Aspose.Slides](../../)