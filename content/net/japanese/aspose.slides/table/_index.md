---
title: Table
second_title: Aspose.Sildes for .NET API リファレンス
description: スライド上のテーブルを表します。
type: docs
weight: 10840
url: /ja/aspose.slides/table/
---
## Table クラス

スライド上のテーブルを表します。

```csharp
public sealed class Table : GraphicalObject, ITable
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [AlternativeText](../../aspose.slides/shape/alternativetext) { get; set; } | シェイプに関連付けられた代替テキストを取得または設定します。読み書き可能 String. |
| [AlternativeTextTitle](../../aspose.slides/shape/alternativetexttitle) { get; set; } | シェイプに関連付けられた代替テキストのタイトルを取得または設定します。読み書き可能 String. |
| [BlackWhiteMode](../../aspose.slides/shape/blackwhitemode) { get; set; } | プロパティは、シェイプが白黒表示モードでどのように描画されるかを指定します。読み書き可能 [`BlackWhiteMode`](../blackwhitemode). |
| [Columns](../../aspose.slides/table/columns) { get; } | 列のコレクションを取得します。読み取り専用 [`IColumnCollection`](../icolumncollection). |
| [ConnectionSiteCount](../../aspose.slides/shape/connectionsitecount) { get; } | シェイプ上の接続ポイントの数を取得します。読み取り専用 Int32. |
| [CustomData](../../aspose.slides/shape/customdata) { get; } | シェイプのカスタム データを取得します。読み取り専用 [`ICustomData`](../icustomdata). |
| virtual [EffectFormat](../../aspose.slides/shape/effectformat) { get; } | シェイプに適用されたピクセル効果を含む EffectFormat オブジェクトを取得します。注: 効果プロパティを持たない特定のシェイプタイプでは null が返される場合があります。読み取り専用 [`IEffectFormat`](../ieffectformat). |
| override [FillFormat](../../aspose.slides/table/fillformat) { get; } | Table の塗りつぶし書式情報を含む TableFormat.FillFormat オブジェクトを取得します。読み取り専用 [`IFillFormat`](../ifillformat). |
| [FirstCol](../../aspose.slides/table/firstcol) { get; set; } | テーブルの最初の列を特別な書式で描画するかどうかを決定します。読み書き可能 Boolean. |
| [FirstRow](../../aspose.slides/table/firstrow) { get; set; } | テーブルの最初の行を特別な書式で描画するかどうかを決定します。読み書き可能 Boolean. |
| [Frame](../../aspose.slides/shape/frame) { get; set; } | シェイプフレームのプロパティを取得または設定します。読み書き可能 [`IShapeFrame`](../ishapeframe). |
| [GraphicalObjectLock](../../aspose.slides/graphicalobject/graphicalobjectlock) { get; } | シェイプのロック状態を取得します。読み取り専用 [`IGraphicalObjectLock`](../igraphicalobjectlock). |
| [Height](../../aspose.slides/shape/height) { get; set; } | ポイント単位でシェイプの高さを取得または設定します。読み書き可能 Single. |
| [Hidden](../../aspose.slides/shape/hidden) { get; set; } | シェイプが非表示かどうかを決定します。読み書き可能 Boolean. |
| [HorizontalBanding](../../aspose.slides/table/horizontalbanding) { get; set; } | 偶数行を別の書式で描画するかどうかを決定します。読み書き可能 Boolean. |
| [HyperlinkClick](../../aspose.slides/shape/hyperlinkclick) { get; set; } | クリック時に使用されるハイパーリンクを取得または設定します。読み書き可能 [`IHyperlink`](../ihyperlink). |
| [HyperlinkManager](../../aspose.slides/shape/hyperlinkmanager) { get; } | ハイパーリンク マネージャーを取得します。読み取り専用 [`IHyperlinkManager`](../ihyperlinkmanager). |
| [HyperlinkMouseOver](../../aspose.slides/shape/hyperlinkmouseover) { get; set; } | マウスオーバー時に使用されるハイパーリンクを取得または設定します。読み書き可能 [`IHyperlink`](../ihyperlink). |
| [IsDecorative](../../aspose.slides/shape/isdecorative) { get; set; } | 「装飾としてマーク」オプションを取得または設定します。読み書き可能 Boolean. |
| [IsGrouped](../../aspose.slides/shape/isgrouped) { get; } | シェイプがグループ化されているかどうかを取得します。読み取り専用 Boolean. |
| [IsTextHolder](../../aspose.slides/shape/istextholder) { get; } | シェイプが TextHolder_PPT かどうかを取得します。読み取り専用 Boolean. |
| [Item](../../aspose.slides/table/item) { get; } | 指定した列インデックスと行インデックスにあるセルを取得します。読み取り専用 [`Cell`](../cell). |
| [LastCol](../../aspose.slides/table/lastcol) { get; set; } | テーブルの最終列を特別な書式で描画するかどうかを決定します。読み書き可能 Boolean. |
| [LastRow](../../aspose.slides/table/lastrow) { get; set; } | テーブルの最終行を特別な書式で描画するかどうかを決定します。読み書き可能 Boolean. |
| virtual [LineFormat](../../aspose.slides/shape/lineformat) { get; } | シェイプの線書式プロパティを含む LineFormat オブジェクトを取得します。注: 線プロパティを持たない特定のシェイプタイプでは null が返される場合があります。読み取り専用 [`ILineFormat`](../ilineformat). |
| [Name](../../aspose.slides/shape/name) { get; set; } | シェイプの名前を取得または設定します。null にはできません。必要に応じて空文字列を使用してください。読み書き可能 String. |
| [OfficeInteropShapeId](../../aspose.slides/shape/officeinteropshapeid) { get; } | スライド内で一意の識別子を取得します。この識別子はシェイプの存続期間中一定で、PowerPoint や Interop コードがドキュメント内の任意の場所からシェイプを確実に参照できるようにします。読み取り専用 UInt32. こちらも参照 [`UniqueId`](../shape/uniqueid). |
| [ParentGroup](../../aspose.slides/shape/parentgroup) { get; } | シェイプがグループ化されている場合は親 GroupShape オブジェクトを取得します。そうでなければ null が返されます。読み取り専用 [`IGroupShape`](../igroupshape). |
| [Placeholder](../../aspose.slides/shape/placeholder) { get; } | シェイプのプレースホルダーを取得します。プレースホルダーがない場合は null が返されます。読み取り専用 [`IPlaceholder`](../iplaceholder). |
| [Presentation](../../aspose.slides/shape/presentation) { get; } | スライドの親プレゼンテーションを取得します。読み取り専用 [`IPresentation`](../ipresentation). |
| [RawFrame](../../aspose.slides/shape/rawframe) { get; set; } | 生のシェイプフレームのプロパティを取得または設定します。読み書き可能 [`IShapeFrame`](../ishapeframe). |
| [RightToLeft](../../aspose.slides/table/righttoleft) { get; set; } | テーブルが右から左へ読む順序であるかどうかを決定します。読み書き可能 Boolean. |
| [Rotation](../../aspose.slides/shape/rotation) { get; set; } | 指定したシェイプが Z 軸を中心に回転する角度（度）を取得または設定します。正の値は時計回り、負の値は反時計回りを示します。読み書き可能 Single. |
| [Rows](../../aspose.slides/table/rows) { get; } | 行のコレクションを取得します。読み取り専用 [`IRowCollection`](../irowcollection). |
| [ShapeLock](../../aspose.slides/graphicalobject/shapelock) { get; } | シェイプのロック状態を取得します。読み取り専用 [`IGraphicalObjectLock`](../igraphicalobjectlock). (2 properties) |
| [Slide](../../aspose.slides/shape/slide) { get; } | シェイプの親スライドを取得します。読み取り専用 [`IBaseSlide`](../ibaseslide). |
| [StylePreset](../../aspose.slides/table/stylepreset) { get; set; } | 組み込みテーブル スタイルを取得または設定します。読み書き可能 [`TableStylePreset`](../tablestylepreset). |
| [TableFormat](../../aspose.slides/table/tableformat) { get; } | このテーブルの書式プロパティを含む TableFormat オブジェクトを取得します。読み取り専用 [`ITableFormat`](../itableformat). |
| virtual [ThreeDFormat](../../aspose.slides/shape/threedformat) { get; } | シェイプの 3D 効果プロパティを含む ThreeDFormat オブジェクトを取得します。注: 3D プロパティを持たない特定のシェイプタイプでは null が返される場合があります。読み取り専用 [`IThreeDFormat`](../ithreedformat). |
| [UniqueId](../../aspose.slides/shape/uniqueid) { get; } | アドインや他のコードが使用するための内部プレゼンテーション スコープの識別子を取得します。この値はユーザーまたはプログラムによって再割り当て可能なため、永続的な一意キーとして扱ってはなりません。読み取り専用 UInt32. こちらも参照 [`OfficeInteropShapeId`](../shape/officeinteropshapeid). |
| [VerticalBanding](../../aspose.slides/table/verticalbanding) { get; set; } | 偶数列を別の書式で描画するかどうかを決定します。読み書き可能 Boolean. |
| [Width](../../aspose.slides/shape/width) { get; set; } | シェイプの幅をポイント単位で取得または設定します。読み書き可能 Single. |
| [X](../../aspose.slides/shape/x) { get; set; } | シェイプ左上隅の X 座標をポイント単位で取得または設定します。読み書き可能 Single. |
| [Y](../../aspose.slides/shape/y) { get; set; } | シェイプ左上隅の Y 座標をポイント単位で取得または設定します。読み書き可能 Single. |
| virtual [ZOrderPosition](../../aspose.slides/shape/zorderposition) { get; } | Z オーダーにおけるシェイプの位置を取得します。Shapes[0] は Z オーダーの最背面にあるシェイプを、Shapes[Shapes.Count - 1] は最前面にあるシェイプを返します。読み取り専用 Int32. |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [AddPlaceholder](../../aspose.slides/shape/addplaceholder)(IPlaceholder) | プレースホルダーが存在しない場合に新しいプレースホルダーを追加し、指定したプレースホルダーのプロパティを設定します。 |
| [GetBasePlaceholder](../../aspose.slides/shape/getbaseplaceholder)() | 基本的なプレースホルダー シェイプを取得します (レイアウトまたはマスタースライドから継承されたシェイプ)。継承されていない場合は null が返されます。 |
| [GetImage](../../aspose.slides/shape/getimage)() | シェイプのサムネイルを取得します。デフォルトで ShapeThumbnailBounds.Shape のサムネイル境界タイプが使用されます。 |
| [GetImage](../../aspose.slides/shape/getimage)(ShapeThumbnailBounds, float, float) | シェイプのサムネイルを取得します。 |
| [GetVisualBounds](../../aspose.slides/shape/getvisualbounds)() | レンダリングされたコンテンツから計算されたシェイプの視覚的境界を取得します。 |
| [MergeCells](../../aspose.slides/table/mergecells)(ICell, ICell, bool) | 隣接するセルを結合します。 |
| [RemovePlaceholder](../../aspose.slides/shape/removeplaceholder)() | このシェイプがプレースホルダーではないことを定義します。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat)(IParagraphFormat) | 定義された段落書式プロパティをすべてのテーブルセルの段落に設定します。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_1)(IPortionFormat) | 定義された部分書式プロパティをすべてのテーブルセルの部分に設定します。 |
| [SetTextFormat](../../aspose.slides/table/settextformat#settextformat_2)(ITextFrameFormat) | 定義されたテキストフレーム書式プロパティをすべてのテーブルセルのテキストフレームに設定します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream) | シェイプの内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/shape/writeassvg)(Stream, ISVGOptions) | シェイプの内容を SVG ファイルとして保存します。 |

### 関連項目

* class [GraphicalObject](../graphicalobject)
* interface [ITable](../itable)
* namespace [Aspose.Slides](../../aspose.slides)
* assembly [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->