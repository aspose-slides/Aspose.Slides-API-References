---
title: OleObjectFrame
second_title: Aspose.Slides for C++ API リファレンス
description: スライド上の OLE オブジェクトを表します。
type: docs
weight: 4603
url: /ja/aspose.slides/oleobjectframe/
---
## OleObjectFrame クラス


スライド上の OLE オブジェクトを表します。

```cpp
class OleObjectFrame : public Aspose::Slides::GraphicalObject,
                       public Aspose::Slides::IOleObjectFrame
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | プレースホルダーがない場合に新しいプレースホルダーを追加し、プレースホルダーのプロパティを指定されたものに設定します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、ここでは 2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、ここでは 2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | シェイプに関連付けられた代替テキストを返します。参照 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | シェイプに関連付けられた代替テキストのタイトルを返します。参照 [System::String](../../system/string/)。 |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。参照 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | シェイプの接続ポイント数を返します。読み取り専用 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | シェイプのカスタムデータを返します。読み取り専用 [ICustomData](../icustomdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | [EffectFormat](../effectformat/) オブジェクト（シェイプに適用されたピクセル効果を含む）を返します。注: 効果プロパティを持たない特定のシェイプ型では null を返すことがあります。読み取り専用 [IEffectFormat](../ieffectformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\> [get_EmbeddedData](./get_embeddeddata/)() override | OLE 埋め込みデータに関する情報を取得します。参照 [IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)。 |
| [System::String](../../system/string/) [get_EmbeddedFileLabel](./get_embeddedfilelabel/)() override | 埋め込み OLE オブジェクトのファイル名を返します。 |
| [System::String](../../system/string/) [get_EmbeddedFileName](./get_embeddedfilename/)() override | 埋め込み OLE オブジェクトのパスを返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | [FillFormat](../fillformat/) オブジェクト（シェイプの塗りつぶし書式プロパティを含む）を返します。注: 塗りつぶしプロパティを持たない特定のシェイプ型では null を返すことがあります。読み取り専用 [IFillFormat](../ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | シェイプフレームのプロパティを返します。参照 [IShapeFrame](../ishapeframe/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | シェイプのロック状態を返します。読み取り専用 [IGraphicalObjectLock](../igraphicalobjectlock/)。 |
| **float** [get_Height](../shape/get_height/)() override | シェイプの高さ（ポイント単位）を取得します。読み取り **float**。 |
| **bool** [get_Hidden](../shape/get_hidden/)() override | シェイプが非表示かどうかを判定します。読み取り **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | マウスクリック用に定義されたハイパーリンクを返します。参照 [IHyperlink](../ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | ハイパーリンクマネージャーを返します。読み取り専用 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | マウスオーバー用に定義されたハイパーリンクを返します。参照 [IHyperlink](../ihyperlink/)。 |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 'Mark as decorative' オプションを取得します。読み書き **bool**。 |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | シェイプがグループ化されているかどうかを判定します。読み取り専用 **bool**。 |
| **bool** [get_IsObjectIcon](./get_isobjecticon/)() override | オブジェクトがアイコンとして表示されるかどうかを判定します。読み取り **bool**。 |
| **bool** [get_IsObjectLink](./get_isobjectlink/)() override | オブジェクトが外部ファイルにリンクされているかどうかを判定します。読み取り専用 **bool**。 |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | シェイプが TextHolder_PPT かどうかを判定します。読み取り専用 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | [LineFormat](../lineformat/) オブジェクト（シェイプの線書式プロパティを含む）を返します。注: 線プロパティを持たない特定のシェイプ型では null を返すことがあります。読み取り専用 [ILineFormat](../ilineformat/)。 |
| [System::String](../../system/string/) [get_LinkFileName](./get_linkfilename/)() override | リンクされたファイルへのフルパスを返します。短いファイル名が使用されます。読み取り専用 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | リンクされたファイルへのフルパスを返します。長いファイル名が使用されます。参照 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_LinkPathRelative](./get_linkpathrelative/)() override | リンクされたファイルへの相対パスが存在すれば返し、存在しなければ空文字列を返します。読み取り専用 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | シェイプの名前を返します。null であってはなりません。必要に応じて空文字列を使用してください。参照 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_ObjectName](./get_objectname/)() override | オブジェクトの名前を返します。参照 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_ObjectProgId](./get_objectprogid/)() override | オブジェクトの ProgID を返します。読み取り専用 [System::String](../../system/string/)。 |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | シェイプのライフタイム中に一定で、PowerPoint または interop コードがドキュメント内の任意の場所からシェイプを確実に参照できるスライドスコープの一意識別子を返します。読み取り専用 **uint32_t**。詳しくは [Shape::get_UniqueId](../shape/get_uniqueid/) を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | シェイプがグループ化されている場合、親 [GroupShape](../groupshape/) オブジェクトを返します。そうでなければ null を返します。読み取り専用 [IGroupShape](../igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | シェイプのプレースホルダーを返します。プレースホラーが無い場合は null を返します。読み取り専用 [IPlaceholder](../iplaceholder/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | スライドの親プレゼンテーションを返します。読み取り専用 [IPresentation](../ipresentation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | 生のシェイプフレームのプロパティを返します。参照 [IShapeFrame](../ishapeframe/)。 |
| **float** [get_Rotation](../shape/get_rotation/)() override | 指定されたシェイプが z 軸周りに回転している度数を返します。正の値は時計回り、負の値は反時計回りを示します。読み取り **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | シェイプのロック状態を返します。読み取り専用 [IBaseShapeLock](../ibaseshapelock/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | シェイプの親スライドを返します。読み取り専用 [IBaseSlide](../ibaseslide/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_SubstitutePictureFormat](./get_substitutepictureformat/)() override | OleObject の画像塗りつぶしプロパティオブジェクトを返します。読み取り専用 [IPictureFillFormat](../ipicturefillformat/)。 |
| [System::String](../../system/string/) [get_SubstitutePictureTitle](./get_substitutepicturetitle/)() override | OleObject アイコンのタイトルを返します。参照 [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | [ThreeDFormat](../threedformat/) オブジェクト（シェイプの 3D エフェクトプロパティを含む）を返します。注: 3D プロパティを持たない特定のシェイプ型では null を返すことがあります。読み取り専用 [IThreeDFormat](../ithreedformat/)。 |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | アドインやその他のコードが使用することを想定した、プレゼンテーションスコープの内部識別子を返します。この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。読み取り専用 **uint32_t**。詳しくは [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/) を参照してください。 |
| **bool** [get_UpdateAutomatic](./get_updateautomatic/)() override | プレゼンテーションが開かれたり印刷されたりしたときに、リンクされた埋め込みオブジェクトが自動的に更新されるかどうかを判定します。読み取り **bool**。 |
| **float** [get_Width](../shape/get_width/)() override | シェイプの幅（ポイント単位）を取得します。読み取り **float**。 |
| **float** [get_X](../shape/get_x/)() override | シェイプの左上隅の x 座標（ポイント単位）を取得します。読み取り **float**。 |
| **float** [get_Y](../shape/get_y/)() override | シェイプの左上隅の y 座標（ポイント単位）を取得します。読み取り **float**。 |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | シェイプの Z オーダーにおける位置を返します。Shapes[0] は Z オーダーの最背面のシェイプを、Shapes[Shapes.Count - 1] は最前面のシェイプを返します。読み取り専用 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | 基本的なプレースホルダーシェイプ（現在のシェイプが継承しているレイアウトまたはマスタースライドからのシェイプ）を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | シェイプのサムネイルを返します。[ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) シェイプサムネイル境界タイプがデフォルトで使用されます。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | シェイプのサムネイルを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() ステートメントのロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によるオブジェクトの比較を行います。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によるオブジェクトの比較を行います。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | このシェイプがプレースホルダーでないことを定義します。 |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | シェイプに関連付けられた代替テキストを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | シェイプに関連付けられた代替テキストのタイトルを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。書き込み [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | シェイプフレームのプロパティを設定します。書き込み [IShapeFrame](../ishapeframe/)。 |
| void [set_Height](../shape/set_height/)(**float**) override | シェイプの高さ（ポイント単位）を設定します。書き込み **float**。 |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | シェイプが非表示かどうかを設定します。書き込み **bool**。 |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | マウスクリック用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../ihyperlink/)。 |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | マウスオーバー用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../ihyperlink/)。 |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 'Mark as decorative' オプションを設定します。書き込み **bool**。 |
| void [set_IsObjectIcon](./set_isobjecticon/)(**bool**) override | オブジェクトがアイコンとして表示されるかどうかを設定します。書き込み **bool**。 |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | リンクされたファイルへのフルパス（長いファイル名が使用されます）を設定します。書き込み [System::String](../../system/string/)。 |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | シェイプの名前を設定します。null であってはなりません。必要に応じて空文字列を使用してください。書き込み [System::String](../../system/string/)。 |
| void [set_ObjectName](./set_objectname/)([System::String](../../system/string/)) override | オブジェクトの名前を設定します。書き込み [System::String](../../system/string/)。 |
| void [set_ObjectProgId](./set_objectprogid/)([System::String](../../system/string/)) override | オブジェクトの ProgID を返します。読み取り専用 [System::String](../../system/string/)。 |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 生のシェイプフレームのプロパティを設定します。書き込み [IShapeFrame](../ishapeframe/)。 |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | 指定されたシェイプが z 軸周りに回転している度数を設定します。正の値は時計回り、負の値は反時計回りを示します。書き込み **float**。 |
| void [set_SubstitutePictureTitle](./set_substitutepicturetitle/)([System::String](../../system/string/)) override | OleObject アイコンのタイトルを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_UpdateAutomatic](./set_updateautomatic/)(**bool**) override | プレゼンテーションが開かれたり印刷されたりしたときに、リンクされた埋め込みオブジェクトが自動的に更新されるかどうかを設定します。書き込み **bool**。 |
| void [set_Width](../shape/set_width/)(**float**) override | シェイプの幅（ポイント単位）を設定します。書き込み **float**。 |
| void [set_X](../shape/set_x/)(**float**) override | シェイプの左上隅の x 座標（ポイント単位）を設定します。書き込み **float**。 |
| void [set_Y](../shape/set_y/)(**float**) override | シェイプの左上隅の y 座標（ポイント単位）を設定します。書き込み **float**。 |
| void [SetEmbeddedData](./setembeddeddata/)([System::SharedPtr](../../system/sharedptr/)\<[IOleEmbeddedDataInfo](../ioleembeddeddatainfo/)\>) override | OLE 埋め込みデータに関する情報を設定します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることが可能です。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センチリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出さず、スマートポインタまたは ThisProtector を使用してください。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/) の内容を SVG ファイルとして保存します。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/) の内容を SVG ファイルとして保存します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 備考


以下の例は OLE オブジェクト フレームへのアクセス方法を示しています。 
```cpp
// PPTX をプレゼンテーションオブジェクトに読み込みます
auto pres = System::MakeObject<Presentation>(u"AccessingOLEObjectFrame.pptx");

// 最初のスライドにアクセスします
auto slide = pres->get_Slides()->idx_get(0);
// シェイプを OleObjectFrame にキャストします
System::SharedPtr<OleObjectFrame> oleObjectFrame = System::AsCast<OleObjectFrame>(slide->get_Shapes()->idx_get(0));
// OLE オブジェクトを読み取り、ディスクに書き込みます
if (oleObjectFrame != nullptr)
{
    // 埋め込みファイルデータを取得します
    System::ArrayPtr<uint8_t> data = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileData();
    // 埋め込みファイルの拡張子を取得します
    System::String fileExtention = oleObjectFrame->get_EmbeddedData()->get_EmbeddedFileExtension();
    // 抽出したファイルを保存するパスを作成します
    System::String extractedPath = System::String(u"excelFromOLE_out") + fileExtention;
    // 抽出したデータを保存します
    auto stream = System::MakeObject<System::IO::FileStream>(extractedPath,
                                                             System::IO::FileMode::Create,
                                                             System::IO::FileAccess::Write);
    stream->Write(data, 0, data->get_Length());
}
```

## 参照

* クラス [GraphicalObject](../graphicalobject/)
* クラス [IOleObjectFrame](../ioleobjectframe/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)