---
title: IVideoFrame
second_title: Aspose.Slides for C++ API リファレンス
description: スライド上のビデオクリップを表します。
type: docs
weight: 4226
url: /ja/aspose.slides/ivideoframe/
---
## IVideoFrame クラス

スライド上のビデオクリップを表します。

```cpp
class IVideoFrame : public virtual Aspose::Slides::IPictureFrame
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | プレースホルダーが存在しない場合は新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | シェイプの要素の配列を作成し、返します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN を含む）と等しくないにもかかわらず、2 つの NaN が等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | 指定されたインデックスのシェイプの調整値を返します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | シェイプの調整値のコレクションを返します。読み取り専用 [IAdjustValueCollection](../iadjustvaluecollection/)。 |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | シェイプに関連付けられた代替テキストを返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | シェイプに関連付けられた代替テキストのタイトルを返します。読み取り [System::String](../../system/string/)。 |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。読み取り [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() | 音声フレームに関連付けられたクローズドキャプションのコレクションを取得します。このプロパティは読み取り専用で、すべてのキャプショントラックを含む [ICaptionsCollection](../icaptionscollection/) を返します。 |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | シェイプ上の接続サイトの数を返します。読み取り専用 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | シェイプのカスタムデータを返します。読み取り専用 [ICustomData](../icustomdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | シェイプに適用されたピクセルエフェクトを含む [EffectFormat](../effectformat/) オブジェクトを返します。読み取り専用 [IEffectFormat](../ieffectformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\> [get_EmbeddedVideo](./get_embeddedvideo/)() | 埋め込みビデオオブジェクトを返します。読み取り [IVideo](../ivideo/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | シェイプの塗りつぶし書式プロパティを含む [FillFormat](../fillformat/) オブジェクトを返します。読み取り専用 [IFillFormat](../ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | シェイプフレームのプロパティを返します。読み取り [IShapeFrame](../ishapeframe/)。 |
| virtual **bool** [get_FullScreenMode](./get_fullscreenmode/)() | ビデオが全画面モードで表示されるかどうかを判定します。読み取り **bool**。 |
| virtual **float** [get_Height](../ishape/get_height/)() | ポイント単位で測定されたシェイプの高さを取得します。読み取り **float**。 |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | シェイプが非表示かどうかを判定します。読み取り **bool**。 |
| virtual **bool** [get_HideAtShowing](./get_hideatshowing/)() | [VideoFrame](../videoframe/) が非表示かどうかを判定します。読み取り **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | マウスクリック用に定義されたハイパーリンクを返します。読み取り [IHyperlink](../ihyperlink/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | ハイパーリンクマネージャー。読み取り専用 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | マウスオーバー用に定義されたハイパーリンクを返します。読み取り [IHyperlink](../ihyperlink/)。 |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | 「装飾としてマーク」オプションを取得します。読み取り/書き込み **bool**。 |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | シェイプがグループ化されているかどうかを判定します。読み取り専用 **bool**。 |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | シェイプが TextHolder かどうかを判定します。読み取り専用 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | シェイプの線書式プロパティを含む [LineFormat](../lineformat/) オブジェクトを返します。読み取り専用 [ILineFormat](../ilineformat/)。 |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | [VideoFrame](../videoframe/) にリンクされたビデオファイルの名前を返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | シェイプの名前を返します。読み取り [System::String](../../system/string/)。 |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | シェイプの存続期間中一定で、PowerPoint またはインターロップコードがドキュメント内のどこからでもシェイプを確実に参照できるスライドスコープの一意識別子を返します。読み取り専用 **uint32_t**。詳細は [IShape::get_UniqueId](../ishape/get_uniqueid/) を参照してください。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | シェイプがグループ化されている場合、親 [GroupShape](../groupshape/) オブジェクトを返します。そうでない場合は null を返します。読み取り専用 [IGroupShape](../igroupshape/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../ipictureframe/get_pictureformat/)() | 画像フレームの [PictureFillFormat](../picturefillformat/) オブジェクトを返します。読み取り専用 [IPictureFillFormat](../ipicturefillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../ipictureframe/get_pictureframelock/)() | [PictureFrame](../pictureframe/) のロックを返します。読み取り専用 [IPictureFrameLock](../ipictureframelock/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | シェイプのプレースホルダーを返します。読み取り専用 [IPlaceholder](../iplaceholder/)。 |
| virtual **bool** [get_PlayLoopMode](./get_playloopmode/)() | ビデオがループ再生されるかどうかを判定します。読み取り **bool**。 |
| virtual [VideoPlayModePreset](../videoplaymodepreset/) [get_PlayMode](./get_playmode/)() | ビデオの再生モードを返します。読み取り [VideoPlayModePreset](../videoplaymodepreset/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | プレゼンテーションを返します。読み取り専用 [IPresentation](../ipresentation/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | 生のシェイプフレームのプロパティを返します。読み取り [IShapeFrame](../ishapeframe/)。 |
| virtual **float** [get_RelativeScaleHeight](../ipictureframe/get_relativescaleheight/)() | 画像フレームの高さのスケール（元の画像サイズに対する相対）を返します。値 1.0 は 100% に相当します。読み取り **float**。 |
| virtual **float** [get_RelativeScaleWidth](../ipictureframe/get_relativescalewidth/)() | 画像フレームの幅のスケール（元の画像サイズに対する相対）を返します。値 1.0 は 100% に相当します。読み取り **float**。 |
| virtual **bool** [get_RewindVideo](./get_rewindvideo/)() | ビデオが再生終了後に自動的に先頭へ巻き戻されるかどうかを判定します。読み取り **bool**。 |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | 指定されたシェイプが z 軸周りに回転した度数を返します。正の値は時計回り、負の値は反時計回りを示します。読み取り **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | シェイプのロックを返します。読み取り専用 [IBaseShapeLock](../ibaseshapelock/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | シェイプのスタイルオブジェクトを返します。読み取り専用 [IShapeStyle](../ishapestyle/)。 |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | ジオメトリプリセットタイプを返します。注: 値が変更されるとすべての調整値がデフォルトにリセットされます。読み取り [Slides::ShapeType](../shapetype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | ベーススライドを返します。読み取り専用 [IBaseSlide](../ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | シェイプの線書式プロパティを含む [ThreeDFormat](../threedformat/) オブジェクトを返します。読み取り専用 [IThreeDFormat](../ithreedformat/)。 |
| virtual **float** [get_TrimFromEnd](./get_trimfromend/)() | トリム終了 [ms] |
| virtual **float** [get_TrimFromStart](./get_trimfromstart/)() | トリム開始 [ms] |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | アドインやその他のコードで使用することを想定した内部のプレゼンテーションスコープ識別子を返します。この値はユーザーまたはプログラムによって再割り当て可能であるため、永続的な一意キーとして扱ってはなりません。読み取り専用 **uint32_t**。詳細は [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/) を参照してください。 |
| virtual [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() | 音量を返します。読み取り [AudioVolumeMode](../audiovolumemode/)。 |
| virtual **float** [get_Width](../ishape/get_width/)() | ポイント単位で測定されたシェイプの幅を取得します。読み取り **float**。 |
| virtual **float** [get_X](../ishape/get_x/)() | ポイント単位で測定されたシェイプの左上隅の x 座標を取得します。読み取り **float**。 |
| virtual **float** [get_Y](../ishape/get_y/)() | ポイント単位で測定されたシェイプの左上隅の y 座標を取得します。読み取り **float**。 |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | z オーダーにおけるシェイプの位置を返します。Shapes[0] は z オーダーの背面にあるシェイプを返し、Shapes[Shapes.Count - 1] は前面にあるシェイプを返します。読み取り専用 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | 基本的なプレースホルダーシェイプ（レイアウトやマスタースライドから継承されたシェイプ）を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられたリファレンスカウンターデータ構造を取得します。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | ジオメトリシェイプのパスのコピーを返します。座標はシェイプの左上隅を基準としています。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドのアナログです。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | シェイプのサムネイルを返します。デフォルトでは [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) シェイプサムネイル境界タイプが使用されます。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | シェイプのサムネイルを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しのアナログです。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるか確認します。C# の 'is' 演算子のアナログです。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文によるロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドのアナログです。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | オブジェクトを参照で比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 値型オブジェクトと nullptr を参照で比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の、文字列と nullptr の場合の特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の、文字列の場合の特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | このシェイプがプレースホルダーでないことを定義します。 |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | シェイプに関連付けられた代替テキストを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | シェイプに関連付けられた代替テキストのタイトルを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。書き込み [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| virtual void [set_EmbeddedVideo](./set_embeddedvideo/)([System::SharedPtr](../../system/sharedptr/)\<[IVideo](../ivideo/)\>) | 埋め込みビデオオブジェクトを設定します。書き込み [IVideo](../ivideo/)。 |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | シェイプフレームのプロパティを設定します。書き込み [IShapeFrame](../ishapeframe/)。 |
| virtual void [set_FullScreenMode](./set_fullscreenmode/)(**bool**) | ビデオが全画面モードで表示されるかどうかを決定します。書き込み **bool**。 |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ポイント単位でシェイプの高さを設定します。書き込み **float**。 |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | シェイプが非表示かどうかを決定します。書き込み **bool**。 |
| virtual void [set_HideAtShowing](./set_hideatshowing/)(**bool**) | [VideoFrame](../videoframe/) が非表示かどうかを決定します。書き込み **bool**。 |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | マウスクリック用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../ihyperlink/)。 |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | マウスオーバー用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../ihyperlink/)。 |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | 「装飾としてマーク」オプションを設定します。読み取り/書き込み **bool**。 |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | [VideoFrame](../videoframe/) にリンクされたビデオファイルの名前を設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | シェイプの名前を設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_PlayLoopMode](./set_playloopmode/)(**bool**) | ビデオがループ再生されるかどうかを決定します。書き込み **bool**。 |
| virtual void [set_PlayMode](./set_playmode/)([VideoPlayModePreset](../videoplaymodepreset/)) | ビデオの再生モードを設定します。書き込み [VideoPlayModePreset](../videoplaymodepreset/)。 |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | 生のシェイプフレームのプロパティを設定します。書き込み [IShapeFrame](../ishapeframe/)。 |
| virtual void [set_RelativeScaleHeight](../ipictureframe/set_relativescaleheight/)(**float**) | 画像フレームの高さのスケール（元の画像サイズに対する相対）を設定します。値 1.0 は 100% に相当します。書き込み **float**。 |
| virtual void [set_RelativeScaleWidth](../ipictureframe/set_relativescalewidth/)(**float**) | 画像フレームの幅のスケール（元の画像サイズに対する相対）を設定します。値 1.0 は 100% に相当します。書き込み **float**。 |
| virtual void [set_RewindVideo](./set_rewindvideo/)(**bool**) | ビデオが再生終了後に自動的に先頭へ巻き戻されるかどうかを決定します。書き込み **bool**。 |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | 指定されたシェイプが z 軸周りに回転した度数を設定します。正の値は時計回り、負の値は反時計回りを示します。書き込み **float**。 |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | ジオメトリプリセットタイプを設定します。注: 値が変更されるとすべての調整値がデフォルトにリセットされます。書き込み [Slides::ShapeType](../shapetype/)。 |
| virtual void [set_TrimFromEnd](./set_trimfromend/)(**float**) | トリム終了 [ms] |
| virtual void [set_TrimFromStart](./set_trimfromstart/)(**float**) | トリム開始 [ms] |
| virtual void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) | 音量を設定します。書き込み [AudioVolumeMode](../audiovolumemode/)。 |
| virtual void [set_Width](../ishape/set_width/)(**float**) | ポイント単位でシェイプの幅を設定します。書き込み **float**。 |
| virtual void [set_X](../ishape/set_x/)(**float**) | ポイント単位でシェイプの左上隅の x 座標を設定します。書き込み **float**。 |
| virtual void [set_Y](../ishape/set_y/)(**float**) | ポイント単位でシェイプの左上隅の y 座標を設定します。書き込み **float**。 |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | [IGeometryPath](../igeometrypath/) オブジェクトからシェイプジオメトリを更新します。座標はシェイプの左上隅を基準とする必要があります。シェイプのタイプ ([ShapeType](../shapetype/)) を [ShapeType::Custom](../shapetype/) に変更します。 |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | [IGeometryPath](../igeometrypath/) の配列からシェイプジオメトリを更新します。座標はシェイプの左上隅を基準とする必要があります。シェイプのタイプ ([ShapeType](../shapetype/)) を [ShapeType::Custom](../shapetype/) に変更します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱ポインタ（共有ではなく）に設定します。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドのアナログです。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) センティリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../shape/) の内容を SVG ファイルとして保存します。 |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../shape/) の内容を SVG ファイルとして保存します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IPictureFrame](../ipictureframe/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)