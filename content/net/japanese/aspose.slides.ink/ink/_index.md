---
title: Ink
second_title: Aspose.Sildes の .NET API リファレンス
description: スライド上のインクオブジェクトを表します。
type: docs
weight: 7530
url: /ja/aspose.slides.ink/ink/
---
## Ink クラス

スライド上のインクオブジェクトを表します。

```csharp
public class Ink : GraphicalObject, IInk
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | シェイプに関連付けられた代替テキストを取得または設定します。読み取り/書き込み String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。読み取り/書き込み String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。読み取り/書き込み [`BlackWhiteMode`](../../aspose.slides/blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | シェイプ上の接続ポイント数を取得します。読み取り専用 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | シェイプのカスタムデータを取得します。読み取り専用 [`ICustomData`](../../aspose.slides/icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを取得します。注: エフェクトプロパティを持たない特定のシェイプタイプでは null が返される場合があります。読み取り専用 [`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを取得します。注: 塗りつぶしプロパティを持たない特定のシェイプタイプでは null が返される場合があります。読み取り専用 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | シェイプ フレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | シェイプのロック情報を取得します。読み取り専用 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | シェイプの高さ（ポイント単位）を取得または設定します。読み取り/書き込み Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | シェイプが非表示かどうかを判断します。読み取り/書き込み Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。読み取り/書き込み [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンクマネージャーを取得します。読み取り専用 [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み取り/書き込み [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 装飾としてマークするオプションを取得または設定します。Reed/write Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | シェイプがグループ化されているかどうかを判断します。読み取り専用 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | シェイプが TextHolder_PPT かどうかを判断します。読み取り専用 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | シェイプの線書式プロパティを含む LineFormat オブジェクトを取得します。注: 線プロパティを持たない特定のシェイプタイプでは null が返される場合があります。読み取り専用 [`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | シェイプの名前を取得または設定します。null であってはなりません。必要に応じて空文字列を使用してください。読み取り/書き込み String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | シェイプの存続期間中に一定で、PowerPoint やインターロップコードが文書内の任意の箇所からシェイプを確実に参照できるスライドスコープの一意識別子を取得します。読み取り専用 UInt32。こちらも参照してください [`UniqueId`](../../aspose.slides/shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | シェイプがグループ化されている場合は親の GroupShape オブジェクトを取得します。それ以外の場合は null を返します。読み取り専用 [`IGroupShape`](../../aspose.slides/igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | シェイプのプレースホルダーを取得します。プレースホルダーがない場合は null を返します。読み取り専用 [`IPlaceholder`](../../aspose.slides/iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを取得します。読み取り専用 [`IPresentation`](../../aspose.slides/ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生のシェイプフレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定されたシェイプが z 軸周りに回転する角度（度）を取得または設定します。正の値は時計回りの回転を示し、負の値は反時計回りの回転を示します。読み取り/書き込み Single。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | シェイプのロック情報を取得します。読み取り専用 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。（2 プロパティ） |
| [Slide](../../aspose.slides/shape/slide) { get; } | シェイプの親スライドを取得します。読み取り専用 [`IBaseSlide`](../../aspose.slides/ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | シェイプの 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを取得します。注: 3D プロパティを持たない特定のシェイプタイプでは null が返される場合があります。読み取り専用 [`IThreeDFormat`](../../aspose.slides/ithreedformat)。 |
| [Traces](../../aspose.slides.ink/ink/traces) { get; } | IInk 要素 [`IInkTrace`](../iinktrace) に含まれるすべてのトレースを取得します。読み取り専用。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードで使用することを意図した、プレゼンテーションスコープの内部識別子を取得します。この値はユーザーやプログラムにより再割り当て可能であるため、永続的な一意キーとして扱ってはいけません。読み取り専用 UInt32。こちらも参照してください [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid)。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | シェイプの幅（ポイント単位）を取得または設定します。読み取り/書き込み Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | シェイプの左上隅の X 座標（ポイント単位）を取得または設定します。読み取り/書き込み Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | シェイプの左上隅の Y 座標（ポイント単位）を取得または設定します。読み取り/書き込み Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | シェイプの Z オーダー内での位置を取得します。Shapes[0] は Z オーダーの最後（背面）にあるシェイプを返し、Shapes[Shapes.Count - 1] は前面にあるシェイプを返します。読み取り専用 Int32。 |
| static [InkEffectImages](../../aspose.slides.ink/ink/inkeffectimages) { get; } | インクブラシの視覚効果をシミュレートするために使用されるカスタム画像のコレクションを取得します。これらの画像は、Galaxy、Rainbow などの特定の [`InkEffectType`](../inkeffecttype) 値でインクをレンダリングする際に使用されます。独自の画像を提供することで、各インク効果の表示方法を制御できます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダーシェイプを取得します（レイアウトまたはマスタースライドから継承された現在のシェイプ）。継承されていない場合は null を返します。 |
| [GetImage](../../aspose.slides/shape/getimage)() | シェイプのサムネイルを取得します。デフォルトでは ShapeThumbnailBounds.Shape のサムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | シェイプのサムネイルを取得します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | このシェイプがプレースホルダーではないことを定義します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | シェイプの内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | シェイプの内容を SVG ファイルとして保存します。 |

### 参照

* クラス [GraphicalObject](../../aspose.slides/graphicalobject)
* インターフェイス [IInk](../iink)
* 名前空間 [Aspose.Slides.Ink](../../aspose.slides.ink)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->