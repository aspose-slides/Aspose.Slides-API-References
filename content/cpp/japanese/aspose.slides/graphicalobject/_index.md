---
title: GraphicalObject
second_title: Aspose.Slides for C++ API リファレンス
description: 抽象的なグラフィカルオブジェクトを表します。
type: docs
weight: 1171
url: /ja/aspose.slides/graphicalobject/
---
## GraphicalObject クラス


抽象的なグラフィカルオブジェクトを表します。

```cpp
class GraphicalObject : public Aspose::Slides::Shape,
                        public virtual Aspose::Slides::IGraphicalObject
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、プレースホルダーのプロパティを指定されたものに設定します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 に従い NaN はどの値とも等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 に従い NaN はどの値とも等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | シェイプに関連付けられた代替テキストを返します。参照 [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | シェイプに関連付けられた代替テキストのタイトルを返します。参照 [System::String](../../system/string/)。 |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。参照 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | シェイプ上の接続ポイントの数を返します。読み取り専用 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | シェイプのカスタムデータを返します。読み取り専用 [ICustomData](../icustomdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | [EffectFormat](../effectformat/) オブジェクトを返します。このオブジェクトはシェイプに適用されたピクセル効果を含みます。注: 効果プロパティを持たない特定のシェイプタイプでは null を返すことがあります。読み取り専用 [IEffectFormat](../ieffectformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | [FillFormat](../fillformat/) オブジェクトを返します。このオブジェクトはシェイプの塗りつぶし書式プロパティを含みます。注: 塗りつぶしプロパティを持たない特定のシェイプタイプでは null を返すことがあります。読み取り専用 [IFillFormat](../ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | シェイプフレームのプロパティを返します。参照 [IShapeFrame](../ishapeframe/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../igraphicalobjectlock/)\> [get_GraphicalObjectLock](./get_graphicalobjectlock/)() override | シェイプのロックを返します。読み取り専用 [IGraphicalObjectLock](../igraphicalobjectlock/)。 |
| **float** [get_Height](../shape/get_height/)() override | シェイプの高さ（ポイント単位）を取得します。読み取り **float**。 |
| **bool** [get_Hidden](../shape/get_hidden/)() override | シェイプが非表示かどうかを判定します。読み取り **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | マウスクリック用に定義されたハイパーリンクを返します。参照 [IHyperlink](../ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | ハイパーリンクマネージャーを返します。読み取り専用 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | マウスオーバー用に定義されたハイパーリンクを返します。参照 [IHyperlink](../ihyperlink/)。 |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 「装飾としてマーク」オプションを取得します。読み取り/書き込み **bool**。 |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | シェイプがグループ化されているかどうかを判定します。読み取り専用 **bool**。 |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | シェイプが TextHolder_PPT かどうかを判定します。読み取り専用 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | [LineFormat](../lineformat/) オブジェクトを返します。このオブジェクトはシェイプの線書式プロパティを含みます。注: 線プロパティを持たない特定のシェイプタイプでは null を返すことがあります。読み取り専用 [ILineFormat](../ilineformat/)。 |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | シェイプの名前を返します。null であってはなりません。必要に応じて空文字列を使用してください。参照 [System::String](../../system/string/)。 |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | スライド単位の一意の識別子を返します。この識別子はシェイプの存続期間中一定で、PowerPoint やインターオップコードが文書内の任意の場所からシェイプを確実に参照できます。読み取り専用 **uint32_t**。詳しくは [Shape::get_UniqueId](../shape/get_uniqueid/) を参照。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | シェイプがグループ化されている場合、親 [GroupShape](../groupshape/) オブジェクトを返します。そうでない場合は null を返します。読み取り専用 [IGroupShape](../igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | シェイプのプレースホルダーを返します。プレースホルダーがない場合は null を返します。読み取り専用 [IPlaceholder](../iplaceholder/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | スライドの親プレゼンテーションを返します。読み取り専用 [IPresentation](../ipresentation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | 生のシェイプフレームのプロパティを返します。参照 [IShapeFrame](../ishapeframe/)。 |
| **float** [get_Rotation](../shape/get_rotation/)() override | 指定されたシェイプが Z 軸周りに回転した角度（度）を返します。正の値は時計回り、負の値は反時計回りを示します。読み取り **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | シェイプのロックを返します。読み取り専用 [IBaseShapeLock](../ibaseshapelock/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | シェイプの親スライドを返します。読み取り専用 [IBaseSlide](../ibaseslide/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | [ThreeDFormat](../threedformat/) オブジェクトを返します。このオブジェクトはシェイプの 3D 効果プロパティを含みます。注: 3D プロパティを持たない特定のシェイプタイプでは null を返すことがあります。読み取り専用 [IThreeDFormat](../ithreedformat/)。 |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | アドインや他のコードで使用することを目的とした、内部のプレゼンテーション単位の識別子を返します。この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはいけません。読み取り専用 **uint32_t**。詳しくは [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/) を参照。 |
| **float** [get_Width](../shape/get_width/)() override | シェイプの幅（ポイント単位）を取得します。読み取り **float**。 |
| **float** [get_X](../shape/get_x/)() override | シェイプの左上隅の x 座標（ポイント単位）を取得します。読み取り **float**。 |
| **float** [get_Y](../shape/get_y/)() override | シェイプの左上隅の y 座標（ポイント単位）を取得します。読み取り **float**。 |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | シェイプの Z 順序における位置を返します。Shapes[0] は Z 順序の最背面のシェイプを、Shapes[Shapes.Count - 1] は最前面のシェイプを返します。読み取り専用 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | 基本的なプレースホルダーシェイプを返します（現在のシェイプが継承しているレイアウトまたはマスタースライドからのシェイプ）。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | シェイプのサムネイルを返します。デフォルトで [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) シェイプサムネイル境界タイプが使用されます。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | シェイプのサムネイルを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | このシェイプがプレースホルダーでないことを定義します。 |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | シェイプに関連付けられた代替テキストを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | シェイプに関連付けられた代替テキストのタイトルを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。書き込み [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | シェイプフレームのプロパティを設定します。書き込み [IShapeFrame](../ishapeframe/)。 |
| void [set_Height](../shape/set_height/)(**float**) override | シェイプの高さ（ポイント単位）を設定します。書き込み **float**。 |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | シェイプが非表示かどうかを設定します。書き込み **bool**。 |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | マウスクリック用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../ihyperlink/)。 |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | マウスオーバー用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../ihyperlink/)。 |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 「装飾としてマーク」オプションを設定します。読み取り/書き込み **bool**。 |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | シェイプの名前を設定します。null であってはなりません。必要に応じて空文字列を使用してください。書き込み [System::String](../../system/string/)。 |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 生のシェイプフレームのプロパティを設定します。書き込み [IShapeFrame](../ishapeframe/)。 |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | 指定されたシェイプが Z 軸周りに回転した角度（度）を設定します。正の値は時計回り、負の値は反時計回りを示します。書き込み **float**。 |
| void [set_Width](../shape/set_width/)(**float**) override | シェイプの幅（ポイント単位）を設定します。書き込み **float**。 |
| void [set_X](../shape/set_x/)(**float**) override | シェイプの左上隅の x 座標（ポイント単位）を設定します。書き込み **float**。 |
| void [set_Y](../shape/set_y/)(**float**) override | シェイプの左上隅の y 座標（ポイント単位）を設定します。書き込み **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/) の内容を SVG ファイルとして保存します。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/) の内容を SVG ファイルとして保存します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [Shape](../shape/)
* クラス [IGraphicalObject](../igraphicalobject/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)