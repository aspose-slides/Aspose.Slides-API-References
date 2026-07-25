---
title: IGroupShape
second_title: Aspose.Slides for C++ API リファレンス
description: スライド上のシェイプのグループを表します。
type: docs
weight: 2484
url: /ja/aspose.slides/igroupshape/
---
## IGroupShape クラス

Represents a group of shapes on a slide.

```cpp
class IGroupShape : public virtual Aspose::Slides::IShape
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、プレースホルダーのプロパティを指定されたものに設定します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 参照型オブジェクトを C# スタイルで比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | 値型オブジェクトを C# スタイルで比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | C# スタイルの浮動小数点比較をエミュレートします。IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | シェイプに関連付けられた代替テキストを返します。参照 [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | シェイプに関連付けられた代替テキストのタイトルを返します。参照 [System::String](../../system/string/)。 |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | プロパティは、シェイプが白黒表示モードでどのように描画されるかを指定します。参照 [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | シェイプの接続ポイント数を返します。読み取り専用 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | シェイプのカスタムデータを返します。読み取り専用 [ICustomData](../icustomdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | [EffectFormat](../effectformat/) オブジェクトを返します。これはシェイプに適用されたピクセル効果を含みます。読み取り専用 [IEffectFormat](../ieffectformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | [FillFormat](../fillformat/) オブジェクトを返します。シェイプの塗りつぶし書式プロパティを含みます。読み取り専用 [IFillFormat](../ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | シェイプフレームのプロパティを返します。参照 [IShapeFrame](../ishapeframe/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShapeLock](../igroupshapelock/)\> [get_GroupShapeLock](./get_groupshapelock/)() | シェイプのロックを返します。読み取り専用 [IGroupShapeLock](../igroupshapelock/)。 |
| virtual **float** [get_Height](../ishape/get_height/)() | シェイプの高さ（ポイント単位）を取得します。読み取り **float**。 |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | シェイプが非表示かどうかを判定します。読み取り **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | マウスクリック用に定義されたハイパーリンクを返します。参照 [IHyperlink](../ihyperlink/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | ハイパーリンクマネージャー。読み取り専用 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | マウスオーバー用に定義されたハイパーリンクを返します。参照 [IHyperlink](../ihyperlink/)。 |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | 'Mark as decorative' オプションを取得します。読み取り/書き込み **bool**。 |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | シェイプがグループ化されているかどうかを判定します。読み取り専用 **bool**。 |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | シェイプが TextHolder かどうかを判定します。読み取り専用 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | [LineFormat](../lineformat/) オブジェクトを返します。シェイプの線書式プロパティを含みます。読み取り専用 [ILineFormat](../ilineformat/)。 |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | シェイプの名前を返します。参照 [System::String](../../system/string/)。 |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | シェイプのライフタイム中に一定で、PowerPoint または相互運用コードがドキュメント内の任意の場所からシェイプを確実に参照できるスライドスコープの一意識別子を返します。読み取り専用 **uint32_t**。[IShape::get_UniqueId](../ishape/get_uniqueid/) も参照ください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](./)\> [get_ParentGroup](../ishape/get_parentgroup/)() | シェイプがグループ化されている場合、親 [GroupShape](../groupshape/) オブジェクトを返します。それ以外の場合は null を返します。読み取り専用 [IGroupShape](./)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | シェイプのプレースホルダーを返します。読み取り専用 [IPlaceholder](../iplaceholder/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | プレゼンテーションを返します。読み取り専用 [IPresentation](../ipresentation/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | 生のシェイプフレームのプロパティを返します。参照 [IShapeFrame](../ishapeframe/)。 |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | 指定されたシェイプが Z 軸周りに回転した角度（度）を返します。正の値は時計回り、負の値は反時計回りを示します。読み取り **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [get_Shape](./get_shape/)(**int32_t**) | 指定されたインデックスのグループ内シェイプを返します。読み取り専用 [Aspose::Slides::IShape](../ishape/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | シェイプのロックを返します。読み取り専用 [IBaseShapeLock](../ibaseshapelock/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeCollection](../ishapecollection/)\> [get_Shapes](./get_shapes/)() | グループ内のシェイプコレクションを返します。読み取り専用 [IShapeCollection](../ishapecollection/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | 基底スライドを返します。読み取り専用 [IBaseSlide](../ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | [ThreeDFormat](../threedformat/) オブジェクトを返します。シェイプの線書式プロパティを含みます。読み取り専用 [IThreeDFormat](../ithreedformat/)。 |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | アドインやその他のコードが使用することを意図した、内部のプレゼンテーションスコープ識別子を返します。この値はユーザーやプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。読み取り専用 **uint32_t**。[IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/) も参照ください。 |
| virtual **float** [get_Width](../ishape/get_width/)() | シェイプの幅（ポイント単位）を取得します。読み取り **float**。 |
| virtual **float** [get_X](../ishape/get_x/)() | シェイプ左上隅の X 座標（ポイント単位）を取得します。読み取り **float**。 |
| virtual **float** [get_Y](../ishape/get_y/)() | シェイプ左上隅の Y 座標（ポイント単位）を取得します。読み取り **float**。 |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | Z オーダー内でシェイプの位置を返します。Shapes[0] は Z オーダーの背面のシェイプを、Shapes[Shapes.Count - 1] は前面のシェイプを返します。読み取り専用 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | 基本的なプレースホルダーシェイプ（レイアウトやマスタースライドから継承されたシェイプ）を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | シェイプのサムネイルを返します。デフォルトで [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) シェイプサムネイル境界タイプが使用されます。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | シェイプのサムネイルを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロック機能を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネイルオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトを nullptr と参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケース向け特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケース向け特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | このシェイプがプレースホルダーでないことを定義します。 |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | シェイプに関連付けられた代替テキストを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | シェイプに関連付けられた代替テキストのタイトルを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | プロパティは、シェイプが白黒表示モードでどのように描画されるかを指定します。書き込み [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | シェイプフレームのプロパティを設定します。書き込み [IShapeFrame](../ishapeframe/)。 |
| virtual void [set_Height](../ishape/set_height/)(**float**) | シェイプの高さ（ポイント単位）を設定します。書き込み **float**。 |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | シェイプが非表示かどうかを設定します。書き込み **bool**。 |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | マウスクリック用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../ihyperlink/)。 |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | マウスオーバー用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../ihyperlink/)。 |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | 'Mark as decorative' オプションを設定します。読み取り/書き込み **bool**。 |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | シェイプの名前を設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | 生のシェイプフレームのプロパティを設定します。書き込み [IShapeFrame](../ishapeframe/)。 |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | 指定されたシェイプが Z 軸周りに回転する角度（度）を設定します。正の値は時計回り、負の値は反時計回りを示します。書き込み **float**。 |
| virtual void [set_Width](../ishape/set_width/)(**float**) | シェイプの幅（ポイント単位）を設定します。書き込み **float**。 |
| virtual void [set_X](../ishape/set_x/)(**float**) | シェイプ左上隅の X 座標（ポイント単位）を設定します。書き込み **float**。 |
| virtual void [set_Y](../ishape/set_y/)(**float**) | シェイプ左上隅の Y 座標（ポイント単位）を設定します。書き込み **float**。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることが可能です。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンターの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントを減少させ、その値を返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティネイルオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントを減少させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../shape/) の内容を SVG ファイルとして保存します。 |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../shape/) の内容を SVG ファイルとして保存します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IShape](../ishape/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)