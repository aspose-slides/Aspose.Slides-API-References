---
title: IAudioFrame
second_title: Aspose.Slides for C++ API リファレンス
description: スライド上のオーディオクリップを表します。
type: docs
weight: 1353
url: /ja/aspose.slides/iaudioframe/
---
## IAudioFrame クラス

スライド上のオーディオクリップを表します。

```cpp
class IAudioFrame : public virtual Aspose::Slides::IPictureFrame
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../ishape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、プレースホルダーのプロパティを指定されたものに設定します。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../igeometryshape/createshapeelements/)() | シェイプの要素の配列を作成して返します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# [Object.Equals](../../system/object/equals/) のセマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN も含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によれば NaN は任意の値（NaN も含む）と等しくないにもかかわらず、2 つの NaN を等しいとみなす C# スタイルの浮動小数点比較をエミュレートします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途専用です。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../igeometryshape/get_adjustment/)(**int32_t**) | 指定されたインデックスのシェイプの調整値を返します。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../igeometryshape/get_adjustments/)() | シェイプの調整値のコレクションを返します。読み取り専用 [IAdjustValueCollection](../iadjustvaluecollection/)。 |
| virtual [System::String](../../system/string/) [get_AlternativeText](../ishape/get_alternativetext/)() | シェイプに関連付けられた代替テキストを返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_AlternativeTextTitle](../ishape/get_alternativetexttitle/)() | シェイプに関連付けられた代替テキストのタイトルを返します。読み取り [System::String](../../system/string/)。 |
| virtual **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() | 最後のトラックインデックスを返します。読み取り **int32_t**。 |
| virtual **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() | 最後のトラック時間を返します。読み取り **int32_t**。 |
| virtual **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() | 開始トラックインデックスを返します。読み取り **int32_t**。 |
| virtual **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() | 開始トラック時間を返します。読み取り **int32_t**。 |
| virtual [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../ishape/get_blackwhitemode/)() | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。読み取り [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() | オーディオフレームに関連付けられたクローズドキャプションのコレクションを取得します。このプロパティは読み取り専用で、すべてのキャプショントラックを含む [ICaptionsCollection](../icaptionscollection/) を返します。 |
| virtual **int32_t** [get_ConnectionSiteCount](../ishape/get_connectionsitecount/)() | シェイプ上の接続ポイントの数を返します。読み取り専用 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../ishape/get_customdata/)() | シェイプのカスタムデータを返します。読み取り専用 [ICustomData](../icustomdata/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../ishape/get_effectformat/)() | シェイプに適用されたピクセルエフェクトを含む [EffectFormat](../effectformat/) オブジェクトを返します。読み取り専用 [IEffectFormat](../ieffectformat/)。 |
| virtual **bool** [get_Embedded](./get_embedded/)() | サウンドがプレゼンテーションに埋め込まれているかどうかを判定します。読み取り専用 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() | 埋め込みオーディオオブジェクトを返します。読み取り [IAudio](../iaudio/)。 |
| virtual **float** [get_FadeInDuration](./get_fadeinduration/)() | メディアの初期フェードインの時間（ミリ秒）を指定します。読み取り **float**。 |
| virtual **float** [get_FadeOutDuration](./get_fadeoutduration/)() | メディアの終了フェードアウトの時間（ミリ秒）を指定します。読み取り **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../ishape/get_fillformat/)() | シェイプの塗りつぶし書式プロパティを含む [FillFormat](../fillformat/) オブジェクトを返します。読み取り専用 [IFillFormat](../ifillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../ishape/get_frame/)() | シェイプフレームのプロパティを返します。読み取り [IShapeFrame](../ishapeframe/)。 |
| virtual **float** [get_Height](../ishape/get_height/)() | ポイント単位で測定されたシェイプの高さを取得します。読み取り **float**。 |
| virtual **bool** [get_Hidden](../ishape/get_hidden/)() | シェイプが非表示かどうかを判定します。読み取り **bool**。 |
| virtual **bool** [get_HideAtShowing](./get_hideatshowing/)() | [AudioFrame](../audioframe/) が非表示かどうかを判定します。読み取り **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../ihyperlinkcontainer/get_hyperlinkclick/)() | マウスクリック用に定義されたハイパーリンクを返します。読み取り [IHyperlink](../ihyperlink/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../ihyperlinkcontainer/get_hyperlinkmanager/)() | ハイパーリンクマネージャー（読み取り専用） [IHyperlinkManager](../ihyperlinkmanager/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../ihyperlinkcontainer/get_hyperlinkmouseover/)() | マウスオーバー用に定義されたハイパーリンクを返します。読み取り [IHyperlink](../ihyperlink/)。 |
| virtual **bool** [get_IsDecorative](../ishape/get_isdecorative/)() | '装飾としてマーク' オプションを取得します。読み書き **bool**。 |
| virtual **bool** [get_IsGrouped](../ishape/get_isgrouped/)() | シェイプがグループ化されているかどうかを判定します。読み取り専用 **bool**。 |
| virtual **bool** [get_IsTextHolder](../ishape/get_istextholder/)() | シェイプが TextHolder かどうかを判定します。読み取り専用 **bool**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../ishape/get_lineformat/)() | シェイプの線書式プロパティを含む [LineFormat](../lineformat/) オブジェクトを返します。読み取り専用 [ILineFormat](../ilineformat/)。 |
| virtual [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() | [AudioFrame](../audioframe/) にリンクされたオーディオファイルの名前を返します。読み取り [System::String](../../system/string/)。 |
| virtual [System::String](../../system/string/) [get_Name](../ishape/get_name/)() | シェイプの名前を返します。読み取り [System::String](../../system/string/)。 |
| virtual **uint32_t** [get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)() | シェイプの存続期間中に一定で、PowerPoint またはインターオプコードがドキュメント内の任意の場所からシェイプを確実に参照できるスライドスコープの一意識別子を返します。読み取り専用 **uint32_t**。参照してください [IShape::get_UniqueId](../ishape/get_uniqueid/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../ishape/get_parentgroup/)() | シェイプがグループ化されている場合、親 [GroupShape](../groupshape/) オブジェクトを返します。そうでない場合は null を返します。読み取り専用 [IGroupShape](../igroupshape/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../ipictureframe/get_pictureformat/)() | 画像フレームの [PictureFillFormat](../picturefillformat/) オブジェクトを返します。読み取り専用 [IPictureFillFormat](../ipicturefillformat/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../ipictureframe/get_pictureframelock/)() | [PictureFrame](../pictureframe/) のロックを返します。読み取り専用 [IPictureFrameLock](../ipictureframelock/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../ishape/get_placeholder/)() | シェイプのプレースホルダーを返します。読み取り専用 [IPlaceholder](../iplaceholder/)。 |
| virtual **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() | オーディオがスライド間で再生されているかどうかを判定します。読み取り **bool**。 |
| virtual **bool** [get_PlayLoopMode](./get_playloopmode/)() | オーディオがループ再生されているかどうかを判定します。読み取り **bool**。 |
| virtual [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() | オーディオ再生モードを返します。読み取り [AudioPlayModePreset](../audioplaymodepreset/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../ipresentationcomponent/get_presentation/)() | プレゼンテーションを返します。読み取り専用 [IPresentation](../ipresentation/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../ishape/get_rawframe/)() | 生のシェイプフレームのプロパティを返します。読み取り [IShapeFrame](../ishapeframe/)。 |
| virtual **float** [get_RelativeScaleHeight](../ipictureframe/get_relativescaleheight/)() | 画像フレームの高さ（元の画像サイズに対する相対）のスケールを返します。値 1.0 は 100% に相当します。読み取り **float**。 |
| virtual **float** [get_RelativeScaleWidth](../ipictureframe/get_relativescalewidth/)() | 画像フレームの幅（元の画像サイズに対する相対）のスケールを返します。値 1.0 は 100% に相当します。読み取り **float**。 |
| virtual **bool** [get_RewindAudio](./get_rewindaudio/)() | オーディオが再生後に自動的に開始位置に巻き戻されるかどうかを判定します。読み取り **bool**。 |
| virtual **float** [get_Rotation](../ishape/get_rotation/)() | 指定されたシェイプが z 軸周りに回転した角度（度）を返します。正の値は時計回り、負の値は反時計回りを示します。読み取り **float**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../ishape/get_shapelock/)() | シェイプのロックを返します。読み取り専用 [IBaseShapeLock](../ibaseshapelock/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../igeometryshape/get_shapestyle/)() | シェイプのスタイルオブジェクトを返します。読み取り専用 [IShapeStyle](../ishapestyle/)。 |
| virtual [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../igeometryshape/get_shapetype/)() | ジオメトリのプリセットタイプを返します。注: 値を変更すると、すべての調整値がデフォルト値にリセットされます。読み取り [Slides::ShapeType](../shapetype/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../islidecomponent/get_slide/)() | ベーススライドを返します。読み取り専用 [IBaseSlide](../ibaseslide/)。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../ishape/get_threedformat/)() | シェイプの線書式プロパティを含む [ThreeDFormat](../threedformat/) オブジェクトを返します。読み取り専用 [IThreeDFormat](../ithreedformat/)。 |
| virtual **float** [get_TrimFromEnd](./get_trimfromend/)() | 再生中にメディアの末尾から削除する時間（ミリ秒）を指定します。読み取り **float**。 |
| virtual **float** [get_TrimFromStart](./get_trimfromstart/)() | 再生中にメディアの先頭から削除する時間（ミリ秒）を指定します。読み取り **float**。 |
| virtual **uint32_t** [get_UniqueId](../ishape/get_uniqueid/)() | アドインやその他のコードが使用することを意図した内部のプレゼンテーションスコープ識別子を返します。この値はユーザーやプログラムによって再割り当てできるため、永続的な一意キーとして扱ってはなりません。読み取り専用 **uint32_t**。参照してください [IShape::get_OfficeInteropShapeId](../ishape/get_officeinteropshapeid/)。 |
| virtual [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() | オーディオの音量を返します。読み取り [AudioVolumeMode](../audiovolumemode/)。 |
| virtual **float** [get_VolumeValue](./get_volumevalue/)() | 音量をパーセンテージで返します。読み取り **float**。 |
| virtual **float** [get_Width](../ishape/get_width/)() | ポイント単位で測定されたシェイプの幅を取得します。読み取り **float**。 |
| virtual **float** [get_X](../ishape/get_x/)() | ポイント単位で測定されたシェイプ左上隅の X 座標を取得します。読み取り **float**。 |
| virtual **float** [get_Y](../ishape/get_y/)() | ポイント単位で測定されたシェイプ左上隅の Y 座標を取得します。読み取り **float**。 |
| virtual **int32_t** [get_ZOrderPosition](../ishape/get_zorderposition/)() | z オーダーにおけるシェイプの位置を返します。Shapes[0] は z オーダーの背面のシェイプを返し、Shapes[Shapes.Count - 1] は前面のシェイプを返します。読み取り専用 **int32_t**。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../ishape/getbaseplaceholder/)() | 基本的なプレースホルダーシェイプ（レイアウトやマスタースライドから継承されたシェイプ）を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンターデータ構造を取得します。 |
| virtual [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../igeometryshape/getgeometrypaths/)() | ジオメトリシェイプのパスのコピーを返します。座標はシェイプの左上隅を基準とします。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似です。カスタムオブジェクトのハッシュ化を可能にします。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)() | シェイプのサムネイルを返します。デフォルトで [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) シェイプのサムネイル境界タイプが使用されます。 |
| virtual [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../ishape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) | シェイプのサムネイルを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスかどうかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似です。カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, T const&) | 参照によってオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const&, std::nullptr_t) | 値型オブジェクトと nullptr を参照比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, std::nullptr_t) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列と nullptr のケースに対する特殊化です。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const&, [String](../../system/string/) const&) | [Object::ReferenceEquals](../../system/object/referenceequals/) の文字列ケースに対する特殊化です。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| virtual void [RemovePlaceholder](../ishape/removeplaceholder/)() | このシェイプがプレースホルダーでないことを定義します。 |
| virtual void [set_AlternativeText](../ishape/set_alternativetext/)([System::String](../../system/string/)) | シェイプに関連付けられた代替テキストを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_AlternativeTextTitle](../ishape/set_alternativetexttitle/)([System::String](../../system/string/)) | シェイプに関連付けられた代替テキストのタイトルを設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) | 最後のトラックインデックスを設定します。書き込み **int32_t**。 |
| virtual void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) | 最後のトラック時間を設定します。書き込み **int32_t**。 |
| virtual void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) | 開始トラックインデックスを設定します。書き込み **int32_t**。 |
| virtual void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) | 開始トラック時間を設定します。書き込み **int32_t**。 |
| virtual void [set_BlackWhiteMode](../ishape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。書き込み [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| virtual void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) | 埋め込みオーディオオブジェクトを設定します。書き込み [IAudio](../iaudio/)。 |
| virtual void [set_FadeInDuration](./set_fadeinduration/)(**float**) | メディアの初期フェードインの時間（ミリ秒）を指定します。書き込み **float**。 |
| virtual void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) | メディアの終了フェードアウトの時間（ミリ秒）を指定します。書き込み **float**。 |
| virtual void [set_Frame](../ishape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | シェイプフレームのプロパティを設定します。書き込み [IShapeFrame](../ishapeframe/)。 |
| virtual void [set_Height](../ishape/set_height/)(**float**) | ポイント単位でシェイプの高さを設定します。書き込み **float**。 |
| virtual void [set_Hidden](../ishape/set_hidden/)(**bool**) | シェイプが非表示かどうかを設定します。書き込み **bool**。 |
| virtual void [set_HideAtShowing](./set_hideatshowing/)(**bool**) | [AudioFrame](../audioframe/) が非表示かどうかを設定します。書き込み **bool**。 |
| virtual void [set_HyperlinkClick](../ihyperlinkcontainer/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | マウスクリック用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../ihyperlink/)。 |
| virtual void [set_HyperlinkMouseOver](../ihyperlinkcontainer/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) | マウスオーバー用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../ihyperlink/)。 |
| virtual void [set_IsDecorative](../ishape/set_isdecorative/)(**bool**) | '装飾としてマーク' オプションを設定します。読み書き **bool**。 |
| virtual void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) | [AudioFrame](../audioframe/) にリンクされたオーディオファイルの名前を設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_Name](../ishape/set_name/)([System::String](../../system/string/)) | シェイプの名前を設定します。書き込み [System::String](../../system/string/)。 |
| virtual void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) | オーディオがスライド間で再生されるかどうかを設定します。書き込み **bool**。 |
| virtual void [set_PlayLoopMode](./set_playloopmode/)(**bool**) | オーディオがループ再生されるかどうかを設定します。書き込み **bool**。 |
| virtual void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) | オーディオ再生モードを設定します。書き込み [AudioPlayModePreset](../audioplaymodepreset/)。 |
| virtual void [set_RawFrame](../ishape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) | 生のシェイプフレームのプロパティを設定します。書き込み [IShapeFrame](../ishapeframe/)。 |
| virtual void [set_RelativeScaleHeight](../ipictureframe/set_relativescaleheight/)(**float**) | 画像フレームの高さ（元の画像サイズに対する相対）のスケールを設定します。値 1.0 は 100% に相当します。書き込み **float**。 |
| virtual void [set_RelativeScaleWidth](../ipictureframe/set_relativescalewidth/)(**float**) | 画像フレームの幅（元の画像サイズに対する相対）のスケールを設定します。値 1.0 は 100% に相当します。書き込み **float**。 |
| virtual void [set_RewindAudio](./set_rewindaudio/)(**bool**) | オーディオが再生後に自動的に開始位置に巻き戻されるかどうかを設定します。書き込み **bool**。 |
| virtual void [set_Rotation](../ishape/set_rotation/)(**float**) | 指定されたシェイプが z 軸周りに回転した角度（度）を設定します。正の値は時計回り、負の値は反時計回りを示します。書き込み **float**。 |
| virtual void [set_ShapeType](../igeometryshape/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) | ジオメトリのプリセットタイプを設定します。注: 値を変更すると、すべての調整値がデフォルト値にリセットされます。書き込み [Slides::ShapeType](../shapetype/)。 |
| virtual void [set_TrimFromEnd](./set_trimfromend/)(**float**) | 再生中にメディアの末尾から削除する時間（ミリ秒）を指定します。書き込み **float**。 |
| virtual void [set_TrimFromStart](./set_trimfromstart/)(**float**) | 再生中にメディアの先頭から削除する時間（ミリ秒）を指定します。書き込み **float**。 |
| virtual void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) | オーディオ音量を設定します。書き込み [AudioVolumeMode](../audiovolumemode/)。 |
| virtual void [set_VolumeValue](./set_volumevalue/)(**float**) | 音量をパーセンテージで設定します。書き込み **float**。 |
| virtual void [set_Width](../ishape/set_width/)(**float**) | ポイント単位でシェイプの幅を設定します。書き込み **float**。 |
| virtual void [set_X](../ishape/set_x/)(**float**) | ポイント単位でシェイプ左上隅の X 座標を設定します。書き込み **float**。 |
| virtual void [set_Y](../ishape/set_y/)(**float**) | ポイント単位でシェイプ左上隅の Y 座標を設定します。書き込み **float**。 |
| virtual void [SetGeometryPath](../igeometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) | [IGeometryPath](../igeometrypath/) オブジェクトからシェイプジオメトリを更新します。座標はシェイプの左上隅を基準とします。シェイプのタイプ ([ShapeType](../shapetype/)) を [ShapeType::Custom](../shapetype/) に変更します。 |
| virtual void [SetGeometryPaths](../igeometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) | [IGeometryPath](../igeometrypath/) 配列からシェイプジオメトリを更新します。座標はシェイプの左上隅を基準とします。シェイプのタイプ ([ShapeType](../shapetype/)) を [ShapeType::Custom](../shapetype/) に変更します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | **uint32_t** の n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 共有参照カウンタの現在値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウントを減少させ、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# [Object.ToString()](../../system/object/tostring/) メソッドの類似です。カスタムオブジェクトを文字列に変換できるようにします。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントを増加させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントを減少させます。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) | [Shape](../shape/) の内容を SVG ファイルとして保存します。 |
| virtual void [WriteAsSvg](../ishape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | [Shape](../shape/) の内容を SVG ファイルとして保存します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 参照

* クラス [IPictureFrame](../ipictureframe/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)