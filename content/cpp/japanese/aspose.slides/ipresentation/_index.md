---
title: IPresentation
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーション ドキュメント
type: docs
weight: 3368
url: /ja/aspose.slides/ipresentation/
---
## IPresentation クラス

[Presentation](../presentation/) ドキュメント

```cpp
class IPresentation : public Aspose::Slides::IPresentationComponent,
                      public System::IDisposable
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual void [Dispose](../../system/idisposable/dispose/)() | 何もしません。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[ICustomXmlPart](../icustomxmlpart/)\>\> [get_AllCustomXmlParts](./get_allcustomxmlparts/)() | プレゼンテーションのすべてのカスタムデータ パーツを返します。読み取り専用 [ICustomXmlPart](../icustomxmlpart/)[]。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_Audio](./get_audio/)(**int32_t**) | 指定されたインデックスのプレゼンテーション内の埋め込みオーディオ ファイルを返します。読み取り専用 [Aspose::Slides::IAudio](../iaudio/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudioCollection](../iaudiocollection/)\> [get_Audios](./get_audios/)() | プレゼンテーション内のすべての埋め込みオーディオ ファイルのコレクションを返します。読み取り専用 [IAudioCollection](../iaudiocollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthor](../icommentauthor/)\> [get_CommentAuthor](./get_commentauthor/)(**int32_t**) | 指定されたインデックスのコメント作成者を返します。読み取り専用 [Aspose::Slides::ICommentAuthor](../icommentauthor/) |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICommentAuthorCollection](../icommentauthorcollection/)\> [get_CommentAuthors](./get_commentauthors/)() | コメント作成者のコレクションを返します。読み取り専用 [ICommentAuthorCollection](../icommentauthorcollection/)。 |
| virtual [System::DateTime](../../system/datetime/) [get_CurrentDateTime](./get_currentdatetime/)() | datetime フィールドの内容を置換する日付と時刻を返します。デフォルトではこの [Presentation](../presentation/) オブジェクトの作成時刻です。読み取り [System::DateTime](../../system/datetime/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](./get_customdata/)() | プレゼンテーションのカスタムデータを返します。読み取り専用 [ICustomData](../icustomdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ITextStyle](../itextstyle/)\> [get_DefaultTextStyle](./get_defaulttextstyle/)() | シェイプのデフォルトテキストスタイルを返します。読み取り専用 [ITextStyle](../itextstyle/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignature](../idigitalsignature/)\> [get_DigitalSignature](./get_digitalsignature/)(**int32_t**) | 指定されたインデックスでプレゼンテーションに署名するデジタル署名を返します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDigitalSignatureCollection](../idigitalsignaturecollection/)\> [get_DigitalSignatures](./get_digitalsignatures/)() | プレゼンテーションに署名するために使用された署名のコレクションを返します。読み取り専用 [IDigitalSignatureCollection](../idigitalsignaturecollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IDocumentProperties](../idocumentproperties/)\> [get_DocumentProperties](./get_documentproperties/)() | [DocumentProperties](../documentproperties/) オブジェクト（標準およびカスタム文書プロパティを含む）を返します。読み取り専用 [IDocumentProperties](../idocumentproperties/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\> [get_DocumentProperty](./get_documentproperty/)([System::String](../../system/string/)) | 名前で定義されたカスタムプロパティを返します。 |
| virtual **int32_t** [get_FirstSlideNumber](./get_firstslidenumber/)() | プレゼンテーションの最初のスライド番号を表します。読み取り **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFontsManager](../ifontsmanager/)\> [get_FontsManager](./get_fontsmanager/)() | フォントマネージャーを返します。読み取り専用 [IFontsManager](../ifontsmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)\> [get_HeaderFooterManager](./get_headerfootermanager/)() | プレゼンテーションのヘッダー/フッターマネージャーを返します。読み取り専用 [IPresentationHeaderFooterManager](../ipresentationheaderfootermanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkQueries](../ihyperlinkqueries/)\> [get_HyperlinkQueries](./get_hyperlinkqueries/)() | すべてのプレゼンテーション スライド（マスター、レイアウト、ノート スライドを除く）に含まれるすべてのハイパーリンクへの簡単なアクセスを提供します。読み取り専用 [IHyperlinkQueries](../ihyperlinkqueries/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_Image](./get_image/)(**int32_t**) | 指定されたインデックスのプレゼンテーション内の画像を返します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImageCollection](../iimagecollection/)\> [get_Images](./get_images/)() | プレゼンテーション内のすべての画像のコレクションを返します。読み取り専用 [IImageCollection](../iimagecollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILayoutSlide](../ilayoutslide/)\> [get_LayoutSlide](./get_layoutslide/)(**int32_t**) | インデックスでレイアウト スライドを返します。読み取り専用 [Aspose::Slides::ILayoutSlide](../ilayoutslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGlobalLayoutSlideCollection](../igloballayoutslidecollection/)\> [get_LayoutSlides](./get_layoutslides/)() | プレゼンテーションで定義されたすべてのレイアウト スライドの一覧を返します。読み取り専用 [IGlobalLayoutSlideCollection](../igloballayoutslidecollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlide](../imasterslide/)\> [get_Master](./get_master/)(**int32_t**) | 指定されたインデックスでプレゼンテーションに定義されたマスター スライドを返します。読み取り専用 [Aspose::Slides::IMasterSlide](../imasterslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterHandoutSlideManager](../imasterhandoutslidemanager/)\> [get_MasterHandoutSlideManager](./get_masterhandoutslidemanager/)() | ハンドアウト マスターマネージャーを返します。読み取り専用 [IMasterHandoutSlideManager](../imasterhandoutslidemanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterNotesSlideManager](../imasternotesslidemanager/)\> [get_MasterNotesSlideManager](./get_masternotesslidemanager/)() | ノート マスターマネージャーを返します。読み取り専用 [IMasterNotesSlideManager](../imasternotesslidemanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IMasterSlideCollection](../imasterslidecollection/)\> [get_Masters](./get_masters/)() | プレゼンテーションで定義されたすべてのマスター スライドの一覧を返します。読み取り専用 [IMasterSlideCollection](../imasterslidecollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/)\> [get_MasterTheme](./get_mastertheme/)() | プレゼンテーションのマスター テーマを返します。読み取り専用 [Theme::IMasterTheme](../../aspose.slides.theme/imastertheme/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[INotesSize](../inotessize/)\> [get_NotesSize](./get_notessize/)() | ノート スライドサイズオブジェクトを返します。読み取り専用 [INotesSize](../inotessize/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](./)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | プレゼンテーションを返します。読み取り専用 [IPresentation](./)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IProtectionManager](../iprotectionmanager/)\> [get_ProtectionManager](./get_protectionmanager/)() | このプレゼンテーションの権限マネージャーを取得します。読み取り専用 [IProtectionManager](../iprotectionmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_Section](./get_section/)(**int32_t**) | 指定されたインデックスでプレゼンテーションに定義されたスライド セクションを返します。読み取り専用 [Aspose::Slides::ISection](../isection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISectionCollection](../isectioncollection/)\> [get_Sections](./get_sections/)() | プレゼンテーションで定義されたすべてのスライド セクションの一覧を返します。読み取り専用 [ISectionCollection](../isectioncollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISensitivityLabelCollection](../isensitivitylabelcollection/)\> [get_SensitivityLabels](./get_sensitivitylabels/)() | プレゼンテーション文書に適用された感度ラベルのコレクションを返します。読み取り専用 [ISensitivityLabelCollection](../isensitivitylabelcollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlide](../islide/)\> [get_Slide](./get_slide/)(**int32_t**) | 指定されたインデックスでプレゼンテーションに定義されたスライドを返します。読み取り専用 [Aspose::Slides::ISlide](../islide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideCollection](../islidecollection/)\> [get_Slides](./get_slides/)() | プレゼンテーションで定義されたすべてのスライドの一覧を返します。読み取り専用 [ISlideCollection](../islidecollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISlideSize](../islidesize/)\> [get_SlideSize](./get_slidesize/)() | スライドサイズオブジェクトを返します。読み取り専用 [ISlideSize](../islidesize/)。 |
| virtual [Aspose::Slides::SourceFormat](../sourceformat/) [get_SourceFormat](./get_sourceformat/)() | プレゼンテーションがロードされた形式に関する情報を返します。読み取り専用 [IPresentation::get_SourceFormat](./get_sourceformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\> [get_VbaProject](./get_vbaproject/)() | プレゼンテーションマクロを含む VBA プロジェクトを取得します。読み取り [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_Video](./get_video/)(**int32_t**) | 指定されたインデックスのプレゼンテーションに埋め込まれたビデオ ファイルを返します。読み取り専用 [Aspose::Slides::IVideo](../ivideo/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IVideoCollection](../ivideocollection/)\> [get_Videos](./get_videos/)() | プレゼンテーション内のすべての埋め込みビデオ ファイルのコレクションを返します。読み取り専用 [IVideoCollection](../ivideocollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IViewProperties](../iviewproperties/)\> [get_ViewProperties](./get_viewproperties/)() | プレゼンテーション全体のビュー プロパティを取得します。読み取り専用 [IViewProperties](../iviewproperties/)。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタ データ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | プレゼンテーションのすべてのスライドに対するサムネイル画像オブジェクトを返します。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>) | プレゼンテーションの指定されたスライドに対するサムネイルビットマップオブジェクトを返します。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, **float**, **float**) | カスタムスケーリングを使用して、プレゼンテーションのすべてのスライドに対するサムネイル画像オブジェクトを返します。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, **float**, **float**) | カスタムスケーリングを使用して、プレゼンテーションの指定されたスライドに対するサムネイル画像オブジェクトを返します。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::Drawing::Size](../../system.drawing/size/)) | 指定されたサイズで、プレゼンテーションのすべてのスライドに対するサムネイル画像オブジェクトを返します。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\>\> [GetImages](./getimages/)([System::SharedPtr](../../system/sharedptr/)\<[Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [System::Drawing::Size](../../system.drawing/size/)) | 指定されたサイズで、プレゼンテーションの指定されたスライドに対するサムネイル画像オブジェクトを返します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [GetSlideById](./getslidebyid/)(**uint32_t**) | Id によって [Slide](../slide/)、[MasterSlide](../masterslide/)、または [LayoutSlide](../layoutslide/) を返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual void [HighlightRegex](./highlightregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) | 正規表現のすべての一致を指定された色でハイライトします。 |
| virtual void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/)) | サンプルテキストのすべての一致を指定された色でハイライトします。 |
| virtual void [HighlightText](./highlighttext/)([System::String](../../system/string/), [System::Drawing::Color](../../system.drawing/color/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) | サンプルテキストのすべての一致を指定された色でハイライトします。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかを確認します。C# の 'is' 演算子のアナログです。 |
| virtual void [JoinPortionsWithSameFormatting](./joinportionswithsameformatting/)() | すべてのスライドのすべての対象シェイプ内のすべての段落で、同じ書式のランを結合します。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文によるロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネル オブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [ReplaceRegex](./replaceregex/)([System::SharedPtr](../../system/sharedptr/)\<[System::Text::RegularExpressions::Regex](../../system.text.regularexpressions/regex/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) | 正規表現のすべての一致を指定された文字列に置き換えます。 |
| virtual void [ReplaceText](./replacetext/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[ITextSearchOptions](../itextsearchoptions/)\>, [System::SharedPtr](../../system/sharedptr/)\<[IFindResultCallback](../ifindresultcallback/)\>) | 指定されたテキストのすべての出現を別の指定テキストに置き換えます。 |
| virtual void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/)) | プレゼンテーションのすべてのスライドを指定された形式のファイルに保存します。 |
| virtual void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) | プレゼンテーションのすべてのスライドを指定された形式のストリームに保存します。 |
| virtual void [Save](./save/)([System::String](../../system/string/), [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) | プレゼンテーションのすべてのスライドを指定された形式と追加オプションでファイルに保存します。 |
| virtual void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) | プレゼンテーションのすべてのスライドを指定された形式と追加オプションでストリームに保存します。 |
| virtual void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) | プレゼンテーションの指定されたスライドを指定された形式のファイルに保存します。 |
| virtual void [Save](./save/)([System::String](../../system/string/), [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) | プレゼンテーションの指定されたスライドを指定された形式のファイルに保存します。 |
| virtual void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/)) | プレゼンテーションの指定されたスライドを指定された形式のストリームに保存します。 |
| virtual void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::ArrayPtr](../../system/arrayptr/)\<**int32_t**\>, [Export::SaveFormat](../../aspose.slides.export/saveformat/), [System::SharedPtr](../../system/sharedptr/)\<[Export::ISaveOptions](../../aspose.slides.export/isaveoptions/)\>) | プレゼンテーションの指定されたスライドを指定された形式のストリームに保存します。 |
| virtual void [Save](./save/)([System::SharedPtr](../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../aspose.slides.export.xaml/ixamloptions/)\>) | プレゼンテーションのすべてのスライドを XAML マーキングを表すファイルのセットに保存します。 |
| virtual void [set_CurrentDateTime](./set_currentdatetime/)([System::DateTime](../../system/datetime/)) | datetime フィールドの内容を置換する日付と時刻を設定します。デフォルトではこの [Presentation](../presentation/) オブジェクトの作成時刻です。書き込み [System::DateTime](../../system/datetime/)。 |
| virtual void [set_DocumentProperty](./set_documentproperty/)([System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[System::Object](../../system/object/)\>) | 名前で定義されたカスタムプロパティを設定します。 |
| virtual void [set_FirstSlideNumber](./set_firstslidenumber/)(**int32_t**) | プレゼンテーションの最初のスライド番号を表します。書き込み **int32_t**。 |
| virtual void [set_VbaProject](./set_vbaproject/)([System::SharedPtr](../../system/sharedptr/)\<[Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)\>) | プレゼンテーションマクロを含む VBA プロジェクトを取得します。書き込み [Vba::IVbaProject](../../aspose.slides.vba/ivbaproject/)。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文によるロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネル オブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IPresentationComponent](../ipresentationcomponent/)
* クラス [IDisposable](../../system/idisposable/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)