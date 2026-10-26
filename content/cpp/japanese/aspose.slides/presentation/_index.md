---
title: Presentation
second_title: Aspose.Slides for C++ API リファレンス
description: Microsoft PowerPoint プレゼンテーションを表します。
type: docs
weight: 4837
url: /ja/aspose.slides/presentation/
---
## Presentation クラス

Microsoft PowerPoint プレゼンテーションを表します。

```cpp
class Presentation : public Aspose::Slides::IPresentation,
                     public Aspose::Slides::IDOMObject
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| void [Dispose](./dispose/)() override | この [Presentation](./) オブジェクトが使用するすべてのリソースを解放します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# の [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は NaN を含む任意の値と等しくありませんが、ここでは 2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は NaN を含む任意の値と等しくありませんが、ここでは 2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用です。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ICustomXmlPart](../icustomxmlpart/)\>\> [get_AllCustomXmlParts](./get_allcustomxmlparts/)() override | プレゼンテーション内のすべてのカスタム データ パーツを返します。読み取り専用 [ICustomXmlPart](../icustomxmlpart/)[]。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Audio](./get_audio/)(**int32_t**) override | 指定されたインデックスのプレゼンテーション内の埋め込みオーディオ ファイルを返します。読み取り専用 [Aspose::Slides::IAudio](../iaudio/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudioCollection](../iaudiocollection/)\> [get_Audios](./get_audios/)() override | プレゼンテーション内のすべての埋め込みオーディオ ファイルのコレクションを返します。読み取り専用 [IAudioCollection](../iaudiocollection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_CommentAuthor](./get_commentauthor/)(**int32_t**) override | 指定されたインデックスのコメント作者を返します。読み取り専用 [Aspose::Slides::ICommentAuthor](../icommentauthor/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthorCollection](../icommentauthorcollection/)\> [get_CommentAuthors](./get_commentauthors/)() override | コメント作者のコレクションを返します。読み取り専用 [ICommentAuthorCollection](../icommentauthorcollection/)。 |
| [System::DateTime](../../system/datetime/) [get_CurrentDateTime](./get_currentdatetime/)() override | 日時フィールドの内容を置き換える日付と時刻を返します。既定ではこの [Presentation](./) オブジェクトの作成時刻です。読み取り [System::DateTime](../../system/datetime/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() override | プレゼンテーションのカスタム データを返します。読み取り専用 [ICustomData](../icustomdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_DefaultTextStyle](./get_defaulttextstyle/)() override | シェイプのデフォルトテキストスタイルを返します。読み取り専用 [ITextStyle](../itextstyle/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignature](../idigitalsignature/)\> [get_DigitalSignature](./get_digitalsignature/)(**int32_t**) override | 指定されたインデックスでプレゼンテーションに署名するために使用されたデジタル署名を返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignatureCollection](../idigitalsignaturecollection/)\> [get_DigitalSignatures](./get_digitalsignatures/)() override | プレゼンテーションに署名するために使用された署名のコレクションを返します。読み取り専用 [IDigitalSignatureCollection](../idigitalsignaturecollection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [get_DocumentProperties](./get_documentproperties/)() override | [DocumentProperties](../documentproperties/) オブジェクトを返します。このオブジェクトは標準およびカスタム ドキュメント プロパティを含みます。読み取り専用 [IDocumentProperties](../idocumentproperties/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_DocumentProperty](./get_documentproperty/)([System::String](../../system/string/)) override | 名前で定義されたカスタム プロパティを返します。 |
| **int32_t** [get_FirstSlideNumber](./get_firstslidenumber/)() override | プレゼンテーション内の最初のスライド番号を表します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFontsManager](../ifontsmanager/)\> [get_FontsManager](./get_fontsmanager/)() override | フォント マネージャーを返します。読み取り専用 [IFontsManager](../ifontsmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() override | 実際のヘッダー/フッターマネージャーを返します。読み取り専用 [IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() override | すべてのプレゼンテーション スライド（マスター、レイアウト、ノート スライドを除く）に含まれるすべてのハイパーリンクへの簡単なアクセスを提供します。読み取り専用 [IHyperlinkQueries](../ihyperlinkqueries/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_Image](./get_image/)(**int32_t**) override | 指定されたインデックスのプレゼンテーション内の画像を返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImageCollection](../iimagecollection/)\> [get_Images](./get_images/)() override | プレゼンテーション内のすべての画像のコレクションを返します。読み取り専用 [IImageCollection](../iimagecollection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) override | インデックスでレイアウト スライドを返します。読み取り専用 [Aspose::Slides::ILayoutSlide](../ilayoutslide/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGlobalLayoutSlideCollection](../igloballayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() override | プレゼンテーションで定義されているすべてのレイアウト スライドのリストを返します。読み取り専用 [IGlobalLayoutSlideCollection](../igloballayoutslidecollection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\> [get_Master](./get_master/)(**int32_t**) override | 指定されたインデックスのプレゼンテーションで定義されたマスター スライドを返します。読み取り専用 [Aspose::Slides::IMasterSlide](../imasterslide/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterHandoutSlideManager](../imasterhandoutslidemanager/)\> [get_MasterHandoutSlideManager](./get_masterhandoutslidemanager/)() override | ハンドアウト マスター マネージャーを返します。読み取り専用 [IMasterHandoutSlideManager](../imasterhandoutslidemanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterNotesSlideManager](../imasternotesslidemanager/)\> [get_MasterNotesSlideManager](./get_masternotesslidemanager/)() override | ノート マスター マネージャーを返します。読み取り専用 [IMasterNotesSlideManager](../imasternotesslidemanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideCollection](../imasterslidecollection/)\> [get_Masters](./get_masters/)() override | プレゼンテーションで定義されているすべてのマスター スライドのリストを返します。読み取り専用 [IMasterSlideCollection](../imasterslidecollection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/)\> [get_MasterTheme](./get_mastertheme/)() override | マスター テーマを返します。読み取り専用 [Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[INotesSize](../inotessize/)\> [get_NotesSize](./get_notessize/)() override | ノート スライド サイズ オブジェクトを返します。読み取り専用 [INotesSize](../inotessize/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IProtectionManager](../iprotectionmanager/)\> [get_ProtectionManager](./get_protectionmanager/)() override | このプレゼンテーションの権限マネージャーを取得します。読み取り専用 [IProtectionManager](../iprotectionmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_Section](./get_section/)(**int32_t**) override | 指定されたインデックスのプレゼンテーションで定義されたスライド セクションを返します。読み取り専用 [Aspose::Slides::ISection](../isection/) |
| [System::SharedPtr](../../system/sharedptr/)\<[ISectionCollection](../isectioncollection/)\> [get_Sections](./get_sections/)() override | プレゼンテーションで定義されたすべてのスライド セクションのリストを返します。読み取り専用 [ISectionCollection](../isectioncollection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabelCollection](../isensitivitylabelcollection/)\> [get_SensitivityLabels](./get_sensitivitylabels/)() override | プレゼンテーション ドキュメントに適用された感度ラベルのコレクションを返します。読み取り専用 [ISensitivityLabelCollection](../isensitivitylabelcollection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](./get_slide/)(**int32_t**) override | 指定されたインデックスのプレゼンテーションで定義されたスライドを返します。読み取り専用 [Aspose::Slides::ISlide](../islide/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideCollection](../islidecollection/)\> [get_Slides](./get_slides/)() override | プレゼンテーションで定義されたすべてのスライドのリストを返します。読み取り専用 [ISlideCollection](../islidecollection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::SlideShowSettings](../slideshowsettings/)\> [get_SlideShowSettings](./get_slideshowsettings/)() const | プレゼンテーションのスライドショー設定を返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISlideSize](../islidesize/)\> [get_SlideSize](./get_slidesize/)() override | スライド サイズ オブジェクトを返します。読み取り専用 [ISlideSize](../islidesize/)。 |
| [Aspose::Slides::SourceFormat](../sourceformat/) [get_SourceFormat](./get_sourceformat/)() override | プレゼンテーションがロードされた形式に関する情報を返します。読み取り専用 [SourceFormat](../sourceformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\> [get_VbaProject](./get_vbaproject/)() override | プレゼンテーションのマクロを含む VBA プロジェクトを取得します。読み取り [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_Video](./get_video/)(**int32_t**) override | 指定されたインデックスのプレゼンテーション内の埋め込みビデオ ファイルを返します。読み取り専用 [Aspose::Slides::IVideo](../ivideo/) |
| [System::SharedPtr](../../system/sharedptr/)\<[IVideoCollection](../ivideocollection/)\> [get_Videos](./get_videos/)() override | プレゼンテーション内のすべての埋め込みビデオ ファイルのコレクションを返します。読み取り専用 [IVideoCollection](../ivideocollection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IViewProperties](../iviewproperties/)\> [get_ViewProperties](./get_viewproperties/)() override | プレゼンテーション全体のビュー プロパティを取得します。読み取り専用 [IViewProperties](../iviewproperties/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタム オブジェクトのハッシュ化を可能にします。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) override | プレゼンテーションのすべてのスライドに対する Image オブジェクトを返します。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) override | プレゼンテーションの指定されたスライドに対するサムネイル Image オブジェクトを返します。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, **float**, **float**) override | カスタム スケーリングでプレゼンテーションのすべてのスライドに対するサムネイル Image オブジェクトを返します。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, **float**, **float**) override | カスタム スケーリングでプレゼンテーションの指定されたスライドに対するサムネイル Image オブジェクトを返します。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::Drawing::Size](../../system.drawing/size/)) override | 指定されたサイズでプレゼンテーションのすべてのスライドに対するサムネイル Image オブジェクトを返します。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [System::Drawing::Size](../../system.drawing/size/)) override | 指定されたサイズでプレゼンテーションの指定されたスライドに対するサムネイル Image オブジェクトを返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [GetSlideById](./getslidebyid/)(**uint32_t**) override | Id により [Slide](../slide/)、[MasterSlide](../masterslide/)、または [LayoutSlide](../layoutslide/) を返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| void [HighlightRegex](./highlightregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | 正規表現のすべての一致箇所を指定された色でハイライトします。 |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/)) override | サンプルテキストのすべての一致箇所を指定された色でハイライトします。 |
| void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | サンプルテキストのすべての一致箇所を指定された色でハイライトします。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかをチェックします。C# の 'is' 演算子の類似です。 |
| void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() override | すべてのスライドのすべての許容されるシェイプ内のすべての段落で、同じ書式のランを結合します。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか [LockContext](../../system/lockcontext/) センティネル オブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
|  [Presentation](./presentation/)() | このコンストラクタは、新規にプレゼンテーションを作成します。作成されたプレゼンテーションには空のスライドが 1 枚含まれます。 |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | このコンストラクタは、新規にプレゼンテーションを作成します。作成されたプレゼンテーションには空のスライドが 1 枚含まれます。 |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | このコンストラクタは既存の [Presentation](./) を読み込む主な手段です。 |
|  [Presentation](./presentation/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | このコンストラクタは既存の [Presentation](./) を読み込む主な手段です。 |
|  [Presentation](./presentation/)([System::String](../../system/string/)) | このコンストラクタは [Presentation](./) の内容を読み込むソース ファイル パスを取得します。 |
|  [Presentation](./presentation/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::LoadOptions](../loadoptions/)\>) | このコンストラクタは [Presentation](./) の内容を読み込むソース ファイル パスを取得します。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | nullptr と値型オブジェクトを参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [ReplaceRegex](./replaceregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | 正規表現のすべての一致箇所を指定された文字列に置換します。 |
| void [ReplaceText](./replacetext/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) override | 指定されたテキストのすべての出現箇所を別の指定テキストに置換します。 |
| void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | プレゼンテーションのすべてのスライドを指定された形式のファイルに保存します。 |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | プレゼンテーションのすべてのスライドを指定された形式のストリームに保存します。 |
| void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | プレゼンテーションのすべてのスライドを指定された形式と追加オプションでファイルに保存します。 |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | プレゼンテーションのすべてのスライドを指定された形式と追加オプションでストリームに保存します。 |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../aspose.slides.export.xaml/ixamloptions/)\>) override | プレゼンテーションのすべてのスライドを XAML マークアップを表すファイルのセットに保存します。 |
| void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | 指定されたスライドをページ番号を保持したまま、指定された形式のファイルに保存します。 |
| void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | 指定されたスライドをページ番号を保持したまま、指定された形式のファイルに保存します。 |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) override | 指定されたスライドをページ番号を保持したまま、指定された形式のストリームに保存します。 |
| void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) override | 指定されたスライドをページ番号を保持したまま、指定された形式のストリームに保存します。 |
| void [set_CurrentDateTime](./set_currentdatetime/)([System::DateTime](../../system/datetime/)) override |日時フィールドの内容を置き換える日付と時刻を設定します。既定ではこの [Presentation](./) オブジェクトの作成時刻です。書き込み [System::DateTime](../../system/datetime/)。 |
| void [set_DocumentProperty](./set_documentproperty/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) override | 名前で定義されたカスタム プロパティを設定します。 |
| void [set_FirstSlideNumber](./set_firstslidenumber/)(**int32_t**) override | プレゼンテーション内の最初のスライド番号を表します。 |
| void [set_VbaProject](./set_vbaproject/)([System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\>) override | プレゼンテーションのマクロを含む VBA プロジェクトを設定します。書き込み [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタム オブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか [LockContext](../../system/lockcontext/) センティネル オブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 備考

次の例は PowerPoint [Presentation](./) の作成方法を示します。  
```cpp
// プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化します
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>();

// 最初のスライドを取得します
auto slide = presentation->get_Slides()->idx_get(0);
// ラインタイプのオートシェイプを追加します
slide->get_Shapes()->AddAutoShape(ShapeType::Line, 50.0f, 150.0f, 300.0f, 0.0f);
// プレゼンテーション ファイルを保存します。
presentation->Save(u"NewPresentation_out.pptx", SaveFormat::Pptx);
```
次の例は [Presentation](./) を開いて保存する方法を示します。  
```cpp
// Presentation でサポートされている任意のファイルをロードします（例：ppt、pptx、odp など）。
System::SharedPtr<Presentation> presentation = System::MakeObject<Presentation>(u"Sample.odp");

// プレゼンテーションファイルを保存します。
presentation->Save(u"OutputPresenation.pptx", SaveFormat::Pptx);
```

## 関連項目

* クラス [IPresentation](../ipresentation/)
* クラス [IDOMObject](../idomobject/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)