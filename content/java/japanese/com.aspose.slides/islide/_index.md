---
title: ISlide
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーション内のスライドを表します。
type: docs
url: /ja/com.aspose.slides/islide/
---
**実装されているすべてのインターフェイス:**  
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ISlide extends IBaseSlide, IOverrideThemeable
```

プレゼンテーション内のスライドを表します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | スライドの HeaderFooter マネージャーを返します。 |
| [getSlideNumber()](#getSlideNumber--) | スライドの番号を返します。 |
| [setSlideNumber(int value)](#setSlideNumber-int-) | スライドの番号を返します。 |
| [getHidden()](#getHidden--) | 指定されたスライドがスライドショー中に非表示かどうかを判定します。 |
| [setHidden(boolean value)](#setHidden-boolean-) | 指定されたスライドがスライドショー中に非表示かどうかを判定します。 |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | カスタムスケーリングされた画像オブジェクトを返します。 |
| [getImage()](#getImage--) | サムネイル画像オブジェクト（実サイズの 20%）を返します。 |
| [getImage(Dimension imageSize)](#getImage-java.awt.Dimension-) | 指定サイズの画像オブジェクトを返します。 |
| [getImage(ITiffOptions options)](#getImage-com.aspose.slides.ITiffOptions-) | 指定されたパラメータでサムネイル TIFF ビットマップオブジェクトを返します。 |
| [getImage(IRenderingOptions options)](#getImage-com.aspose.slides.IRenderingOptions-) | サムネイルビットマップオブジェクトを返します。 |
| [getImage(IRenderingOptions options, float scaleX, float scaleY)](#getImage-com.aspose.slides.IRenderingOptions-float-float-) | カスタムスケーリングされたサムネイルビットマップオブジェクトを返します。 |
| [getImage(IRenderingOptions options, Dimension imageSize)](#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-) | 指定サイズのサムネイルビットマップオブジェクトを返します。 |
| [getLayoutSlide()](#getLayoutSlide--) | 現在のスライドのレイアウトスライドを取得または設定します。 |
| [setLayoutSlide(ILayoutSlide value)](#setLayoutSlide-com.aspose.slides.ILayoutSlide-) | 現在のスライドのレイアウトスライドを取得または設定します。 |
| [getNotesSlideManager()](#getNotesSlideManager--) | ノートスライドへのアクセス、追加および削除を可能にします。 |
| [getSlideComments(ICommentAuthor author)](#getSlideComments-com.aspose.slides.ICommentAuthor-) | 特定の作成者によって追加されたすべてのスライドコメントを返します。 |
| [writeAsSvg(OutputStream stream)](#writeAsSvg-java.io.OutputStream-) | スライドの内容を SVG ファイルとして保存します。 |
| [writeAsSvg(OutputStream stream, ISVGOptions svgOptions)](#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-) | スライドの内容を SVG ファイルとして保存します。 |
| [writeAsEmf(OutputStream stream)](#writeAsEmf-java.io.OutputStream-) | スライドの内容を EMF ファイルとして保存します。 |
| [remove()](#remove--) | プレゼンテーションからスライドを削除します。 |
| [reset()](#reset--) | LayoutSlide にプロトタイプを持つすべてのシェイプの位置、サイズ、書式設定をリセットします。 |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ISlideHeaderFooterManager getHeaderFooterManager()
```

スライドの HeaderFooter マネージャーを返します。読み取り専用 [ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)。

**返り値:**
[ISlideHeaderFooterManager](../../com.aspose.slides/islideheaderfootermanager)

### getSlideNumber() {#getSlideNumber--}
```
public abstract int getSlideNumber()
```

スライドの番号を返します。[IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) コレクション内のスライドのインデックスは常に SlideNumber - 1 と等しいです。読み取り/書き込み可能な int。

**返り値:**
int

### setSlideNumber(int value) {#setSlideNumber-int-}
```
public abstract void setSlideNumber(int value)
```

スライドの番号を返します。[IPresentation.getSlides](../../com.aspose.slides/ipresentation\#getSlides) コレクション内のスライドのインデックスは常に SlideNumber - 1 と等しいです。読み取り/書き込み可能な int。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getHidden() {#getHidden--}
```
public abstract boolean getHidden()
```

指定されたスライドがスライドショー中に非表示かどうかを判定します。読み取り/書き込み可能な boolean。

**返り値:**
boolean

### setHidden(boolean value) {#setHidden-boolean-}
```
public abstract void setHidden(boolean value)
```

指定されたスライドがスライドショー中に非表示かどうかを判定します。読み取り/書き込み可能な boolean。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```

カスタムスケーリングした画像オブジェクトを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| scaleX | float | このサムネイルを x 軸方向に拡大縮小する値。 |
| scaleY | float | このサムネイルを y 軸方向に拡大縮小する値。 |

**返り値:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage

### getImage() {#getImage--}
```
public abstract IImage getImage()
```

サムネイル画像オブジェクト（実サイズの 20%）を返します。

**返り値:**
[IImage](../../com.aspose.slides/iimage) - Image object java.awt.image.BufferedImage

### getImage(Dimension imageSize) {#getImage-java.awt.Dimension-}
```
public abstract IImage getImage(Dimension imageSize)
```

指定サイズの画像オブジェクトを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| imageSize | java.awt.Dimension | 作成する画像のサイズ。 |

**返り値:**
[IImage](../../com.aspose.slides/iimage) - Bitmap object.

### getImage(ITiffOptions options) {#getImage-com.aspose.slides.ITiffOptions-}
```
public abstract IImage getImage(ITiffOptions options)
```

指定されたパラメータでサムネイル TIFF ビットマップオブジェクトを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | [ITiffOptions](../../com.aspose.slides/itiffoptions) | Tiff オプション。 |

**返り値:**
[IImage](../../com.aspose.slides/iimage) - Image object.

### getImage(IRenderingOptions options) {#getImage-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage getImage(IRenderingOptions options)
```

サムネイル Bitmap オブジェクトを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |

**返り値:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, float scaleX, float scaleY) {#getImage-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage getImage(IRenderingOptions options, float scaleX, float scaleY)
```

カスタムスケーリングされたサムネイル Bitmap オブジェクトを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |
| scaleX | float | このサムネイルを x 軸方向に拡大縮小する値。 |
| scaleY | float | このサムネイルを y 軸方向に拡大縮小する値。 |

**返り値:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getImage(IRenderingOptions options, Dimension imageSize) {#getImage-com.aspose.slides.IRenderingOptions-java.awt.Dimension-}
```
public abstract IImage getImage(IRenderingOptions options, Dimension imageSize)
```

指定サイズのサムネイル Bitmap オブジェクトを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | レンダリングオプション。 |
| imageSize | java.awt.Dimension | 作成する画像のサイズ。 |

**返り値:**
[IImage](../../com.aspose.slides/iimage) - Bitmap objects.

### getLayoutSlide() {#getLayoutSlide--}
```
public abstract ILayoutSlide getLayoutSlide()
```

現在のスライドのレイアウトスライドを取得または設定します。読み取り/書き込み可能な [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**返り値:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)

### setLayoutSlide(ILayoutSlide value) {#setLayoutSlide-com.aspose.slides.ILayoutSlide-}
```
public abstract void setLayoutSlide(ILayoutSlide value)
```

現在のスライドのレイアウトスライドを取得または設定します。読み取り/書き込み可能な [ILayoutSlide](../../com.aspose.slides/ilayoutslide)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) |  |

### getNotesSlideManager() {#getNotesSlideManager--}
```
public abstract INotesSlideManager getNotesSlideManager()
```

ノートスライドへのアクセス、追加および削除を可能にします。読み取り専用 [INotesSlideManager](../../com.aspose.slides/inotesslidemanager)。

**返り値:**
[INotesSlideManager](../../com.aspose.slides/inotesslidemanager)

### getSlideComments(ICommentAuthor author) {#getSlideComments-com.aspose.slides.ICommentAuthor-}
```
public abstract IComment[] getSlideComments(ICommentAuthor author)
```

特定の作成者が追加したすべてのスライドコメントを返します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| author | [ICommentAuthor](../../com.aspose.slides/icommentauthor) | 検索するコメントの作成者、またはすべてのコメントを返す場合は null。 |

**返り値:**
com.aspose.slides.IComment[] - [IComment](../../com.aspose.slides/icomment) の配列。

### writeAsSvg(OutputStream stream) {#writeAsSvg-java.io.OutputStream-}
```
public abstract void writeAsSvg(OutputStream stream)
```

スライドの内容を SVG ファイルとして保存します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 対象ストリーム |

### writeAsSvg(OutputStream stream, ISVGOptions svgOptions) {#writeAsSvg-java.io.OutputStream-com.aspose.slides.ISVGOptions-}
```
public abstract void writeAsSvg(OutputStream stream, ISVGOptions svgOptions)
```

スライドの内容を SVG ファイルとして保存します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | java.io.OutputStream | 対象ストリーム |
| svgOptions | [ISVGOptions](../../com.aspose.slides/isvgoptions) | SVG 生成オプション |

### writeAsEmf(OutputStream stream) {#writeAsEmf-java.io.OutputStream-}
```
public abstract void writeAsEmf(OutputStream stream)
```

スライドの内容を EMF ファイルとして保存します。

**パラメーター:**
| パラメーター | 型 | 説明 |
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

LayoutSlide にプロトタイプを持つすべてのシェイプの位置、サイズ、書式設定をリセットします。