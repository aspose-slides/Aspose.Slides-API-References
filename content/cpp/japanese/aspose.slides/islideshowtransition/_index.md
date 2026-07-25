---
title: ISlideShowTransition
second_title: Aspose.Slides for C++ API リファレンス
description: スライドショー遷移を表します。
type: docs
weight: 3810
url: /ja/aspose.slides/islideshowtransition/
---
## ISlideShowTransition クラス

スライドショー遷移を表します。

```cpp
class ISlideShowTransition : public virtual System::Object
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C#-style の浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C#-style の浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| virtual **bool** [get_AdvanceAfter](./get_advanceafter/)() | この属性は、スライドショーが一定時間後に次のスライドへ移動するかどうかを指定します。**bool** を読み取ります。 |
| virtual **uint32_t** [get_AdvanceAfterTime](./get_advanceaftertime/)() | 遷移が開始されるまでの時間をミリ秒で指定します。この設定は advClick 属性と併用できます。この属性が指定されていない場合、auto-advance が行われないものとみなされます。**uint32_t** を読み取ります。 |
| virtual **bool** [get_AdvanceOnClick](./get_advanceonclick/)() | マウスクリックでスライドが進むかどうかを指定します。この属性が指定されていない場合、true が想定されます。**bool** を読み取ります。 |
| virtual **int32_t** [get_Duration](./get_duration/)() | スライド遷移効果の期間をミリ秒で取得します。**int32_t** を読み取ります。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Sound](./get_sound/)() | 埋め込みオーディオデータを返します。[IAudio](../iaudio/) を読み取ります。 |
| virtual **bool** [get_SoundIsBuiltIn](./get_soundisbuiltin/)() | このサウンドが組み込みサウンドかどうかを指定します。この属性が true に設定されている場合、生成アプリケーションは組み込みサウンド一覧でこのサウンドに指定された name 属性を確認し、必要に応じてカスタム名や UI を表示できます。**bool** を読み取ります。 |
| virtual **bool** [get_SoundLoop](./get_soundloop/)() | この属性は、サウンドがスライドショーで次のサウンドイベントが発生するまでループするかどうかを指定します。**bool** を読み取ります。 |
| virtual [SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/) [get_SoundMode](./get_soundmode/)() | スライド遷移のサウンドモードを設定または取得します。[TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/) を読み取ります。 |
| virtual [System::String](../../system/string/) [get_SoundName](./get_soundname/)() | 遷移サウンドの人間が読める名前を指定します。[ISlideShowTransition::set_Sound](./set_sound/) を設定してサウンド名の取得または設定を行う必要があります。[System::String](../../system/string/) を読み取ります。 |
| virtual [SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/) [get_Speed](./get_speed/)() | 現在のスライドから次のスライドへの遷移時に使用される遷移速度を指定します。[TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/) を読み取ります。 |
| virtual [SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/) [get_Type](./get_type/)() | 遷移の種類です。[TransitionType](../../aspose.slides.slideshow/transitiontype/) を読み取ります。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/)\> [get_Value](./get_value/)() | [Slide](../slide/) ショー遷移値です。読み取り専用 [SlideShow::ITransitionValueBase](../../aspose.slides.slideshow/itransitionvaluebase/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタムタイプのクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_AdvanceAfter](./set_advanceafter/)(**bool**) | この属性は、スライドショーが一定時間後に次のスライドへ移動するかどうかを指定します。**bool** に書き込みます。 |
| virtual void [set_AdvanceAfterTime](./set_advanceaftertime/)(**uint32_t**) | 遷移が開始されるまでの時間をミリ秒で指定します。この設定は advClick 属性と併用できます。この属性が指定されていない場合、auto-advance が行われないものとみなされます。**uint32_t** に書き込みます。 |
| virtual void [set_AdvanceOnClick](./set_advanceonclick/)(**bool**) | マウスクリックでスライドが進むかどうかを指定します。この属性が指定されていない場合、true が想定されます。**bool** に書き込みます。 |
| virtual void [set_Duration](./set_duration/)(**int32_t**) | スライド遷移効果の期間をミリ秒で設定します。**int32_t** に書き込みます。 |
| virtual void [set_Sound](./set_sound/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | 埋め込みオーディオデータを設定します。[IAudio](../iaudio/) に書き込みます。 |
| virtual void [set_SoundIsBuiltIn](./set_soundisbuiltin/)(**bool**) | このサウンドが組み込みサウンドかどうかを指定します。この属性が true に設定されている場合、生成アプリケーションは組み込みサウンド一覧でこのサウンドに指定された name 属性を確認し、必要に応じてカスタム名や UI を表示できます。**bool** に書き込みます。 |
| virtual void [set_SoundLoop](./set_soundloop/)(**bool**) | この属性は、サウンドがスライドショーで次のサウンドイベントが発生するまでループするかどうかを指定します。**bool** に書き込みます。 |
| virtual void [set_SoundMode](./set_soundmode/)([SlideShow::TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/)) | スライド遷移のサウンドモードを設定または取得します。[TransitionSoundMode](../../aspose.slides.slideshow/transitionsoundmode/) に書き込みます。 |
| virtual void [set_SoundName](./set_soundname/)([System::String](../../system/string/)) | 遷移サウンドの人間が読める名前を指定します。[ISlideShowTransition::set_Sound](./set_sound/) を設定してサウンド名の取得または設定を行う必要があります。[System::String](../../system/string/) に書き込みます。 |
| virtual void [set_Speed](./set_speed/)([SlideShow::TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/)) | 現在のスライドから次のスライドへの遷移時に使用される遷移速度を指定します。[TransitionSpeed](../../aspose.slides.slideshow/transitionspeed/) に書き込みます。 |
| virtual void [set_Type](./set_type/)([SlideShow::TransitionType](../../aspose.slides.slideshow/transitiontype/)) | 遷移の種類です。[TransitionType](../../aspose.slides.slideshow/transitiontype/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を共有ではなく弱参照ポインタに設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Object](../../system/object/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)