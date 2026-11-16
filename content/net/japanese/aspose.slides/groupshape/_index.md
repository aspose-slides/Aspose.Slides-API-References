---
title: GroupShape
second_title: Aspose.Sildes for .NET API リファレンス
description: スライド上の形状のグループを表します。
type: docs
weight: 5110
url: /ja/aspose.slides/groupshape/
---
## GroupShape クラス

スライド上の形状のグループを表します。

```csharp
public class GroupShape : Shape, IGroupShape
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 形状に関連付けられた代替テキストを取得または設定します。読み書き可能な String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 形状に関連付けられた代替テキストのタイトルを取得または設定します。読み書き可能な String。 |
| [AsIShape](../../aspose.slides/groupshape/asishape) { get; } | ベース IShape インターフェイスを取得できます。読み取り専用 [`IShape`](../ishape)。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | プロパティは、形状が白黒表示モードでどのように描画されるかを指定します。読み書き可能な [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 形状上の接続ポイントの数を取得します。読み取り専用 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 形状のカスタムデータを取得します。読み取り専用 [`ICustomData`](../icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | ピクセルエフェクトを含む EffectFormat オブジェクトを取得します。注: エフェクトプロパティを持たない特定の形状タイプの場合、null が返されることがあります。読み取り専用 [`IEffectFormat`](../ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 形状の塗りつぶし書式プロパティを含む FillFormat オブジェクトを取得します。注: 塗りつぶしプロパティを持たない特定の形状タイプの場合、null が返されることがあります。読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 形状フレームのプロパティを取得または設定します。読み書き可能な [`IShapeFrame`](../ishapeframe)。 |
| [GroupShapeLock](../../aspose.slides/groupshape/groupshapelock) { get; } | 形状のロック状態を取得します。読み取り専用 [`IGroupShapeLock`](../igroupshapelock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | 形状の高さ（ポイント単位）を取得または設定します。読み書き可能な Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 形状が非表示かどうかを判定します。読み書き可能な Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。読み書き可能な [`IHyperlink`](../ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンク マネージャーを取得します。読み取り専用 [`IHyperlinkManager`](../ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み書き可能な [`IHyperlink`](../ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 「装飾としてマーク」オプションを取得または設定します。読み書き可能な Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 形状がグループ化されているかどうかを判定します。読み取り専用 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 形状が TextHolder_PPT かどうかを判定します。読み取り専用 Boolean。 |
| override [LineFormat](../../aspose.slides/groupshape/lineformat) { get; } | 形状の線書式プロパティを含む LineFormat オブジェクトを取得します。注: GroupShape オブジェクトは線プロパティを持たないため、null が返されます。読み取り専用 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | 形状の名前を取得または設定します。null であってはならず、必要に応じて空文字列を使用してください。読み書き可能な String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | スライドスコープの一意の識別子を取得します。この識別子は形状の存続期間中一定で、PowerPoint またはインターロップ コードがドキュメント内の任意の場所から形状を確実に参照できます。読み取り専用 UInt32。参照先: [`UniqueId`](../shape/uniqueid)。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 形状がグループ化されている場合は親 GroupShape オブジェクトを取得します。そうでない場合は null を返します。読み取り専用 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 形状のプレースホルダーを取得します。プレースホルダーがない場合は null を返します。読み取り専用 [`IPlaceholder`](../iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを取得します。読み取り専用 [`IPresentation`](../ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生の形状フレームのプロパティを取得または設定します。読み書き可能な [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定された形状が Z 軸周りに回転する角度（度）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。読み書き可能な Single。 |
| [ShapeLock](../../aspose.slides/groupshape/shapelock) { get; } | 形状のロック状態を取得します。読み取り専用 [`IGroupShapeLock`](../igroupshapelock)。（2 つのプロパティ） |
| [Shapes](../../aspose.slides/groupshape/shapes) { get; } | グループ内の形状コレクションを取得します。読み取り専用 [`IShapeCollection`](../ishapecollection)。 |
| [Slide](../../aspose.slides/shape/slide) { get; } | 形状の親スライドを取得します。読み取り専用 [`IBaseSlide`](../ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 形状の 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを取得します。注: 3D プロパティを持たない特定の形状タイプの場合、null が返されることがあります。読み取り専用 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 内部のプレゼンテーションスコープの識別子を取得します。これはアドインや他のコードで使用することを意図しています。この値はユーザーやプログラムによって再割り当て可能で、永続的な一意キーとして扱うべきではありません。読み取り専用 UInt32。[`OfficeInteropShapeId`](../shape/officeinteropshapeid) を参照してください。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | 形状の幅（ポイント単位）を取得または設定します。読み書き可能な Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | 形状の左上隅の x 座標（ポイント単位）を取得または設定します。読み書き可能な Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | 形状の左上隅の y 座標（ポイント単位）を取得または設定します。読み書き可能な Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 形状の Z オーダーにおける位置を取得します。Shapes[0] は Z オーダーの最背面、Shapes[Shapes.Count - 1] は最前面を表します。読み取り専用 Int32。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 新しいプレースホルダーが存在しない場合に追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダー形状を取得します（レイアウトまたはマスタースライドから継承された形状）。現在の形状が継承されていない場合は null が返されます。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 形状のサムネイルを取得します。デフォルトでは ShapeThumbnailBounds.Shape のサムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 形状のサムネイルを取得します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | レンダリングされたコンテンツから計算された形状の視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | この形状がプレースホルダーでないことを定義します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape の内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape の内容を SVG ファイルとして保存します。 |

### 関連項目

* クラス [Shape](../shape)
* インターフェイス [IGroupShape](../igroupshape)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->