---
title: GifOptions
second_title: Aspose.Slides for C++ API リファレンス
description: GIF エクスポートオプションを表します。
type: docs
weight: 53
url: /ja/aspose.slides.export/gifoptions/
---
## GifOptions クラス

GIF エクスポートオプションを表します。

```cpp
class GifOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IGifOptions
```

## Methods

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | 2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします (IEC 60559:1989 によれば NaN は任意の値、NaN 自身を含めて等しくありません)。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | 2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします (IEC 60559:1989 によれば NaN は任意の値、NaN 自身を含めて等しくありません)。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部使用のみです。 |
| **int32_t** [get_DefaultDelay](./get_defaultdelay/)() override | デフォルトの遅延時間 [ms] を取得します。この値は [ISlideShowTransition::set_AdvanceAfterTime()](../../aspose.slides/islideshowtransition/set_advanceaftertime/) メソッドが呼び出されなかった場合に使用されます。デフォルトは 1000 です。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | ソースフォントが見つからない場合に使用されるフォントを返します。[System::String](../../system/string/) を読み取ります。 |
| **bool** [get_ExportHiddenSlides](./get_exporthiddenslides/)() override | 非表示スライドをエクスポートするかどうかを決定します。デフォルトは false です。 |
| [System::Drawing::Size](../../system.drawing/size/) [get_FrameSize](./get_framesize/)() override | フレームサイズを取得します。 |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | グラデーションのビジュアルスタイルを返します。[GradientStyle](../../aspose.slides/gradientstyle/) を読み取ります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 進行状況をパーセンテージで保存するコールバックオブジェクトを表します。[IProgressCallback](../../aspose.slides/iprogresscallback/) を参照してください。 |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | プレゼンテーション保存時に JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。**bool** を読み取ります。デフォルトは **false** です。 |
| **int32_t** [get_TransitionFps](./get_transitionfps/)() override | トランジションの FPS [frames/sec] を取得します。デフォルトは 25 です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 警告を受け取り、ロード処理を継続するか中止するかを決定するオブジェクトを返すまたは設定します。[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) を読み取ります。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を有効にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
|  [GifOptions](./gifoptions/)() | [GifOptions](./) クラスの新しいインスタンスを初期化します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() ステートメントのロックを実装します。直接呼び出すか [LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を有効にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr の場合の [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | 文字列の場合の [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウンタを減少させます。 |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultDelay](./set_defaultdelay/)(**int32_t**) override | デフォルトの遅延時間 [ms] を設定します。この値は [ISlideShowTransition::set_AdvanceAfterTime()](../../aspose.slides/islideshowtransition/set_advanceaftertime/) メソッドが呼び出されなかった場合に使用されます。デフォルトは 1000 です。 |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | ソースフォントが見つからない場合に使用されるフォントを設定します。[System::String](../../system/string/) に書き込みます。 |
| void [set_ExportHiddenSlides](./set_exporthiddenslides/)(**bool**) override | 非表示スライドをエクスポートするかどうかを決定します。デフォルトは false です。 |
| void [set_FrameSize](./set_framesize/)([System::Drawing::Size](../../system.drawing/size/)) override | フレームサイズを設定します。 |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | グラデーションのビジュアルスタイルを設定します。[GradientStyle](../../aspose.slides/gradientstyle/) に書き込みます。 |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 進行状況をパーセンテージで保存するコールバックオブジェクトを表します。[IProgressCallback](../../aspose.slides/iprogresscallback/) を参照してください。 |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | プレゼンテーション保存時に JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。**bool** に書き込みます。デフォルトは **false** です。 |
| void [set_TransitionFps](./set_transitionfps/)(**int32_t**) override | トランジションの FPS [frames/sec] を設定します。デフォルトは 25 です。 |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 警告を受け取り、ロード処理を継続するか中止するかを決定するオブジェクトを返すまたは設定します。[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウンタをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウンタをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換することを可能にします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() ステートメントのロック解除を実装します。直接呼び出すか [LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## Remarks

以下の例は、カスタム設定を使用してプレゼンテーションをアニメーション GIF に変換する方法を示しています。
```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
auto gifOptions = System::MakeObject<GifOptions>();

gifOptions->set_FrameSize(System::Drawing::Size(960, 720)); // 結果として得られる GIF のサイズ
gifOptions->set_DefaultDelay(2000); // 各スライドが次に切り替わるまで表示される時間
gifOptions->set_TransitionFps(35); // トランジションアニメーションの品質向上のために FPS を上げる

pres->Save(u"pres.gif", SaveFormat::Gif, gifOptions);
```

## See Also

* クラス [SaveOptions](../saveoptions/)
* クラス [IGifOptions](../igifoptions/)
* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)