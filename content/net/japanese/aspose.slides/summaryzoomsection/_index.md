---
title: SummaryZoomSection
second_title: Aspose.Sildes for .NET API リファレンス
description: Summary Zoom フレーム内の Summary Zoom Section オブジェクトを表します。
type: docs
weight: 10760
url: /ja/aspose.slides/summaryzoomsection/
---
## SummaryZoomSection クラス

Summary Zoom フレーム内の Summary Zoom Section オブジェクトを表します。

```csharp
public class SummaryZoomSection : SectionZoomFrame, ISummaryZoomSection
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | シェイプに関連付けられた代替テキストを取得または設定します。読み取り/書き込み String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。読み取り/書き込み String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。読み取り/書き込み [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | シェイプ上の接続ポイントの数を取得します。読み取り専用 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | シェイプのカスタム データを取得します。読み取り専用 [`ICustomData`](../icustomdata). |
| [Description](../../aspose.slides/summaryzoomsection/description) { get; set; } | SummaryZoomSection オブジェクトのテキスト説明を取得します。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを取得します。注: 効果プロパティを持たない特定のシェイプの場合、null が返されることがあります。読み取り専用 [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを取得します。注: 塗りつぶしプロパティを持たない特定のシェイプの場合、null が返されることがあります。読み取り専用 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | シェイプ フレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | シェイプのロック情報を取得します。読み取り専用 [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | シェイプの高さ（ポイント単位）を取得または設定します。読み取り/書き込み Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | シェイプが非表示かどうかを決定します。読み取り/書き込み Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。読み取り/書き込み [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンク マネージャーを取得します。読み取り専用 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み取り/書き込み [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | ズームオブジェクトの画像タイプを取得または設定します。読み取り/書き込み [`ZoomImageType`](../zoomimagetype)。デフォルト値: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 'Mark as decorative' オプションを取得または設定します。読み取り/書き込み Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | シェイプがグループ化されているかどうかを判断します。読み取り専用 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | シェイプが TextHolder_PPT かどうかを判断します。読み取り専用 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | シェイプの線書式プロパティを含む LineFormat オブジェクトを取得します。注: 線プロパティを持たない特定のシェイプの場合、null が返されることがあります。読み取り専用 [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | シェイプの名前を取得または設定します。null であってはなりません。必要に応じて空文字列を使用してください。読み取り/書き込み String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | スライドスコープの一意の識別子を取得します。この識別子はシェイプの存続期間中一定で、PowerPoint またはインターロップ コードがドキュメント内の任意の場所からシェイプを確実に参照できるようにします。読み取り専用 UInt32。参照: [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | シェイプがグループ化されている場合、親 GroupShape オブジェクトを取得します。そうでない場合は null を返します。読み取り専用 [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | シェイプのプレースホルダーを取得します。プレースホルダーがない場合は null を返します。読み取り専用 [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを取得します。読み取り専用 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生のシェイプ フレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | スライドショーでのナビゲーション動作を取得または設定します。読み取り/書き込み Boolean。デフォルト値: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定されたシェイプが Z 軸周りに回転する角度（度）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。読み取り/書き込み Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | シェイプのロック情報を取得します。読み取り専用 [`IGraphicalObjectLock`](../igraphicalobjectlock)。（2 プロパティ） |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | ズームが宛先スライドの背景を使用するかどうかを指定する値を取得または設定します。読み取り/書き込み Boolean。デフォルト値: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | シェイプの親スライドを取得します。読み取り専用 [`IBaseSlide`](../ibaseslide). |
| [TargetSection](../../aspose.slides/sectionzoomframe/targetsection) { get; set; } | Section Zoom オブジェクトがリンクするセクションオブジェクトを取得または設定します。読み取り/書き込み [`ISection`](../isection). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | シェイプの 3D 効果プロパティを含む ThreeDFormat オブジェクトを取得します。注: 3D プロパティを持たない特定のシェイプの場合、null が返されることがあります。読み取り専用 [`IThreeDFormat`](../ithreedformat). |
| [Title](../../aspose.slides/summaryzoomsection/title) { get; set; } | SummaryZoomSection オブジェクトのテキストタイトルを取得します。 |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Zoom とスライド間の遷移時間を取得または設定します。読み取り/書き込み Single。デフォルト値: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | 内部のプレゼンテーションスコープの識別子を取得します。この値はアドインやその他のコードによって使用されることを想定しています。ユーザーやプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはいけません。読み取り専用 UInt32。参照: [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | シェイプの幅（ポイント単位）を取得または設定します。読み取り/書き込み Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | シェイプの左上隅の X 座標（ポイント単位）を取得または設定します。読み取り/書き込み Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | シェイプの左上隅の Y 座標（ポイント単位）を取得または設定します。読み取り/書き込み Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | ズームオブジェクトの画像を取得または設定します。読み取り/書き込み [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | シェイプの Z 順序における位置を取得します。Shapes[0] は Z 順序の後方にあるシェイプを返し、Shapes[Shapes.Count - 1] は前方にあるシェイプを返します。読み取り専用 Int32. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定されたプレースホルダーのプロパティを設定します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダー シェイプを取得します（現在のシェイプが継承元となるレイアウトまたはマスタースライドからのシェイプ）。現在のシェイプが継承されていない場合は null を返します。 |
| [GetImage](../../aspose.slides/shape/getimage)() | シェイプのサムネイルを取得します。デフォルトでは ShapeThumbnailBounds.Shape のサムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | シェイプのサムネイルを取得します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | このシェイプがプレースホルダーではないことを定義します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | シェイプの内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISSVGOptions) | シェイプの内容を SVG ファイルとして保存します。 |

### 参照

* クラス [SectionZoomFrame](../sectionzoomframe)
* インターフェイス [ISummaryZoomSection](../isummaryzoomsection)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->