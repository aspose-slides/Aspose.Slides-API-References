---
title: SwfOptions
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションが Swf 形式で保存される方法を制御するオプションを提供します。
type: docs
weight: 742
url: /ja/aspose.slides.export/swfoptions/
---
## SwfOptions クラス

Provides options that control how a presentation is saved in Swf format.

```cpp
class SwfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISwfOptions
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいと見なします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいと見なします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| **bool** [get_Compressed](./get_compressed/)() override | 生成された SWF ドキュメントを圧縮するかどうかを指定します。デフォルトは **true** です。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | ソースフォントが見つからない場合に使用されるフォントを返します。[System::String](../../system/string/) を読み取ります。 |
| **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() override | コンテキストメニューを有効化/無効化します。デフォルトは true です。 |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | グラデーションのビジュアルスタイルを返します。[GradientStyle](../../aspose.slides/gradientstyle/) を読み取ります。 |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | JPEG 画像の品質を指定します。デフォルトは 95 です。 |
| [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() override | ビューアの右上隅にロゴとして表示される画像です。画像は 32x64 ピクセルの PNG である必要があり、そうでない場合ロゴが正しく表示されない可能性があります。 |
| [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() override | ロゴの完全なハイパーリンクアドレスを取得します。[set_LogoImageBytes()](./set_logoimagebytes/) が指定されている場合にのみ効果があります。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 進捗のパーセンテージ更新を保存するためのコールバックオブジェクトを表します。[IProgressCallback](../../aspose.slides/iprogresscallback/) を参照してください。 |
| **bool** [get_ShowBottomPane](./get_showbottompane/)() override | 下部ペインを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| **bool** [get_ShowFullScreen](./get_showfullscreen/)() override | 全画面ボタンを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは **false** です。 |
| **bool** [get_ShowLeftPane](./get_showleftpane/)() override | 左ペインを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| **bool** [get_ShowPageBorder](./get_showpageborder/)() override | ページ周囲の境界線を表示するかどうかを指定します。デフォルトは true です。 |
| **bool** [get_ShowPageStepper](./get_showpagestepper/)() override | ページステッパーを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| **bool** [get_ShowSearch](./get_showsearch/)() override | 検索セクションを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| **bool** [get_ShowTopPane](./get_showtoppane/)() override | 上部全体ペインを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | プレゼンテーションを保存する際に JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。**bool** を読み取ります。デフォルト値は **false** です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | プレゼンテーション [ISlidesLayoutOptions](../islideslayoutoptions/) をエクスポートするときにスライドがページ上に配置されるモードを取得します。このプロパティは [HandoutLayoutingOptions](../handoutlayoutingoptions/) 型のオブジェクトの代入をサポートしません。 |
| **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() override | 左ペインを開いた状態で開始します。flashvars で上書き可能です。デフォルトは false です。 |
| **bool** [get_ViewerIncluded](./get_viewerincluded/)() override | 生成された SWF ドキュメントに統合ビューアを含めるかどうかを指定します。デフォルトは **true** です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを返すまたは設定します。[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) を読み取ります。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_Compressed](./set_compressed/)(**bool**) override | 生成された SWF ドキュメントを圧縮するかどうかを指定します。デフォルトは **true** です。 |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | ソースフォントが見つからない場合に使用されるフォントを設定します。[System::String](../../system/string/) に書き込みます。 |
| void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) override | コンテキストメニューを有効化/無効化します。デフォルトは true です。 |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | グラデーションのビジュアルスタイルを設定します。[GradientStyle](../../aspose.slides/gradientstyle/) に書き込みます。 |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | JPEG 画像の品質を指定します。デフォルトは 95 です。 |
| void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) override | ビューアの右上隅にロゴとして表示される画像です。画像は 32x64 ピクセルの PNG である必要があり、そうでない場合ロゴが正しく表示されない可能性があります。 |
| void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) override | ロゴの完全なハイパーリンクアドレスを設定します。[set_LogoImageBytes()](./set_logoimagebytes/) が指定されている場合にのみ効果があります。 |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 進捗のパーセンテージ更新を保存するためのコールバックオブジェクトを表します。[IProgressCallback](../../aspose.slides/iprogresscallback/) を参照してください。 |
| void [set_ShowBottomPane](./set_showbottompane/)(**bool**) override | 下部ペインを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) override | 全画面ボタンを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは **false** です。 |
| void [set_ShowLeftPane](./set_showleftpane/)(**bool**) override | 左ペインを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| void [set_ShowPageBorder](./set_showpageborder/)(**bool**) override | ページ周囲の境界線を表示するかどうかを指定します。デフォルトは true です。 |
| void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) override | ページステッパーを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| void [set_ShowSearch](./set_showsearch/)(**bool**) override | 検索セクションを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| void [set_ShowTopPane](./set_showtoppane/)(**bool**) override | 上部全体ペインを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | プレゼンテーションを保存する際に JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。**bool** に書き込みます。デフォルト値は **false** です。 |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | プレゼンテーション [ISlidesLayoutOptions](../islideslayoutoptions/) をエクスポートするときにスライドがページ上に配置されるモードを設定します。このプロパティは [HandoutLayoutingOptions](../handoutlayoutingoptions/) 型のオブジェクトの代入をサポートしません。 |
| void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) override | 左ペインを開いた状態で開始します。flashvars で上書き可能です。デフォルトは false です。 |
| void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) override | 生成された SWF ドキュメントに統合ビューアを含めるかどうかを指定します。デフォルトは **true** です。 |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを返すまたは設定します。[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（shared ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることが可能です。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
|  [SwfOptions](./swfoptions/)() | デフォルトコンストラクタです。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のアンロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 備考

以下の例は PowerPoint を SWF Flash に変換する方法を示しています。 
```cpp
auto presentation = System::MakeObject<Presentation>(u"HelloWorld.pptx");
auto swfOptions = System::MakeObject<SwfOptions>();

swfOptions->set_ViewerIncluded(false);
auto notesOptions = swfOptions->get_NotesCommentsLayouting();
notesOptions->set_NotesPosition(NotesPositions::BottomFull);

// Saving presentation and notes pages
presentation->Save(u"SaveAsSwf_out.swf", SaveFormat::Swf, swfOptions);
swfOptions->set_ViewerIncluded(true);
presentation->Save(u"SaveNotes_out.swf", SaveFormat::Swf, swfOptions);
```

## 参照

* クラス [SaveOptions](../saveoptions/)
* クラス [ISwfOptions](../iswfoptions/)
* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)