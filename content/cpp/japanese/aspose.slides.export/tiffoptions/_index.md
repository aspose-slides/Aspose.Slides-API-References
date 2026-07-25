---
title: TiffOptions
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションを TIFF 形式で保存する方法を制御するオプションを提供します。
type: docs
weight: 768
url: /ja/aspose.slides.export/tiffoptions/
---
## TiffOptions クラス

プレゼンテーションを TIFF 形式で保存する方法を制御するオプションを提供します。

```cpp
class TiffOptions : public Aspose::Slides::Export::SaveOptions,
                    public Aspose::Slides::Export::ITiffOptions
```

## メソッド

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部使用専用です。 |
| [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() override | カラー画像を白黒画像に変換するアルゴリズムを指定します。このオプションは [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) が [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) または [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) に設定されている場合にのみ適用されます。読み取り [BlackWhiteConversionMode](../blackwhiteconversionmode/)。デフォルトは [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/) です。 |
| [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() override | 圧縮タイプを指定します。読み取り [TiffCompressionTypes](../tiffcompressiontypes/)。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | ソースフォントが見つからない場合に使用されるフォントを返します。読み取り [System::String](../../system/string/)。 |
| **uint32_t** [get_DpiX](./get_dpix/)() override | インチあたりドット数で水平解像度を指定します。読み取り **uint32_t**。 |
| **uint32_t** [get_DpiY](./get_dpiy/)() override | インチあたりドット数で垂直解像度を指定します。読み取り **uint32_t**。 |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | グラデーションのビジュアルスタイルを返します。読み取り [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() override | 生成される TIFF 画像のサイズを指定します。デフォルト値は 0x0 で、これは生成画像のサイズがプレゼンテーションのスライドサイズに基づいて計算されることを意味します。読み取り [System::Drawing::Size](../../system.drawing/size/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | エクスポートされたドキュメント内の [Ink](../../aspose.slides.ink/) オブジェクトの外観を制御するオプションを提供します。読み取り専用 [IInkOptions](../iinkoptions/) |
| [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() override | 生成された画像のピクセル形式を指定します。読み取り [ImagePixelFormat](../imagepixelformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 進捗率の保存更新のためのコールバックオブジェクトを表します。[IProgressCallback](../../aspose.slides/iprogresscallback/) を参照してください。 |
| **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() override | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは **false** です。 |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | プレゼンテーションを保存する際に JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。読み取り **bool**。デフォルト値は **false** です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() override | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得します [ISlidesLayoutOptions](../islideslayoutoptions/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 警告を受け取り、読み込みプロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。読み取り [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) override | カラー画像を白黒画像に変換するアルゴリズムを指定します。このオプションは [ITiffOptions::get_CompressionType()](../itiffoptions/get_compressiontype/) が [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) または [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) に設定されている場合にのみ適用されます。書き込み [BlackWhiteConversionMode](../blackwhiteconversionmode/)。デフォルトは [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/) です。 |
| void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) override | 圧縮タイプを指定します。書き込み [TiffCompressionTypes](../tiffcompressiontypes/)。 |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | ソースフォントが見つからない場合に使用されるフォントを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_DpiX](./set_dpix/)(**uint32_t**) override | インチあたりドット数で水平解像度を指定します。書き込み **uint32_t**。 |
| void [set_DpiY](./set_dpiy/)(**uint32_t**) override | インチあたりドット数で垂直解像度を指定します。書き込み **uint32_t**。 |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | グラデーションのビジュアルスタイルを設定します。書き込み [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) override | 生成される TIFF 画像のサイズを指定します。デフォルト値は 0x0 で、これは生成画像のサイズがプレゼンテーションのスライドサイズに基づいて計算されることを意味します。書き込み [System::Drawing::Size](../../system.drawing/size/)。 |
| void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) override | 生成された画像のピクセル形式を指定します。書き込み [ImagePixelFormat](../imagepixelformat/)。 |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 進捗率の保存更新のためのコールバックオブジェクトを表します。[IProgressCallback](../../aspose.slides/iprogresscallback/) を参照してください。 |
| void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) override | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは **false** です。 |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | プレゼンテーションを保存する際に JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。書き込み **bool**。デフォルト値は **false** です。 |
| void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) override | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを設定します [ISlidesLayoutOptions](../islideslayoutoptions/)。 |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 警告を受け取り、読み込みプロセスを継続するか中止するかを決定するオブジェクトを取得または設定します。書き込み [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
|  [TiffOptions](./tiffoptions/)() |  |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 備考

次の例は、PowerPoint をデフォルトサイズの TIFF に変換する方法を示しています。  
```cpp
// プレゼンテーションファイルを表す Presentation オブジェクトを生成します
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

// プレゼンテーションを TIFF ドキュメントとして保存します
presentation->Save(u"Tiffoutput_out.tiff", SaveFormat::Tiff);
```
次の例は、PowerPoint をカスタムサイズの TIFF に変換する方法を示しています。  
```cpp
// プレゼンテーションファイルを表す Presentation オブジェクトを生成します
auto pres = System::MakeObject<Presentation>(u"Convert_Tiff_Custom.pptx");

// TiffOptions クラスを生成します
System::SharedPtr<TiffOptions> opts = System::MakeObject<TiffOptions>();
// 圧縮タイプを設定します
opts->set_CompressionType(TiffCompressionTypes::Default);

System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomFull);
opts->set_SlidesLayoutOptions(slidesLayoutOptions);

// 圧縮タイプ
// Default - デフォルトの圧縮方式 (LZW) を指定します。
// None - 圧縮なしを指定します。
// CCITT3
// CCITT4
// LZW
// RLE
// 深度は圧縮タイプに依存し、手動で設定できません。
// 解像度単位は常に "2"（ドット毎インチ）です。
// 画像 DPI を設定します
opts->set_DpiX(200);
opts->set_DpiY(100);
// 画像サイズを設定します
opts->set_ImageSize(System::Drawing::Size(1728, 1078));
// 指定した画像サイズでプレゼンテーションを TIFF として保存します
pres->Save(u"TiffWithCustomSize_out.tiff", SaveFormat::Tiff, opts);
```
次の例は、PowerPoint をカスタム画像ピクセル形式の TIFF に変換する方法を示しています。  
```cpp
// プレゼンテーションファイルを表す Presentation オブジェクトを生成します
auto presentation = System::MakeObject<Presentation>(u"DemoFile.pptx");

System::SharedPtr<TiffOptions> options = System::MakeObject<TiffOptions>();
options->set_PixelFormat(ImagePixelFormat::Format8bppIndexed);

// 指定した画像サイズでプレゼンテーションを TIFF として保存します
presentation->Save(u"Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat::Tiff, options);
```

## 参照

* クラス [SaveOptions](../saveoptions/)
* クラス [ITiffOptions](../itiffoptions/)
* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)