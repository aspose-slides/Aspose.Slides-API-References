---
title: IShape
second_title: Aspose.Sildes for .NET API リファレンス
description: スライド上のシェイプを表します。
type: docs
weight: 6970
url: /ja/aspose.slides/ishape/
---
## IShape インターフェイス

シェイプを表します。

```csharp
public interface IShape : IHyperlinkContainer, ISlideComponent
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/ishape/alternativetext) { get; set; } | シェイプに関連付けられた代替テキストを取得または設定します。読み取り/書き込み String。 |
| [AlternativeTextTitle](../../aspose.slides/ishape/alternativetexttitle) { get; set; } | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。読み取り/書き込み String。 |
| [AsIHyperlinkContainer](../../aspose.slides/ishape/asihyperlinkcontainer) { get; } | 基本 IHyperlinkContainer インターフェイスを取得できます。読み取り専用 [`IHyperlinkContainer`](../ihyperlinkcontainer)。 |
| [AsISlideComponent](../../aspose.slides/ishape/asislidecomponent) { get; } | 基本 ISlideComponent インターフェイスを取得できます。読み取り専用 [`ISlideComponent`](../islidecomponent)。 |
| [BlackWhiteMode](../../aspose.slides/ishape/blackwhitemode) { get; set; } | シェイプが白黒表示モードでどのように描画されるかを指定するプロパティです。読み取り/書き込み [`BlackWhiteMode`](../blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/ishape/connectionsitecount) { get; } | シェイプ上の接続ポイントの数を取得します。読み取り専用 Int32。 |
| [CustomData](../../aspose.slides/ishape/customdata) { get; } | シェイプのカスタム データを取得します。読み取り専用 [`ICustomData`](../icustomdata)。 |
| [EffectFormat](../../aspose.slides/ishape/effectformat) { get; } | シェイプに適用されたピクセル エフェクトを含む EffectFormat オブジェクトを取得します。読み取り専用 [`IEffectFormat`](../ieffectformat)。 |
| [FillFormat](../../aspose.slides/ishape/fillformat) { get; } | シェイプの塗りつぶし書式設定プロパティを含む FillFormat オブジェクトを取得します。読み取り専用 [`IFillFormat`](../ifillformat)。 |
| [Frame](../../aspose.slides/ishape/frame) { get; set; } | シェイプ フレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../ishapeframe)。 |
| [Height](../../aspose.slides/ishape/height) { get; set; } | シェイプの高さ（ポイント単位）を取得または設定します。読み取り/書き込み Single。 |
| [Hidden](../../aspose.slides/ishape/hidden) { get; set; } | シェイプが非表示かどうかを決定します。読み取り/書き込み Boolean。 |
| [IsDecorative](../../aspose.slides/ishape/isdecorative) { get; set; } | 「装飾としてマークする」オプションを取得または設定します。読み取り/書き込み Boolean。 |
| [IsGrouped](../../aspose.slides/ishape/isgrouped) { get; } | シェイプがグループ化されているかどうかを判断します。読み取り専用 Boolean。 |
| [IsTextHolder](../../aspose.slides/ishape/istextholder) { get; } | シェイプが TextHolder かどうかを判断します。読み取り専用 Boolean。 |
| [LineFormat](../../aspose.slides/ishape/lineformat) { get; } | シェイプの線書式設定プロパティを含む LineFormat オブジェクトを取得します。読み取り専用 [`ILineFormat`](../ilineformat)。 |
| [Name](../../aspose.slides/ishape/name) { get; set; } | シェイプの名前を取得または設定します。読み取り/書き込み String。 |
| [OfficeInteropShapeId](../../aspose.slides/ishape/officeinteropshapeid) { get; } | スライド内で一意の識別子を取得します。この識別子はシェイプの存続期間中は一定であり、PowerPoint または interop コードがドキュメント内の任意の場所からシェイプを確実に参照できます。読み取り専用 UInt32。[`UniqueId`](./uniqueid) も参照してください。 |
| [ParentGroup](../../aspose.slides/ishape/parentgroup) { get; } | シェイプがグループ化されている場合は親の GroupShape オブジェクトを取得します。そうでない場合は null を返します。読み取り専用 [`IGroupShape`](../igroupshape)。 |
| [Placeholder](../../aspose.slides/ishape/placeholder) { get; } | シェイプのプレースホルダーを取得します。読み取り専用 [`IPlaceholder`](../iplaceholder)。 |
| [RawFrame](../../aspose.slides/ishape/rawframe) { get; set; } | 生のシェイプ フレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../ishapeframe)。 |
| [Rotation](../../aspose.slides/ishape/rotation) { get; set; } | 指定されたシェイプが Z 軸周りに回転する角度（度数）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。読み取り/書き込み Single。 |
| [ShapeLock](../../aspose.slides/ishape/shapelock) { get; } | シェイプのロック状態を取得します。読み取り専用 [`IBaseShapeLock`](../ibaseshapelock)。 |
| [ThreeDFormat](../../aspose.slides/ishape/threedformat) { get; } | シェイプの線書式設定プロパティを含む ThreeDFormat オブジェクトを取得します。読み取り専用 [`IThreeDFormat`](../ithreedformat)。 |
| [UniqueId](../../aspose.slides/ishape/uniqueid) { get; } | アドインやその他のコードで使用することを想定した、プレゼンテーション内でスコープされる内部識別子を取得します。この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。読み取り専用 UInt32。[`OfficeInteropShapeId`](./officeinteropshapeid) も参照してください。 |
| [Width](../../aspose.slides/ishape/width) { get; set; } | シェイプの幅（ポイント単位）を取得または設定します。読み取り/書き込み Single。 |
| [X](../../aspose.slides/ishape/x) { get; set; } | シェイプの左上隅の X 座標（ポイント単位）を取得または設定します。読み取り/書き込み Single。 |
| [Y](../../aspose.slides/ishape/y) { get; set; } | シェイプの左上隅の Y 座標（ポイント単位）を取得または設定します。読み取り/書き込み Single。 |
| [ZOrderPosition](../../aspose.slides/ishape/zorderposition) { get; } | シェイプの Z オーダー内での位置を取得します。Shapes[0] は Z オーダーの最背面のシェイプを返し、Shapes[Shapes.Count - 1] は最前面のシェイプを返します。読み取り専用 Int32。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/ishape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、プレースホルダーのプロパティを指定されたものに設定します。 |
| [GetBasePlaceholder](../../aspose.slides/ishape/getbaseplaceholder)() | 基本的なプレースホルダー シェイプを取得します（現在のシェイプが継承元となっているレイアウトまたはマスタースライドからのシェイプ）。現在のシェイプが継承されていない場合は null が返されます。 |
| [GetImage](../../aspose.slides/ishape/getimage#getimage)() | シェイプのサムネイルを取得します。デフォルトでは ShapeThumbnailBounds.Shape のシェイプサムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/ishape/getimage#getimage_1)(ShapeThumbnailBounds, float, float) | シェイプのサムネイルを取得します。 |
| [RemovePlaceholder](../../aspose.slides/ishape/removeplaceholder)() | このシェイプがプレースホルダーでないことを定義します。 |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg)(Stream) | シェイプの内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/ishape/writeassvg#writeassvg_1)(Stream, ISVGOptions) | シェイプの内容を SVG ファイルとして保存します。 |

### 参照

* インターフェイス [IHyperlinkContainer](../ihyperlinkcontainer)
* インターフェイス [ISlideComponent](../islidecomponent)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->