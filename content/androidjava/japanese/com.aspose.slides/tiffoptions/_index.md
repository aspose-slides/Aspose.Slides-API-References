---
title: TiffOptions
second_title: Aspose.Slides for Android の Java API リファレンス
description: プレゼンテーションをTIFF形式で保存する方法を制御するオプションを提供します。
type: docs
url: /ja/com.aspose.slides/tiffoptions/
---
**継承:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ITiffOptions](../../com.aspose.slides/itiffoptions)
```
public class TiffOptions extends SaveOptions implements ITiffOptions
```

Provides options that control how a presentation is saved in TIFF format.

--------------------

> ```
> The following example shows how to convert PowerPoint to TIFF with default size.
>  
>  // プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化します
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      // プレゼンテーションを TIFF ドキュメントとして保存します
>      pres.save("Tiffoutput_out.tiff", SaveFormat.Tiff);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom size.
>  
>  // プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化します
>  Presentation pres = new Presentation("Convert_Tiff_Custom.pptx");
>  try {
>      // TiffOptions クラスをインスタンス化します
>      TiffOptions opts = new TiffOptions();
>      // 圧縮タイプを設定します
>      opts.setCompressionType(TiffCompressionTypes.Default);
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setNotesPosition(NotesPositions.BottomFull);
>      opts.setSlidesLayoutOptions(notesOptions);
>      // 圧縮タイプ
>      // Default - デフォルトの圧縮方式 (LZW) を指定します。
>      // None - 圧縮なしを指定します。
>      // CCITT3
>      // CCITT4
>      // LZW
>      // RLE
>      // 深度は圧縮タイプに依存し、手動で設定できません。
>      // 解像度単位は常に 2（ドット/インチ）です。
>      // 画像 DPI を設定します
>      opts.setDpiX(200);
>      opts.setDpiY(100);
>      // 画像サイズを設定します
>      opts.setImageSize(new com.aspose.slides.android.Size(1728, 1078));
>      // 指定した画像サイズでプレゼンテーションを TIFF に保存します
>      pres.save("TiffWithCustomSize_out.tiff", SaveFormat.Tiff, opts);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to convert PowerPoint to TIFF with custom image pixel format.
>  
>  // プレゼンテーション ファイルを表す Presentation オブジェクトをインスタンス化します
>  Presentation pres = new Presentation("DemoFile.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      options.setPixelFormat(ImagePixelFormat.Format8bppIndexed);
> 
>      //ImagePixelFormat には以下の値が含まれます（ドキュメント参照）：
>      //Format1bppIndexed; // 1 ビット/ピクセル、インデックス付き。
>      //Format4bppIndexed; // 4 ビット/ピクセル、インデックス付き。
>      //Format8bppIndexed; // 8 ビット/ピクセル、インデックス付き。
>      //Format24bppRgb; // 24 ビット/ピクセル、RGB。
>      //Format32bppArgb; // 32 ビット/ピクセル、ARGB。
> 
>      // 指定した画像サイズでプレゼンテーションを TIFF に保存します
>      pres.save("Tiff_With_Custom_Image_Pixel_Format_out.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TiffOptions()](#TiffOptions--) | デフォルトコンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getInkOptions()](#getInkOptions--) | エクスポートされたドキュメント内のインクオブジェクトの外観を制御するオプションを提供します。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [getImageSize()](#getImageSize--) | 生成されたTIFF画像のサイズを指定します。 |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | 生成されたTIFF画像のサイズを指定します。 |
| [getDpiX()](#getDpiX--) | 水平解像度（インチあたりのドット数）を指定します。 |
| [setDpiX(long value)](#setDpiX-long-) | 水平解像度（インチあたりのドット数）を指定します。 |
| [getDpiY()](#getDpiY--) | 垂直解像度（インチあたりのドット数）を指定します。 |
| [setDpiY(long value)](#setDpiY-long-) | 垂直解像度（インチあたりのドット数）を指定します。 |
| [getCompressionType()](#getCompressionType--) | 圧縮タイプを指定します。 |
| [setCompressionType(int value)](#setCompressionType-int-) | 圧縮タイプを指定します。 |
| [getPixelFormat()](#getPixelFormat--) | 生成された画像のピクセル形式を指定します。 |
| [setPixelFormat(int value)](#setPixelFormat-int-) | 生成された画像のピクセル形式を指定します。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getBwConversionMode()](#getBwConversionMode--) | カラー画像を白黒画像に変換するアルゴリズムを指定します。 |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | カラー画像を白黒画像に変換するアルゴリズムを指定します。 |
### TiffOptions() {#TiffOptions--}
```
public TiffOptions()
```


デフォルトコンストラクタ。

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


エクスポートされたドキュメント内のインクオブジェクトの外観を制御するオプションを提供します。読み取り専用 [IInkOptions](../../com.aspose.slides/iinkoptions)

**戻り値:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public final boolean getShowHiddenSlides()
```


生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは false です。

**戻り値:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public final void setShowHiddenSlides(boolean value)
```


生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは false です。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getImageSize() {#getImageSize--}
```
public final Size getImageSize()
```


生成されたTIFF画像のサイズを指定します。デフォルト値は 0x0 で、生成された画像サイズはプレゼンテーションのスライドサイズに基づいて計算されることを意味します。読み書き [Size](../../com.aspose.slides.android/size)。

**戻り値:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public final void setImageSize(Size value)
```


生成されたTIFF画像のサイズを指定します。デフォルト値は 0x0 で、生成された画像サイズはプレゼンテーションのスライドサイズに基づいて計算されることを意味します。読み書き [Size](../../com.aspose.slides.android/size)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public final long getDpiX()
```


水平解像度（インチあたりのドット数）を指定します。読み書き long。

**戻り値:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public final void setDpiX(long value)
```


水平解像度（インチあたりのドット数）を指定します。読み書き long。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public final long getDpiY()
```


垂直解像度（インチあたりのドット数）を指定します。読み書き long。

**戻り値:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public final void setDpiY(long value)
```


垂直解像度（インチあたりのドット数）を指定します。読み書き long。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getCompressionType() {#getCompressionType--}
```
public final int getCompressionType()
```


圧縮タイプを指定します。読み書き [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)。

**戻り値:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public final void setCompressionType(int value)
```


圧縮タイプを指定します。読み書き [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public final int getPixelFormat()
```


生成された画像のピクセル形式を指定します。読み書き [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)。

**戻り値:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public final void setPixelFormat(int value)
```


生成された画像のピクセル形式を指定します。読み書き [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**戻り値:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


プレゼンテーションをエクスポートする際に、スライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      TiffOptions options = new TiffOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      pres.save("pres.tiff", SaveFormat.Tiff, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public final int getBwConversionMode()
```


カラー画像を白黒画像に変換するアルゴリズムを指定します。このオプションは、CompressionType（\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)）が [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) または [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) に設定されている場合にのみ適用されます。読み書き [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode)。デフォルトは [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default)です。

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**戻り値:**
int
### setBwConversionMode(int value) {#setBwConversionMode-int-}
```
public final void setBwConversionMode(int value)
```


カラー画像を白黒画像に変換するアルゴリズムを指定します。このオプションは、CompressionType（\#getCompressionType.getCompressionType/\#setCompressionType(int).setCompressionType(int)）が [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) または [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) に設定されている場合にのみ適用されます。読み書き [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode)。デフォルトは [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default)です。

--------------------

> ```
> TiffOptions tiffOptions = new TiffOptions();
>  tiffOptions.setCompressionType(TiffCompressionTypes.CCITT4);
>  tiffOptions.setBwConversionMode(BlackWhiteConversionMode.Dithering);
>  Presentation presentation = new Presentation();
>  try {
>      presentation.save(tiffFilePath, SaveFormat.Tiff, tiffOptions);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | int |  |