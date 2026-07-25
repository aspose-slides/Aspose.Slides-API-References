---
title: AudioFrame
second_title: Aspose.Slides for C++ API リファレンス
description: スライド上のオーディオクリップを表します。
type: docs
weight: 53
url: /ja/aspose.slides/audioframe/
---
## AudioFrame クラス

スライド上のオーディオクリップを表します。

```cpp
class AudioFrame : public Aspose::Slides::PictureFrame,
                   public Aspose::Slides::IAudioFrame
```

## メソッド

| メソッド | 説明 |
| --- | --- |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [AddPlaceholder](../shape/addplaceholder/)([System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\>) override | 新しいプレースホルダーがない場合に追加し、プレースホルダーのプロパティを指定されたものに設定します。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IShapeElement](../ishapeelement/)\>\> [CreateShapeElements](../geometryshape/createshapeelements/)() override | シェイプの要素の配列を作成して返します。 |
| virtual **bool** [Equals](../../system/object/equals/)([ptr](../../system/object/ptr/)) | C# の [Object.Equals](../../system/object/equals/) セマンティクスを使用してオブジェクトを比較します。 |
| static std::enable_if\<[IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&[IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで参照型オブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T1\>::value\&&\![IsSmartPtr](../../system/issmartptr/)\<T2\>::value, **bool**\>::type [Equals](../../system/object/equals/)(T1 const\&, T2 const\&) | C# スタイルで値型オブジェクトを比較します。 |
| static **bool** [Equals](../../system/object/equals/)(**float** const\&, **float** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいと見なします。 |
| static **bool** [Equals](../../system/object/equals/)(**double** const\&, **double** const\&) | IEC 60559:1989 によると NaN は任意の値（NaN を含む）と等しくないが、C# スタイルの浮動小数点比較をエミュレートし、2 つの NaN を等しいと見なします。 |
| virtual **bool** [FastCast](../../system/object/fastcast/)(const Details::FastRttiBase\&, void **) const | 内部用途のみです。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValue](../iadjustvalue/)\> [get_Adjustment](../geometryshape/get_adjustment/)(**int32_t**) override | 指定されたインデックスのシェイプの調整値を返します。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAdjustValueCollection](../iadjustvaluecollection/)\> [get_Adjustments](../geometryshape/get_adjustments/)() override | シェイプの調整値のコレクションを返します。読み取り専用 [IAdjustValueCollection](../iadjustvaluecollection/)。 |
| [System::String](../../system/string/) [get_AlternativeText](../shape/get_alternativetext/)() override | シェイプに関連付けられた代替テキストを返します。読み取り [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_AlternativeTextTitle](../shape/get_alternativetexttitle/)() override | シェイプに関連付けられた代替テキストのタイトルを返します。読み取り [System::String](../../system/string/)。 |
| **int32_t** [get_AudioCdEndTrack](./get_audiocdendtrack/)() override | 最後のトラックインデックスを返します。読み取り **int32_t**。 |
| **int32_t** [get_AudioCdEndTrackTime](./get_audiocdendtracktime/)() override | 最後のトラック時間を返します。読み取り **int32_t**。 |
| **int32_t** [get_AudioCdStartTrack](./get_audiocdstarttrack/)() override | 開始トラックインデックスを返します。読み取り **int32_t**。 |
| **int32_t** [get_AudioCdStartTrackTime](./get_audiocdstarttracktime/)() override | 開始トラック時間を返します。読み取り **int32_t**。 |
| [Aspose::Slides::BlackWhiteMode](../blackwhitemode/) [get_BlackWhiteMode](../shape/get_blackwhitemode/)() override | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。読み取り [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICaptionsCollection](../icaptionscollection/)\> [get_CaptionTracks](./get_captiontracks/)() override | 音声フレームに関連付けられたクローズドキャプションのコレクションを取得します。このプロパティは読み取り専用で、すべてのキャプショントラックを含む [ICaptionsCollection](../icaptionscollection/) を返します。 |
| **int32_t** [get_ConnectionSiteCount](../shape/get_connectionsitecount/)() override | シェイプ上の接続点の数を返します。読み取り専用 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ICustomData](../icustomdata/)\> [get_CustomData](../shape/get_customdata/)() override | シェイプのカスタムデータを返します。読み取り専用 [ICustomData](../icustomdata/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IEffectFormat](../ieffectformat/)\> [get_EffectFormat](../shape/get_effectformat/)() override | シェイプに適用されたピクセルエフェクトを含む [EffectFormat](../effectformat/) オブジェクトを返します。注: エフェクトプロパティを持たない特定のシェイプでは null を返す場合があります。読み取り専用 [IEffectFormat](../ieffectformat/)。 |
| **bool** [get_Embedded](./get_embedded/)() override | サウンドがプレゼンテーションに埋め込まれているかどうかを判定します。読み取り専用 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\> [get_EmbeddedAudio](./get_embeddedaudio/)() override | 埋め込みオーディオオブジェクトを返します。読み取り [IAudio](../iaudio/)。 |
| **float** [get_FadeInDuration](./get_fadeinduration/)() override | メディアの初期フェードインの時間長さ（ミリ秒）を指定します。読み取り **float**。 |
| **float** [get_FadeOutDuration](./get_fadeoutduration/)() override | メディアの終了フェードアウトの時間長さ（ミリ秒）を指定します。読み取り **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IFillFormat](../ifillformat/)\> [get_FillFormat](../shape/get_fillformat/)() override | [FillFormat](../fillformat/) オブジェクト（シェイプの塗りつぶし書式プロパティを含む）を返します。注: 塗りつぶしプロパティを持たない特定のシェイプでは null を返す場合があります。読み取り専用 [IFillFormat](../ifillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_Frame](../shape/get_frame/)() override | シェイプフレームのプロパティを返します。読み取り [IShapeFrame](../ishapeframe/)。 |
| **float** [get_Height](../shape/get_height/)() override | シェイプの高さ（ポイント単位）を取得します。読み取り **float**。 |
| **bool** [get_Hidden](../shape/get_hidden/)() override | シェイプが非表示かどうかを判定します。読み取り **bool**。 |
| **bool** [get_HideAtShowing](./get_hideatshowing/)() override | [AudioFrame](./) が非表示かどうかを判定します。読み取り **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkClick](../shape/get_hyperlinkclick/)() override | マウスクリック用に定義されたハイパーリンクを返します。読み取り [IHyperlink](../ihyperlink/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlinkManager](../ihyperlinkmanager/)\> [get_HyperlinkManager](../shape/get_hyperlinkmanager/)() override | ハイパーリンクマネージャーを返します。読み取り専用 [IHyperlinkManager](../ihyperlinkmanager/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\> [get_HyperlinkMouseOver](../shape/get_hyperlinkmouseover/)() override | マウスオーバー用に定義されたハイパーリンクを返します。読み取り [IHyperlink](../ihyperlink/)。 |
| **bool** [get_IsCameo](../pictureframe/get_iscameo/)() | [PictureFrame](../pictureframe/) が Cameo オブジェクトかどうかを判定します。読み取り専用 **bool**。 |
| **bool** [get_IsDecorative](../shape/get_isdecorative/)() override | 'Mark as decorative' オプションを取得/設定します。読み取り/書き込み **bool**。 |
| **bool** [get_IsGrouped](../shape/get_isgrouped/)() override | シェイプがグループ化されているかどうかを判定します。読み取り専用 **bool**。 |
| **bool** [get_IsTextHolder](../shape/get_istextholder/)() override | シェイプが TextHolder_PPT かどうかを判定します。読み取り専用 **bool**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[ILineFormat](../ilineformat/)\> [get_LineFormat](../shape/get_lineformat/)() override | シェイプの線書式プロパティを含む [LineFormat](../lineformat/) オブジェクトを返します。注: 線プロパティを持たない特定のシェイプでは null を返す場合があります。読み取り専用 [ILineFormat](../ilineformat/)。 |
| [System::String](../../system/string/) [get_LinkPathLong](./get_linkpathlong/)() override | [AudioFrame](./) にリンクされたオーディオファイルの名前を返します。読み取り [System::String](../../system/string/)。 |
| [System::String](../../system/string/) [get_Name](../shape/get_name/)() override | シェイプの名前を返します。null であってはなりません。必要に応じて空文字列を使用してください。読み取り [System::String](../../system/string/)。 |
| **uint32_t** [get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)() override | スライドスコープの一意の識別子を返します。この識別子はシェイプの存続期間中一定で、PowerPoint またはインターロップコードがドキュメント内の任意の場所からシェイプを確実に参照できます。読み取り専用 **uint32_t**。参照 [Shape::get_UniqueId](../shape/get_uniqueid/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IGroupShape](../igroupshape/)\> [get_ParentGroup](../shape/get_parentgroup/)() override | シェイプがグループ化されている場合、親 [GroupShape](../groupshape/) オブジェクトを返します。そうでない場合は null を返します。読み取り専用 [IGroupShape](../igroupshape/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFillFormat](../ipicturefillformat/)\> [get_PictureFormat](../pictureframe/get_pictureformat/)() override | 画像フレームの [PictureFillFormat](../picturefillformat/) オブジェクトを返します。読み取り専用 [IPictureFillFormat](../ipicturefillformat/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPictureFrameLock](../ipictureframelock/)\> [get_PictureFrameLock](../pictureframe/get_pictureframelock/)() override | シェイプのロックを返します。読み取り専用 [IPictureFrameLock](../ipictureframelock/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPlaceholder](../iplaceholder/)\> [get_Placeholder](../shape/get_placeholder/)() override | シェイプのプレースホルダーを返します。プレースホルダーがない場合は null を返します。読み取り専用 [IPlaceholder](../iplaceholder/)。 |
| **bool** [get_PlayAcrossSlides](./get_playacrossslides/)() override | スライド全体でオーディオが再生されているかどうかを判定します。読み取り **bool**。 |
| **bool** [get_PlayLoopMode](./get_playloopmode/)() override | オーディオがループ再生されているかどうかを判定します。読み取り **bool**。 |
| [AudioPlayModePreset](../audioplaymodepreset/) [get_PlayMode](./get_playmode/)() override | オーディオの再生モードを返します。読み取り [AudioPlayModePreset](../audioplaymodepreset/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IPresentation](../ipresentation/)\> [get_Presentation](../shape/get_presentation/)() override | スライドの親プレゼンテーションを返します。読み取り専用 [IPresentation](../ipresentation/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\> [get_RawFrame](../shape/get_rawframe/)() override | 生のシェイプフレームのプロパティを返します。読み取り [IShapeFrame](../ishapeframe/)。 |
| **float** [get_RelativeScaleHeight](../pictureframe/get_relativescaleheight/)() override | 画像フレームの高さのスケール（元の画像サイズに対する比率）を返します。値 1.0 は 100% に相当します。読み取り **float**。 |
| **float** [get_RelativeScaleWidth](../pictureframe/get_relativescalewidth/)() override | 画像フレームの幅のスケール（元の画像サイズに対する比率）を返します。値 1.0 は 100% に相当します。読み取り **float**。 |
| **bool** [get_RewindAudio](./get_rewindaudio/)() override | 再生後にオーディオが自動的に先頭に巻き戻されるかどうかを判定します。読み取り **bool**。 |
| **float** [get_Rotation](../shape/get_rotation/)() override | 指定されたシェイプが Z 軸周りに回転した角度（度）を返します。正の値は時計回り、負の値は反時計回りを示します。読み取り **float**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseShapeLock](../ibaseshapelock/)\> [get_ShapeLock](../shape/get_shapelock/)() override | シェイプのロックを返します。読み取り専用 [IBaseShapeLock](../ibaseshapelock/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShapeStyle](../ishapestyle/)\> [get_ShapeStyle](../geometryshape/get_shapestyle/)() override | シェイプのスタイルオブジェクトを返します。読み取り専用 [IShapeStyle](../ishapestyle/)。 |
| [Aspose::Slides::ShapeType](../shapetype/) [get_ShapeType](../pictureframe/get_shapetype/)() override |  |
| [System::SharedPtr](../../system/sharedptr/)\<[IBaseSlide](../ibaseslide/)\> [get_Slide](../shape/get_slide/)() override | シェイプの親スライドを返します。読み取り専用 [IBaseSlide](../ibaseslide/)。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IThreeDFormat](../ithreedformat/)\> [get_ThreeDFormat](../shape/get_threedformat/)() override | シェイプの 3D エフェクトプロパティを含む [ThreeDFormat](../threedformat/) オブジェクトを返します。注: 3D プロパティを持たない特定のシェイプでは null を返す場合があります。読み取り専用 [IThreeDFormat](../ithreedformat/)。 |
| **float** [get_TrimFromEnd](./get_trimfromend/)() override | 再生時にメディアの末尾から除去する時間長さ（ミリ秒）を指定します。読み取り **float**。 |
| **float** [get_TrimFromStart](./get_trimfromstart/)() override | 再生時にメディアの先頭から除去する時間長さ（ミリ秒）を指定します。読み取り **float**。 |
| **uint32_t** [get_UniqueId](../shape/get_uniqueid/)() override | アドインやその他のコードで使用することを想定した、プレゼンテーションスコープの内部識別子を返します。この値はユーザーまたはプログラムにより再割り当て可能なため、永続的な一意キーとして扱ってはなりません。読み取り専用 **uint32_t**。参照 [Shape::get_OfficeInteropShapeId](../shape/get_officeinteropshapeid/)。 |
| [AudioVolumeMode](../audiovolumemode/) [get_Volume](./get_volume/)() override | オーディオの音量を返します。読み取り [AudioVolumeMode](../audiovolumemode/)。 |
| **float** [get_VolumeValue](./get_volumevalue/)() override | 音量をパーセントで返します。読み取り **float**。 |
| **float** [get_Width](../shape/get_width/)() override | シェイプの幅（ポイント単位）を取得します。読み取り **float**。 |
| **float** [get_X](../shape/get_x/)() override | シェイプの左上隅の X 座標（ポイント単位）を取得します。読み取り **float**。 |
| **float** [get_Y](../shape/get_y/)() override | シェイプの左上隅の Y 座標（ポイント単位）を取得します。読み取り **float**。 |
| **int32_t** [get_ZOrderPosition](../shape/get_zorderposition/)() override | z オーダー内でのシェイプの位置を返します。Shapes[0] は z オーダーの背面のシェイプを、Shapes[Shapes.Count - 1] は前面のシェイプを返します。読み取り専用 **int32_t**。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IShape](../ishape/)\> [GetBasePlaceholder](../shape/getbaseplaceholder/)() override | 基本的なプレースホルダーシェイプ（レイアウトまたはマスタースライドから継承されたシェイプ）を返します。 |
| Detail::SmartPtrCounter * [GetCounter](../../system/object/getcounter/)() | オブジェクトに関連付けられた参照カウンタデータ構造を取得します。 |
| [System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\> [GetGeometryPaths](../geometryshape/getgeometrypaths/)() override | ジオメトリシェイプのパスのコピーを返します。座標はシェイプの左上隅を基準とします。 |
| virtual **int32_t** [GetHashCode](../../system/object/gethashcode/)() const | C# の [Object.GetHashCode()](../../system/object/gethashcode/) メソッドの類似で、カスタムオブジェクトのハッシュ化を可能にします。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)() override | シェイプのサムネイルを返します。デフォルトでは [ShapeThumbnailBounds::Shape](../shapethumbnailbounds/) シェイプサムネイル境界タイプが使用されます。 |
| [System::SharedPtr](../../system/sharedptr/)\<[IImage](../iimage/)\> [GetImage](../shape/getimage/)([ShapeThumbnailBounds](../shapethumbnailbounds/), **float**, **float**) override | シェイプのサムネイルを返します。 |
| virtual const [TypeInfo](../../system/typeinfo/)\& [GetType](../../system/object/gettype/)() const | オブジェクトの実際の型を取得します。C# の [System.Object.GetType()](../../system/object/gettype/) 呼び出しの類似です。 |
| [System::Drawing::RectangleF](../../system.drawing/rectanglef/) [GetVisualBounds](../shape/getvisualbounds/)() | レンダリングされたコンテンツから計算されたシェイプの視覚境界を取得します。 |
| virtual **bool** [Is](../../system/object/is/)(const [TypeInfo](../../system/typeinfo/)\&) const | オブジェクトが targetType で記述された型のインスタンスであるかをチェックします。C# の 'is' 演算子の類似です。 |
| void [Lock](../../system/object/lock/)() | C# の lock() 文のロックを実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| virtual [ptr](../../system/object/ptr/) [MemberwiseClone](../../system/object/memberwiseclone/)() const | C# の [Object.MemberwiseClone()](../../system/object/memberwiseclone/) メソッドの類似で、カスタム型のクローン作成を可能にします。 |
|  [Object](../../system/object/object/)() | オブジェクトを作成します。すべての内部データ構造を初期化します。 |
|  [Object](../../system/object/object/)([Object](../../system/object/) const\&) | コピーコンストラクタ。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| [Object](../../system/object/)\& [operator=](../../system/object/operator_equal/)([Object](../../system/object/) const\&) | 代入演算子。実際には何もコピーせず、新しいオブジェクトを初期化し、サブクラスのコピー構築を可能にします。 |
| static **bool** [ReferenceEquals](../../system/object/referenceequals/)([ptr](../../system/object/ptr/) const\&, [ptr](../../system/object/ptr/) const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, T const\&) | 参照によりオブジェクトを比較します。 |
| static std::enable_if<\![IsSmartPtr](../../system/issmartptr/)\<T\>::value, **bool**\>::type [ReferenceEquals](../../system/object/referenceequals/)(T const\&, std::nullptr_t) | 参照で値型オブジェクトと nullptr を比較します。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, std::nullptr_t) | 文字列と nullptr のケース向けに [Object::ReferenceEquals](../../system/object/referenceequals/) を特殊化したものです。 |
| **bool** [ReferenceEquals](../../system/object/referenceequals/)([String](../../system/string/) const\&, [String](../../system/string/) const\&) | [Object::ReferenceEquals](../../system/object/referenceequals/) を文字列のケース向けに特殊化したものです。 |
| int [RemovedSharedRefs](../../system/object/removedsharedrefs/)(int) | 指定された値だけ共有参照カウントを減少させます。 |
| void [RemovePlaceholder](../shape/removeplaceholder/)() override | このシェイプがプレースホルダーではないことを定義します。 |
| void [set_AlternativeText](../shape/set_alternativetext/)([System::String](../../system/string/)) override | シェイプに関連付けられた代替テキストを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_AlternativeTextTitle](../shape/set_alternativetexttitle/)([System::String](../../system/string/)) override | シェイプに関連付けられた代替テキストのタイトルを設定します。書き込み [System::String](../../system/string/)。 |
| void [set_AudioCdEndTrack](./set_audiocdendtrack/)(**int32_t**) override | 最後のトラックインデックスを設定します。書き込み **int32_t**。 |
| void [set_AudioCdEndTrackTime](./set_audiocdendtracktime/)(**int32_t**) override | 最後のトラック時間を設定します。書き込み **int32_t**。 |
| void [set_AudioCdStartTrack](./set_audiocdstarttrack/)(**int32_t**) override | 開始トラックインデックスを設定します。書き込み **int32_t**。 |
| void [set_AudioCdStartTrackTime](./set_audiocdstarttracktime/)(**int32_t**) override | 開始トラック時間を設定します。書き込み **int32_t**。 |
| void [set_BlackWhiteMode](../shape/set_blackwhitemode/)([Aspose::Slides::BlackWhiteMode](../blackwhitemode/)) override | プロパティはシェイプが白黒表示モードでどのように描画されるかを指定します。書き込み [Slides::BlackWhiteMode](../blackwhitemode/)。 |
| void [set_EmbeddedAudio](./set_embeddedaudio/)([System::SharedPtr](../../system/sharedptr/)\<[IAudio](../iaudio/)\>) override | 埋め込みオーディオオブジェクトを設定します。書き込み [IAudio](../iaudio/)。 |
| void [set_FadeInDuration](./set_fadeinduration/)(**float**) override | メディアの初期フェードインの時間長さ（ミリ秒）を指定します。書き込み **float**。 |
| void [set_FadeOutDuration](./set_fadeoutduration/)(**float**) override | メディアの終了フェードアウトの時間長さ（ミリ秒）を指定します。書き込み **float**。 |
| void [set_Frame](../shape/set_frame/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | シェイプフレームのプロパティを設定します。書き込み [IShapeFrame](../ishapeframe/)。 |
| void [set_Height](../shape/set_height/)(**float**) override | シェイプの高さ（ポイント単位）を設定します。書き込み **float**。 |
| void [set_Hidden](../shape/set_hidden/)(**bool**) override | シェイプが非表示かどうかを判定します。書き込み **bool**。 |
| void [set_HideAtShowing](./set_hideatshowing/)(**bool**) override | [AudioFrame](./) が非表示かどうかを判定します。書き込み **bool**。 |
| void [set_HyperlinkClick](../shape/set_hyperlinkclick/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | マウスクリック用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../ihyperlink/)。 |
| void [set_HyperlinkMouseOver](../shape/set_hyperlinkmouseover/)([System::SharedPtr](../../system/sharedptr/)\<[IHyperlink](../ihyperlink/)\>) override | マウスオーバー用に定義されたハイパーリンクを設定します。書き込み [IHyperlink](../ihyperlink/)。 |
| void [set_IsDecorative](../shape/set_isdecorative/)(**bool**) override | 'Mark as decorative' オプションを設定します。読み取り/書き込み **bool**。 |
| void [set_LinkPathLong](./set_linkpathlong/)([System::String](../../system/string/)) override | [AudioFrame](./) にリンクされたオーディオファイルの名前を設定します。書き込み [System::String](../../system/string/)。 |
| void [set_Name](../shape/set_name/)([System::String](../../system/string/)) override | シェイプの名前を設定します。null であってはなりません。必要に応じて空文字列を使用してください。書き込み [System::String](../../system/string/)。 |
| void [set_PlayAcrossSlides](./set_playacrossslides/)(**bool**) override | スライド全体でオーディオが再生されているかどうかを設定します。書き込み **bool**。 |
| void [set_PlayLoopMode](./set_playloopmode/)(**bool**) override | オーディオがループ再生されているかどうかを設定します。書き込み **bool**。 |
| void [set_PlayMode](./set_playmode/)([AudioPlayModePreset](../audioplaymodepreset/)) override | オーディオの再生モードを設定します。書き込み [AudioPlayModePreset](../audioplaymodepreset/)。 |
| void [set_RawFrame](../shape/set_rawframe/)([System::SharedPtr](../../system/sharedptr/)\<[IShapeFrame](../ishapeframe/)\>) override | 生のシェイプフレームのプロパティを設定します。書き込み [IShapeFrame](../ishapeframe/)。 |
| void [set_RelativeScaleHeight](../pictureframe/set_relativescaleheight/)(**float**) override | 画像フレームの高さのスケール（元の画像サイズに対する比率）を設定します。値 1.0 は 100% に相当します。書き込み **float**。 |
| void [set_RelativeScaleWidth](../pictureframe/set_relativescalewidth/)(**float**) override | 画像フレームの幅のスケール（元の画像サイズに対する比率）を設定します。値 1.0 は 100% に相当します。書き込み **float**。 |
| void [set_RewindAudio](./set_rewindaudio/)(**bool**) override | 再生後にオーディオが自動的に先頭に巻き戻されるかどうかを設定します。書き込み **bool**。 |
| void [set_Rotation](../shape/set_rotation/)(**float**) override | 指定されたシェイプが Z 軸周りに回転した角度（度）を設定します。正の値は時計回り、負の値は反時計回りを示します。書き込み **float**。 |
| [set_ShapeType](../pictureframe/set_shapetype/)([Aspose::Slides::ShapeType](../shapetype/)) override |  |
| void [set_TrimFromEnd](./set_trimfromend/)(**float**) override | 再生時にメディアの末尾から除去する時間長さ（ミリ秒）を指定します。書き込み **float**。 |
| void [set_TrimFromStart](./set_trimfromstart/)(**float**) override | 再生時にメディアの先頭から除去する時間長さ（ミリ秒）を指定します。書き込み **float**。 |
| void [set_Volume](./set_volume/)([AudioVolumeMode](../audiovolumemode/)) override | オーディオ音量を設定します。書き込み [AudioVolumeMode](../audiovolumemode/)。 |
| void [set_VolumeValue](./set_volumevalue/)(**float**) override | 音量をパーセントで設定します。書き込み **float**。 |
| void [set_Width](../shape/set_width/)(**float**) override | シェイプの幅（ポイント単位）を設定します。書き込み **float**。 |
| void [set_X](../shape/set_x/)(**float**) override | シェイプの左上隅の X 座標（ポイント単位）を設定します。書き込み **float**。 |
| void [set_Y](../shape/set_y/)(**float**) override | シェイプの左上隅の Y 座標（ポイント単位）を設定します。書き込み **float**。 |
| void [SetGeometryPath](../geometryshape/setgeometrypath/)([System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>) override | [IGeometryPath](../igeometrypath/) オブジェクトからシェイプジオメトリを更新します。座標はシェイプの左上隅を基準としなければなりません。シェイプのタイプ ([ShapeType](../shapetype/)) を [ShapeType::Custom](../shapetype/) に変更します。 |
| void [SetGeometryPaths](../geometryshape/setgeometrypaths/)([System::ArrayPtr](../../system/arrayptr/)\<[System::SharedPtr](../../system/sharedptr/)\<[IGeometryPath](../igeometrypath/)\>\>) override | [IGeometryPath](../igeometrypath/) の配列からシェイプジオメトリを更新します。座標はシェイプの左上隅を基準としなければなりません。シェイプのタイプ ([ShapeType](../shapetype/)) を [ShapeType::Custom](../shapetype/) に変更します。 |
| virtual void [SetTemplateWeakPtr](../../system/object/settemplateweakptr/)(**uint32_t**) | n 番目のテンプレート引数を弱参照ポインタに設定します（共有ではなく）。コンテナ内のポインタを弱モードに切り替えることができます。 |
| int [SharedCount](../../system/object/sharedcount/)() const | 現在の共有参照カウンタの値を取得します。 |
| [Object](../../system/object/) * [SharedRefAdded](../../system/object/sharedrefadded/)() | 共有参照カウンタをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| int [SharedRefRemovedSafe](../../system/object/sharedrefremovedsafe/)() | 共有参照カウンタをデクリメントし、返します。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| virtual [String](../../system/string/) [ToString](../../system/object/tostring/)() const | C# の [Object.ToString()](../../system/object/tostring/) メソッドの類似で、カスタムオブジェクトを文字列に変換できます。 |
| static const [TypeInfo](../../system/typeinfo/)\& [Type](../../system/object/type/)() | C# の typeof([System.Object](../../system/object/)) 構文を実装します。 |
| void [Unlock](../../system/object/unlock/)() | C# の lock() 文のロック解除を実装します。直接呼び出すか、[LockContext](../../system/lockcontext/) セントリーオブジェクトを使用してください。 |
| Detail::SmartPtrCounter * [WeakRefAdded](../../system/object/weakrefadded/)() | 弱参照カウントをインクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WeakRefRemoved](../../system/object/weakrefremoved/)() | 弱参照カウントをデクリメントします。直接呼び出すべきではなく、スマートポインタまたは ThisProtector を使用してください。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>) override | [Shape](../shape/) の内容を SVG ファイルとして保存します。 |
| void [WriteAsSvg](../shape/writeassvg/)([System::SharedPtr](../../system/sharedptr/)\<[System::IO::Stream](../../system.io/stream/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) override | [Shape](../shape/) の内容を SVG ファイルとして保存します。 |
| virtual  [~Object](../../system/object/~object/)() | オブジェクトを破棄します。すべての内部データ構造を解放します。 |

## 備考

次の例は [Audio](../audio/) の再生オプションを変更する方法を示します。

```cpp
auto pres = System::MakeObject<Presentation>(u"AudioFrameEmbed_out.pptx");

// Gets the AudioFrame shape
System::SharedPtr<AudioFrame> audioFrame = System::ExplicitCast<AudioFrame>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
// Sets the Play mode to play on click
audioFrame->set_PlayMode(AudioPlayModePreset::OnClick);
// Sets the volume to Low
audioFrame->set_Volume(AudioVolumeMode::Low);
// Sets the audio to play across slides
audioFrame->set_PlayAcrossSlides(true);
// Disables loop for the audio
audioFrame->set_PlayLoopMode(false);
// Hides the AudioFrame during the slide show
audioFrame->set_HideAtShowing(true);
// Rewinds the audio to start after playing
audioFrame->set_RewindAudio(true);
// Saves the PowerPoint file to disk
pres->Save(u"AudioFrameEmbed_changed.pptx", SaveFormat::Pptx);
```

## 参照

* クラス [PictureFrame](../pictureframe/)
* クラス [IAudioFrame](../iaudioframe/)
* 名前空間 [Aspose::Slides](../)
* ライブラリ [Aspose.Slides](../../)