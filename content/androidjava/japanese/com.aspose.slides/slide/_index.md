---
title: Slide
second_title: Java API リファレンスを介した Android 用 Aspose.Slides
description: プレゼンテーション内のスライドを表します。
type: docs
url: /ja/com.aspose.slides/slide/
---
**継承:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**実装されているすべてのインターフェイス:**  
[com.aspose.slides.ISlide](../../com.aspose.slides/islide)  
```
public final class Slide extends BaseSlide implements ISlide
```

プレゼンテーション内のスライドを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | スライドの HeaderFooter マネージャーを返します。 |
| [getThemeManager()](#getThemeManager--) | オーバーライドされたテーママネージャーを返します。 |
| [getSlideNumber()](#getSlideNumber--) | スライドの番号を返します。 |
| [setSlideNumber(int value)](#setSlideNumber-int-) | スライドの番号を返します。 |
| [getHidden()](#getHidden--) | 指定されたスライドがスライドショー中に非表示かどうかを判定します。 |
| [setHidden(boolean value)](#setHidden-boolean-) | 指定されたスライドがスライドショー中に非表示かどうかを判定します。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | マスタースライド上のシェイプをスライドに表示するかどうかを指定します。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | マスタースライド上のシェイプをスライドに表示するかどうかを指定します。 |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | カスタムスケーリングされた Thumbnail Image オブジェクトを返します。 |
| [getImage()](#getImage--) | 実サイズの 20% の Thumbnail Image オブジェクトを返します。 |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | 指定サイズの Thumbnail Image オブジェクトを返します。 |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | 指定パラメータの Thumbnail tiff イメージオブジェクトを返します。 |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Thumbnail Image オブジェクトを返します。 |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | カスタムスケーリングされた Thumbnail Image オブジェクトを返します。 |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | 指定サイズの Thumbnail Image オブジェクトを返します。 |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | スライドのコンテンツを SVG ファイルとして保存します。 |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | スライドのコンテンツを SVG ファイルとして保存します。 |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | スライドのコンテンツを EMF ファイルとして保存します。 |
| [remove()](#remove--) | プレゼンテーションからスライドを削除します。 |
| [getLayoutSlide()](#getLayoutSlide--) | 現在のスライドのレイアウトスライドを取得または設定します。 |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | 現在のスライドのレイアウトスライドを取得または設定します。 |
| [reset()](#reset--) | LayoutSlide 上にプロトタイプを持つすべてのシェイプの位置、サイズ、書式設定をリセットします。 |
| [getNotesSlideManager()](#getNotesSlideManager--) | ノートスライドにアクセスし、追加および削除できるようにします。 |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | 特定の作成者が追加したすべてのスライドコメントを返します。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | すべての許容可能なシェイプ内のすべての段落で、同じ書式設定のランを結合します。 |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

スライドの HeaderFooter マネージャーを返します。読み取り専用 [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager).

**戻り値:**  
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

オーバーライドされたテーママネージャーを返します。読み取り専用 [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**戻り値:**  
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

スライドの番号を返します。[Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) コレクション内のスライドのインデックスは常に SlideNumber - Presentation.FirstSlideNumber と等しくなります。読み書き可能な int。

**戻り値:**  
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

スライドの番号を返します。[Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) コレクション内のスライドのインデックスは常に SlideNumber - Presentation.FirstSlideNumber と等しくなります。読み書き可能な int。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

指定されたスライドがスライドショー中に非表示かどうかを判定します。読み書き可能な boolean。

**戻り値:**  
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

指定されたスライドがスライドショー中に非表示かどうかを判定します。読み書き可能な boolean。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

マスタースライド上のシェイプをスライドに表示するかどうかを指定します。読み書き可能な boolean。

**戻り値:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

マスタースライド上のシェイプをスライドに表示するかどうかを指定します。読み書き可能な boolean。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

カスタムスケーリングされた Thumbnail Image オブジェクトを返します。

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // 最初のスライドにアクセス
>      ISlide sld = pres.getSlides().get_Item(0);
>      // フルスケールの画像を作成
>      IImage bmp = sld.getImage(1f, 1f);
>      // 画像を JPEG 形式でディスクに保存
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // プレゼンテーションの最初のスライドを Bitmap オブジェクトに変換
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // 画像を PNG 形式で保存
>      bmp.save("Slide_0.png", ImageFormat.Png);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.ppt");
>  try {
>      for (ISlide sld : pres.getSlides())
>      {
>          // フルスケールの画像を作成
>          IImage bmp = sld.getImage(1f, 1f);
>          // 画像を JPEG 形式でディスクに保存
>          bmp.save("Slide_"+sld.getSlideNumber()+"0.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint PPT/PPTX to JPG with customized dimensions.
>  
>  Presentation pres = new Presentation("PowerPoint-Presentation.pptx");
>  try {
>      // 寸法を定義
>      int desiredX = 1200;
>      int desiredY = 800;
>      // X と Y のスケール値を取得
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // フルスケールの画像を作成
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // 画像を JPEG 形式でディスクに保存
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| scaleX | float | このサムネイルを x 軸方向に拡大縮小する値。 |
| scaleY | float | このサムネイルを y 軸方向に拡大縮小する値。 |

**戻り値:**  
[IImage](../../com.aspose.slides/iimage) - IImage オブジェクト。

### getImage() {#getImage--}
```
public final IImage getImage()
```

実サイズの 20% の Thumbnail Image オブジェクトを返します。

**戻り値:**  
[IImage](../../com.aspose.slides/iimage)

### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public final IImage getImage(Size imageSize)
```

指定サイズの Thumbnail Image オブジェクトを返します。

--------------------

> ```
> カスタムサイズを使用してスライドを画像に変換する方法を示す例です（C# 使用）。
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // プレゼンテーションの最初のスライドを指定されたサイズの Bitmap に変換
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new com.aspose.slides.android.Size(1820, 1040));
>      // 画像を JPEG 形式で保存
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | 作成する画像のサイズ。 |

**戻り値:**  
[IImage](../../com.aspose.slides/iimage) - Image オブジェクト。

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

指定パラメータの Thumbnail tiff イメージオブジェクトを返します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff オプション。 |

**戻り値:**  
[IImage](../../com.aspose.slides/iimage) - Image オブジェクト。

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Thumbnail Image オブジェクトを返します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |

**戻り値:**  
[IImage](../../com.aspose.slides/iimage) - Image オブジェクト。

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

カスタムスケーリングされた Thumbnail Image オブジェクトを返します。

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // レンダリングオプションを作成
>      IRenderingOptions options = new RenderingOptions();
>      // ノートとコメントのレイアウトオプションを作成
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // ページ上のノートの位置を設定
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // ページ上のコメントの位置を設定
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // コメント出力領域の幅を設定
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // コメント領域の色を設定
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // レンダリングのレイアウトオプションを設定
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // プレゼンテーションの最初のスライドを android.graphics.Bitmap オブジェクトに変換
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // 画像を GIF 形式で保存
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |
| scaleX | float | このサムネイルを x 軸方向に拡大縮小する値。 |
| scaleY | float | このサムネイルを y 軸方向に拡大縮小する値。 |

**戻り値:**  
[IImage](../../com.aspose.slides/iimage) - Bitmap オブジェクト。

### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public final IImage getImage(IRenderingOptions options, Size imageSize)
```

指定サイズの Thumbnail Image オブジェクトを返します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |
| imageSize | [Size](../../com.aspose.slides.android/size) | 作成する画像のサイズ。 |

**戻り値:**  
[IImage](../../com.aspose.slides/iimage) - Image オブジェクト。

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

スライドのコンテンツを SVG ファイルとして保存します。

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.svg");
>      {
>          // 最初のスライドを SVG ファイルとして保存します
>          pres.getSlides().get_Item(0).writeAsSvg(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 対象ストリーム |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

スライドのコンテンツを SVG ファイルとして保存します。

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into an SVG file with options.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide1.svg");
>      SVGOptions options = new SVGOptions();
>      options.setVectorizeText(true);
>      // 最初のスライドを SVG ファイルとして保存します
>      pres.getSlides().get_Item(0).writeAsSvg(fileStream, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 対象ストリーム |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 生成オプション |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

スライドのコンテンツを EMF ファイルとして保存します。

--------------------

> ```
> The following code example demonstrates how to convert the first slide from a PowerPoint presentation into a metafile.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      FileOutputStream fileStream = new FileOutputStream("slide_1.emf");
>      {
>          // 最初のスライドをメタファイルとして保存します
>          pres.getSlides().get_Item(0).writeAsEmf(fileStream);
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 対象ストリーム |

### remove() {#remove--}
```
public final void remove()
```

プレゼンテーションからスライドを削除します。

### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

現在のスライドのレイアウトスライドを取得または設定します。読み書き可能な [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**戻り値:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

現在のスライドのレイアウトスライドを取得または設定します。読み書き可能な [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### reset() {#reset--}
```
public final void reset()
```

LayoutSlide 上にプロトタイプを持つすべてのシェイプの位置、サイズ、書式設定をリセットします。

### getNotesSlideManager() {#getNotesSlideManager--}
```
public final INotesSlideManager getNotesSlideManager()
```

ノートスライドにアクセスし、追加および削除できるようにします。読み取り専用 [INotesSlideManager](../../com.aspose.slides/inotesslidemanager)。

**戻り値:**  
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

特定の作成者が追加したすべてのスライドコメントを返します。

**パラメーター:**  
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | 検索するコメントの作成者、またはすべてのコメントを返す場合は null。 |

**戻り値:**  
com.aspose.slides.IComment[] - [Comment](../../com.aspose.slides/comment) の配列。

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

すべての許容可能なシェイプ内のすべての段落で、同じ書式設定のランを結合します。