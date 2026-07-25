---
title: SummaryZoomFrame
second_title: Aspose.Slides for C++ API リファレンス
description: スライド内の Summary Zoom オブジェクトを表します。
type: docs
weight: 5318
url: /ja/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame クラス

スライド内の Summary Zoom オブジェクトを表します。

```cpp
class SummaryZoomFrame : public Aspose::Slides::GraphicalObject,
                         public Aspose::Slides::ISummaryZoomFrame
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定したプレースホルダーのプロパティを設定します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 に基づき NaN はどの値とも等しくないと規定されていますが、C# スタイルの浮動小数点比較をエミュレートし、二つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 に基づき NaN はどの値とも等しくないと規定されていますが、C# スタイルの浮動小数点比較をエミュレートし、二つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | シェイプに関連付けられた代替テキストを返します。[System::String](../../system/string/) を参照してください。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | シェイプに関連付けられた代替テキストのタイトルを返します。[System::String](../../system/string/) を参照してください。 |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | プロパティはシェイプが白黒表示モードでどのようにレンダリングされるかを指定します。[Slides::BlackWhiteMode](../blackwhitemode/) を参照してください。 |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | シェイプ上の接続ポイントの数を返します。読み取り専用 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | シェイプのカスタムデータを返します。読み取り専用 [ICustomData](../icustomdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | シェイプに適用されたピクセルエフェクトを含む [EffectFormat](../effectformat/) オブジェクトを返します。注: エフェクトプロパティを持たない特定のシェイプタイプでは null を返す可能性があります。読み取り専用 [IEffectFormat](../ieffectformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | シェイプの塗りつぶし書式プロパティを含む [FillFormat](../fillformat/) オブジェクトを返します。注: 塗りつぶしプロパティを持たない特定のシェイプタイプでは null を返す可能性があります。読み取り専用 [IFillFormat](../ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | シェイプフレームのプロパティを返します。[IShapeFrame](../ishapeframe/) を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](../graphicalobject/get_graphicalobjectlock/)() override | シェイプのロック情報を返します。読み取り専用 [IGraphicalObjectLock](../igraphicalobjectlock/)。 |
| **float** [get_Height](../shape/get_height/)() override | シェイプの高さ（ポイント単位）を取得します。読み取り **float**。 |
| **bool** [get_Hidden](../shape/get_hidden/)() override | シェイプが非表示かどうかを判定します。読み取り **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | マウスクリック用に定義されたハイパーリンクを返します。[IHyperlink](../ihyperlink/) を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | ハイパーリンクマネージャーを返します。読み取り専用 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | マウスオーバー用に定義されたハイパーリンクを返します。[IHyperlink](../ihyperlink/) を参照してください。 |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | ‘装飾としてマーク’ オプションを取得します。読み書き **bool**。 |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | シェイプがグループ化されているかどうかを判定します。読み取り専用 **bool**。 |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | シェイプが TextHolder_PPT かどうかを判定します。読み取り専用 **bool**。 |
| [ZoomLayout](../zoomlayout/) [get_Layout](./get_layout/)() override | フレーム内の Summary Zoom セクションのレイアウトを取得します。デフォルト値は GridLayout です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | シェイプの線書式プロパティを含む [LineFormat](../lineformat/) オブジェクトを返します。注: 線プロパティを持たない特定のシェイプでは null を返す可能性があります。読み取り専用 [ILineFormat](../ilineformat/)。 |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | シェイプの名前を返します。null であってはなりません。必要に応じて空文字列を使用してください。[System::String](../../system/string/) を参照してください。 |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | シェイプの存続期間中一定のスライドスコープの一意識別子を返し、PowerPoint またはインターロップコードがドキュメント内どこからでもシェイプを確実に参照できるようにします。読み取り専用 **uint32_t**。詳しくは [Shape::get_UniqueId](../shape/get_uniqueid/) を参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | シェイプがグループ化されている場合は親 [GroupShape](../groupshape/) オブジェクトを返します。そうでない場合は null を返します。読み取り専用 [IGroupShape](../igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | シェイプのプレースホルダーを返します。プレースホルダーがない場合は null を返します。読み取り専用 [IPlaceholder](../iplaceholder/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | スライドの親プレゼンテーションを返します。読み取り専用 [IPresentation](../ipresentation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | シェイプフレームの生データプロパティを返します。[IShapeFrame](../ishapeframe/) を参照してください。 |
| **float** [get_Rotation](../shape/get_rotation/)() override | 指定したシェイプが z 軸周りに回転した角度（度）を返します。正の値は時計回り、負の値は反時計回りを示します。読み取り **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | シェイプのロック情報を返します。読み取り専用 [IBaseShapeLock](../ibaseshapelock/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | シェイプの親スライドを返します。読み取り専用 [IBaseSlide](../ibaseslide/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISummaryZoomSectionCollection](../isummaryzoomsectioncollection/)\> [get_SummaryZoomCollection](./get_summaryzoomcollection/)() override | Summary Zoom フレームオブジェクトの [ISummaryZoomSectionCollection](../isummaryzoomsectioncollection/) を取得します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ISummaryZoomSection](../isummaryzoomsection/)\> [get_SummaryZoomSection](./get_summaryzoomsection/)(**int32_t**) override | 指定インデックスのスライド内の Summary Zoom [Section](../section/) オブジェクトを返します。読み取り専用 [Aspose::Slides::ISummaryZoomSection](../isummaryzoomsection/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | シェイプの 3D エフェクトプロパティを含む [ThreeDFormat](../threedformat/) オブジェクトを返します。注: 3D プロパティを持たない特定のシェイプでは null を返す可能性があります。読み取り専用 [IThreeDFormat](../ithreedformat/)。 |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | アドインやその他のコードで使用することを目的とした、内部のプレゼンテーションスコープの識別子を返します。この値はユーザーやプログラムによって再割り当て可能なため、永続的な一意キーとして扱うべきではありません。読み取り専用 **uint32_t**。詳しくは [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/) を参照してください。 |
| **float** [get_Width](../shape/get_width/)() override | シェイプの幅（ポイント単位）を取得します。読み取り **float**。 |
| **float** [get_X](../shape/get_x/)() override | シェイプの左上隅の X 座標（ポイント単位）を取得します。読み取り **float**。 |
| **float** [get_Y](../shape/get_y/)() override | シェイプの左上隅の Y 座標（ポイント単位）を取得します。読み取り **float**。 |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | シェイプの Z オーダー内での位置を返します。Shapes[0] は Z オーダーの最背面のシェイプを、Shapes[Shapes.Count - 1] は最前面のシェイプを返します。読み取り専用 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | 基本的なプレースホルダーシェイプ（現在のシェイプが継承しているレイアウトまたはマスタースライドからのシェイプ）を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | シェイプのサムネイルを返します。デフォルトでは [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) シェイプサムネイル境界タイプが使用されます。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | シェイプのサムネイルを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロック機能を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
| [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照でオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列のケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | このシェイプがプレースホルダーではないことを定義します。 |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | シェイプに関連付けられた代替テキストを設定します。[System::String](../../system/string/) に書き込みます。 |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | シェイプに関連付けられた代替テキストのタイトルを設定します。[System::String](../../system/string/) に書き込みます。 |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | プロパティはシェイプが白黒表示モードでどのようにレンダリングされるかを指定します。[Slides::BlackWhiteMode](../blackwhitemode/) に書き込みます。 |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | シェイプフレームのプロパティを設定します。[IShapeFrame](../ishapeframe/) に書き込みます。 |
| void [set_Height](../shape/set_height/)(**float**) override | シェイプの高さ（ポイント単位）を設定します。**float** で書き込みます。 |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | シェイプが非表示かどうかを設定します。**bool** で書き込みます。 |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | マウスクリック用に定義されたハイパーリンクを設定します。[IHyperlink](../ihyperlink/) に書き込みます。 |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | マウスオーバー用に定義されたハイパーリンクを設定します。[IHyperlink](../ihyperlink/) に書き込みます。 |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | ‘装飾としてマーク’ オプションを設定します。**bool** で読み書きします。 |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | シェイプの名前を設定します。null であってはなりません。必要に応じて空文字列を使用してください。[System::String](../../system/string/) に書き込みます。 |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | シェイプフレームの生データプロパティを設定します。[IShapeFrame](../ishapeframe/) に書き込みます。 |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | 指定されたシェイプが z 軸周りに回転した角度（度）を設定します。正の値は時計回り、負の値は反時計回りを示します。**float** で書き込みます。 |
| void [set_Width](../shape/set_width/)(**float**) override | シェイプの幅（ポイント単位）を設定します。**float** で書き込みます。 |
| void [set_X](../shape/set_x/)(**float**) override | シェイプの左上隅の X 座標（ポイント単位）を設定します。**float** で書き込みます。 |
| void [set_Y](../shape/set_y/)(**float**) override | シェイプの左上隅の Y 座標（ポイント単位）を設定します。**float** で書き込みます。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を共有ではなく弱参照ポインタに設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/) の内容を SVG ファイルとして保存します。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/) の内容を SVG ファイルとして保存します。 |
| virtual [~Object](../../system/object/~object/)() | オブジェクトを破棄し、すべての内部データ構造を解放します。 |

## 参照

* クラス [GraphicalObject](../graphicalobject/)
* クラス [ISummaryZoomFrame](../isummaryzoomframe/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)