---
title: IInk
second_title: Aspose.Slides for C++ APIリファレンス
description: スライド上のインク オブジェクトを表します。
type: docs
weight: 1
url: /ja/aspose.slides.ink/iink/
---
## IInk クラス

スライド上のインク オブジェクトを表します。

```cpp
class IInk : public virtual Aspose::Slides::IGraphicalObject
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、プレースホルダーのプロパティを指定されたものに設定します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# の [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN はどの値（NaN を含む）とも等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN はどの値（NaN を含む）とも等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/ishape/get_alternativetext/)() | シェイプに関連付けられた代替テキストを返します。[System::String](../../system/string/) を参照してください。 |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/ishape/get_alternativetexttitle/)() | シェイプに関連付けられた代替テキストのタイトルを返します。[System::String](../../system/string/) を参照してください。 |
| virtual [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/ishape/get_blackwhitemode/)() | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。[Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) を参照してください。 |
| virtual **int32_t** [get_ConnectionSiteCount](../../aspose.slides/ishape/get_connectionsitecount/)() | シェイプ上の接続ポイントの数を返します。読み取り専用 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/ishape/get_customdata/)() | シェイプのカスタムデータを返します。読み取り専用 [ICustomData](../../aspose.slides/icustomdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/ishape/get_effectformat/)() | [EffectFormat](../../aspose.slides/effectformat/) オブジェクトを返します。このオブジェクトはシェイプに適用されたピクセル効果を含みます。読み取り専用 [IEffectFormat](../../aspose.slides/ieffectformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/ishape/get_fillformat/)() | [FillFormat](../../aspose.slides/fillformat/) オブジェクトを返します。このオブジェクトはシェイプの塗りつぶし書式プロパティを含みます。読み取り専用 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/ishape/get_frame/)() | シェイプフレームのプロパティを返します。[IShapeFrame](../../aspose.slides/ishapeframe/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)\> [get_GraphicalObjectLock](../../aspose.slides/igraphicalobject/get_graphicalobjectlock/)() | シェイプのロック情報を返します。読み取り専用 [IGraphicalObjectLock](../../aspose.slides/igraphicalobjectlock/)。 |
| virtual **float** [get_Height](../../aspose.slides/ishape/get_height/)() | シェイプの高さ（ポイント単位）を取得します。読み取り専用 **float**。 |
| virtual **bool** [get_Hidden](../../aspose.slides/ishape/get_hidden/)() | シェイプが非表示かどうかを判定します。読み取り専用 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkclick/)() | マウスクリック用に定義されたハイパーリンクを返します。[IHyperlink](../../aspose.slides/ihyperlink/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmanager/)() | ハイパーリンクマネージャー。読み取り専用 [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/get_hyperlinkmouseover/)() | マウスオーバー用に定義されたハイパーリンクを返します。[IHyperlink](../../aspose.slides/ihyperlink/) を参照してください。 |
| virtual **bool** [get_IsDecorative](../../aspose.slides/ishape/get_isdecorative/)() | '装飾としてマーク' オプションを取得します。読み書き可能 **bool**。 |
| virtual **bool** [get_IsGrouped](../../aspose.slides/ishape/get_isgrouped/)() | シェイプがグループ化されているかどうかを判定します。読み取り専用 **bool**。 |
| virtual **bool** [get_IsTextHolder](../../aspose.slides/ishape/get_istextholder/)() | シェイプが TextHolder かどうかを判定します。読み取り専用 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/ishape/get_lineformat/)() | [LineFormat](../../aspose.slides/lineformat/) オブジェクトを返します。このオブジェクトはシェイプの線書式プロパティを含みます。読み取り専用 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| virtual [System::String](../../system/string/) [get_Name](../../aspose.slides/ishape/get_name/)() | シェイプの名前を返します。[System::String](../../system/string/) を参照してください。 |
| virtual **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/)() | シェイプの存続期間中一定で、スライド内で一意の識別子を返します。これにより、PowerPoint や相互運用コードがドキュメント内の任意の場所からシェイプを確実に参照できます。読み取り専用 **uint32_t**。[IShape::get_UniqueId](../../aspose.slides/ishape/get_uniqueid/) も参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/ishape/get_parentgroup/)() | シェイプがグループ化されている場合は親 [GroupShape](../../aspose.slides/groupshape/) オブジェクトを返します。それ以外の場合は null を返します。読み取り専用 [IGroupShape](../../aspose.slides/igroupshape/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/ishape/get_placeholder/)() | シェイプのプレースホルダーを返します。読み取り専用 [IPlaceholder](../../aspose.slides/iplaceholder/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/ipresentationcomponent/get_presentation/)() | プレゼンテーションを返します。読み取り専用 [IPresentation](../../aspose.slides/ipresentation/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/ishape/get_rawframe/)() | 生のシェイプフレームのプロパティを返します。[IShapeFrame](../../aspose.slides/ishapeframe/) を参照してください。 |
| virtual **float** [get_Rotation](../../aspose.slides/ishape/get_rotation/)() | 指定されたシェイプが Z 軸を中心に回転した角度（度）を返します。正の値は時計回り、負の値は反時計回りを示します。読み取り専用 **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/ishape/get_shapelock/)() | シェイプのロック情報を返します。読み取り専用 [IBaseShapeLock](../../aspose.slides/ibaseshapelock/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/islidecomponent/get_slide/)() | 基底スライドを返します。読み取り専用 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/ishape/get_threedformat/)() | [ThreeDFormat](../../aspose.slides/threedformat/) オブジェクトを返します。このオブジェクトはシェイプの線書式プロパティを含みます。読み取り専用 [IThreeDFormat](../../aspose.slides/ithreedformat/)。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IInkTrace](../iinktrace/)\>\> [get_Traces](./get_traces/)() | [IInk](./) 要素 [IInkTrace](../iinktrace/) に含まれるすべてのトレースを取得します。読み取り専用。 |
| virtual **uint32_t** [get_UniqueId](../../aspose.slides/ishape/get_uniqueid/)() | アドインやその他のコードが使用することを意図した、内部のプレゼンテーションスコープの識別子を返します。この値はユーザーやプログラムによって再割り当て可能なため、永続的な一意キーとして扱うべきではありません。読み取り専用 **uint32_t**。[IShape::get_OfficeInteropShapeId](../../aspose.slides/ishape/get_officeinteropshapeid/) も参照してください。 |
| virtual **float** [get_Width](../../aspose.slides/ishape/get_width/)() | シェイプの幅（ポイント単位）を取得します。読み取り専用 **float**。 |
| virtual **float** [get_X](../../aspose.slides/ishape/get_x/)() | シェイプの左上隅の x 座標（ポイント単位）を取得します。読み取り専用 **float**。 |
| virtual **float** [get_Y](../../aspose.slides/ishape/get_y/)() | シェイプの左上隅の y 座標（ポイント単位）を取得します。読み取り専用 **float**。 |
| virtual **int32_t** [get_ZOrderPosition](../../aspose.slides/ishape/get_zorderposition/)() | シェイプの Z オーダー上の位置を返します。Shapes[0] は Z オーダーの背面にあるシェイプを返し、Shapes[Shapes.Count - 1] は前面にあるシェイプを返します。読み取り専用 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder/)() | 基本的なプレースホルダーシェイプ（現在のシェイプが継承元となるレイアウトまたはマスタースライドからのシェイプ）を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタのデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)() | シェイプのサムネイルを返します。デフォルトで [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) シェイプサムネイルの境界タイプが使用されます。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/ishape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) | シェイプのサムネイルを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかどうかをチェックします。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロック機構を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列の場合に対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder/)() | このシェイプがプレースホルダーでないことを定義します。 |
| virtual void [set_AlternativeText](../../aspose.slides/ishape/set_alternativetext/)([System::String](../../system/string/)) | シェイプに関連付けられた代替テキストを設定します。[System::String](../../system/string/) に書き込んでください。 |
| virtual void [set_AlternativeTextTitle](../../aspose.slides/ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | シェイプに関連付けられた代替テキストのタイトルを設定します。[System::String](../../system/string/) に書き込んでください。 |
| virtual void [set_BlackWhiteMode](../../aspose.slides/ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。[Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) に書き込んでください。 |
| virtual void [set_Frame](../../aspose.slides/ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | シェイプフレームのプロパティを設定します。[IShapeFrame](../../aspose.slides/ishapeframe/) に書き込んでください。 |
| virtual void [set_Height](../../aspose.slides/ishape/set_height/)(**float**) | シェイプの高さ（ポイント単位）を設定します。**float** に書き込んでください。 |
| virtual void [set_Hidden](../../aspose.slides/ishape/set_hidden/)(**bool**) | シェイプが非表示かどうかを設定します。**bool** に書き込んでください。 |
| virtual void [set_HyperlinkClick](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | マウスクリック用に定義されたハイパーリンクを設定します。[IHyperlink](../../aspose.slides/ihyperlink/) に書き込んでください。 |
| virtual void [set_HyperlinkMouseOver](../../aspose.slides/ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) | マウスオーバー用に定義されたハイパーリンクを設定します。[IHyperlink](../../aspose.slides/ihyperlink/) に書き込んでください。 |
| virtual void [set_IsDecorative](../../aspose.slides/ishape/set_isdecorative/)(**bool**) | '装飾としてマーク' オプションを設定します。読み書き可能 **bool**。 |
| virtual void [set_Name](../../aspose.slides/ishape/set_name/)([System::String](../../system/string/)) | シェイプの名前を設定します。[System::String](../../system/string/) に書き込んでください。 |
| virtual void [set_RawFrame](../../aspose.slides/ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) | 生のシェイプフレームのプロパティを設定します。[IShapeFrame](../../aspose.slides/ishapeframe/) に書き込んでください。 |
| virtual void [set_Rotation](../../aspose.slides/ishape/set_rotation/)(**float**) | 指定されたシェイプが Z 軸を中心に回転した角度（度）を設定します。正の値は時計回り、負の値は反時計回りを示します。**float** に書き込んでください。 |
| virtual void [set_Width](../../aspose.slides/ishape/set_width/)(**float**) | シェイプの幅（ポイント単位）を設定します。**float** に書き込んでください。 |
| virtual void [set_X](../../aspose.slides/ishape/set_x/)(**float**) | シェイプの左上隅の x 座標（ポイント単位）を設定します。**float** に書き込んでください。 |
| virtual void [set_Y](../../aspose.slides/ishape/set_y/)(**float**) | シェイプの左上隅の y 座標（ポイント単位）を設定します。**float** に書き込んでください。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱いポインタに設定します（共有ではなく）。コンテナ内のポインタを弱参照モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウントの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../../aspose.slides/shape/) の内容を SVG ファイルとして保存します。 |
| virtual void [WriteAsSvg](../../aspose.slides/ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../../aspose.slides/shape/) の内容を SVG ファイルとして保存します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IGraphicalObject](../../aspose.slides/igraphicalobject/)
* 名前空間 [Aspose::Slides::Ink](../)
* ライブラリ [Aspose.Slides](../../)