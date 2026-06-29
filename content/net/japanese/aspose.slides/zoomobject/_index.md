---
title: ZoomObject
second_title: Aspose.Sildes for .NET API リファレンス
description: スライド内の Zoom オブジェクトを表します。
type: docs
weight: 11850
url: /ja/aspose.slides/zoomobject/
---
## ZoomObject クラス

スライド内の Zoom オブジェクトを表します。

```csharp
public class ZoomObject : GraphicalObject, IZoomObject
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | 形状に関連付けられた代替テキストを取得または設定します。 読み取り/書き込み String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | 形状に関連付けられた代替テキストのタイトルを取得または設定します。 読み取り/書き込み String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | 形状が白黒表示モードでどのように描画されるかを指定します。 読み取り/書き込み [`BlackWhiteMode`](../blackwhitemode). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | 形状上の接続ポイントの数を取得します。 読み取り専用 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | 形状のカスタムデータを取得します。 読み取り専用 [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | エフェクトが適用されたピクセル効果を含む EffectFormat オブジェクトを取得します。 特定の形状でエフェクトプロパティが存在しない場合は null を返すことがあります。 読み取り専用 [`IEffectFormat`](../ieffectformat). |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | 塗りつぶし書式プロパティを含む FillFormat オブジェクトを取得します。 特定の形状で塗りつぶしプロパティが存在しない場合は null を返すことがあります。 読み取り専用 [`IFillFormat`](../ifillformat). |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | 形状フレームのプロパティを取得または設定します。 読み取り/書き込み [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | 形状のロック情報を取得します。 読み取り専用 [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ポイント単位で測定した形状の高さを取得または設定します。 読み取り/書き込み Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | 形状が非表示かどうかを決定します。 読み取り/書き込み Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | クリック時に定義されたハイパーリンクを取得または設定します。 読み取り/書き込み [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンクマネージャーを取得します。 読み取り専用 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー時に定義されたハイパーリンクを取得または設定します。 読み取り/書き込み [`IHyperlink`](../ihyperlink). |
| [ImageType](../../aspose.slides/zoomobject/imagetype) { get; set; } | Zoom オブジェクトの画像タイプを取得または設定します。 読み取り/書き込み [`ZoomImageType`](../zoomimagetype). デフォルト値: Preview |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 「装飾としてマーク」オプションを取得または設定します。 読み取り/書き込み Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | 形状がグループ化されているかどうかを判定します。 読み取り専用 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | 形状が TextHolder_PPT かどうかを判定します。 読み取り専用 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | 線の書式プロパティを含む LineFormat オブジェクトを取得します。 特定の形状で線プロパティが存在しない場合は null を返すことがあります。 読み取り専用 [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | 形状の名前を取得または設定します。 null にはできません。 必要に応じて空文字列を使用してください。 読み取り/書き込み String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | スライドスコープで一意の識別子を取得します。この識別子は形状の存続期間中一定で、PowerPoint や interop コードが文書内の任意の場所から形状を確実に参照できます。 読み取り専用 UInt32. 参照: [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | 形状がグループ化されている場合は親 GroupShape オブジェクトを取得します。そうでない場合は null を返します。 読み取り専用 [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | 形状のプレースホルダーを取得します。プレースホルダーがない場合は null を返します。 読み取り専用 [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを取得します。 読み取り専用 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生の形状フレームのプロパティを取得または設定します。 読み取り/書き込み [`IShapeFrame`](../ishapeframe). |
| [ReturnToParent](../../aspose.slides/zoomobject/returntoparent) { get; set; } | スライドショー中のナビゲーション動作を取得または設定します。 読み取り/書き込み Boolean. デフォルト値: false |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定された形状が Z 軸周りに回転する角度（度）を取得または設定します。正の値は時計回り、負の値は反時計回りを表します。 読み取り/書き込み Single. |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | 形状のロック情報を取得します。 読み取り専用 [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 プロパティ) |
| [ShowBackground](../../aspose.slides/zoomobject/showbackground) { get; set; } | Zoom が対象スライドの背景を使用するかどうかを示す値を取得または設定します。 読み取り/書き込み Boolean. デフォルト値: true |
| [Slide](../../aspose.slides/shape/slide) { get; } | 形状の親スライドを取得します。 読み取り専用 [`IBaseSlide`](../ibaseslide). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | 3D 効果プロパティを含む ThreeDFormat オブジェクトを取得します。 特定の形状で 3D プロパティが存在しない場合は null を返すことがあります。 読み取り専用 [`IThreeDFormat`](../ithreedformat). |
| [TransitionDuration](../../aspose.slides/zoomobject/transitionduration) { get; set; } | Zoom とスライド間の遷移時間を取得または設定します。 読み取り/書き込み Single. デフォルト値: 1.0f |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードが使用することを想定した、プレゼンテーションスコープの内部識別子を取得します。この値はユーザーやプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。 読み取り専用 UInt32. 参照: [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [Width](../../aspose.slides/shape/width) { get; set; } | ポイント単位で測定した形状の幅を取得または設定します。 読み取り/書き込み Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | ポイント単位で測定した形状の左上隅の X 座標を取得または設定します。 読み取り/書き込み Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | ポイント単位で測定した形状の左上隙の Y 座標を取得または設定します。 読み取り/書き込み Single. |
| [ZoomImage](../../aspose.slides/zoomobject/zoomimage) { get; set; } | Zoom オブジェクトの画像を取得または設定します。 読み取り/書き込み [`IPPImage`](../ippimage). |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Z オーダー内での形状の位置を取得します。Shapes[0] は Z オーダーの最背面、Shapes[Shapes.Count - 1] は最前面の形状を返します。 読み取り専用 Int32. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定したプレースホルダーのプロパティを設定します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダー形状を取得します（レイアウトまたはマスタースライドから継承された形状）。継承されていない場合は null を返します。 |
| [GetImage](../../aspose.slides/shape/getimage)() | 形状サムネイルを取得します。デフォルトでは ShapeThumbnailBounds.Shape が使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | 形状サムネイルを取得します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | レンダリングされたコンテンツから計算された形状のビジュアル境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | この形状がプレースホルダーではないことを定義します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | Shape の内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | Shape の内容を SVG ファイルとして保存します。 |

### 参照

* クラス [GraphicalObject](../graphicalobject)
* インターフェイス [IZoomObject](../izoomobject)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->