---
title: InkActions
second_title: Aspose.Sildes for .NET API リファレンス
description: インク アクションのルートを表します。
type: docs
weight: 7580
url: /ja/aspose.slides.ink/inkactions/
---
## InkActions クラス

シェイプのアクションのルートを表します。

```csharp
public class InkActions : GraphicalObject, IInkActions
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | シェイプに関連付けられた代替テキストを取得または設定します。読み取り/書き込み String。 |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。読み取り/書き込み String。 |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | プロパティは、シェイプが白黒表示モードでどのようにレンダリングされるかを指定します。読み取り/書き込み [`BlackWhiteMode`](../../aspose.slides/blackwhitemode)。 |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | シェイプ上の接続サイトの数を取得します。読み取り専用 Int32。 |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | シェイプのカスタムデータを取得します。読み取り専用 [`ICustomData`](../../aspose.slides/icustomdata)。 |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを取得します。注: エフェクト プロパティを持たない特定のタイプのシェイプの場合、null を返すことがあります。読み取り専用 [`IEffectFormat`](../../aspose.slides/ieffectformat)。 |
| virtual [FillFormat](../../aspose.slides/shape/fillformat) { get; } | シェイプの塗りつぶし書式プロパティを含む FillFormat オブジェクトを取得します。注: 塗りつぶしプロパティを持たない特定のタイプのシェイプの場合、null を返すことがあります。読み取り専用 [`IFillFormat`](../../aspose.slides/ifillformat)。 |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | シェイプ フレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | シェイプのロックを取得します。読み取り専用 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。 |
| [Height](../../aspose.slides/shape/height) { get; set; } | シェイプの高さをポイントで取得または設定します。読み取り/書き込み Single。 |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | シェイプが非表示かどうかを決定します。読み取り/書き込み Boolean。 |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | マウスクリック用に定義されたハイパーリンクを取得または設定します。読み取り/書き込み [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンク マネージャーを取得します。読み取り専用 [`IHyperlinkManager`](../../aspose.slides/ihyperlinkmanager)。 |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー用に定義されたハイパーリンクを取得または設定します。読み取り/書き込み [`IHyperlink`](../../aspose.slides/ihyperlink)。 |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 装飾としてマークするオプションを取得または設定します。Reed/write Boolean。 |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | シェイプがグループ化されているかどうかを決定します。読み取り専用 Boolean。 |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | シェイプが TextHolder_PPT かどうかを決定します。読み取り専用 Boolean。 |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | シェイプの線書式プロパティを含む LineFormat オブジェクトを取得します。注: 線プロパティを持たない特定のタイプのシェイプの場合、null を返すことがあります。読み取り専用 [`ILineFormat`](../../aspose.slides/ilineformat)。 |
| [Name](../../aspose.slides/shape/name) { get; set; } | シェイプの名前を取得または設定します。null であってはなりません。必要に応じて空文字列を使用してください。読み取り/書き込み String。 |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | スライド スコープの一意識別子を取得します。この識別子はシェイプの存続期間中に一定であり、PowerPoint またはインターオップコードがドキュメント内の任意の場所からシェイプを確実に参照できるようにします。読み取り専用 UInt32。[`UniqueId`](../../aspose.slides/shape/uniqueid) を参照してください。 |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | シェイプがグループ化されている場合、親の GroupShape オブジェクトを取得します。そうでない場合は null を返します。読み取り専用 [`IGroupShape`](../../aspose.slides/igroupshape)。 |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | シェイプのプレースホルダーを取得します。プレースホルダーがない場合は null を返します。読み取り専用 [`IPlaceholder`](../../aspose.slides/iplaceholder)。 |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを取得します。読み取り専用 [`IPresentation`](../../aspose.slides/ipresentation)。 |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生のシェイプ フレームのプロパティを取得または設定します。読み取り/書き込み [`IShapeFrame`](../../aspose.slides/ishapeframe)。 |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定されたシェイプが Z 軸周りに回転する角度（度数）を取得または設定します。正の値は時計回りの回転、負の値は逆時計回りの回転を示します。読み取り/書き込み Single。 |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | シェイプのロックを取得します。読み取り専用 [`IGraphicalObjectLock`](../../aspose.slides/igraphicalobjectlock)。 （2 プロパティ） |
| [Slide](../../aspose.slides/shape/slide) { get; } | シェイプの親スライドを取得します。読み取り専用 [`IBaseSlide`](../../aspose.slides/ibaseslide)。 |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | シェイプの 3D エフェクトプロパティを含む ThreeDFormat オブジェクトを取得します。注: 3D プロパティを持たない特定のタイプのシェイプの場合、null を返すことがあります。読み取り専用 [`IThreeDFormat`](../../aspose.slides/ithreedformat)。 |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインやその他のコードで使用されることを想定した、内部的なプレゼンテーション スコープの識別子を取得します。この値はユーザーやプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはいけません。読み取り専用 UInt32。[`OfficeInteropShapeId`](../../aspose.slides/shape/officeinteropshapeid) を参照してください。 |
| [Width](../../aspose.slides/shape/width) { get; set; } | シェイプの幅をポイントで取得または設定します。読み取り/書き込み Single。 |
| [X](../../aspose.slides/shape/x) { get; set; } | シェイプの左上隅の X 座標をポイントで取得または設定します。読み取り/書き込み Single。 |
| [Y](../../aspose.slides/shape/y) { get; set; } | シェイプの左上隅の Y 座標をポイントで取得または設定します。読み取り/書き込み Single。 |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | シェイプの Z 順序における位置を取得します。Shapes[0] は Z 順序の最背面のシェイプを返し、Shapes[Shapes.Count - 1] は前面のシェイプを返します。読み取り専用 Int32。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | 新しいプレースホルダーが存在しない場合に追加し、プレースホルダー プロパティを指定されたものに設定します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダー シェイプを取得します（現在のシェイプが継承されているレイアウトまたはマスタースライドからのシェイプ）。現在のシェイプが継承されていない場合は null が返されます。 |
| [GetImage](../../aspose.slides/shape/getimage)() | シェイプのサムネイルを取得します。デフォルトでは ShapeThumbnailBounds.Shape のシェイプ サムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | シェイプのサムネイルを取得します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | このシェイプがプレースホルダーではないことを定義します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | シェイプの内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | シェイプの内容を SVG ファイルとして保存します。 |

### 参照

* クラス [GraphicalObject](../../aspose.slides/graphicalobject)
* インターフェイス [IInkActions](../iinkactions)
* 名前空間 [Aspose.Slides.Ink](../../aspose.slides.ink)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->