---
title: PdfOptions
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションが Pdf 形式で保存される方法を制御するオプションを提供します。
type: docs
weight: 573
url: /ja/aspose.slides.export/pdfoptions/
---
## PdfOptions クラス

プレゼンテーションが PDF 形式で保存される方法を制御するオプションを提供します。

```cpp
class PdfOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::IPdfOptions
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにも関わらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにも関わらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() override | ドキュメントがユーザーアクセスで開かれたときに付与されるアクセス権限を指定するフラグの集合を含みます。参照 [PdfAccessPermissions](../pdfaccesspermissions/)。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() override | [Aspose.Slides](../../aspose.slides/) が共通と見なすべきフォントファミリのユーザー定義名の配列を返します。[System::String](../../system/string/)[] を参照してください。 |
| **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() override | **true** の場合、指定された透明色を画像に適用します。 |
| **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() override | 各画像に対して最も効果的な圧縮（デフォルトではなく）を自動的に選択すべきかを示します。**bool**.true に設定すると、プレゼンテーション内のすべての画像に対して最適な圧縮アルゴリズムが選択され、結果として生成される PDF ドキュメントのサイズが小さくなります。 |
| [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() override | 生成された PDF ドキュメントの目的とする適合レベルです。[PdfCompliance](../pdfcompliance/) を参照してください。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | ソースフォントが見つからない場合に使用されるフォントを返します。[System::String](../../system/string/) を参照してください。 |
| **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() override | 各スライドの周囲に黒枠を描画する場合は true に設定します。**bool** を参照してください。 |
| **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() override | フォントのすべての文字を埋め込むか、使用されたサブセットのみを埋め込むかを決定します。**bool** を参照してください。 |
| **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() override | [Aspose.Slides](../../aspose.slides/) が ASCII（33..127 のコード範囲）のテキスト用に共通フォントを埋め込むかを決定します。127 を超える文字コードについては常に埋め込まれます（[Fonts](../../aspose.slides/fonts/)）。共通フォントリストには PDF のベース 14 フォントと、ユーザーが指定した追加フォントが含まれます。**bool** を参照してください。 |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | グラデーションのビジュアルスタイルを返します。[GradientStyle](../../aspose.slides/gradientstyle/) を参照してください。 |
| [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() override | 画像の透明色を取得します。 |
| **bool** [get_IncludeOleData](./get_includeoledata/)() override | **bool** が true の場合、プレゼンテーションのすべての OLE データを結果の PDF に埋め込まれたファイルに変換します。**bool** を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | [Ink](../../aspose.slides.ink/) オブジェクトのエクスポートドキュメントでの外観を制御するオプションを提供します。読み取り専用 [IInkOptions](../iinkoptions/) |
| **uint8_t** [get_JpegQuality](./get_jpegquality/)() override | PDF ドキュメント内の JPEG 画像の品質を決定する値を返します。**uint8_t** を参照してください。 |
| [System::String](../../system/string/) [get_Password](./get_password/)() override | PDF ドキュメントを保護するためのユーザーパスワードを設定します。[System::String](../../system/string/) を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 進捗率の保存更新のためのコールバックオブジェクトを表します。[IProgressCallback](../../aspose.slides/iprogresscallback/) を参照してください。 |
| **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() override | フォントが太字スタイルをサポートしない場合に、テキストをビットマップとしてラスタライズし PDF に保存すべきかを示します。このアプローチは特定のフォントにおいて、結果の PDF のテキスト品質を向上させることがあります。**bool** を参照してください。 |
| **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() override | **bool** が true の場合、プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換します。**bool** を参照してください。 |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | 生成されたドキュメントに隠しスライドを含めるかどうかを指定します。デフォルトは **false** です。 |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。**bool** を参照してください。デフォルト値は **false** です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを取得します。[ISlidesLayoutOptions](../islideslayoutoptions/)。 |
| **float** [get_SufficientResolution](./get_sufficientresolution/)() override | PDF ドキュメント内の画像解像度を決定する値を返します。 |
| [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() override | ドキュメント内のすべてのテキストコンテンツに使用される圧縮タイプを指定します。[PdfTextCompression](../pdftextcompression/) を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを返すまたは設定します。[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) を参照してください。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるか確認します。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック機能を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
|  [PdfOptions](./pdfoptions/)() | デフォルトコンストラクタです。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 共有参照カウントを指定された値だけ減少させます。 |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) override | ドキュメントがユーザーアクセスで開かれたときに付与すべきアクセス権限を指定するフラグの集合を含みます。[PdfAccessPermissions](../pdfaccesspermissions/) を参照してください。 |
| void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) override | ユーザー定義のフォントファミリ名配列を設定します。[Aspose.Slides](../../aspose.slides/) が共通とみなすべきものです。[System::String](../../system/string/)[] に書き込みます。 |
| void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) override | **true** の場合、指定された透明色を画像に適用します。 |
| void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) override | 各画像に対してデフォルトの代わりに最も効果的な圧縮を自動的に選択すべきかを示します。**bool**.true に設定すると、プレゼンテーション内のすべての画像について最適な圧縮アルゴリズムが選択され、結果として生成される PDF ドキュメントのサイズが小さくなります。 |
| void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) override | 生成される PDF ドキュメントの希望する適合レベルです。[PdfCompliance](../pdfcompliance/) に書き込みます。 |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | 元フォントが見つからない場合に使用するフォントを設定します。[System::String](../../system/string/) に書き込みます。 |
| void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) override | 各スライドの周囲に黒枠を描画する場合は true にします。**bool** に書き込みます。 |
| void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) override | フォントのすべての文字を埋め込むか、使用したサブセットのみを埋め込むかを決定します。**bool** に書き込みます。 |
| void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) override | [Aspose.Slides](../../aspose.slides/) が ASCII (33..127 のコード範囲) テキスト用に共通フォントを埋め込むかどうかを決定します。127 より大きい文字コードに対しては [Fonts](../../aspose.slides/fonts/) が常に埋め込まれます。共通フォントリストには PDF の基本 14 フォントと追加のユーザー指定フォントが含まれます。**bool** に書き込みます。 |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | グラデーションの視覚スタイルを設定します。[GradientStyle](../../aspose.slides/gradientstyle/) に書き込みます。 |
| void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) override | 画像の透明色を設定します。 |
| void [set_IncludeOleData](./set_includeoledata/)(**bool**) override | プレゼンテーションのすべての OLE データを結果の PDF 内の埋め込みファイルに変換する場合は true にします。**bool** に書き込みます。 |
| void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) override | PDF ドキュメント内の JPEG 画像の品質を決定する値を設定します。**uint8_t** に書き込みます。 |
| void [set_Password](./set_password/)([System::String](../../system/string/)) override | PDF ドキュメントを保護するためのユーザーパスワードを設定します。[System::String](../../system/string/) に書き込みます。 |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 保存進捗をパーセンテージで更新するコールバックオブジェクトを表します。[IProgressCallback](../../aspose.slides/iprogresscallback/) を参照してください。 |
| void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) override | フォントが太字スタイルをサポートしない場合に、テキストをビットマップとしてラスタライズし PDF に保存すべきかを示します。この方法は特定のフォントに対して結果の PDF のテキスト品質を向上させることがあります。**bool** に書き込みます。 |
| void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) override | プレゼンテーションで使用されているすべてのメタファイルを PNG 画像に変換する場合は true にします。**bool** に書き込みます。 |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | 生成されるドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは **false** です。 |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | プレゼンテーションを保存するときに JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。**bool** に書き込みます。デフォルト値は **false** です。 |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | プレゼンテーション [ISlidesLayoutOptions](../islideslayoutoptions/) をエクスポートする際にスライドがページ上に配置されるモードを設定します。 |
| void [set_SufficientResolution](./set_sufficientresolution/)(**float**) override | PDF ドキュメント内の画像の解像度を決定する値を設定します。 |
| void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) override | ドキュメント内のすべてのテキストコンテンツに使用する圧縮タイプを指定します。[PdfTextCompression](../pdftextcompression/) に書き込みます。 |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 警告を受け取り、ロードプロセスの続行または中止を決定するオブジェクトを取得または設定します。[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ (shared ではなく) に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではありません。代わりにスマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |
## 備考

次の例は、カスタムオプションで PowerPoint を PDF に変換する方法を示しています。  
```cpp
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// PdfOptions クラスのインスタンスを作成します
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// Jpeg の品質を設定します
pdfOptions->set_JpegQuality(90);
// メタファイルの動作を設定します
pdfOptions->set_SaveMetafilesAsPng(true);
// テキスト圧縮レベルを設定します
pdfOptions->set_TextCompression(PdfTextCompression::Flate);
// PDF 標準を定義します
pdfOptions->set_Compliance(PdfCompliance::Pdf15);
// プレゼンテーションを PDF として保存します
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```  
次の例は、非表示スライドを含む PowerPoint を PDF に変換する方法を示しています。  
```cpp
// PowerPoint ファイルを表す Presentation クラスのインスタンスを作成します
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

// PdfOptions クラスのインスタンスを作成します
System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
// 非表示スライドを追加します
pdfOptions->set_ShowHiddenSlides(true);
// プレゼンテーションを PDF として保存します
presentation->Save(u"PowerPoint-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```  
次の例は、パスワード保護された PDF に PowerPoint を変換する方法を示しています。  
```cpp
// PowerPoint ファイルを表す Presentation オブジェクトのインスタンスを作成します
auto presentation = System::MakeObject<Presentation>(u"PowerPoint.pptx");

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();

// PDF パスワードとアクセス許可を設定します
pdfOptions->set_Password(u"password");
pdfOptions->set_AccessPermissions(PdfAccessPermissions::PrintDocument | PdfAccessPermissions::HighQualityPrint);
// プレゼンテーションを PDF として保存します
presentation->Save(u"PPTX-to-PDF.pdf", SaveFormat::Pdf, pdfOptions);
```  
次の例は、ノート付きで PowerPoint を PDF に変換する方法を示しています。  
```cpp
// プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化します
auto presentation = System::MakeObject<Presentation>(u"SelectedSlides.pptx");

auto auxPresentation = System::MakeObject<Presentation>();

auto slide = presentation->get_Slides()->idx_get(0);
auxPresentation->get_Slides()->InsertClone(0, slide);

// Setting Slide Type and Size
auxPresentation->get_SlideSize()->SetSize(612.F, 792.F, SlideSizeScaleType::EnsureFit);

System::SharedPtr<PdfOptions> pdfOptions = System::MakeObject<PdfOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
pdfOptions->set_SlidesLayoutOptions(slidesLayoutOptions);
auxPresentation->Save(u"PDFnotes_out.pdf", SaveFormat::Pdf, pdfOptions);
```

## 参照

* クラス [SaveOptions](../saveoptions/)
* クラス [IPdfOptions](../ipdfoptions/)
* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)