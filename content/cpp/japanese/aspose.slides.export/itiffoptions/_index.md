---
title: ITiffOptions
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションを TIFF 形式で保存する方法を制御するオプションを提供します。
type: docs
weight: 495
url: /ja/aspose.slides.export/itiffoptions/
---
## ITiffOptions クラス

プレゼンテーションが TIFF 形式で保存される方法を制御するオプションを提供します。

```cpp
class ITiffOptions : public virtual Aspose::Slides::Export::ISaveOptions
```

## メソッド

| Method | 説明 |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# の [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいと見なす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいと見なす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部目的専用です。 |
| virtual [BlackWhiteConversionMode](../blackwhiteconversionmode/) [get_BwConversionMode](./get_bwconversionmode/)() | カラー画像を白黒画像に変換するアルゴリズムを指定します。このオプションは [ITiffOptions::get_CompressionType()](./get_compressiontype/) が [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) または [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) に設定されている場合にのみ適用されます。読み取り [BlackWhiteConversionMode](../blackwhiteconversionmode/)。既定値は [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/)です。 |
| virtual [TiffCompressionTypes](../tiffcompressiontypes/) [get_CompressionType](./get_compressiontype/)() | 圧縮タイプを指定します。読み取り [TiffCompressionTypes](../tiffcompressiontypes/)。 |
| virtual [System::String](../../system/string/) [get_DefaultRegularFont](../isaveoptions/get_defaultregularfont/)() | 元のフォントが見つからない場合に使用されるフォントを返します。読み取り [System::String](../../system/string/)。 |
| virtual **uint32_t** [get_DpiX](./get_dpix/)() | 水平解像度（dpi）を指定します。読み取り **uint32_t**。 |
| virtual **uint32_t** [get_DpiY](./get_dpiy/)() | 垂直解像度（dpi）を指定します。読み取り **uint32_t**。 |
| virtual [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../isaveoptions/get_gradientstyle/)() | グラデーションの視覚スタイルを返します。読み取り [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| virtual [System::Drawing::Size](../../system.drawing/size/) [get_ImageSize](./get_imagesize/)() | 生成された TIFF 画像のサイズを指定します。デフォルト値は 0x0 で、これは生成画像サイズがプレゼンテーションのスライドサイズに基づいて計算されることを意味します。読み取り [System::Drawing::Size](../../system.drawing/size/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() | エクスポートされたドキュメント内の [Ink](../../aspose.slides.ink/) オブジェクトの外観を制御するオプションを提供します。読み取り専用 [IInkOptions](../iinkoptions/) |
| virtual [ImagePixelFormat](../imagepixelformat/) [get_PixelFormat](./get_pixelformat/)() | 生成された画像のピクセルフォーマットを指定します。読み取り [ImagePixelFormat](../imagepixelformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../isaveoptions/get_progresscallback/)() | 進捗率の更新を保存するためのコールバックオブジェクトを表します。[IProgressCallback](../../aspose.slides/iprogresscallback/) を参照してください。 |
| virtual **bool** [get_ShowHiddenSlides](./get_showhiddenslides/)() | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。既定は **false** です。 |
| virtual **bool** [get_SkipJavaScriptLinks](../isaveoptions/get_skipjavascriptlinks/)() | プレゼンテーションの保存時に JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。読み取り **bool**。デフォルト値は **false** です。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\> [get_SlidesLayoutOptions](./get_slideslayoutoptions/)() | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得します [ISlidesLayoutOptions](../islideslayoutoptions/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../isaveoptions/get_warningcallback/)() | 警告を受け取り、ロード処理を継続するか中止するかを決定するオブジェクトを返します。読み取り [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 参照で値型オブジェクトと nullptr を比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [set_BwConversionMode](./set_bwconversionmode/)([BlackWhiteConversionMode](../blackwhiteconversionmode/)) | カラー画像を白黒画像に変換するアルゴリズムを指定します。このオプションは [ITiffOptions::get_CompressionType()](./get_compressiontype/) が [TiffCompressionTypes::CCITT4](../tiffcompressiontypes/) または [TiffCompressionTypes::CCITT3](../tiffcompressiontypes/) に設定されている場合にのみ適用されます。書き込み [BlackWhiteConversionMode](../blackwhiteconversionmode/)。既定値は [BlackWhiteConversionMode::Default](../blackwhiteconversionmode/)です。 |
| virtual void [set_CompressionType](./set_compressiontype/)([TiffCompressionTypes](../tiffcompressiontypes/)) | 圧縮タイプを指定します。書き込み [TiffCompressionTypes](../tiffcompressiontypes/)。 |
| virtual void [set_DefaultRegularFont](../isaveoptions/set_defaultregularfont/)([System::String](../../system/string/)) | 元のフォントが見つからない場合に使用されるフォントを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_DpiX](./set_dpix/)(**uint32_t**) | 水平解像度（dpi）を指定します。書き込み **uint32_t**。 |
| virtual void [set_DpiY](./set_dpiy/)(**uint32_t**) | 垂直解像度（dpi）を指定します。書き込み **uint32_t**。 |
| virtual void [set_GradientStyle](../isaveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) | グラデーションの視覚スタイルを設定します。書き込み [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| virtual void [set_ImageSize](./set_imagesize/)([System::Drawing::Size](../../system.drawing/size/)) | 生成された TIFF 画像のサイズを指定します。デフォルト値は 0x0 で、生成画像サイズがプレゼンテーションのスライドサイズに基づいて計算されることを意味します。書き込み [System::Drawing::Size](../../system.drawing/size/)。 |
| virtual void [set_PixelFormat](./set_pixelformat/)([ImagePixelFormat](../imagepixelformat/)) | 生成された画像のピクセルフォーマットを指定します。書き込み [ImagePixelFormat](../imagepixelformat/)。 |
| virtual void [set_ProgressCallback](../isaveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) | 進捗率の更新を保存するコールバックオブジェクトを表します。[IProgressCallback](../../aspose.slides/iprogresscallback/) を参照してください。 |
| virtual void [set_ShowHiddenSlides](./set_showhiddenslides/)(**bool**) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。既定は **false** です。 |
| virtual void [set_SkipJavaScriptLinks](../isaveoptions/set_skipjavascriptlinks/)(**bool**) | プレゼンテーションの保存時に JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。書き込み **bool**。デフォルト値は **false** です。 |
| virtual void [set_SlidesLayoutOptions](./set_slideslayoutoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ISlidesLayoutOptions](../islideslayoutoptions/)\>) | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを設定します [ISlidesLayoutOptions](../islideslayoutoptions/)。 |
| virtual void [set_WarningCallback](../isaveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) | 警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを設定します。書き込み [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [ISaveOptions](../isaveoptions/)
* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)