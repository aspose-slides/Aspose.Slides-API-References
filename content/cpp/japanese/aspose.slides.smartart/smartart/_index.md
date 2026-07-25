---
title: SmartArt
second_title: Aspose.Slides for C++ API リファレンス
description: SmartArt ダイアグラムを表します
type: docs
weight: 66
url: /ja/aspose.slides.smartart/smartart/
---
## SmartArt クラス

[SmartArt](./) ダイアグラムを表します

```cpp
class SmartArt : public Aspose::Slides::GraphicalObject,
                 public Aspose::Slides::SmartArt::ISmartArt
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、プレースホルダーのプロパティを指定されたものに設定します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、ここでは NaN 同士を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN はどの値とも等しくありませんが、ここでは NaN 同士を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_AllNodes](./get_allnodes/)() override | [SmartArt](./) オブジェクト内のすべてのノードのコレクションを返します。読み取り専用 [ISmartArtNodeCollection](../ismartartnodecollection/)。 |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | シェイプに関連付けられた代替テキストを返します。読み取り [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | シェイプに関連付けられた代替テキストのタイトルを返します。読み取り [System::String](../../system/string/)。 |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | プロパティはシェイプが白黒表示モードでどのようにレンダリングされるかを指定します。読み取り [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| [SmartArtColorType](../smartartcolortype/) [get_ColorStyle](./get_colorstyle/)() override | [SmartArt](./) オブジェクトのカラースタイルを返します。読み取り [SmartArtColorType](../smartartcolortype/)。 |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | シェイプ上の接続サイトの数を返します。読み取り専用 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | シェイプのカスタムデータを返します。読み取り専用 [ICustomData](../../aspose.slides/icustomdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | [EffectFormat](../../aspose.slides/effectformat/) オブジェクトを返します。このオブジェクトはシェイプに適用されたピクセルエフェクトを含みます。注: エフェクトプロパティを持たない特定のシェイプタイプでは null を返すことがあります。読み取り専用 [IEffectFormat](../../aspose.slides/ieffectformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | [FillFormat](../../aspose.slides/fillformat/) オブジェクトを返します。このオブジェクトはシェイプの塗りつぶし書式プロパティを含みます。注: 塗りつぶしプロパティを持たないシェイプタイプでは null を返すことがあります。読み取り専用 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | シェイプフレームのプロパティを返します。読み取り [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/graphicalobject/get_graphicalobjectlock/)() override | シェイプのロックを返します。読み取り専用 [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)。 |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | シェイプの高さ（ポイント単位）を取得します。読み取り **float**。 |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | シェイプが非表示かどうかを判定します。読み取り **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | マウスクリック用に定義されたハイパーリンクを返します。読み取り [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | ハイパーリンクマネージャーを返します。読み取り専用 [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | マウスオーバー用に定義されたハイパーリンクを返します。読み取り [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | 『装飾としてマーク』オプションを取得します。読み取り/書き込み **bool**。 |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | シェイプがグループ化されているかどうかを判定します。読み取り専用 **bool**。 |
| **bool** [get_IsReversed](./get_isreversed/)() override | [SmartArt](./) ダイアグラムが (左から右) LTR または (右から左) RTL の状態を返すまたは設定します（逆転がサポートされている場合）。読み取り **bool**。 |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | シェイプが TextHolder_PPT かどうかを判定します。読み取り専用 **bool**。 |
| [SmartArtLayoutType](../smartartlayouttype/) [get_Layout](./get_layout/)() override | [SmartArt](./) オブジェクトのレイアウトを返します。読み取り [SmartArtLayoutType](../smartartlayouttype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | [LineFormat](../../aspose.slides/lineformat/) オブジェクトを返します。このオブジェクトはシェイプの線書式プロパティを含みます。注: 線プロパティを持たないシェイプタイプでは null を返すことがあります。読み取り専用 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | シェイプの名前を返します。null であってはなりません。必要に応じて空文字列を使用してください。読み取り [System::String](../../system/string/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_Node](./get_node/)(**int32_t**) override | [SmartArt](./) オブジェクトのルートノードコレクションから、指定インデックスのノードを返します。読み取り専用 [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNode](../ismartartnode/)\> [get_NodeFromAll](./get_nodefromall/)(**int32_t**) override | [SmartArt](./) オブジェクトの全ノードコレクションから、指定インデックスのノードを返します。読み取り専用 [Aspose::Slides::SmartArt::ISmartArtNode](../ismartartnode/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISmartArtNodeCollection](../ismartartnodecollection/)\> [get_Nodes](./get_nodes/)() override | [SmartArt](./) オブジェクトのルートノードコレクションを返します。読み取り専用 [ISmartArtNodeCollection](../ismartartnodecollection/)。 |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | スライドスコープの一意の識別子を返します。この識別子はシェイプの存続期間中一定で、PowerPoint またはインタープコードがドキュメント内の任意の場所からシェイプを確実に参照できるようにします。読み取り専用 **uint32_t**。詳細は [Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/) を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | シェイプがグループ化されている場合、親 [GroupShape](../../aspose.slides/groupshape/) オブジェクトを返します。そうでない場合は null を返します。読み取り専用 [IGroupShape](../../aspose.slides/igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | シェイプのプレースホルダーを返します。プレースホルダーがない場合は null を返します。読み取り専用 [IPlaceholder](../../aspose.slides/iplaceholder/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | スライドの親プレゼンテーションを返します。読み取り専用 [IPresentation](../../aspose.slides/ipresentation/)。 |
| [SmartArtQuickStyleType](../smartartquickstyletype/) [get_QuickStyle](./get_quickstyle/)() override | [SmartArt](./) オブジェクトのクイックスタイルを返します。読み取り [SmartArtQuickStyleType](../smartartquickstyletype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | 生のシェイプフレームのプロパティを返します。読み取り [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | 指定されたシェイプが z 軸周りに回転した角度（度）を返します。正の値は時計回り、負の値は反時計回りを示します。読み取り **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | シェイプのロックを返します。読み取り専用 [IBaseShapeLock](../../aspose.slides/ibaseshapelock/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | シェイプの親スライドを返します。読み取り専用 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | [ThreeDFormat](../../aspose.slides/threedformat/) オブジェクトを返します。このオブジェクトはシェイプの 3D エフェクトプロパティを含みます。注: 3D プロパティを持たないシェイプタイプでは null を返すことがあります。読み取り専用 [IThreeDFormat](../../aspose.slides/ithreedformat/)。 |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | 内部的なプレゼンテーションスコープの識別子を返します。この識別子はアドインやその他のコードで使用することを意図していますが、ユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。読み取り専用 **uint32_t**。詳細は [Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/) を参照してください。 |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | シェイプの幅（ポイント単位）を取得します。読み取り **float**。 |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | シェイプの左上隅の x 座標（ポイント単位）を取得します。読み取り **float**。 |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | シェイプの左上隅の y 座標（ポイント単位）を取得します。読み取り **float**。 |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | シェイプの Z オーダー内での位置を返します。Shapes[0] は Z オーダーの後方にあるシェイプを、Shapes[Shapes.Count - 1] は前方にあるシェイプを返します。読み取り専用 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | 基本的なプレースホルダーシェイプを返します（現在のシェイプが継承しているレイアウトまたはマスタースライドからのシェイプ）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | シェイプのサムネイルを返します。デフォルトでは [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) シェイプサムネイル境界タイプが使用されます。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | シェイプのサムネイルを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
| [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | このシェイプがプレースホルダーでないことを定義します。 |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | シェイプに関連付けられた代替テキストを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | シェイプに関連付けられた代替テキストのタイトルを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | プロパティはシェイプが白黒表示モードでどのようにレンダリングされるかを指定します。書き込み [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| void [set_ColorStyle](./set_colorstyle/)([SmartArtColorType](../smartartcolortype/)) override | [SmartArt](./) オブジェクトのカラースタイルを設定します。書き込み [SmartArtColorType](../smartartcolortype/)。 |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | シェイプフレームのプロパティを設定します。書き込み [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | シェイプの高さ（ポイント単位）を設定します。書き込み **float**。 |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | シェイプが非表示かどうかを設定します。書き込み **bool**。 |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | マウスクリック用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | マウスオーバー用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | 『装飾としてマーク』オプションを設定します。読み取り/書き込み **bool**。 |
| void [set_IsReversed](./set_isreversed/)(**bool**) override | [SmartArt](./) ダイアグラムが (左から右) LTR または (右から左) RTL の状態を返すまたは設定します（逆転がサポートされている場合）。書き込み **bool**。 |
| void [set_Layout](./set_layout/)([SmartArtLayoutType](../smartartlayouttype/)) override | [SmartArt](./) オブジェクトのレイアウトを設定します。書き込み [SmartArtLayoutType](../smartartlayouttype/)。 |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | シェイプの名前を設定します。null であってはなりません。必要に応じて空文字列を使用してください。書き込み [System::String](../../system/string/)。 |
| void [set_QuickStyle](./set_quickstyle/)([SmartArtQuickStyleType](../smartartquickstyletype/)) override | [SmartArt](./) オブジェクトのクイックスタイルを設定します。書き込み [SmartArtQuickStyleType](../smartartquickstyletype/)。 |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | 生のシェイプフレームのプロパティを設定します。書き込み [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | 指定されたシェイプが z 軸周りに回転した角度（度）を設定します。正の値は時計回り、負の値は反時計回りを示します。書き込み **float**。 |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | シェイプの幅（ポイント単位）を設定します。書き込み **float**。 |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | シェイプの左上隅の x 座標（ポイント単位）を設定します。書き込み **float**。 |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | シェイプの左上隅の y 座標（ポイント単位）を設定します。書き込み **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../../aspose.slides/shape/) の内容を SVG ファイルとして保存します。 |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../../aspose.slides/shape/) の内容を SVG ファイルとして保存します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [GraphicalObject](../../aspose.slides/graphicalobject/)
* クラス [ISmartArt](../ismartart/)
* 名前空間 [Aspose::Slides::SmartArt](../)
* ライブラリ [Aspose.Slides](../../)