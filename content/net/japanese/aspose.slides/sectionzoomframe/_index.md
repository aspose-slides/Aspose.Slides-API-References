---
title: SectionZoomFrame
second_title: Aspose.Sildes for .NET API リファレンス
description: スライド内の Section Zoom オブジェクトを表します。
type: docs
weight: 9780
url: /ja/aspose.slides/sectionzoomframe/
---
## SectionZoomFrame class

スライド内の Section Zoom オブジェクトを表します。

```csharp
public class SectionZoomFrame : ZoomObject, ISectionZoomFrame
```

## Properties

| Name | Description |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 形状に関連付けられた代替テキストを取得または設定します。Read/write String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 形状に関連付けられた代替テキストのタイトルを取得または設定します。Read/write String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | プロパティは、形状が白黒表示モードでどのように描画されるかを指定します。Read/write [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 形状の接続ポイントの数を返します。Read-only Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 形状のカスタム データを返します。Read-only [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | ピクセル効果が適用された EffectFormat オブジェクトを返します。効果プロパティを持たない特定の形状では null を返すことがあります。Read-only [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 塗りつぶしプロパティを含む FillFormat オブジェクトを返します。塗りつぶしプロパティを持たない特定の形状では null を返すことがあります。Read-only [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 形状フレームのプロパティを取得または設定します。Read/write [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 形状のロック情報を返します。Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | 形状の高さ（ポイント単位）を取得または設定します。Read/write Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 形状が非表示かどうかを決定します。Read/write Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。Read/write [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンクマネージャーを返します。Read-only [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。Read/write [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | ズーム オブジェクトの画像タイプを取得または設定します。Read/write [`ZoomImageType`](../zoomimagetype). デフォルト値: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 「装飾としてマーク」オプションを取得または設定します。Read/write Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 形状がグループ化されているかどうかを判断します。Read-only Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 形状が TextHolder_PPT かどうかを判断します。Read-only Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 線の書式設定プロパティを含む LineFormat オブジェクトを返します。線プロパティを持たない特定の形状では null を返すことがあります。Read-only [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 形状の名前を取得または設定します。null にはできません。必要に応じて空文字列を使用してください。Read/write String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | スライド スコープの一意識別子を返します。この識別子は形状の存続期間中一定で、PowerPoint や interop コードがドキュメント内の任意の場所から形状を確実に参照できます。Read-only UInt32. 参照: [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 形状がグループ化されている場合は親 GroupShape オブジェクトを返します。そうでない場合は null を返します。Read-only [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 形状のプレースホルダーを返します。プレースホルダーがない場合は null を返します。Read-only [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを返します。Read-only [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生の形状フレームのプロパティを取得または設定します。Read/write [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | スライドショーのナビゲーション動作を取得または設定します。Read/write Boolean. デフォルト値: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定された形状が Z 軸周りに回転する角度（度）を取得または設定します。正の値は時計回り、負の値は逆時計回りです。Read/write Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 形状のロック情報を返します。Read-only [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Zoom が宛先スライドの背景を使用するかどうかを指定する値を取得または設定します。Read/write Boolean. デフォルト値: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | 形状の親スライドを返します。Read-only [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Section Zoom オブジェクトがリンクするセクション オブジェクトを取得または設定します。Read/write [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 形状の 3D 効果プロパティを含む ThreeDFormat オブジェクトを返します。3D プロパティを持たない特定の形状では null を返すことがあります。Read-only [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Zoom とスライド間の遷移時間を取得または設定します。Read/write Single. デフォルト値: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインや他のコードが使用するための内部プレゼンテーション スコープの識別子を返します。この値はユーザーまたはプログラムによって再割り当て可能であるため、永続的な一意キーとして扱ってはいけません。Read-only UInt32. 参照: [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | 形状の幅（ポイント単位）を取得または設定します。Read/write Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | 形状の左上隅の X 座標（ポイント単位）を取得または設定します。Read/write Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | 形状の左上隅の Y 座標（ポイント単位）を取得または設定します。Read/write Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | ズーム オブジェクトの画像を取得または設定します。Read/write [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | 形状の Z オーダーにおける位置を返します。Shapes[0] は Z オーダーの最背面、Shapes[Shapes.Count - 1] は最前面の形状を示します。Read-only Int32. |

## Methods

| Name | Description |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定したプレースホルダーのプロパティを設定します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダー形状（レイアウトまたはマスタースライドから継承された形状）を返します。継承されていない場合は null を返します。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 形状サムネイルを返します。デフォルトでは ShapeThumbnailBounds.Shape が使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 形状サムネイルを返します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | 描画されたコンテンツから計算された形状のビジュアル境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | この形状がプレースホルダーではないことを定義します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape の内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape の内容を SVG ファイルとして保存します。 |

### See Also

* class [ZoomObject](../zoomobject)
* interface [ISectionZoomFrame](../isectionzoomframe)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->