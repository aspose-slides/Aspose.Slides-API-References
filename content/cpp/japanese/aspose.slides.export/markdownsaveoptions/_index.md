---
title: MarkdownSaveOptions
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションを Markdown に保存する方法を制御するオプションを表します。
type: docs
weight: 547
url: /ja/aspose.slides.export/markdownsaveoptions/
---
## MarkdownSaveOptions クラス


プレゼンテーションを Markdown に保存する方法を制御するオプションを表します。

```cpp
class MarkdownSaveOptions : public Aspose::Slides::Export::SaveOptions
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用です。 |
| [System::String](../../system/string/) [get_BasePath](./get_basepath/)() const | リソース付きドキュメントの保存先ベースパスを指定します。デフォルトはアプリケーションの現在のディレクトリです。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | ソースフォントが見つからない場合に使用されるフォントを返します。[System::String](../../system/string/) を読み取ります。 |
| [MarkdownExportType](../markdownexporttype/) [get_ExportType](./get_exporttype/)() const | プレゼンテーションを変換する Markdown 仕様を指定します。デフォルトは **TextOnly** です。 |
| [Aspose::Slides::Export::Flavor](../flavor/) [get_Flavor](./get_flavor/)() const | プレゼンテーションを変換する Markdown 仕様を指定します。デフォルトは **Multi-markdown** です。 |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | グラデーションのビジュアルスタイルを返します。[GradientStyle](../../aspose.slides/gradientstyle/) を読み取ります。 |
| [Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/) [get_HandleRepeatedSpaces](./get_handlerepeatedspaces/)() const | Markdown エクスポート中に連続した通常のスペース文字をどのように処理するかを指定します。 |
| [System::String](../../system/string/) [get_ImagesSaveFolderName](./get_imagessavefoldername/)() const | 画像を保存するフォルダー名を指定します。デフォルトは **[Images](../../aspose.slides/images/)** です。 |
| [Aspose::Slides::Export::NewLineType](../newlinetype/) [get_NewLineType](./get_newlinetype/)() const | 生成されたドキュメントの改行コードを \r（Macintosh）か \n（Unix）か \r\n（Windows）にするかを指定します。デフォルトは **Unix** です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 進捗率の保存更新用コールバックオブジェクトを表します。[IProgressCallback](../../aspose.slides/iprogresscallback/) を参照してください。 |
| **bool** [get_RemoveEmptyLines](./get_removeemptylines/)() const | true に設定すると、最終的な Markdown 出力から空行または空白のみの行を削除します。デフォルトは **false** です。 |
| **bool** [get_ShowComments](./get_showcomments/)() const | 生成されたドキュメントがコメントを表示するかどうかを指定します。デフォルトは **false** です。 |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() const | 生成されたドキュメントが非表示スライドを含むかどうかを指定します。デフォルトは **false** です。 |
| **bool** [get_ShowSlideNumber](./get_showslidenumber/)() const | 生成されたドキュメントが各スライドの番号を表示するかどうかを指定します。デフォルトは **false** です。 |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。**bool** を読み取ります。デフォルト値は **false** です。 |
| [System::String](../../system/string/) [get_SlideNumberFormat](./get_slidenumberformat/)() | Markdown 出力のスライド番号ヘッダーに使用される書式文字列を取得します。書式には "{0}" プレースホルダーを含める必要があり、エクスポート時にスライドインデックスに置き換えられます。例: "# Slide {0}" は "# Slide 1", "# Slide 2" などを生成します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 警告を受け取り、ロード処理を継続するか中止するかを決定するオブジェクトを取得または設定します。[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) を読み取ります。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
|  [MarkdownSaveOptions](./markdownsaveoptions/)() | コンストラクタです。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウンタを減少させます。 |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BasePath](./set_basepath/)([System::String](../../system/string/)) | リソース付きドキュメントの保存先ベースパスを指定します。デフォルトはアプリケーションの現在のディレクトリです。 |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | ソースフォントが見つからない場合に使用するフォントを設定します。[System::String](../../system/string/) に書き込みます。 |
| void [set_ExportType](./set_exporttype/)([MarkdownExportType](../markdownexporttype/)) | プレゼンテーションを変換する Markdown 仕様を指定します。デフォルトは **TextOnly** です。 |
| void [set_Flavor](./set_flavor/)([Aspose::Slides::Export::Flavor](../flavor/)) | プレゼンテーションを変換する Markdown 仕様を指定します。デフォルトは **Multi-markdown** です。 |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | グラデーションのビジュアルスタイルを設定します。[GradientStyle](../../aspose.slides/gradientstyle/) に書き込みます。 |
| void [set_HandleRepeatedSpaces](./set_handlerepeatedspaces/)([Aspose::Slides::Export::HandleRepeatedSpaces](../handlerepeatedspaces/)) | Markdown エクスポート中に連続した通常のスペース文字をどのように処理するかを指定します。 |
| void [set_ImagesSaveFolderName](./set_imagessavefoldername/)([System::String](../../system/string/)) | 画像を保存するフォルダー名を指定します。デフォルトは **[Images](../../aspose.slides/images/)** です。 |
| void [set_NewLineType](./set_newlinetype/)([Aspose::Slides::Export::NewLineType](../newlinetype/)) | 生成されたドキュメントの改行コードを \r（Macintosh）か \n（Unix）か \r\n（Windows）にするかを指定します。デフォルトは **Unix** です。 |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 進捗率の保存更新用コールバックオブジェクトを表します。[IProgressCallback](../../aspose.slides/iprogresscallback/) を参照してください。 |
| void [set_RemoveEmptyLines](./set_removeemptylines/)(**bool**) | true に設定すると、最終的な Markdown 出力から空行または空白のみの行を削除します。デフォルトは **false** です。 |
| void [set_ShowComments](./set_showcomments/)(**bool**) | 生成されたドキュメントがコメントを表示するかどうかを指定します。デフォルトは **false** です。 |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | 生成されたドキュメントが非表示スライドを含むかどうかを指定します。デフォルトは **false** です。 |
| void [set_ShowSlideNumber](./set_showslidenumber/)(**bool**) | 生成されたドキュメントが各スライドの番号を表示するかどうかを指定します。デフォルトは **false** です。 |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。**bool** に書き込みます。デフォルト値は **false** です。 |
| void [set_SlideNumberFormat](./set_slidenumberformat/)([System::String](../../system/string/)) | Markdown 出力のスライド番号ヘッダーに使用される書式文字列を設定します。書式には "{0}" プレースホルダーを含める必要があり、エクスポート時にスライドインデックスに置き換えられます。例: "# Slide {0}" は "# Slide 1", "# Slide 2" などを生成します。 |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 警告を受け取り、ロード処理を継続するか中止するかを決定するオブジェクトを取得または設定します。[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのアンロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 型定義

| 型定義 | 説明 |
| --- | --- |
| [MarkdownImageSavingHandler](./markdownimagesavinghandler/) | Markdown エクスポート中に非 SVG 画像（ビットマップまたはメタファイル）ごとに呼び出されます。指定された *link* を使用する場合は **true** を返し、デフォルトの保存ロジックを適用する場合は **false** を返します。 |
| [MarkdownSvgImageSavingHandler](./markdownsvgimagesavinghandler/) | Markdown エクスポート中に SVG 画像ごとに呼び出されます。指定された *link* を使用する場合は **true** を返し、デフォルトの保存ロジックを適用する場合は **false** を返します。 |

## 備考

例: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::SharedPtr<MarkdownSaveOptions> markdownSaveOptions = System::MakeObject<MarkdownSaveOptions>();
markdownSaveOptions->set_ShowHiddenSlides(true);
markdownSaveOptions->set_ShowSlideNumber(true);
markdownSaveOptions->set_Flavor(Flavor::Github);
markdownSaveOptions->set_ExportType(MarkdownExportType::Sequential);
markdownSaveOptions->set_NewLineType(NewLineType::Windows);

System::ArrayPtr<int32_t> slideIndices = System::MakeArray<int32_t>({1, 2, 3, 4, 5, 6, 7, 8, 9});

pres->Save(u"doc.md", slideIndices, SaveFormat::Md, markdownSaveOptions);
```

## 参照

* クラス [SaveOptions](../saveoptions/)
* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)