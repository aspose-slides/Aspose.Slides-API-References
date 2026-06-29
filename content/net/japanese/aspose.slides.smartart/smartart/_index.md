---
title: SmartArt
second_title: Aspose.Sildes for .NET API リファレンス
description: SmartArt ダイアグラムを表します
type: docs
weight: 10580
url: /ja/aspose.slides.smartart/smartart/
---
## SmartArt クラス

SmartArt ダイアグラムを表します

```csharp
public class SmartArt : GraphicalObject, ISmartArt
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AllNodes](../../aspose.slides.smartart/smartart/allnodes) { get; } | SmartArt オブジェクト内のすべてのノードのコレクションを返します。読み取り専用 [`ISmartArtNodeCollection`](../ismartartnodecollection)。 |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | シェイプに関連付けられた代替テキストを取得または設定します。読み取り/書き込み String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。読み取り/書き込み String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。読み取り/書き込み [`BlackWhiteMode`](../../aspose.slides/blackwhitemode)。 |
| [ColorStyle](../../aspose.slides.smartart/smartart/colorstyle) { get; set; } | SmartArt オブジェクトのカラー スタイルを取得または設定します。読み取り/書き込み [`SmartArtColorType`](../smartartcolortype)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | シェイプ上の接続ポイントの数を返します。読み取り専用 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | シェイプのカスタム データを返します。読み取り専用 [`ICustomData`](../../aspose.slides/icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを返します。注意: 効果プロパティを持たない特定のタイプのシェイプについては null を返す場合があります。読み取り専用 [`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを返します。注意: 塗りつぶしプロパティを持たない特定のタイプのシェイプについては null を返す場合があります。読み取り専用 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | シェイプフレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | シェイプのロックを返します。読み取り専用 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | シェイプの高さをポイント単位で取得または設定します。読み取り/書き込み Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | シェイプが非表示かどうかを決定します。読み取り/書き込み Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。読み取り/書き込み [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンク マネージャーを返します。読み取り専用 [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み取り/書き込み [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 「装飾としてマーク」のオプションを取得または設定します。読み取り/書き込み Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | シェイプがグループ化されているかどうかを決定します。読み取り専用 Boolean。 |
| [IsReversed](../../aspose.slides.smartart/smartart/isreversed) { get; set; } | SmartArt 図が左から右 (LTR) または右から左 (RTL) の方向をサポートしている場合、その状態を取得または設定します。読み取り/書き込み Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | シェイプが TextHolder_PPT かどうかを決定します。読み取り専用 Boolean。 |
| [Layout](../../aspose.slides.smartart/smartart/layout) { get; set; } | SmartArt オブジェクトのレイアウトを取得または設定します。読み取り/書き込み [`SmartArtLayoutType`](../smartartlayouttype)。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | シェイプの線書式プロパティを含む LineFormat オブジェクトを返します。注意: 線プロパティを持たない特定のタイプのシェイプについては null を返す場合があります。読み取り専用 [`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | シェイプの名前を取得または設定します。null であってはなりません。必要に応じて空文字列を使用します。読み取り/書き込み String。 |
| [Nodes](../../aspose.slides.smartart/smartart/nodes) { get; } | SmartArt オブジェクト内のルート ノードのコレクションを返します。読み取り専用 [`ISmartArtNodeCollection`](../ismartartnodecollection)。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | シェイプの存続期間中に一定で、PowerPoint やインターロップ コードがドキュメント内の任意の場所からシェイプを確実に参照できるスライドスコープの一意識別子を返します。読み取り専用 UInt32。関連項目 [`UniqueId`](../../aspose.slides/shape/uniqueid) を参照してください。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | シェイプがグループ化されている場合は親の GroupShape オブジェクトを返します。そうでない場合は null を返します。読み取り専用 [`IGroupShape`](../../aspose.slides/igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | シェイプのプレースホルダーを返します。プレースホルダーがない場合は null を返します。読み取り専用 [`IPlaceholder`](../../aspose.slides/iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを返します。読み取り専用 [`IPresentation`](../../aspose.slides/ipresentation)。 |
| [QuickStyle](../../aspose.slides.smartart/smartart/quickstyle) { get; set; } | SmartArt オブジェクトのクイック スタイルを取得または設定します。読み取り/書き込み [`SmartArtQuickStyleType`](../smartartquickstyletype)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生のシェイプフレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定されたシェイプが Z 軸周りに回転する角度（度数）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。読み取り/書き込み Single。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | シェイプのロックを返します。読み取り専用 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。 (2 プロパティ) |
| [Slide](../../aspose.slides/shape/slide) { get; } | シェイプの親スライドを返します。読み取り専用 [`IBaseSlide`](../../aspose.slides/ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | シェイプの 3D 効果プロパティを含む ThreeDFormat オブジェクトを返します。注意: 3D プロパティを持たない特定のタイプのシェイプについては null を返す場合があります。読み取り専用 [`IThreeDFormat`](../../aspose.slides/ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードが使用することを意図した、内部のプレゼンテーションスコープの識別子を返します。この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。読み取り専用 UInt32。関連項目 [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) を参照してください。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | シェイプの幅をポイント単位で取得または設定します。読み取り/書き込み Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | シェイプの左上隅の X 座標をポイント単位で取得または設定します。読み取り/書き込み Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | シェイプの左上隅の Y 座標をポイント単位で取得または設定します。読み取り/書き込み Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | シェイプの Z 順序上の位置を返します。Shapes[0] は Z 順序の最背面のシェイプを返し、Shapes[Shapes.Count - 1] は最前面のシェイプを返します。読み取り専用 Int32。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダー シェイプ（現在のシェイプが継承しているレイアウトまたはマスタースライドからのシェイプ）を返します。継承されていない場合は null が返されます。 |
| [GetImage](../../aspose.slides/shape/getimage)() | シェイプのサムネイルを返します。デフォルトでは ShapeThumbnailBounds.Shape のシェイプサムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | シェイプのサムネイルを返します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | シェイプのレンダリングされたコンテンツから計算された視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | このシェイプがプレースホルダーではないことを定義します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | シェイプの内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | シェイプの内容を SVG ファイルとして保存します。 |

### 関連項目

* クラス [GraphicalObject](../../aspose.slides/graphicalobject)
* インターフェイス [ISmartArt](../ismartart)
* 名前空間 [Aspose.Slides.SmartArt](../../aspose.slides.smartart)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->