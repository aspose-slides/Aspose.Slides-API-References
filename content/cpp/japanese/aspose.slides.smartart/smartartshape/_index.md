---
title: SmartArtShape
second_title: Aspose.Slides for C++ API リファレンス
description: SmartArt シェイプを表します
type: docs
weight: 105
url: /ja/aspose.slides.smartart/smartartshape/
---
## SmartArtShape クラス


Represents [SmartArt](../smartart/) shape

```cpp
class SmartArtShape : public Aspose::Slides::GeometryShape,
                      public Aspose::Slides::SmartArt::ISmartArtShape
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [AddPlaceholder](../../aspose.slides/shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\>) override | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../../aspose.slides/ishapeelement/)\>\> [CreateShapeElements](../../aspose.slides/geometryshape/createshapeelements/)() override | シェイプの要素の配列を作成して返します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいとみなします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../../aspose.slides/iadjustvalue/)\> [get_Adjustment](../../aspose.slides/geometryshape/get_adjustment/)(**int32_t**) override | 指定されたインデックスのシェイプの調整値を返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/)\> [get_Adjustments](../../aspose.slides/geometryshape/get_adjustments/)() override | シェイプの調整値のコレクションを返します。読み取り専用 [IAdjustValueCollection](../../aspose.slides/iadjustvaluecollection/)。 |
| [System::String](../../system/string/) [get_AlternativeText](../../aspose.slides/shape/get_alternativetext/)() override | シェイプに関連付けられた代替テキストを返します。読み取り [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../../aspose.slides/shape/get_alternativetexttitle/)() override | シェイプに関連付けられた代替テキストのタイトルを返します。読み取り [System::String](../../system/string/)。 |
| [Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/) [get_BlackWhiteMode](../../aspose.slides/shape/get_blackwhitemode/)() override | プロパティはシェイプが白黒表示モードでどのようにレンダリングされるかを指定します。読み取り [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| **int32_t** [get_ConnectionSiteCount](../../aspose.slides/shape/get_connectionsitecount/)() override | シェイプ上の接続ポイントの数を返します。読み取り専用 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../../aspose.slides/icustomdata/)\> [get_CustomData](../../aspose.slides/shape/get_customdata/)() override | シェイプのカスタムデータを返します。読み取り専用 [ICustomData](../../aspose.slides/icustomdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../../aspose.slides/ieffectformat/)\> [get_EffectFormat](../../aspose.slides/shape/get_effectformat/)() override | シェイプに適用されたピクセル効果を含む [EffectFormat](../../aspose.slides/effectformat/) オブジェクトを返します。注: 効果プロパティを持たない特定のシェイプタイプでは null を返すことがあります。読み取り専用 [IEffectFormat](../../aspose.slides/ieffectformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../../aspose.slides/ifillformat/)\> [get_FillFormat](../../aspose.slides/shape/get_fillformat/)() override | シェイプの塗りつぶし書式プロパティを含む [FillFormat](../../aspose.slides/fillformat/) オブジェクトを返します。注: 塗りつぶしプロパティを持たない特定のシェイプタイプでは null を返すことがあります。読み取り専用 [IFillFormat](../../aspose.slides/ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_Frame](../../aspose.slides/shape/get_frame/)() override | シェイプフレームのプロパティを返します。読み取り [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| **float** [get_Height](../../aspose.slides/shape/get_height/)() override | シェイプの高さ（ポイント単位）を取得します。読み取り **float**。 |
| **bool** [get_Hidden](../../aspose.slides/shape/get_hidden/)() override | シェイプが非表示かどうかを判定します。読み取り **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkClick](../../aspose.slides/shape/get_hyperlinkclick/)() override | マウスクリック用に定義されたハイパーリンクを返します。読み取り [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)\> [get_HyperlinkManager](../../aspose.slides/shape/get_hyperlinkmanager/)() override | ハイパーリンクマネージャーを返します。読み取り専用 [IHyperlinkManager](../../aspose.slides/ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\> [get_HyperlinkMouseOver](../../aspose.slides/shape/get_hyperlinkmouseover/)() override | マウスオーバー用に定義されたハイパーリンクを返します。読み取り [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| **bool** [get_IsDecorative](../../aspose.slides/shape/get_isdecorative/)() override | 装飾としてマークするオプションを取得します。読み取り/書き込み **bool**。 |
| **bool** [get_IsGrouped](../../aspose.slides/shape/get_isgrouped/)() override | シェイプがグループ化されているかどうかを判定します。読み取り専用 **bool**。 |
| **bool** [get_IsTextHolder](../../aspose.slides/shape/get_istextholder/)() override | シェイプが TextHolder_PPT かどうかを判定します。読み取り専用 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../../aspose.slides/ilineformat/)\> [get_LineFormat](../../aspose.slides/shape/get_lineformat/)() override | シェイプの線書式プロパティを含む [LineFormat](../../aspose.slides/lineformat/) オブジェクトを返します。注: 線プロパティを持たない特定のシェイプタイプでは null を返すことがあります。読み取り専用 [ILineFormat](../../aspose.slides/ilineformat/)。 |
| [System::String](../../system/string/) [get_Name](../../aspose.slides/shape/get_name/)() override | シェイプの名前を返します。null であってはなりません。必要に応じて空文字列を使用してください。読み取り [System::String](../../system/string/)。 |
| **uint32_t** [get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/)() override | シェイプのライフタイム中に一定で、PowerPoint またはインターオップコードがドキュメント内の任意の場所からシェイプを確実に参照できるスライドスコープの一意な識別子を返します。読み取り専用 **uint32_t**。[Shape::get_UniqueId](../../aspose.slides/shape/get_uniqueid/) も参照してください。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../../aspose.slides/igroupshape/)\> [get_ParentGroup](../../aspose.slides/shape/get_parentgroup/)() override | シェイプがグループ化されている場合、親 [GroupShape](../../aspose.slides/groupshape/) オブジェクトを返します。そうでなければ null を返します。読み取り専用 [IGroupShape](../../aspose.slides/igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../../aspose.slides/iplaceholder/)\> [get_Placeholder](../../aspose.slides/shape/get_placeholder/)() override | シェイプのプレースホルダーを返します。プレースホルダーがない場合は null を返します。読み取り専用 [IPlaceholder](../../aspose.slides/iplaceholder/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../../aspose.slides/ipresentation/)\> [get_Presentation](../../aspose.slides/shape/get_presentation/)() override | スライドの親プレゼンテーションを返します。読み取り専用 [IPresentation](../../aspose.slides/ipresentation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\> [get_RawFrame](../../aspose.slides/shape/get_rawframe/)() override | 生のシェイプフレームのプロパティを返します。読み取り [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| **float** [get_Rotation](../../aspose.slides/shape/get_rotation/)() override | 指定されたシェイプが z 軸周りに回転した角度（度）を返します。正の値は時計回り、負の値は反時計回りを示します。読み取り **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../../aspose.slides/ibaseshapelock/)\> [get_ShapeLock](../../aspose.slides/shape/get_shapelock/)() override | シェイプのロック状態を返します。読み取り専用 [IBaseShapeLock](../../aspose.slides/ibaseshapelock/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../../aspose.slides/ishapestyle/)\> [get_ShapeStyle](../../aspose.slides/geometryshape/get_shapestyle/)() override | シェイプのスタイルオブジェクトを返します。読み取り専用 [IShapeStyle](../../aspose.slides/ishapestyle/)。 |
| [Aspose::Slides::ShapeType](../../aspose.slides/shapetype/) [get_ShapeType](./get_shapetype/)() override | ジオメトリのプリセットタイプを返します。注: 値が変更されると、すべての調整値はデフォルト値にリセットされます。読み取り [Slides::ShapeType](../../aspose.slides/shapetype/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../../aspose.slides/ibaseslide/)\> [get_Slide](../../aspose.slides/shape/get_slide/)() override | シェイプの親スライドを返します。読み取り専用 [IBaseSlide](../../aspose.slides/ibaseslide/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ITextFrame](../../aspose.slides/itextframe/)\> [get_TextFrame](./get_textframe/)() override | [SmartArt](../smartart/) シェイプのテキストを返します。読み取り専用 [ITextFrame](../../aspose.slides/itextframe/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../../aspose.slides/ithreedformat/)\> [get_ThreeDFormat](../../aspose.slides/shape/get_threedformat/)() override | シェイプの 3D 効果プロパティを含む [ThreeDFormat](../../aspose.slides/threedformat/) オブジェクトを返します。注: 3D プロパティを持たない特定のシェイプタイプでは null を返すことがあります。読み取り専用 [IThreeDFormat](../../aspose.slides/ithreedformat/)。 |
| **uint32_t** [get_UniqueId](../../aspose.slides/shape/get_uniqueid/)() override | アドインやその他のコードが使用することを想定した内部のプレゼンテーションスコープの識別子を返します。この値はユーザーやプログラムにより再割り当て可能なため、永続的な固有キーとして扱ってはなりません。読み取り専用 **uint32_t**。[Shape::get_OfficeInteropShapeId](../../aspose.slides/shape/get_officeinteropshapeid/) も参照してください。 |
| **float** [get_Width](../../aspose.slides/shape/get_width/)() override | シェイプの幅（ポイント単位）を取得します。読み取り **float**。 |
| **float** [get_X](../../aspose.slides/shape/get_x/)() override | シェイプ左上隅の x 座標（ポイント単位）を取得します。読み取り **float**。 |
| **float** [get_Y](../../aspose.slides/shape/get_y/)() override | シェイプ左上隅の y 座標（ポイント単位）を取得します。読み取り **float**。 |
| **int32_t** [get_ZOrderPosition](../../aspose.slides/shape/get_zorderposition/)() override | シェイプの Z オーダー内での位置を返します。Shapes[0] は Z オーダーの最後（背面）のシェイプを返し、Shapes[Shapes.Count - 1] は最前面のシェイプを返します。読み取り専用 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../../aspose.slides/ishape/)\> [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder/)() override | 基本的なプレースホルダーシェイプ（レイアウトやマスタースライドから継承されたシェイプ）を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)>\> [GetGeometryPaths](../../aspose.slides/geometryshape/getgeometrypaths/)() override | ジオメトリシェイプのパスのコピーを返します。座標はシェイプの左上隅に対して相対的です。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)() override | シェイプのサムネイルを返します。デフォルトでは [ShapeThumbnailBounds::Shape](../../aspose.slides/shapethumbnailbounds/) のシェイプサムネイル境界タイプが使用されます。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../../aspose.slides/iimage/)\> [GetImage](../../aspose.slides/shape/getimage/)([ShapeThumbnailBounds](../../aspose.slides/shapethumbnailbounds/), **float**, **float**) override | シェイプのサムネイルを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../../aspose.slides/shape/getvisualbounds/)() | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() ステートメントのロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
| [Object](../../system/object/object/)() | オブジェクトを作成し、すべての内部データ構造を初期化します。 |
| [Object](../../system/object/object/)([Object](../../system/object/) const&) | コピーコンストラクタです。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const&) | 代入演算子です。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const&, [ptr](../../system/object/ptr/) const&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)<T>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | 文字列と nullptr のケースに対する [Object::ReferenceEquals](../../system/object/referenceequals/) の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder/)() override | このシェイプがプレースホルダーではないことを定義します。 |
| void [set_AlternativeText](../../aspose.slides/shape/set_alternativetext/)([System::String](../../system/string/)) override | シェイプに関連付けられた代替テキストを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_AlternativeTextTitle](../../aspose.slides/shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | シェイプに関連付けられた代替テキストのタイトルを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_BlackWhiteMode](../../aspose.slides/shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)) override | プロパティはシェイプが白黒表示モードでどのようにレンダリングされるかを指定します。書き込み [Slides::BlackWhiteMode](../../aspose.slides/blackwhitemode/)。 |
| void [set_Frame](../../aspose.slides/shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | シェイプフレームのプロパティを設定します。書き込み [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| void [set_Height](../../aspose.slides/shape/set_height/)(**float**) override | シェイプの高さ（ポイント単位）を設定します。書き込み **float**。 |
| void [set_Hidden](../../aspose.slides/shape/set_hidden/)(**bool**) override | シェイプが非表示かどうかを設定します。書き込み **bool**。 |
| void [set_HyperlinkClick](../../aspose.slides/shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | マウスクリック用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| void [set_HyperlinkMouseOver](../../aspose.slides/shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../../aspose.slides/ihyperlink/)\>) override | マウスオーバー用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../../aspose.slides/ihyperlink/)。 |
| void [set_IsDecorative](../../aspose.slides/shape/set_isdecorative/)(**bool**) override | '装飾としてマーク' オプションを設定します。書き込み **bool**。 |
| void [set_Name](../../aspose.slides/shape/set_name/)([System::String](../../system/string/)) override | シェイプの名前を設定します。null であってはなりません。必要に応じて空文字列を使用してください。書き込み [System::String](../../system/string/)。 |
| void [set_RawFrame](../../aspose.slides/shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../../aspose.slides/ishapeframe/)\>) override | 生のシェイプフレームのプロパティを設定します。書き込み [IShapeFrame](../../aspose.slides/ishapeframe/)。 |
| void [set_Rotation](../../aspose.slides/shape/set_rotation/)(**float**) override | 指定されたシェイプが z 軸周りに回転した角度（度）を設定します。正の値は時計回り、負の値は反時計回りを示します。書き込み **float**。 |
| void [set_ShapeType](./set_shapetype/)([Aspose::Slides::ShapeType](../../aspose.slides/shapetype/)) override | ジオメトリのプリセットタイプを設定します。注: 値が変更されると、すべての調整値はデフォルトにリセットされます。書き込み [Slides::ShapeType](../../aspose.slides/shapetype/)。 |
| void [set_Width](../../aspose.slides/shape/set_width/)(**float**) override | シェイプの幅（ポイント単位）を設定します。書き込み **float**。 |
| void [set_X](../../aspose.slides/shape/set_x/)(**float**) override | シェイプ左上隅の x 座標（ポイント単位）を設定します。書き込み **float**。 |
| void [set_Y](../../aspose.slides/shape/set_y/)(**float**) override | シェイプ左上隅の y 座標（ポイント単位）を設定します。書き込み **float**。 |
| void [SetGeometryPath](../../aspose.slides/geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>) override | [IGeometryPath](../../aspose.slides/igeometrypath/) オブジェクトからシェイプジオメトリを更新します。座標はシェイプの左上隅に対して相対的でなければなりません。シェイプのタイプ ([ShapeType](../../aspose.slides/shapetype/)) を [ShapeType::Custom](../../aspose.slides/shapetype/) に変更します。 |
| void [SetGeometryPaths](../../aspose.slides/geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../../aspose.slides/igeometrypath/)\>\>) override | [IGeometryPath](../../aspose.slides/igeometrypath/) の配列からシェイプジオメトリを更新します。座標はシェイプの左上隅に対して相対的でなければなりません。シェイプのタイプ ([ShapeType](../../aspose.slides/shapetype/)) を [ShapeType::Custom](../../aspose.slides/shapetype/) に変更します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタ（共有ポインタではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在の値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() ステートメントのロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../../aspose.slides/shape/) の内容を SVG ファイルとして保存します。 |
| void [WriteAsSvg](../../aspose.slides/shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../../aspose.slides/shape/) の内容を SVG ファイルとして保存します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄し、すべての内部データ構造を解放します。 |

## 参照

* クラス [GeometryShape](../../aspose.slides/geometryshape/)
* クラス [ISmartArtShape](../ismartartshape/)
* 名前空間 [Aspose::Slides::SmartArt](../)
* ライブラリ [Aspose.Slides](../../)