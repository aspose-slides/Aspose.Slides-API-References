---
title: Slide
second_title: Aspose.Sildes の .NET 用 API リファレンス
description: プレゼンテーション内のスライドを表します。
type: docs
weight: 9980
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
| [CustomData](../../aspose.slides/baseslide/customdata) { get; } | スライドのカスタム データを返します。読み取り専用 [`ICustomData`](../icustomdata)。 |
| [HeaderFooterManager](../../aspose.slides/slide/headerfootermanager) { get; } | スライドの HeaderFooter マネージャーを返します。読み取り専用 [`ISlideHeaderFooterManager`](../islideheaderfootermanager)。 |
| [Hidden](../../aspose.slides/slide/hidden) { get; set; } | スライドショー中に指定されたスライドが非表示かどうかを決定します。読み書き可能な Boolean。 |
| [HyperlinkQueries](../../aspose.slides/baseslide/hyperlinkqueries) { get; } | 含まれるハイパーリンクへの簡単なアクセスを提供します。読み取り専用 [`IHyperlinkQueries`](../ihyperlinkqueries)。 |
| [LayoutSlide](../../aspose.slides/slide/layoutslide) { get; set; } | 現在のスライドのレイアウト スライドを取得または設定します。読み書き可能な [`ILayoutSlide`](../ilayoutslide)。 |
| virtual [Name](../../aspose.slides/baseslide/name) { get; set; } | スライドの名前を取得または設定します。読み書き可能な String。 |
| [NotesSlideManager](../../aspose.slides/slide/notesslidemanager) { get; } | ノート スライドにアクセスし、追加および削除できます。読み取り専用 [`INotesSlideManager`](../inotesslidemanager)。 |
| [Presentation](../../aspose.slides/baseslide/presentation) { get; } | IPresentation インターフェイスを返します。読み取り専用 [`IPresentation`](../ipresentation)。 |
| [Shapes](../../aspose.slides/baseslide/shapes) { get; } | スライドのシェイプを返します。読み取り専用 [`IShapeCollection`](../ishapecollection)。 |
| override [ShowMasterShapes](../../aspose.slides/slide/showmastershapes) { get; set; } | マスタースライド上のシェイプをスライドに表示するかどうかを指定します。読み書き可能な Boolean。 |
| [SlideId](../../aspose.slides/baseslide/slideid) { get; } | スライドの ID を返します。読み取り専用 UInt32。 |
| [SlideNumber](../../aspose.slides/slide/slidenumber) { get; set; } | スライドの番号を返します。[`Slides`](../presentation/slides) コレクション内のスライドインデックスは常に SlideNumber - Presentation.FirstSlideNumber と等しくなります。読み書き可能な Int32。 |
| virtual [SlideShowTransition](../../aspose.slides/baseslide/slideshowtransition) { get; } | 指定されたスライドがスライドショー中にどのように進むかに関する情報を含む Transition オブジェクトを返します。読み取り専用 [`ISlideShowTransition`](../islideshowtransition)。 |
| [ThemeManager](../../aspose.slides/slide/thememanager) { get; } | オーバーライドテーママネージャーを返します。読み取り専用 [`IOverrideThemeManager`](../../aspose.slides.theme/ioverridethememanager)。 |
| [Timeline](../../aspose.slides/baseslide/timeline) { get; } | アニメーション タイムライン オブジェクトを返します。読み取り専用 [`IAnimationTimeLine`](../ianimationtimeline)。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [CreateThemeEffective](../../aspose.slides/baseslide/createthemeeffective)() | このスライドの実効テーマを返します。 |
| [Equals](../../aspose.slides/baseslide/equals)(IBaseSlide) | 2 つの IBaseSlide インスタンスが等しいかどうかを判定します。返される値はスライドの構造と静的コンテンツに基づいて計算されます。すべてのシェイプ、スタイル、テキスト、アニメーションおよびその他の設定等が等しい場合、スライドは等しいとみなされます。比較では SlideId などの一意識別子や、日付プレースホルダーの現在の日付値などの動的コンテンツは考慮されません。 |
| [FindShapeByAltText](../../aspose.slides/baseslide/findshapebyalttext)(string) | 指定された代替テキストを持つシェイプの最初の出現を検索します。 |
| [GetImage](../../aspose.slides/slide/getimage#getimage)() | 実サイズの 20% のサムネイル画像オブジェクトを返します。 |
| [GetImage](../../aspose.slides/slide/getimage#getimage_1)(IRenderingOptions) | サムネイル画像オブジェクトを返します。 |
| [GetImage](../../aspose.slides/slide/getimage#getimage_4)(ITiffOptions) | 指定されたパラメーターでサムネイル TIFF 画像オブジェクトを返します。 |
| [GetImage](../../aspose.slides/slide/getimage#getimage_6)(Size) | 指定されたサイズのサムネイル画像オブジェクトを返します。 |
| [GetImage](../../aspose.slides/slide/getimage#getimage_5)(float, float) | カスタムスケーリングでサムネイル画像オブジェクトを返します。 |
| [GetImage](../../aspose.slides/slide/getimage#getimage_3)(IRenderingOptions, Size) | 指定されたサイズのサムネイル画像オブジェクトを返します。 |
| [GetImage](../../aspose.slides/slide/getimage#getimage_2)(IRenderingOptions, float, float) | カスタムスケーリングでサムネイル画像オブジェクトを返します。 |
| [GetSlideComments](../../aspose.slides/slide/getslidecomments)(ICommentAuthor) | 特定の作者が追加したすべてのスライドコメントを返します。 |
| override [JoinPortionsWithSameFormatting](../../aspose.slides/slide/joinportionswithsameformatting#joinportionswithsameformatting)() | すべての許容可能なシェイプのすべての段落において、同じ書式のランを結合します。 |
| virtual [JoinPortionsWithSameFormatting](../../aspose.slides/baseslide/joinportionswithsameformatting)(IShapeCollection) | すべての許容可能なシェイプのすべての段落において、同じ書式のランを結合します。 |
| [Remove](../../aspose.slides/slide/remove)() | プレゼンテーションからスライドを削除します。 |
| [Reset](../../aspose.slides/slide/reset)() | LayoutSlide にプロトタイプがあるすべてのシェイプの位置、サイズ、書式設定をリセットします。 |
| [WriteAsEmf](../../aspose.slides/slide/writeasemf)(Stream) | スライドの内容を EMF ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg)(Stream) | スライドの内容を SVG ファイルとして保存します。 |
| [WriteAsSvg](../../aspose.slides/slide/writeassvg#writeassvg_1)(Stream, ISVGOptions) | スライドの内容を SVG ファイルとして保存します。 |

### 参照

* クラス [BaseSlide](../baseslide)
* インターフェイス [ISlide](../islide)
* 名前空間 [Aspose.Slides](../../aspose.slides)
* アセンブリ [Aspose.Slides](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Slides.dll -->