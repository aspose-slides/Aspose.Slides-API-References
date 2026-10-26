---
title: Slide
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーション内のスライドを表します。
type: docs
url: /ja/com.aspose.slides/slide/
---
**継承:** [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

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
| [getThemeManager()](#getThemeManager--) | 上書き theme manager を返します。 |
| [getSlideNumber()](#getSlideNumber--) | スライドの番号を返します。 |
| [setSlideNumber(int value)](#setSlideNumber-int-) | スライドの番号を返します。 |
| [getHidden()](#getHidden--) | スライドショー中に指定されたスライドが非表示かどうかを判定します。 |
| [setHidden(boolean value)](#setHidden-boolean-) | スライドショー中に指定されたスライドが非表示かどうかを判定します。 |
| [getShowMasterShapes()](#getShowMasterShapes--) | マスタースライド上のシェイプをスライドに表示するかどうかを指定します。 |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | マスタースライド上のシェイプをスライドに表示するかどうかを指定します。 |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | カスタムスケーリングで Thumbnail Image オブジェクトを返します。 |
| [getImage()](#getImage--) | Thumbnail Image オブジェクト（実サイズの20%）を返します。 |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | 指定サイズの Thumbnail Image オブジェクトを返します。 |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | 指定されたパラメータで Thumbnail tiff image オブジェクトを返します。 |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | Thumbnail Image オブジェクトを返します。 |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | カスタムスケーリングで Thumbnail Image オブジェクトを返します。 |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | 指定サイズの Thumbnail Image オブジェクトを返します。 |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | スライドコンテンツを SVG ファイルとして保存します。 |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | スライドコンテンツを SVG ファイルとして保存します。 |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | スライドコンテンツを EMF ファイルとして保存します。 |
| [remove()](#remove--) | プレゼンテーションからスライドを削除します。 |
| [getLayoutSlide()](#getLayoutSlide--) | 現在のスライドのレイアウトスライドを取得または設定します。 |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | 現在のスライドのレイアウトスライドを取得または設定します。 |
| [reset()](#reset--) | LayoutSlide 上にプロトタイプを持つすべてのシェイプの位置、サイズ、書式設定をリセットします。 |
| [getNotesSlideManager()](#getNotesSlideManager--) | ノートスライドにアクセスし、追加・削除できます。 |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | 特定の作者が追加したすべてのスライドコメントを取得します。 |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | すべての許容可能なシェイプ内のすべての段落で、書式が同じランを結合します。 |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ISlideHeaderFooterManager getHeaderFooterManager()
```

スライドの HeaderFooter マネージャーを返します。**読み取り専用** [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)。

**戻り値:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

上書き theme manager を返します。**読み取り専用** [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)。

**戻り値:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getSlideNumber() {#getSlideNumber--}
```
public final int getSlideNumber()
```

スライドの番号を返します。[Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) コレクション内のインデックスは常に SlideNumber - Presentation.FirstSlideNumber と等しいです。**読み書き可能** int。

**戻り値:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public final void setSlideNumber(int value)
```

スライドの番号を設定します。[Presentation.getSlides](../../com.aspose.slides/presentation\#getSlides) コレクション内のインデックスは常に SlideNumber - Presentation.FirstSlideNumber と等しいです。**読み書き可能** int。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public final boolean getHidden()
```

スライドショー中に指定されたスライドが非表示かどうかを判定します。**読み書き可能** boolean。

**戻り値:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public final void setHidden(boolean value)
```

スライドショー中に指定されたスライドが非表示かどうかを設定します。**読み書き可能** boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

マスタースライド上のシェイプをスライドに表示するかどうかを指定します。**読み書き可能** boolean。

**戻り値:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

マスタースライド上のシェイプをスライドに表示するかどうかを設定します。**読み書き可能** boolean。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

カスタムスケーリングで Thumbnail Image オブジェクトを返します。

--------------------

> ```
> The following example shows how to generate thumbnails from PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("ThumbnailFromSlide.pptx");
>  try {
>      // Access the first slide
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Create a full scale image
>      IImage bmp = sld.getImage(1f, 1f);
>      // Save the image to disk in JPEG format
>      bmp.save("Thumbnail_out.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
>  
>  The following example shows how to converting slides to bitmap and saving the images in PNG.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // Converts the first slide in the presentation to a Bitmap object
>      IImage bmp = pres.getSlides().get_Item(0).getImage();
>      // Saves the image in the PNG format
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
>          // Create a full scale image
>          IImage bmp = sld.getImage(1f, 1f);
>          // Save the image to disk in JPEG format
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
>      // Define dimensions
>      int desiredX = 1200;
>      int desiredY = 800;
>      // Get scaled values of X and Y
>      float ScaleX = (float)(1.0 / pres.getSlideSize().getSize().getWidth()) * desiredX;
>      float ScaleY = (float)(1.0 / pres.getSlideSize().getSize().getHeight()) * desiredY;
>      for (ISlide sld : pres.getSlides())
>      {
>          // Create a full scale image
>          IImage bmp = sld.getImage(ScaleX, ScaleY);
>          // Save the image to disk in JPEG format
>          bmp.save("Slide.jpg", ImageFormat.Jpeg);
>      }
>  } finally {
>      pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| scaleX | float | X 軸方向のスケール値。 |
| scaleY | float | Y 軸方向のスケール値。 |

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - IImage オブジェクト。

### getImage() {#getImage--}
```
public final IImage getImage()
```

Thumbnail Image オブジェクト（実サイズの20%）を返します。

**戻り値:**
[IImage](../../com.aspose.slides/iimage)

### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public final IImage getImage(Dimension imageSize)
```

指定サイズの Thumbnail Image オブジェクトを返します。

--------------------

> ```
> The following example shows how to converting slides to images with custom sizes using C#.
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      // プレゼンテーションの最初のスライドを指定されたサイズの Bitmap に変換します
>      IImage bmp = pres.getSlides().get_Item(0).getImage(new Dimension(1820, 1040));
>      // 画像を JPEG 形式で保存します
>      bmp.save("Slide_0.jpg", ImageFormat.Jpeg);
>  } finally {
>      pres.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| imageSize | java.awt.Dimension | 作成する画像のサイズ。 |

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - Image オブジェクト。

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public final IImage getImage(ITiffOptions options)
```

指定されたパラメータで Thumbnail tiff image オブジェクトを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff オプション。 |

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - Image オブジェクト。

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public final IImage getImage(IRenderingOptions options)
```

Thumbnail Image オブジェクトを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - Image オブジェクト。

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public final IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

カスタムスケーリングで Thumbnail Image オブジェクトを返します。

--------------------

> ```
> The following example shows how to converting slides With notes and comments to Images.
>  
>  Presentation pres = new Presentation("PresentationNotesComments.pptx");
>  try {
>      // Create the rendering options
>      IRenderingOptions options = new RenderingOptions();
>      // Create notes and comments layouting options
>      NotesCommentsLayoutingOptions notesCommentsLayouting = new NotesCommentsLayoutingOptions();
>      // Sets the position of the notes on the page
>      notesCommentsLayouting.setNotesPosition(NotesPositions.BottomTruncated);
>      // Sets the position of the comments on the page
>      notesCommentsLayouting.setCommentsPosition(CommentsPositions.Right);
>      // Sets the width of the comment output area
>      notesCommentsLayouting.setCommentsAreaWidth(500);
>      // Sets the color for the comments area
>      notesCommentsLayouting.setCommentsAreaColor(Color.WHITE);
>      // Set layout options for rendering
>      options.setSlidesLayoutOptions(notesCommentsLayouting);
>      // Converts the first slide of the presentation to a BufferedImage object
>      IImage image = pres.getSlides().get_Item(0).getImage(options, 2f, 2f);
>      // Saves the image in the GIF format
>      image.save("Slide_Notes_Comments_0.gif", ImageFormat.Gif);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |
| scaleX | float | X 軸方向のスケール値。 |
| scaleY | float | Y 軸方向のスケール値。 |

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - Bitmap オブジェクト。

### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public final IImage getImage(IRenderingOptions options, Dimension imageSize)
```

指定サイズの Thumbnail Image オブジェクトを返します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |
| imageSize | java.awt.Dimension | 作成する画像のサイズ。 |

**戻り値:**
[IImage](../../com.aspose.slides/iimage) - Image オブジェクト。

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public final void writeAsSvg(OutputStream stream)
```

スライドコンテンツを SVG ファイルとして保存します。

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


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | ターゲットストリーム |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public final void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

スライドコンテンツを SVG ファイルとして保存します。

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


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | ターゲットストリーム |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 生成オプション |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public final void writeAsEmf(OutputStream stream)
```

スライドコンテンツを EMF ファイルとして保存します。

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


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | ターゲットストリーム |

### remove() {#remove--}
```
public final void remove()
```

プレゼンテーションからスライドを削除します。

### getLayoutSlide() {#getLayoutSlide--}
```
public final ILayoutSlide getLayoutSlide()
```

現在のスライドのレイアウトスライドを取得または設定します。**読み書き可能** [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**戻り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public final void setLayoutSlide(ILayoutSlide value)
```

現在のスライドのレイアウトスライドを設定します。**読み書き可能** [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**パラメータ:**
| パラメータ | 型 | 説明 |
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

ノートスライドにアクセスし、追加・削除できます。**読み取り専用** [INotesSlideManager](../../com.aspose.slides/inotesslidemanager)。

**戻り値:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public final IComment[] getSlideComments(ICommentAuthor author)
```

特定の作者が追加したすべてのスライドコメントを取得します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | コメントを検索する作者、またはすべてのコメントを取得する場合は null。 |

**戻り値:**
com.aspose.slides.IComment[] - [Comment](../../com.aspose.slides/comment) の配列。

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

すべての許容可能なシェイプ内のすべての段落で、書式が同じランを結合します。