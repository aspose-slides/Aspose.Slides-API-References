---
title: SVGOptions
second_title: Aspose.Slides for C++ API リファレンス
description: SVG オプションを表します。
type: docs
weight: 703
url: /ja/aspose.slides.export/svgoptions/
---
## SVGOptions クラス

SVG オプションを表します。

```cpp
class SVGOptions : public Aspose::Slides::Export::SaveOptions,
                   public Aspose::Slides::Export::ISVGOptions
```

## メソッド

| Method | Description |
| --- | --- |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部的な目的のみです。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Default](./get_default/)() | デフォルト設定を返します。読み取り専用 [SVGOptions](./)。 |
| [System::String](../../system/string/) [get_DefaultRegularFont](../saveoptions/get_defaultregularfont/)() override | フォントが見つからない場合に使用されるフォントを返します。読み取り [System::String](../../system/string/)。 |
| **bool** [get_DeletePicturesCroppedAreas](./get_deletepicturescroppedareas/)() override | ブールフラグは、トリミングされた部分がドキュメントの一部として残るかどうかを示します。true の場合、トリミングされた部分は削除され、false の場合はドキュメントにシリアライズされます（ファイルが大きくなる可能性があります）。 |
| **bool** [get_Disable3DText](./get_disable3dtext/)() override | SVG で 3D テキストが無効かどうかを決定します。読み取り **bool**。 |
| **bool** [get_DisableFontLigatures](./get_disablefontligatures/)() override | テキストが合字を使用せずにレンダリングされるかどうかを示す値を取得します。**true** に設定すると、レンダリング出力で合字が無効になります。既定ではこのプロパティは **false** に設定されています。 |
| **bool** [get_DisableGradientSplit](./get_disablegradientsplit/)() override | FromCornerX および FromCenter グラデーションの分割を無効にします。読み取り **bool**。 |
| **bool** [get_DisableLineEndCropping](./get_disablelineendcropping/)() override | SVG 1.1 ではマーカーのインセットを定義できません。[Aspose.Slides](../../aspose.slides/) SVG 書き込みエンジンはその問題に対処するため、矢印付きの線の端をトリミングし、線がマーカーと重ならないようにします。このオプションはその動作をオフにします。読み取り **bool**。 |
| [SvgExternalFontsHandling](../svgexternalfontshandling/) [get_ExternalFontsHandling](./get_externalfontshandling/)() override | 外部ロードされたフォントの処理方法を決定します。読み取り [SvgExternalFontsHandling](../svgexternalfontshandling/)。 |
| [Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/) [get_GradientStyle](../saveoptions/get_gradientstyle/)() override | グラデーションのビジュアルスタイルを返します。読み取り [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IInkOptions](../iinkoptions/)\> [get_InkOptions](./get_inkoptions/)() override | エクスポートされたドキュメント内の [Ink](../../aspose.slides.ink/) オブジェクトの外観を制御するオプションを提供します。読み取り専用 [IInkOptions](../iinkoptions/) |
| **int32_t** [get_JpegQuality](./get_jpegquality/)() override | JPEG エンコード品質を決定します。読み取り **int32_t**。 |
| **int32_t** [get_MetafileRasterizationDpi](./get_metafilerasterizationdpi/)() override | メタファイルのラスタライズの下限解像度を返します。読み取り **int32_t**。 |
| [Aspose::Slides::Export::PicturesCompression](../picturescompression/) [get_PicturesCompression](./get_picturescompression/)() override | 画像の圧縮レベルを表します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\> [get_ProgressCallback](../saveoptions/get_progresscallback/)() override | 進捗更新をパーセンテージで保存するコールバックオブジェクトを表します。[IProgressCallback](../../aspose.slides/iprogresscallback/) を参照。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\> [get_ShapeFormattingController](./get_shapeformattingcontroller/)() override | ユーザーがシェイプ変換を制御できるコールバックインターフェイスを返し、設定します。読み取り [ISvgShapeFormattingController](../isvgshapeformattingcontroller/)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_Simple](./get_simple/)() | 最もシンプルで小さい SVG ファイル生成の設定を返します。読み取り専用 [SVGOptions](./)。 |
| **bool** [get_SkipJavaScriptLinks](../saveoptions/get_skipjavascriptlinks/)() override | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。読み取り **bool**。デフォルト値は **false** です。 |
| **bool** [get_UseFrameRotation](./get_useframerotation/)() override | レンダリング時にシェイプの指定回転を実行するかどうかを決定します。読み取り **bool**。デフォルト値は true です。 |
| **bool** [get_UseFrameSize](./get_useframesize/)() override | テキストフレームをレンダリング領域に含めるかどうかを決定します。読み取り **bool**。デフォルト値は false です。 |
| **bool** [get_VectorizeText](./get_vectorizetext/)() override | スライド上のテキストをグラフィックとして保存するかどうかを決定します。読み取り **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\> [get_WarningCallback](../saveoptions/get_warningcallback/)() override | 警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを返すまたは設定します。読み取り [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| static [System::SharedPtr](../../system/sharedptr/)\<[SVGOptions](./)\> [get_WYSIWYG](./get_wysiwyg/)() | 最も正確な SVG ファイル生成の設定を返します。読み取り専用 [SVGOptions](./)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
|  [SaveOptions](../saveoptions/saveoptions/)() |  |
| void [set_DefaultRegularFont](../saveoptions/set_defaultregularfont/)([System::String](../../system/string/)) override | フォントが見つからない場合に使用されるフォントを設定します。[System::String](../../system/string/) に書き込みます。 |
| void [set_DeletePicturesCroppedAreas](./set_deletepicturescroppedareas/)(**bool**) override | ブールフラグは、トリミングされた部分がドキュメントの一部として残るかどうかを示します。true の場合、トリミングされた部分は削除され、false の場合はドキュメントにシリアライズされます（ファイルが大きくなる可能性があります）。 |
| void [set_Disable3DText](./set_disable3dtext/)(**bool**) override | SVG で 3D テキストが無効かどうかを決定します。書き込み **bool**。 |
| void [set_DisableFontLigatures](./set_disablefontligatures/)(**bool**) override | テキストが合字を使用せずにレンダリングされるかどうかを示す値を設定します。**true** に設定すると、レンダリング出力で合字が無効になります。既定ではこのプロパティは **false** に設定されています。 |
| void [set_DisableGradientSplit](./set_disablegradientsplit/)(**bool**) override | FromCornerX および FromCenter グラデーションの分割を無効にします。書き込み **bool**。 |
| void [set_DisableLineEndCropping](./set_disablelineendcropping/)(**bool**) override | SVG 1.1 ではマーカーのインセットを定義できません。[Aspose.Slides](../../aspose.slides/) SVG 書き込みエンジンはこの問題への対処として、矢印付きの線の端をトリミングし、線がマーカーと重ならないようにします。このオプションはその動作をオフにします。書き込み **bool**。 |
| void [set_ExternalFontsHandling](./set_externalfontshandling/)([SvgExternalFontsHandling](../svgexternalfontshandling/)) override | 外部ロードされたフォントの処理方法を決定します。書き込み [SvgExternalFontsHandling](../svgexternalfontshandling/)。 |
| void [set_GradientStyle](../saveoptions/set_gradientstyle/)([Aspose::Slides::GradientStyle](../../aspose.slides/gradientstyle/)) override | グラデーションのビジュアルスタイルを設定します。書き込み [GradientStyle](../../aspose.slides/gradientstyle/)。 |
| void [set_JpegQuality](./set_jpegquality/)(**int32_t**) override | JPEG エンコード品質を決定します。書き込み **int32_t**。 |
| void [set_MetafileRasterizationDpi](./set_metafilerasterizationdpi/)(**int32_t**) override | メタファイルのラスタライズの下限解像度を設定します。書き込み **int32_t**。 |
| void [set_PicturesCompression](./set_picturescompression/)([Aspose::Slides::Export::PicturesCompression](../picturescompression/)) override | 画像の圧縮レベルを表します。 |
| void [set_ProgressCallback](../saveoptions/set_progresscallback/)([System::SharedPtr](../../system/sharedptr/)\<[IProgressCallback](../../aspose.slides/iprogresscallback/)\>) override | 進捗更新をパーセンテージで保存するコールバックオブジェクトを表します。[IProgressCallback](../../aspose.slides/iprogresscallback/) を参照。 |
| void [set_ShapeFormattingController](./set_shapeformattingcontroller/)([System::SharedPtr](../../system/sharedptr/)\<[ISvgShapeFormattingController](../isvgshapeformattingcontroller/)\>) override | ユーザーがシェイプ変換を制御できるコールバックインターフェイスを返し、設定します。書き込み [ISvgShapeFormattingController](../isvgshapeformattingcontroller/)。 |
| void [set_SkipJavaScriptLinks](../saveoptions/set_skipjavascriptlinks/)(**bool**) override | プレゼンテーションを保存する際に、JavaScript 呼び出しを含むハイパーリンクをスキップするかどうかを指定します。書き込み **bool**。デフォルト値は **false** です。 |
| void [set_UseFrameRotation](./set_useframerotation/)(**bool**) override | レンダリング時にシェイプの指定回転を実行するかどうかを決定します。書き込み **bool**。デフォルト値は true です。 |
| void [set_UseFrameSize](./set_useframesize/)(**bool**) override | テキストフレームをレンダリング領域に含めるかどうかを決定します。書き込み **bool**。デフォルト値は false です。 |
| void [set_VectorizeText](./set_vectorizetext/)(**bool**) override | スライド上のテキストをグラフィックとして保存するかどうかを決定します。書き込み **bool**。 |
| void [set_WarningCallback](../saveoptions/set_warningcallback/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)\>) override | 警告を受け取り、ロードプロセスを継続するか中止するかを決定するオブジェクトを返すまたは設定します。書き込み [Aspose::Slides::Warnings::IWarningCallback](../../aspose.slides.warnings/iwarningcallback/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることが可能です。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
|  [SVGOptions](./svgoptions/)() | [SVGOptions](./) クラスの新しいインスタンスを初期化します。 |
|  [SVGOptions](./svgoptions/)([System::SharedPtr](../../system/sharedptr/)\<[ILinkEmbedController](../ilinkembedcontroller/)\>) | [SVGOptions](./) クラスの新しいインスタンスを、リンク埋め込みコントローラオブジェクトを指定して初期化します。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のアンロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用します。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [SaveOptions](../saveoptions/)
* クラス [ISVGOptions](../isvgoptions/)
* 名前空間 [Aspose::Slides::Export](../)
* ライブラリ [Aspose.Slides](../../)