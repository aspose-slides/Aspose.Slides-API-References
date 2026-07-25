---
title: ISwfOptions
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションが SWF 形式で保存される方法を制御するオプションを提供します。
type: docs
weight: 469
url: /ja/aspose.slides.export/iswfoptions/
---
## ISwfOptions クラス

プレゼンテーションが SWF 形式で保存される方法を制御するオプションを提供します。

```cpp
class ISwfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual **bool** [get_Compressed](./get_compressed/)() | 生成された SWF ドキュメントを圧縮するかどうかを指定します。デフォルトは **true** です。 |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | ソースフォントが見つからない場合に使用されるフォントを返します。[System::String](../../system/string/) を読み取ります。 |
| virtual **bool** [get_EnableContextMenu](./get_enablecontextmenu/)() | コンテキストメニューを有効/無効にします。デフォルトは true です。 |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | グラデーションのビジュアルスタイルを返します。[GradientStyle](../../aspose.slides/gradientstyle/) を読み取ります。 |
| virtual **int32_t** [get_JpegQuality](./get_jpegquality/)() | JPEG 画像の品質を指定します。<br><br>デフォルトは 95 です。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\> [get_LogoImageBytes](./get_logoimagebytes/)() | ビューアの右上隅にロゴとして表示される画像。<br><br>画像は 32x64 ピクセルの PNG である必要があります。そうでない場合、ロゴが正しく表示されない可能性があります。 |
| virtual [System::String](../../system/string/) [get_LogoLink](./get_logolink/)() | ロゴの完全なハイパーリンクアドレスを取得します。[set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) が指定されている場合にのみ効果があります。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | 進行状況のパーセンテージ更新を保存するためのコールバックオブジェクトを表します。[IProgressCallback](../../aspose.slides/iprogresscallback/) を参照してください。 |
| virtual **bool** [get_ShowBottomPane](./get_showbottompane/)() | 下部ペインを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| virtual **bool** [get_ShowFullScreen](./get_showfullscreen/)() | 全画面ボタンを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは **false** です。 |
| virtual **bool** [get_ShowLeftPane](./get_showleftpane/)() | 左ペインを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| virtual **bool** [get_ShowPageBorder](./get_showpageborder/)() | ページ周囲の枠線を表示するかどうかを指定します。デフォルトは true です。 |
| virtual **bool** [get_ShowPageStepper](./get_showpagestepper/)() | ページステッパーを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| virtual **bool** [get_ShowSearch](./get_showsearch/)() | 検索セクションを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| virtual **bool** [get_ShowTopPane](./get_showtoppane/)() | 上部全体ペインを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。**bool** を読み取ります。デフォルト値は **false** です。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | プレゼンテーション [ISlidesLayoutOptions](../islideslayoutoptions/) をエクスポートする際にスライドがページ上に配置されるモードを取得します。このプロパティは **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** 型のオブジェクトの代入をサポートしません。 |
| virtual **bool** [get_StartOpenLeftPane](./get_startopenleftpane/)() | 左ペインを開いた状態で開始します。flashvars で上書き可能です。デフォルトは false です。 |
| virtual **bool** [get_ViewerIncluded](./get_viewerincluded/)() | 生成された SWF ドキュメントに統合されたドキュメントビューアを含めるかどうかを指定します。デフォルトは **true** です。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | 警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを返します。[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) を読み取ります。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられたリファレンスカウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有リファレンスカウントを減少させます。 |
| virtual void [set_Compressed](./set_compressed/)(**bool**) | 生成された SWF ドキュメントを圧縮するかどうかを指定します。デフォルトは **true** です。 |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | ソースフォントが見つからない場合に使用されるフォントを設定します。[System::String](../../system/string/) に書き込みます。 |
| virtual void [set_EnableContextMenu](./set_enablecontextmenu/)(**bool**) | コンテキストメニューを有効/無効にします。デフォルトは true です。 |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | グラデーションのビジュアルスタイルを設定します。[GradientStyle](../../aspose.slides/gradientstyle/) に書き込みます。 |
| virtual void [set_JpegQuality](./set_jpegquality/)(**int32_t**) | JPEG 画像の品質を指定します。<br><br>デフォルトは 95 です。 |
| virtual void [set_LogoImageBytes](./set_logoimagebytes/)([System::ArrayPtr](../../system/arrayptr/)\<**uint8_t**\>) | ビューアの右上隅にロゴとして表示される画像。<br><br>画像は 32x64 ピクセルの PNG である必要があります。そうでない場合、ロゴが正しく表示されない可能性があります。 |
| virtual void [set_LogoLink](./set_logolink/)([System::String](../../system/string/)) | ロゴの完全なハイパーリンクアドレスを設定します。[set_LogoImageBytes()](../swfoptions/set_logoimagebytes/) が指定されている場合にのみ効果があります。 |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | 進行状況のパーセンテージ更新を保存するためのコールバックオブジェクトを表します。[IProgressCallback](../../aspose.slides/iprogresscallback/) を参照してください。 |
| virtual void [set_ShowBottomPane](./set_showbottompane/)(**bool**) | 下部ペインを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| virtual void [set_ShowFullScreen](./set_showfullscreen/)(**bool**) | 全画面ボタンを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは **false** です。 |
| virtual void [set_ShowLeftPane](./set_showleftpane/)(**bool**) | 左ペインを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| virtual void [set_ShowPageBorder](./set_showpageborder/)(**bool**) | ページ周囲の枠線を表示するかどうかを指定します。デフォルトは true です。 |
| virtual void [set_ShowPageStepper](./set_showpagestepper/)(**bool**) | ページステッパーを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| virtual void [set_ShowSearch](./set_showsearch/)(**bool**) | 検索セクションを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| virtual void [set_ShowTopPane](./set_showtoppane/)(**bool**) | 上部全体ペインを表示/非表示にします。flashvars で上書き可能です。デフォルトは true です。 |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。**bool** に書き込みます。デフォルト値は **false** です。 |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | プレゼンテーション [ISlidesLayoutOptions](../islideslayoutoptions/) をエクスポートする際にスライドがページ上に配置されるモードを設定します。このプロパティは **[Aspose.Slides.Export.HandoutLayoutingOptions](../handoutlayoutingoptions/)** 型のオブジェクトの代入をサポートしません。 |
| virtual void [set_StartOpenLeftPane](./set_startopenleftpane/)(**bool**) | 左ペインを開いた状態で開始します。flashvars で上書き可能です。デフォルトは false です。 |
| virtual void [set_ViewerIncluded](./set_viewerincluded/)(**bool**) | 生成された SWF ドキュメントに統合されたドキュメントビューアを含めるかどうかを指定します。デフォルトは **true** です。 |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | 警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを設定します。[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有リファレンスカウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有リファレンスカウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有リファレンスカウントを減少させ、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトの文字列変換を可能にします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱リファレンスカウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱リファレンスカウントを減少させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [ISaveOptions](../isaveoptions/)
* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)