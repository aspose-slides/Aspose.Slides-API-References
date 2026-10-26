---
title: IPdfOptions
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションが PDF 形式で保存される方法を制御するオプションを提供します。
type: docs
weight: 274
url: /ja/aspose.slides.export/ipdfoptions/
---
## IPdfOptions クラス

プレゼンテーションが PDF 形式で保存される方法を制御するオプションを提供します。

```cpp
class IPdfOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 風に参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# 風に値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# 風の浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# 風の浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [PdfAccessPermissions](../pdfaccesspermissions/) [get_AccessPermissions](./get_accesspermissions/)() | ユーザーアクセスでドキュメントが開かれたときに付与すべきアクセス許可を指定するフラグのセットを含みます。[PdfAccessPermissions](../pdfaccesspermissions/) を参照してください。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\> [get_AdditionalCommonFontFamilies](./get_additionalcommonfontfamilies/)() | [Aspose.Slides](../../aspose.slides/) が共通とみなすフォントファミリーのユーザー定義名の配列を返します。[System::String](../../system/string/)[] を参照してください。 |
| virtual **bool** [get_ApplyImageTransparent](./get_applyimagetransparent/)() | **true** の場合、指定された透明色を画像に適用します。 |
| virtual **bool** [get_BestImagesCompressionRatio](./get_bestimagescompressionratio/)() | 各画像に対してデフォルトではなく最も効果的な圧縮を自動的に選択すべきかを示します。**bool**.true に設定すると、プレゼンテーション内のすべての画像に最適な圧縮アルゴリズムが選択され、結果として PDF ドキュメントのサイズが小さくなります。 |
| virtual [PdfCompliance](../pdfcompliance/) [get_Compliance](./get_compliance/)() | 生成された PDF ドキュメントの目標標準拠レベルです。[PdfCompliance](../pdfcompliance/) を参照してください。 |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | ソースフォントが見つからない場合に使用されるフォントを返します。[System::String](../../system/string/) を参照してください。 |
| virtual **bool** [get_DrawSlidesFrame](./get_drawslidesframe/)() | 各スライドの周囲に黒枠を描画する場合は **bool** に書き込んでください。 |
| virtual **bool** [get_EmbedFullFonts](./get_embedfullfonts/)() | フォントのすべての文字を埋め込むか、使用されたサブセットのみを埋め込むかを決定します。**bool** に書き込んでください。 |
| virtual **bool** [get_EmbedTrueTypeFontsForASCII](./get_embedtruetypefontsforascii/)() | ASCII 文字 32-127 用に TrueType フォントを埋め込む場合は **bool** に書き込んでください。127 より大きい文字コードについては [Fonts](../../aspose.slides/fonts/) が常に埋め込まれます。 |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | グラデーションのビジュアルスタイルを返します。[GradientStyle](../../aspose.slides/gradientstyle/) を参照してください。 |
| virtual [System::Drawing::Color](../../system.drawing/color/) [get_ImageTransparentColor](./get_imagetransparentcolor/)() | 画像の透明色を取得します。 |
| virtual **bool** [get_IncludeOleData](./get_includeoledata/)() | プレゼンテーションのすべての OLE データを結果の PDF に埋め込みファイルに変換する場合は **bool** に書き込んでください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | エクスポートドキュメントでの [Ink](../../aspose.slides.ink/) オブジェクトの外観を制御するオプションを提供します。読み取り専用 [IInkOptions](../iinkoptions/) |
| virtual **uint8_t** [get_JpegQuality](./get_jpegquality/)() | PDF ドキュメント内の JPEG 画像の品質を決定する値を返します。**uint8_t** を参照してください。 |
| virtual [System::String](../../system/string/) [get_Password](./get_password/)() | PDF ドキュメントを保護するためのユーザーパスワードを設定します。[System::String](../../system/string/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | 進捗更新（パーセンテージ）を保存するコールバックオブジェクトを表します。[IProgressCallback](../../aspose.slides/iprogresscallback/) を参照してください。 |
| virtual **bool** [get_RasterizeUnsupportedFontStyles](./get_rasterizeunsupportedfontstyles/)() | フォントが太字スタイルをサポートしない場合に、テキストをビットマップとしてラスタライズし PDF に保存すべきかを示します。この方法は特定のフォントに対して、結果の PDF のテキスト品質を向上させることがあります。**bool** を参照してください。 |
| virtual **bool** [get_SaveMetafilesAsPng](./get_savemetafilesaspng/)() | プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換する場合は **bool** に書き込んでください。 |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは **false** です。 |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。**bool** に書き込んでください。デフォルト値は **false** です。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを取得します [ISlidesLayoutOptions](../islideslayoutoptions/)。 |
| virtual **float** [get_SufficientResolution](./get_sufficientresolution/)() | PDF ドキュメント内の画像解像度を決定する値を返します。 |
| virtual [PdfTextCompression](../pdftextcompression/) [get_TextCompression](./get_textcompression/)() | ドキュメント内のすべてのテキストコンテンツに使用される圧縮タイプを指定します。[PdfTextCompression](../pdftextcompression/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | 警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを返します。[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) を参照してください。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_AccessPermissions](./set_accesspermissions/)([PdfAccessPermissions](../pdfaccesspermissions/)) | ユーザーアクセスでドキュメントが開かれたときに付与すべきアクセス許可を指定するフラグのセットを含みます。[PdfAccessPermissions](../pdfaccesspermissions/) を参照してください。 |
| virtual void [set_AdditionalCommonFontFamilies](./set_additionalcommonfontfamilies/)([System::ArrayPtr](../../system/arrayptr/)\<[System::String](../../system/string/)\>) | [Aspose.Slides](../../aspose.slides/) が共通とみなすフォントファミリーのユーザー定義名の配列を設定します。[System::String](../../system/string/)[] に書き込みます。 |
| virtual void [set_ApplyImageTransparent](./set_applyimagetransparent/)(**bool**) | **true** の場合、指定された透明色を画像に適用します。 |
| virtual void [set_BestImagesCompressionRatio](./set_bestimagescompressionratio/)(**bool**) | 各画像に対してデフォルトではなく最も効果的な圧縮を自動的に選択すべきかを示します。**bool**.true に設定すると、プレゼンテーション内のすべての画像に最適な圧縮アルゴリズムが選択され、結果として PDF ドキュメントのサイズが小さくなります。**bool** に書き込んでください。 |
| virtual void [set_Compliance](./set_compliance/)([PdfCompliance](../pdfcompliance/)) | 生成された PDF ドキュメントの目標標準拠レベルです。[PdfCompliance](../pdfcompliance/) に書き込んでください。 |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | ソースフォントが見つからない場合に使用されるフォントを設定します。[System::String](../../system/string/) に書き込みます。 |
| virtual void [set_DrawSlidesFrame](./set_drawslidesframe/)(**bool**) | 各スライドの周囲に黒枠を描画するには **bool** に書き込んでください。 |
| virtual void [set_EmbedFullFonts](./set_embedfullfonts/)(**bool**) | フォントのすべての文字を埋め込むか、使用されたサブセットのみを埋め込むかを決定します。**bool** に書き込んでください。 |
| virtual void [set_EmbedTrueTypeFontsForASCII](./set_embedtruetypefontsforascii/)(**bool**) | ASCII 文字 32-127 用に TrueType フォントを埋め込む場合は **bool** に書き込んでください。127 より大きい文字コードについては [Fonts](../../aspose.slides/fonts/) が常に埋め込まれます。 |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | グラデーションのビジュアルスタイルを設定します。[GradientStyle](../../aspose.slides/gradientstyle/) に書き込んでください。 |
| virtual void [set_ImageTransparentColor](./set_imagetransparentcolor/)([System::Drawing::Color](../../system.drawing/color/)) | 画像の透明色を設定します。 |
| virtual void [set_IncludeOleData](./set_includeoledata/)(**bool**) | プレゼンテーションのすべての OLE データを結果の PDF に埋め込みファイルに変換する場合は **bool** に書き込んでください。 |
| virtual void [set_JpegQuality](./set_jpegquality/)(**uint8_t**) | PDF ドキュメント内の JPEG 画像の品質を決定する値を設定します。**uint8_t** に書き込んでください。 |
| virtual void [set_Password](./set_password/)([System::String](../../system/string/)) | PDF ドキュメントを保護するためのユーザーパスワードを設定します。[System::String](../../system/string/) に書き込んでください。 |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | 進捗更新（パーセンテージ）を保存するコールバックオブジェクトを表します。[IProgressCallback](../../aspose.slides/iprogresscallback/) を参照してください。 |
| virtual void [set_RasterizeUnsupportedFontStyles](./set_rasterizeunsupportedfontstyles/)(**bool**) | フォントが太字スタイルをサポートしない場合に、テキストをビットマップとしてラスタライズし PDF に保存すべきかを示します。この方法は特定のフォントに対して、結果の PDF のテキスト品質を向上させることがあります。**bool** に書き込んでください。 |
| virtual void [set_SaveMetafilesAsPng](./set_savemetafilesaspng/)(**bool**) | プレゼンテーションで使用されるすべてのメタファイルを PNG 画像に変換する場合は **bool** に書き込んでください。 |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは **false** です。 |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。**bool** に書き込んでください。デフォルト値は **false** です。 |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを設定します [ISlidesLayoutOptions](../islideslayoutoptions/)。 |
| virtual void [set_SufficientResolution](./set_sufficientresolution/)(**float**) | PDF ドキュメント内の画像解像度を決定する値を設定します。 |
| virtual void [set_TextCompression](./set_textcompression/)([PdfTextCompression](../pdftextcompression/)) | ドキュメント内のすべてのテキストコンテンツに使用される圧縮タイプを指定します。[PdfTextCompression](../pdftextcompression/) に書き込んでください。 |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | 警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを設定します。[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/) に書き込んでください。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | テンプレート引数 n 番目を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [ISaveOptions](../isaveoptions/)
* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)