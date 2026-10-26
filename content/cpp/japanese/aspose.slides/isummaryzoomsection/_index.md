---
title: ISummaryZoomSection
second_title: Aspose.Slides for C++ API リファレンス
description: Summary Zoom フレーム内の Summary Zoom Section オブジェクトを表します。
type: docs
weight: 3927
url: /ja/aspose.slides/isummaryzoomsection/
---
## ISummaryZoomSection クラス

Summary Zoom フレーム内の Summary Zoom [Section](../section/) オブジェクトを表します。

```cpp
class ISummaryZoomSection : public virtual Aspose::Slides::ISectionZoomFrame
```

## メソッド

| Method | Description |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、プレースホルダーのプロパティを指定されたものに設定します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくありませんが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | シェイプに関連付けられた代替テキストを返します。[System::String](../../system/string/) を参照してください。 |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | シェイプに関連付けられた代替テキストのタイトルを返します。[System::String](../../system/string/) を参照してください。 |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。[Slides::BlackWhiteMode](../blackwhitemode/) を参照してください。 |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | シェイプ上の接続ポイントの数を返します。読み取り専用 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | シェイプのカスタムデータを返します。読み取り専用 [ICustomData](../icustomdata/)。 |
| virtual [System::String](../../system/string/) [get_Description](./get_description/)() | Summary Zoom [Section](../section/) オブジェクトのテキスト記述を返します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | [EffectFormat](../effectformat/) オブジェクトを返します。このオブジェクトはシェイプに適用されたピクセル効果を含みます。読み取り専用 [IEffectFormat](../ieffectformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | [FillFormat](../fillformat/) オブジェクトを返します。このオブジェクトはシェイプの塗りつぶし書式プロパティを含みます。読み取り専用 [IFillFormat](../ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | シェイプフレームのプロパティを返します。[IShapeFrame](../ishapeframe/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../igraphicalobject/get_graphicalobjectlock/)() | シェイプのロックを返します。読み取り専用 [IGraphicalObjectLock](../igraphicalobjectlock/)。 |
| virtual **float** [get_Height](../ishape/get_height/)() | シェイプの高さ（ポイント単位）を取得します。読み取り **float**。 |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | シェイプが非表示かどうかを判定します。読み取り **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | マウスクリック用に定義されたハイパーリンクを返します。[IHyperlink](../ihyperlink/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | ハイパーリンクマネージャーです。読み取り専用 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | マウスオーバー用に定義されたハイパーリンクを返します。[IHyperlink](../ihyperlink/) を参照してください。 |
| virtual [ZoomImageType](../zoomimagetype/) [get_ImageType](../izoomobject/get_imagetype/)() | ズームオブジェクトの画像タイプを取得します。[ZoomImageType](../zoomimagetype/) を参照してください。デフォルト値: Preview |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | 「Mark as decorative」オプションを取得します。読み取り/書き込み **bool**。 |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | シェイプがグループ化されているかどうかを判定します。読み取り専用 **bool**。 |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | シェイプが TextHolder かどうかを判定します。読み取り専用 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | [LineFormat](../lineformat/) オブジェクトを返します。このオブジェクトはシェイプの線書式プロパティを含みます。読み取り専用 [ILineFormat](../ilineformat/)。 |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | シェイプの名前を返します。[System::String](../../system/string/) を参照してください。 |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | シェイプの存続期間中一定で、PowerPoint やインタープコードがドキュメント内の任意の場所からシェイプを確実に参照できるスライドスコープの固有識別子を返します。読み取り専用 **uint32_t**。[IShape::get_UniqueId](../ishape/get_uniqueid/) も参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | シェイプがグループ化されている場合、親 [GroupShape](../groupshape/) オブジェクトを返します。そうでない場合は null を返します。読み取り専用 [IGroupShape](../igroupshape/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | シェイプのプレースホルダーを返します。読み取り専用 [IPlaceholder](../iplaceholder/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | プレゼンテーションを返します。読み取り専用 [IPresentation](../ipresentation/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | 生のシェイプフレームのプロパティを返します。[IShapeFrame](../ishapeframe/) を参照してください。 |
| virtual **bool** [get_ReturnToParent](../izoomobject/get_returntoparent/)() | スライドショーでのナビゲーション動作を取得します。読み取り **bool**。デフォルト値: false |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | 指定されたシェイプが z 軸周りに回転している角度（度）を返します。正の値は時計回り回転、負の値は反時計回り回転を示します。読み取り **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | シェイプのロックを返します。読み取り専用 [IBaseShapeLock](../ibaseshapelock/)。 |
| virtual **bool** [get_ShowBackground](../izoomobject/get_showbackground/)() | ズームが宛先スライドの背景を使用するかどうかを示す値を取得します。読み取り **bool**。デフォルト値: true |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | 基底スライドを返します。読み取り専用 [IBaseSlide](../ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\> [get_TargetSection](../isectionzoomframe/get_targetsection/)() | [Section](../section/) ズームオブジェクトがリンクされているセクションオブジェクトを取得します。[ISection](../isection/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | [ThreeDFormat](../threedformat/) オブジェクトを返します。このオブジェクトはシェイプの線書式プロパティを含みます。読み取り専用 [IThreeDFormat](../ithreedformat/)。 |
| virtual [System::String](../../system/string/) [get_Title](./get_title/)() | Summary Zoom [Section](../section/) オブジェクトのテキストタイトルを返します。 |
| virtual **float** [get_TransitionDuration](../izoomobject/get_transitionduration/)() | ズームとスライド間の遷移時間を取得します。読み取り **float**。デフォルト値: 1.0f |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | アドインやその他のコードで使用することを意図した、内部のプレゼンテーションスコープの識別子を返します。この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な固有キーとして扱うべきではありません。読み取り専用 **uint32_t**。[IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/) も参照してください。 |
| virtual **float** [get_Width](../ishape/get_width/)() | シェイプの幅（ポイント単位）を取得します。読み取り **float**。 |
| virtual **float** [get_X](../ishape/get_x/)() | シェイプの左上隅の X 座標（ポイント単位）を取得します。読み取り **float**。 |
| virtual **float** [get_Y](../ishape/get_y/)() | シェイプの左上隅の Y 座標（ポイント単位）を取得します。読み取り **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\> [get_ZoomImage](../izoomobject/get_zoomimage/)() | ズームオブジェクトの画像を取得します。[IPPImage](../ippimage/) を参照してください。 |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | シェイプの Z 順序における位置を返します。Shapes[0] は Z 順序の背面のシェイプを返し、Shapes[Shapes.Count - 1] は前面のシェイプを返します。読み取り専用 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | 基本的なプレースホルダーシェイプを返します（現在のシェイプが継承しているレイアウトまたはマスタースライドからのシェイプ）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | シェイプのサムネイルを返します。デフォルトでは [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) のシェイプサムネイル境界タイプが使用されます。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | シェイプのサムネイルを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | このシェイプがプレースホルダーではないことを定義します。 |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | シェイプに関連付けられた代替テキストを設定します。[System::String](../../system/string/) に書き込みます。 |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | シェイプに関連付けられた代替テキストのタイトルを設定します。[System::String](../../system/string/) に書き込みます。 |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。[Slides::BlackWhiteMode](../blackwhitemode/) に書き込みます。 |
| virtual void [set_Description](./set_description/)([System::String](../../system/string/)) | Summary Zoom [Section](../section/) オブジェクトのテキスト記述を返します。 |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | シェイプフレームのプロパティを設定します。[IShapeFrame](../ishapeframe/) に書き込みます。 |
| virtual void [set_Height](../ishape/set_height/)(**float**) | シェイプの高さ（ポイント単位）を設定します。**float** に書き込みます。 |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | シェイプが非表示かどうかを設定します。**bool** に書き込みます。 |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | マウスクリック用に定義されたハイパーリンクを設定します。[IHyperlink](../ihyperlink/) に書き込みます。 |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | マウスオーバー用に定義されたハイパーリンクを設定します。[IHyperlink](../ihyperlink/) に書き込みます。 |
| virtual void [set_ImageType](../izoomobject/set_imagetype/)([ZoomImageType](../zoomimagetype/)) | ズームオブジェクトの画像タイプを設定します。[ZoomImageType](../zoomimagetype/) に書き込みます。デフォルト値: Preview |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | 『Mark as decorative』オプションを設定します。読み取り/書き込み **bool**。 |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | シェイプの名前を設定します。[System::String](../../system/string/) に書き込みます。 |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | 生のシェイプフレームのプロパティを設定します。[IShapeFrame](../ishapeframe/) に書き込みます。 |
| virtual void [set_ReturnToParent](../izoomobject/set_returntoparent/)(**bool**) | スライドショーでのナビゲーション動作を設定します。**bool** に書き込みます。デフォルト値: false |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | 指定されたシェイプが z 軸周りに回転している角度（度）を設定します。正の値は時計回り回転、負の値は反時計回り回転を示します。**float** に書き込みます。 |
| virtual void [set_ShowBackground](../izoomobject/set_showbackground/)(**bool**) | ズームが宛先スライドの背景を使用するかどうかを示す値を設定します。**bool** に書き込みます。デフォルト値: true |
| virtual void [set_TargetSection](../isectionzoomframe/set_targetsection/)([System::SharedPtr](../../system/sharedptr/)\<[ISection](../isection/)\>) | [Section](../section/) ズームオブジェクトがリンクされているセクションオブジェクトを設定します。[ISection](../isection/) に書き込みます。 |
| virtual void [set_Title](./set_title/)([System::String](../../system/string/)) | Summary Zoom [Section](../section/) オブジェクトのテキストタイトルを返します。 |
| virtual void [set_TransitionDuration](../izoomobject/set_transitionduration/)(**float**) | ズームとスライド間の遷移時間を設定します。**float** に書き込みます。デフォルト値: 1.0f |
| virtual void [set_Width](../ishape/set_width/)(**float**) | シェイプの幅（ポイント単位）を設定します。**float** に書き込みます。 |
| virtual void [set_X](../ishape/set_x/)(**float**) | シェイプの左上隅の X 座標（ポイント単位）を設定します。**float** に書き込みます。 |
| virtual void [set_Y](../ishape/set_y/)(**float**) | シェイプの左上隅の Y 座標（ポイント単位）を設定します。**float** に書き込みます。 |
| virtual void [set_ZoomImage](../izoomobject/set_zoomimage/)([System::SharedPtr](../../system/sharedptr/)\<[IPPImage](../ippimage/)\>) | ズームオブジェクトの画像を設定します。[IPPImage](../ippimage/) に書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../shape/) の内容を SVG ファイルとして保存します。 |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../shape/) の内容を SVG ファイルとして保存します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [ISectionZoomFrame](../isectionzoomframe/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)