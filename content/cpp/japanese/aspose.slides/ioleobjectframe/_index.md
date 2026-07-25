---
title: IOleObjectFrame
second_title: Aspose.Slides for C++ API リファレンス
description: スライド上の OLE オブジェクトを表します。
type: docs
weight: 3095
url: /ja/aspose.slides/ioleobjectframe/
---
## IOleObjectFrame クラス


スライド上の OLE オブジェクトを表します。

```cpp
class IOleObjectFrame : public virtual Aspose::Slides::IGraphicalObject
```

## メソッド

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | シェイプに関連付けられた代替テキストを返します。参照 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | シェイプに関連付けられた代替テキストのタイトルを返します。参照 [System::String](../../system/string/)。 |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。参照 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | シェイプ上の接続ポイントの数を返します。読み取り専用 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | シェイプのカスタムデータを返します。読み取り専用 [ICustomData](../icustomdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | シェイプに適用されたピクセル効果を含む [EffectFormat](../effectformat/) オブジェクトを返します。読み取り専用 [IEffectFormat](../ieffectformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() | OLE 埋め込みデータに関する情報を取得します。読み取り専用 [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)。 |
| virtual [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() | 埋め込み OLE オブジェクトのファイル名を返します |
| virtual [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() | 埋め込み OLE オブジェクトのパスを返します |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | シェイプの塗りつぶし書式プロパティを含む [FillFormat](../fillformat/) オブジェクトを返します。読み取り専用 [IFillFormat](../ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | シェイプフレームのプロパティを返します。参照 [IShapeFrame](../ishapeframe/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | シェイプのロック情報を返します。読み取り専用 [IGraphicalObjectLock](../igraphicalobjectlock/)。 |
| virtual **float** [get_Height](../ishape/get_height/)() | シェイプの高さ（ポイント単位）を取得します。読み取り **float**。 |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | シェイプが非表示かどうかを判定します。読み取り **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | マウスクリック用に定義されたハイパーリンクを返します。参照 [IHyperlink](../ihyperlink/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | ハイパーリンクマネージャー。読み取り専用 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | マウスオーバー用に定義されたハイパーリンクを返します。参照 [IHyperlink](../ihyperlink/)。 |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | 'Mark as decorative' オプションを取得/設定します **bool**。 |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | シェイプがグループ化されているかどうかを判定します。読み取り専用 **bool**。 |
| virtual **bool** [get_IsObjectIcon](./get_isobjecticon/)() | オブジェクトがアイコンとして表示されるかどうかを判定します。読み取り **bool**。 |
| virtual **bool** [get_IsObjectLink](./get_isobjectlink/)() | オブジェクトが外部ファイルにリンクされているかどうかを判定します。読み取り専用 **bool**。 |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | シェイプが TextHolder かどうかを判定します。読み取り専用 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | シェイプの線書式プロパティを含む [LineFormat](../lineformat/) オブジェクトを返します。読み取り専用 [ILineFormat](../ilineformat/)。 |
| virtual [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() | リンクされたファイルへのフルパスを返します。短いファイル名が使用されます。読み取り専用 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | リンクされたファイルへのフルパスを返します。長いファイル名が使用されます。参照 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() | リンクされたファイルが存在する場合は相対パスを返し、存在しない場合は空文字列を返します。読み取り専用 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | シェイプの名前を返します。参照 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() | オブジェクトの名前を返します。参照 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() | オブジェクトの ProgID を返します。読み取り専用 [System::String](../../system/string/)。 |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | シェイプの存続期間中は一定で、ドキュメント内のどこからでも PowerPoint またはインタロップコードがシェイプを確実に参照できるスライドスコープの一意の識別子を返します。読み取り専用 **uint32_t**。 参照 [IShape::get_UniqueId](../ishape/get_uniqueid/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | シェイプがグループ化されている場合は親 [GroupShape](../groupshape/) オブジェクトを返します。そうでない場合は null を返します。読み取り専用 [IGroupShape](../igroupshape/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | シェイプのプレースホルダーを返します。読み取り専用 [IPlaceholder](../iplaceholder/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | プレゼンテーションを返します。読み取り専用 [IPresentation](../ipresentation/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | シェイプフレームの生データプロパティを返します。参照 [IShapeFrame](../ishapeframe/)。 |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | 指定されたシェイプが z 軸まわりに回転している角度（度）を返します。正の値は時計回り、負の値は反時計回りを示します。読み取り **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | シェイプのロック情報を返します。読み取り専用 [IBaseShapeLock](../ibaseshapelock/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | 基底スライドを返します。読み取り専用 [IBaseSlide](../ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() | OleObject の画像塗りつぶしプロパティオブジェクトを返します。読み取り専用 [IPictureFillFormat](../ipicturefillformat/)。 |
| virtual [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() | OleObject アイコンのタイトルを返します。参照 [System::String](../../system/string/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | シェイプの線書式プロパティを含む [ThreeDFormat](../threedformat/) オブジェクトを返します。読み取り専用 [IThreeDFormat](../ithreedformat/)。 |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | 内部の、プレゼンテーションスコープの識別子を返します。アドインやその他のコードでの使用を目的としています。この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。読み取り専用 **uint32_t**。 参照 [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)。 |
| virtual **bool** [get_UpdateAutomatic](./get_updateautomatic/)() | プレゼンテーションが開かれたり印刷されたりした際に、リンクされた埋め込みオブジェクトが自動的に更新されるかどうかを判定します。読み取り **bool**。 |
| virtual **float** [get_Width](../ishape/get_width/)() | シェイプの幅（ポイント単位）を取得します。読み取り **float**。 |
| virtual **float** [get_X](../ishape/get_x/)() | シェイプの左上隅の x 座標（ポイント単位）を取得します。読み取り **float**。 |
| virtual **float** [get_Y](../ishape/get_y/)() | シェイプの左上隅の y 座標（ポイント単位）を取得します。読み取り **float**。 |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | z オーダーにおけるシェイプの位置を返します。Shapes[0] は z オーダーの最背面のシェイプを返し、Shapes[Shapes.Count - 1] は最前面のシェイプを返します。読み取り専用 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | 基本的なプレースホルダーシェイプ（レイアウトやマスタースライドから継承されたシェイプ）を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | シェイプのサムネイルを返します。デフォルトで [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) シェイプサムネイルのバウンドタイプが使用されます。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | シェイプのサムネイルを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定した値だけ共有参照カウントを減少させます。 |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | このシェイプがプレースホルダーでないことを定義します。 |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | シェイプに関連付けられた代替テキストを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | シェイプに関連付けられた代替テキストのタイトルを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。書き込み [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | シェイプフレームのプロパティを設定します。書き込み [IShapeFrame](../ishapeframe/)。 |
| virtual void [set_Height](../ishape/set_height/)(**float**) | シェイプの高さ（ポイント単位）を設定します。書き込み **float**。 |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | シェイプが非表示かどうかを設定します。書き込み **bool**。 |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | マウスクリック用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../ihyperlink/)。 |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | マウスオーバー用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../ihyperlink/)。 |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | 'Mark as decorative' オプションを設定します。読み書き **bool**。 |
| virtual void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) | オブジェクトがアイコンとして表示されるかどうかを設定します。書き込み **bool**。 |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | リンクされたファイルへのフルパスを返します。長いファイル名が使用されます。書き込み [System::String](../../system/string/)。 |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | シェイプの名前を設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) | オブジェクトの名前を設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) | オブジェクトの ProgID を返します。読み取り専用 [System::String](../../system/string/)。 |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | シェイプフレームの生データプロパティを設定します。書き込み [IShapeFrame](../ishapeframe/)。 |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | 指定されたシェイプが z 軸まわりに回転している角度（度）を設定します。正の値は時計回り、負の値は反時計回りを示します。書き込み **float**。 |
| virtual void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) | OleObject アイコンのタイトルを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) | プレゼンテーションが開かれたり印刷されたりした際に、リンクされた埋め込みオブジェクトが自動的に更新されるかどうかを設定します。書き込み **bool**。 |
| virtual void [set_Width](../ishape/set_width/)(**float**) | シェイプの幅（ポイント単位）を設定します。書き込み **float**。 |
| virtual void [set_X](../ishape/set_x/)(**float**) | シェイプの左上隅の x 座標（ポイント単位）を設定します。書き込み **float**。 |
| virtual void [set_Y](../ishape/set_y/)(**float**) | シェイプの左上隅の y 座標（ポイント単位）を設定します。書き込み **float**。 |
| virtual void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) | OLE 埋め込みデータに関する情報を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることが可能です。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウントの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../shape/) の内容を SVG ファイルとして保存します。 |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../shape/) の内容を SVG ファイルとして保存します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IGraphicalObject](../igraphicalobject/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)