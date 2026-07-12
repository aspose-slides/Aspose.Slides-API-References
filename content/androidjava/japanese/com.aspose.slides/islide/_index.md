---
title: ISlide
second_title: Java API リファレンスを使用した Android 用 Aspose.Slides
description: プレゼンテーション内のスライドを表します。
type: docs
url: /ja/com.aspose.slides/islide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

プレゼンテーション内のスライドを表します。

## Methods

| Method | Description |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | スライドの HeaderFooter マネージャーを取得します。 |
| [getSlideNumber()](#getSlideNumber--) | スライド番号を取得します。 |
| [setSlideNumber(int value)](#setSlideNumber-int-) | スライド番号を取得します。 |
| [getHidden()](#getHidden--) | スライドショー中に指定されたスライドが非表示かどうかを判定します。 |
| [setHidden(boolean value)](#setHidden-boolean-) | スライドショー中に指定されたスライドが非表示かどうかを判定します。 |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | カスタムスケーリングを使用した画像オブジェクトを取得します。 |
| [getImage()](#getImage--) | 実サイズの 20% のサムネイル画像オブジェクトを取得します。 |
| [getImage(Size imageSize)](#getImage-com.aspose.slides.android.Size-) | 指定したサイズの画像オブジェクトを取得します。 |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | 指定したパラメータでサムネイル TIFF ビットマップオブジェクトを取得します。 |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | サムネイルビットマップオブジェクトを取得します。 |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | カスタムスケーリングを使用したサムネイルビットマップオブジェクトを取得します。 |
| [getImage(IRenderingOptions options, Size imageSize)](#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | 指定したサイズのサムネイルビットマップオブジェクトを取得します。 |
| [getLayoutSlide()](#getLayoutSlide--) | 現在のスライドのレイアウトスライドを取得または設定します。 |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | 現在のスライドのレイアウトスライドを取得または設定します。 |
| [getNotesSlideManager()](#getNotesSlideManager--) | ノートスライドにアクセスし、追加および削除できるようにします。 |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | 特定の作成者が追加したすべてのスライドコメントを取得します。 |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | スライドの内容を SVG ファイルとして保存します。 |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | スライドの内容を SVG ファイルとして保存します。 |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | スライドの内容を EMF ファイルとして保存します。 |
| [remove()](#remove--) | プレゼンテーションからスライドを削除します。 |
| [reset()](#reset--) | LayoutSlide 上のプロトタイプを持つすべてのシェイプの位置、サイズ、書式設定をリセットします。 |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

スライドの HeaderFooter マネージャーを取得します。読み取り専用 [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)。

**Returns:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

スライド番号を取得します。[IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) コレクション内のインデックスは常に SlideNumber - 1 に等しいです。読み書き int。

**Returns:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

スライド番号を設定します。[IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) コレクション内のインデックスは常に SlideNumber - 1 に等しいです。読み書き int。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

スライドショー中に指定されたスライドが非表示かどうかを判定します。読み書き boolean。

**Returns:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

スライドショー中に指定されたスライドが非表示かどうかを設定します。読み書き boolean。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

カスタムスケーリングを使用した画像オブジェクトを取得します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| scaleX | float | X 軸方向にこのサムネイルを拡大縮小する値。 |
| scaleY | float | Y 軸方向にこのサムネイルを拡大縮小する値。 |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

実サイズの 20% のサムネイル画像オブジェクトを取得します。

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Image object android.graphics.Bitmap

### getImage(Size imageSize) {#getImage-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(Size imageSize)
```

指定したサイズの画像オブジェクトを取得します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| imageSize | [Size](../../com.aspose.slides.android/size) | 作成する画像のサイズ。 |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

指定したパラメータでサムネイル TIFF ビットマップオブジェクトを取得します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | TIFF オプション。 |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

サムネイルビットマップオブジェクトを取得します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

カスタムスケーリングを使用したサムネイルビットマップオブジェクトを取得します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |
| scaleX | float | X 軸方向にこのサムネイルを拡大縮小する値。 |
| scaleY | float | Y 軸方向にこのサムネイルを拡大縮小する値。 |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, Size imageSize) {#getImage-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage getImage(IRenderingOptions options, Size imageSize)
```

指定したサイズのサムネイルビットマップオブジェクトを取得します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |
| imageSize | [Size](../../com.aspose.slides.android/size) | 作成する画像のサイズ。 |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

現在のスライドのレイアウトスライドを取得または設定します。読み書き [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

現在のスライドのレイアウトスライドを設定します。読み書き [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

ノートスライドにアクセスし、追加および削除できるようにします。読み取り専用 [INotesSlideManager](../../com.aspose.slides/inotesslidemanager)。

**Returns:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

特定の作成者が追加したすべてのスライドコメントを取得します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | コメントの作成者（すべてのコメントを取得する場合は null）。 |

**Returns:**
com.aspose.slides.IComment[] - Array of [IComment](../../com.aspose.slides/icomment).

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

スライドの内容を SVG ファイルとして保存します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 対象ストリーム |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

スライドの内容を SVG ファイルとして保存します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 対象ストリーム |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 生成オプション |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

スライドの内容を EMF ファイルとして保存します。

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | 対象ストリーム |

### remove() {#remove--}
```
public abstract void remove()
```

プレゼンテーションからスライドを削除します。

### reset() {#reset--}
```
public abstract void reset()
```

LayoutSlide 上のプロトタイプを持つすべてのシェイプの位置、サイズ、書式設定をリセットします。