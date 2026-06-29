---
title: SummaryZoomFrame
second_title: Aspose.Sildes for .NET API リファレンス
description: スライド内の Summary Zoom オブジェクトを表します。
type: docs
weight: 10750
url: /ja/aspose.slides/summaryzoomframe/
---
## SummaryZoomFrame クラス

スライド内の Summary Zoom オブジェクトを表します。

```csharp
public class SummaryZoomFrame : GraphicalObject, ISummaryZoomFrame
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | シェイプに関連付けられた代替テキストを取得または設定します。読み取り/書き込み String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。読み取り/書き込み String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | プロパティは、シェイプが白黒表示モードでどのように描画されるかを指定します。読み取り/書き込み [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | シェイプ上の接続ポイントの数を取得します。読み取り専用 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | シェイプのカスタムデータを取得します。読み取り専用 [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | シェイプに適用されたピクセルエフェクトを含む EffectFormat オブジェクトを取得します。注: エフェクトプロパティを持たない特定の種類のシェイプでは null を返す可能性があります。読み取り専用 [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | シェイプの塗りの書式プロパティを含む FillFormat オブジェクトを取得します。注: 塗りプロパティを持たない特定の種類のシェイプでは null を返す可能性があります。読み取り専用 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | シェイプフレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | シェイプのロックを取得します。読み取り専用 [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | シェイプの高さ（ポイント単位）を取得または設定します。読み取り/書き込み Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | シェイプが非表示かどうかを決定します。読み取り/書き込み Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。読み取り/書き込み [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンクマネージャーを取得します。読み取り専用 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み取り/書き込み [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 「装飾としてマーク」オプションを取得または設定します。読み取り/書き込み Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | シェイプがグループ化されているかどうかを判定します。読み取り専用 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | シェイプが TextHolder_PPT かどうかを判定します。読み取り専用 Boolean. |
| [Layout](../../aspose.slides/summaryzoomframe/layout) { get; } | フレーム内の Summary Zoom セクションのレイアウトを取得します。デフォルト値は GridLayout です。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | シェイプの線書式プロパティを含む LineFormat オブジェクトを取得します。注: 線プロパティを持たない特定の種類のシェイプでは null を返す可能性があります。読み取り専用 [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | シェイプの名前を取得または設定します。null であってはなりません。必要に応じて空文字列を使用してください。読み取り/書き込み String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | スライドスコープの一意の識別子を取得します。この識別子はシェイプの存続期間中一定であり、PowerPoint またはインタープコードがドキュメント内の任意の場所からシェイプを確実に参照できるようにします。読み取り専用 UInt32。[`UniqueId`](../shape/uniqueid) も参照してください。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | シェイプがグループ化されている場合は親 GroupShape オブジェクトを取得します。そうでない場合は null を返します。読み取り専用 [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | シェイプのプレースホルダーを取得します。プレースホルダーがない場合は null を返します。読み取り専用 [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを取得します。読み取り専用 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生のシェイプフレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定されたシェイプが Z 軸周りに回転する度数を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。読み取り/書き込み Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | シェイプのロックを取得します。読み取り専用 [`IGraphicalObjectLock`](../igraphicalobjectlock).（2 つのプロパティ） |
| [Slide](../../aspose.slides/shape/slide) { get; } | シェイプの親スライドを取得します。読み取り専用 [`IBaseSlide`](../ibaseslide). |
| [SummaryZoomCollection](../../aspose.slides/summaryzoomframe/summaryzoomcollection) { get; } | Summary Zoom フレームオブジェクトの [`ISummaryZoomSectionCollection`](../isummaryzoomsectioncollection) を取得します。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | シェイプの 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを取得します。注: 3D プロパティを持たない特定の種類のシェイプでは null を返す可能性があります。読み取り専用 [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードで使用することを目的とした、内部のプレゼンテーションスコープの識別子を取得します。この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。読み取り専用 UInt32。[`OfficeInteropShapeId`](../shape/officeinteropshapeid) も参照してください。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | シェイプの幅（ポイント単位）を取得または設定します。読み取り/書き込み Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | シェイプの左上隅の X 座標（ポイント単位）を取得または設定します。読み取り/書き込み Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | シェイプの左上隅の Y 座標（ポイント単位）を取得または設定します。読み取り/書き込み Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | z オーダーにおけるシェイプの位置を取得します。Shapes[0] は z オーダーの最背面のシェイプを返し、Shapes[Shapes.Count - 1] は最前面のシェイプを返します。読み取り専用 Int32. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダーシェイプを取得します（現在のシェイプが継承しているレイアウトまたはマスタースライドからのシェイプ）。現在のシェイプが継承されていない場合は null を返します。 |
| [GetImage](../../aspose.slides/shape/getimage)() | シェイプのサムネイルを取得します。デフォルトでは ShapeThumbnailBounds.Shape のサムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | シェイプのサムネイルを取得します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | このシェイプがプレースホルダーではないことを定義します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | シェイプの内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | シェイプの内容を SVG ファイルとして保存します。 |

### 参照

* クラス [GraphicalObject](../graphicalobject)
* インターフェイス [ISummaryZoomFrame](../isummaryzoomframe)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->