---
title: ITiffOptions
second_title: Java API リファレンスによる Aspose.Slides for Android
description: プレゼンテーションがTIFF形式で保存される方法を制御するオプションを提供します。
type: docs
url: /ja/com.aspose.slides/itiffoptions/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ITiffOptions extends ISaveOptions
```

プレゼンテーションがTIFF形式で保存される方法を制御するオプションを提供します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getImageSize()](#getImageSize--) | 生成されたTIFF画像のサイズを指定します。 |
| [setImageSize(Size value)](#setImageSize-com.aspose.slides.android.Size-) | 生成されたTIFF画像のサイズを指定します。 |
| [getDpiX()](#getDpiX--) | 水平方向の解像度（dpi）を指定します。 |
| [setDpiX(long value)](#setDpiX-long-) | 水平方向の解像度（dpi）を指定します。 |
| [getDpiY()](#getDpiY--) | 垂直方向の解像度（dpi）を指定します。 |
| [setDpiY(long value)](#setDpiY-long-) | 垂直方向の解像度（dpi）を指定します。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [getCompressionType()](#getCompressionType--) | 圧縮タイプを指定します。 |
| [setCompressionType(int value)](#setCompressionType-int-) | 圧縮タイプを指定します。 |
| [getPixelFormat()](#getPixelFormat--) | 生成された画像のピクセル形式を指定します。 |
| [setPixelFormat(int value)](#setPixelFormat-int-) | 生成された画像のピクセル形式を指定します。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getBwConversionMode()](#getBwConversionMode--) | カラー画像を白黒画像に変換するアルゴリズムを指定します。 |
| [setBwConversionMode(int value)](#setBwConversionMode-int-) | カラー画像を白黒画像に変換するアルゴリズムを指定します。 |
| [getInkOptions()](#getInkOptions--) | エクスポートされたドキュメント内のインクオブジェクトの外観を制御するオプションを提供します。 |
### getImageSize() {#getImageSize--}
```
public abstract Size getImageSize()
```

生成されたTIFF画像のサイズを指定します。デフォルト値は0x0で、これは生成された画像サイズがプレゼンテーションのスライドサイズの値に基づいて計算されることを意味します。読み書き [Size](../../com.aspose.slides.android/size)。

**戻り値:**
[Size](../../com.aspose.slides.android/size)
### setImageSize(Size value) {#setImageSize-com.aspose.slides.android.Size-}
```
public abstract void setImageSize(Size value)
```

生成されたTIFF画像のサイズを指定します。デフォルト値は0x0で、これは生成された画像サイズがプレゼンテーションのスライドサイズの値に基づいて計算されることを意味します。読み書き [Size](../../com.aspose.slides.android/size)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [Size](../../com.aspose.slides.android/size) |  |

### getDpiX() {#getDpiX--}
```
public abstract long getDpiX()
```

水平方向の解像度（dpi）を指定します。読み書き long.

**戻り値:**
long
### setDpiX(long value) {#setDpiX-long-}
```
public abstract void setDpiX(long value)
```

水平方向の解像度（dpi）を指定します。読み書き long。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getDpiY() {#getDpiY--}
```
public abstract long getDpiY()
```

垂直方向の解像度（dpi）を指定します。読み書き long。

**戻り値:**
long
### setDpiY(long value) {#setDpiY-long-}
```
public abstract void setDpiY(long value)
```

垂直方向の解像度（dpi）を指定します。読み書き long。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | long |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは false です。

**戻り値:**
boolean
### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。デフォルトは false です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getCompressionType() {#getCompressionType--}
```
public abstract int getCompressionType()
```

圧縮タイプを指定します。読み書き [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)。

**戻り値:**
int
### setCompressionType(int value) {#setCompressionType-int-}
```
public abstract void setCompressionType(int value)
```

圧縮タイプを指定します。読み書き [TiffCompressionTypes](../../com.aspose.slides/tiffcompressiontypes)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getPixelFormat() {#getPixelFormat--}
```
public abstract int getPixelFormat()
```

生成された画像のピクセル形式を指定します。読み書き [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)。

**戻り値:**
int
### setPixelFormat(int value) {#setPixelFormat-int-}
```
public abstract void setPixelFormat(int value)
```

生成された画像のピクセル形式を指定します。読み書き [ImagePixelFormat](../../com.aspose.slides/imagepixelformat)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

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
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

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


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getBwConversionMode() {#getBwConversionMode--}
```
public abstract int getBwConversionMode()
```

カラー画像を白黒画像に変換するアルゴリズムを指定します。このオプションは、CompressionType（#getCompressionType.getCompressionType/#setCompressionType(int).setCompressionType(int)）が [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) または [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) に設定されている場合にのみ適用されます。読み書き [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode)。デフォルトは [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default)。

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
public abstract void setBwConversionMode(int value)
```

カラー画像を白黒画像に変換するアルゴリズムを指定します。このオプションは、CompressionType（#getCompressionType.getCompressionType/#setCompressionType(int).setCompressionType(int)）が [TiffCompressionTypes.CCITT4](../../com.aspose.slides/tiffcompressiontypes\#CCITT4) または [TiffCompressionTypes.CCITT3](../../com.aspose.slides/tiffcompressiontypes\#CCITT3) に設定されている場合にのみ適用されます。読み書き [BlackWhiteConversionMode](../../com.aspose.slides/blackwhiteconversionmode)。デフォルトは [BlackWhiteConversionMode.Default](../../com.aspose.slides/blackwhiteconversionmode\#Default)。

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


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

エクスポートされたドキュメント内のインクオブジェクトの外観を制御するオプションを提供します。読み取り専用 [IInkOptions](../../com.aspose.slides/iinkoptions)

**戻り値:**
[IInkOptions](../../com.aspose.slides/iinkoptions)