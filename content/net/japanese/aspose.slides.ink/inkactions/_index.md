---
title: InkActions
second_title: Aspose.Sildes for .NET API リファレンス
description: インク アクションのルートを表します。
type: docs
weight: 7540
url: /ja/aspose.slides.ink/inkactions/
---
## InkActions クラス

インク アクションのルートを表します。

```csharp
public class InkActions : GraphicalObject, IInkActions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | シェイプに関連付けられた代替テキストを取得または設定します。Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | プロパティは、シェイプが白黒表示モードでどのように描画されるかを指定します。Read/write [`BlackWhiteMode`](../../aspose.slides/blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | シェイプ上の接続ポイントの数を取得します。Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | シェイプのカスタムデータを取得します。Read-only [`ICustomData`](../../aspose.slides/icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを取得します。注: エフェクトプロパティを持たない特定のシェイプタイプでは null が返される場合があります。Read-only [`IEffectFormat`](../../aspose.slides/ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを取得します。注: 塗りつぶしプロパティを持たない特定のシェイプタイプでは null が返される場合があります。Read-only [`IFillFormat`](../../aspose.slides/ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | シェイプフレームのプロパティを取得または設定します。Read/write [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | シェイプのロックを取得します。Read-only [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | シェイプの高さ（ポイント単位）を取得または設定します。Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | シェイプが非表示かどうかを決定します。Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。Read/write [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンクマネージャーを取得します。Read-only [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。Read/write [`IHyperlink`](../../aspose.slides/ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' オプションを取得または設定します。Read/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | シェイプがグループ化されているかどうかを判定します。Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | シェイプが TextHolder_PPT かどうかを判定します。Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | シェイプの線書式プロパティを含む LineFormat オブジェクトを取得します。注: 線プロパティを持たない特定のシェイプタイプでは null が返される場合があります。Read-only [`ILineFormat`](../../aspose.slides/ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | シェイプの名前を取得または設定します。null であってはならず、必要に応じて空文字列を使用してください。Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | スライドスコープの一意の識別子を取得します。この識別子はシェイプの存続期間中固定で、PowerPoint またはインタープコードがドキュメント内の任意の場所からシェイプを確実に参照できるようにします。Read-only UInt32. See also [`UniqueId`](../../aspose.slides/shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | シェイプがグループ化されている場合は親 GroupShape オブジェクトを取得し、そうでなければ null を返します。Read-only [`IGroupShape`](../../aspose.slides/igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | シェイプのプレースホルダーを取得します。プレースホルダーがない場合は null が返されます。Read-only [`IPlaceholder`](../../aspose.slides/iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを取得します。Read-only [`IPresentation`](../../aspose.slides/ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生のシェイプフレームのプロパティを取得または設定します。Read/write [`IShapeFrame`](../../aspose.slides/ishapeframe). |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定されたシェイプが z 軸周りに回転する角度（度）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。Read/write Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | シェイプのロックを取得します。Read-only [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | シェイプの親スライドを取得します。Read-only [`IBaseSlide`](../../aspose.slides/ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | シェイプの 3D 効果プロパティを含む ThreeDFormat オブジェクトを取得します。注: 3D プロパティを持たない特定のシェイプタイプでは null が返される場合があります。Read-only [`IThreeDFormat`](../../aspose.slides/ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードで使用することを目的とした、プレゼンテーションスコープの内部識別子を取得します。この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。Read-only UInt32. See also [`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | シェイプの幅（ポイント単位）を取得または設定します。Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | シェイプの左上隅の x 座標を取得または設定します（ポイント単位）。Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | シェイプの左上隅の y 座標を取得または設定します（ポイント単位）。Read/write Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | シェイプの Z オーダー内での位置を取得します。Shapes[0] は Z オーダーの背面にあるシェイプを返し、Shapes[Shapes.Count - 1] は前面にあるシェイプを返します。Read-only Int32. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、プレースホルダーのプロパティを指定されたものに設定します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダーシェイプを返します（現在のシェイプが継承しているレイアウトまたはマスタースライドからのシェイプ）。現在のシェイプが継承されていない場合は null が返されます。 |
| [GetImage](../../aspose.slides/shape/getimage)() | シェイプのサムネイルを返します。デフォルトでは ShapeThumbnailBounds.Shape のシェイプサムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | シェイプのサムネイルを返します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | シェイプの描画内容から計算された視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | このシェイプがプレースホルダーではないことを定義します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | シェイプの内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | シェイプの内容を SVG ファイルとして保存します。 |

### 参照

* クラス [GraphicalObject](../../aspose.slides/graphicalobject)
* インターフェイス [IInkActions](../iinkactions)
* 名前空間 [Aspose.Slides.Ink](../../aspose.slides.ink)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->