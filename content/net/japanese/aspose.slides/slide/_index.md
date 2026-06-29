---
title: Slide
second_title: Aspose.Sildes for .NET API リファレンス
description: プレゼンテーション内のスライドを表します。
type: docs
weight: 9940
url: /ja/aspose.slides/slide/
---
## Slide クラス

プレゼンテーション内のスライドを表します。

```csharp
public sealed class Slide : BaseSlide, ISlide
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Background](../../aspose.slides/baseslide/background) { get; } | スライドの背景を返します。読み取り専用 [`IBackground`](../ibackground)。 |
| [Controls](../../aspose.slides/baseslide/controls) { get; } | スライド上の ActiveX コントロールのコレクションを返します。読み取り専用 [`IControlCollection`](../icontrolcollection)。 |
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | スライドのカスタムデータを返します。読み取り専用 [`ICustomData`](../icustomdata)。 |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | スライドの HeaderFooter マネージャーを返します。読み取り専用 [`ISlideHeaderFooterManager`](../islideheaderfootermanager)。 |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | スライドショー中に指定されたスライドが非表示かどうかを決定します。読み書き可能 Boolean。 |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | 含まれるハイパーリンクへの簡易アクセスを提供します。読み取り専用 [`IHyperlinkQueries`](../ihyperlinkqueries)。 |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | 現在のスライドのレイアウトスライドを取得または設定します。読み書き可能 [`ILayoutSlide`](../ilayoutslide)。 |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | スライドの名前を取得または設定します。読み書き可能 String。 |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | ノートスライドにアクセスし、追加・削除できるようにします。読み取り専用 [`INotesSlideManager`](../inotesslidemanager)。 |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | IPresentation インターフェイスを返します。読み取り専用 [`IPresentation`](../ipresentation)。 |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | スライドのシェイプを返します。読み取り専用 [`IShapeCollection`](../ishapecollection)。 |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | マスタースライド上のシェイプをスライド上に表示するかどうかを指定します。読み書き可能 Boolean。 |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | スライドの ID を返します。読み取り専用 UInt32。 |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | スライドの番号を返します。[`Slides`](../presentation/slides) コレクション内のインデックスは常に SlideNumber - Presentation.FirstSlideNumber と等しくなります。読み書き可能 Int32。 |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | スライドショー中に指定されたスライドがどのように進行するかに関する情報を含む Transition オブジェクトを返します。読み取り専用 [`ISlideShowTransition`](../islideshowtransition)。 |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | 上書きテーマ マネージャーを返します。読み取り専用 [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager)。 |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | アニメーション タイムライン オブジェクトを返します。読み取り専用 [`IAnimationTimeLine`](../ianimationtimeline)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | このスライドの有効なテーマを返します。 |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | 2 つの IBaseSlide インスタンスが等しいかどうかを判定します。返り値はスライドの構造と静的コンテンツに基づいて計算されます。すべてのシェイプ、スタイル、テキスト、アニメーションおよびその他の設定などが等しい場合、スライドは等しいとみなされます。比較では SlideId などの一意の識別子や、Date Placeholder の現在の日付値などの動的コンテンツは考慮されません。 |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | 指定された代替テキストを持つシェイプを最初に検索します。 |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | サムネイル画像オブジェクトを返します（実サイズの 20%）。 |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | サムネイル画像オブジェクトを返します。 |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | 指定されたパラメータでサムネイル TIFF 画像オブジェクトを返します。 |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | 指定されたサイズでサムネイル画像オブジェクトを返します。 |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | カスタムスケーリングでサムネイル画像オブジェクトを返します。 |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | 指定されたサイズでサムネイル画像オブジェクトを返します。 |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | カスタムスケーリングでサムネイル画像オブジェクトを返します。 |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | 特定の作者が追加したすべてのスライドコメントを返します。 |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | 適切なすべてのシェイプ内のすべての段落において、同じ書式設定のランを結合します。 |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | 適切なすべてのシェイプ内のすべての段落において、同じ書式設定のランを結合します。 |
| [Remove](../../aspose.slides/slide/remove)() | プレゼンテーションからスライドを削除します。 |
| [Reset](../../aspose.slides/slide/reset)() | LayoutSlide 上にプロトタイプがあるすべてのシェイプの位置、サイズ、書式設定をリセットします。 |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | スライドの内容を EMF ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | スライドの内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | スライドの内容を SVG ファイルとして保存します。 |

### 参照

* クラス [BaseSlide](../baseslide)
* インターフェイス [ISlide](../islide)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->