---
title: ISwfOptions
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーションが SWF 形式で保存される方法を制御するオプションを提供します。
type: docs
url: /ja/com.aspose.slides/iswfoptions/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface ISwfOptions extends ISaveOptions
```

プレゼンテーションがSWF形式で保存される方法を制御するオプションを提供します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCompressed()](#getCompressed--) | 生成されたSWFドキュメントを圧縮するかどうかを指定します。 |
| [setCompressed(boolean value)](#setCompressed-boolean-) | 生成されたSWFドキュメントを圧縮するかどうかを指定します。 |
| [getViewerIncluded()](#getViewerIncluded--) | 生成されたSWFドキュメントに統合ドキュメントビューアを含めるかどうかを指定します。 |
| [setViewerIncluded(boolean value)](#setViewerIncluded-boolean-) | 生成されたSWFドキュメントに統合ドキュメントビューアを含めるかどうかを指定します。 |
| [getShowPageBorder()](#getShowPageBorder--) | ページ周囲の境界を表示するかどうかを指定します。 |
| [setShowPageBorder(boolean value)](#setShowPageBorder-boolean-) | ページ周囲の境界を表示するかどうかを指定します。 |
| [getShowHiddenSlides()](#getShowHiddenSlides--) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [setShowHiddenSlides(boolean value)](#setShowHiddenSlides-boolean-) | 生成されたドキュメントに非表示スライドを含めるかどうかを指定します。 |
| [getShowFullScreen()](#getShowFullScreen--) | 全画面ボタンの表示/非表示を切り替えます。 |
| [setShowFullScreen(boolean value)](#setShowFullScreen-boolean-) | 全画面ボタンの表示/非表示を切り替えます。 |
| [getShowPageStepper()](#getShowPageStepper--) | ページステッパーの表示/非表示を切り替えます。 |
| [setShowPageStepper(boolean value)](#setShowPageStepper-boolean-) | ページステッパーの表示/非表示を切り替えます。 |
| [getShowSearch()](#getShowSearch--) | 検索セクションの表示/非表示を切り替えます。 |
| [setShowSearch(boolean value)](#setShowSearch-boolean-) | 検索セクションの表示/非表示を切り替えます。 |
| [getShowTopPane()](#getShowTopPane--) | 上部全体ペインの表示/非表示を切り替えます。 |
| [setShowTopPane(boolean value)](#setShowTopPane-boolean-) | 上部全体ペインの表示/非表示を切り替えます。 |
| [getShowBottomPane()](#getShowBottomPane--) | 下部ペインの表示/非表示を切り替えます。 |
| [setShowBottomPane(boolean value)](#setShowBottomPane-boolean-) | 下部ペインの表示/非表示を切り替えます。 |
| [getShowLeftPane()](#getShowLeftPane--) | 左側ペインの表示/非表示を切り替えます。 |
| [setShowLeftPane(boolean value)](#setShowLeftPane-boolean-) | 左側ペインの表示/非表示を切り替えます。 |
| [getStartOpenLeftPane()](#getStartOpenLeftPane--) | 左側ペインを開いた状態で開始します。 |
| [setStartOpenLeftPane(boolean value)](#setStartOpenLeftPane-boolean-) | 左側ペインを開いた状態で開始します。 |
| [getEnableContextMenu()](#getEnableContextMenu--) | コンテキストメニューの有効化/無効化を切り替えます。 |
| [setEnableContextMenu(boolean value)](#setEnableContextMenu-boolean-) | コンテキストメニューの有効化/無効化を切り替えます。 |
| [getLogoImageBytes()](#getLogoImageBytes--) | ビューアの右上隅にロゴとして表示される画像です。 |
| [setLogoImageBytes(byte[] value)](#setLogoImageBytes-byte---) | ビューアの右上隅にロゴとして表示される画像です。 |
| [getLogoLink()](#getLogoLink--) | ロゴの完全なハイパーリンクアドレスを取得または設定します。 |
| [setLogoLink(String value)](#setLogoLink-java.lang.String-) | ロゴの完全なハイパーリンクアドレスを取得または設定します。 |
| [getJpegQuality()](#getJpegQuality--) | JPEG画像の品質を指定します。 |
| [setJpegQuality(int value)](#setJpegQuality-int-) | JPEG画像の品質を指定します。 |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |

### getCompressed() {#getCompressed--}
```
public abstract boolean getCompressed()
```

生成されたSWFドキュメントを圧縮するかどうかを指定します。既定値は true です。

**戻り値:**
boolean

### setCompressed(boolean value) {#setCompressed-boolean-}
```
public abstract void setCompressed(boolean value)
```

生成されたSWFドキュメントを圧縮するかどうかを指定します。既定値は true です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getViewerIncluded() {#getViewerIncluded--}
```
public abstract boolean getViewerIncluded()
```

生成されたSWFドキュメントに統合ドキュメントビューアを含めるかどうかを指定します。既定値は true です。

**戻り値:**
boolean

### setViewerIncluded(boolean value) {#setViewerIncluded-boolean-}
```
public abstract void setViewerIncluded(boolean value)
```

生成されたSWFドキュメントに統合ドキュメントビューアを含めるかどうかを指定します。既定値は true です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowPageBorder() {#getShowPageBorder--}
```
public abstract boolean getShowPageBorder()
```

ページ周囲の境界を表示するかどうかを指定します。既定値は true です。

**戻り値:**
boolean

### setShowPageBorder(boolean value) {#setShowPageBorder-boolean-}
```
public abstract void setShowPageBorder(boolean value)
```

ページ周囲の境界を表示するかどうかを指定します。既定値は true です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowHiddenSlides() {#getShowHiddenSlides--}
```
public abstract boolean getShowHiddenSlides()
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。既定値は false です。

**戻り値:**
boolean

### setShowHiddenSlides(boolean value) {#setShowHiddenSlides-boolean-}
```
public abstract void setShowHiddenSlides(boolean value)
```

生成されたドキュメントに非表示スライドを含めるかどうかを指定します。既定値は false です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowFullScreen() {#getShowFullScreen--}
```
public abstract boolean getShowFullScreen()
```

全画面ボタンの表示/非表示を切り替えます。flashvars で上書き可能です。既定値は true です。

**戻り値:**
boolean

### setShowFullScreen(boolean value) {#setShowFullScreen-boolean-}
```
public abstract void setShowFullScreen(boolean value)
```

全画面ボタンの表示/非表示を切り替えます。flashvars で上書き可能です。既定値は true です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowPageStepper() {#getShowPageStepper--}
```
public abstract boolean getShowPageStepper()
```

ページステッパーの表示/非表示を切り替えます。flashvars で上書き可能です。既定値は true です。

**戻り値:**
boolean

### setShowPageStepper(boolean value) {#setShowPageStepper-boolean-}
```
public abstract void setShowPageStepper(boolean value)
```

ページステッパーの表示/非表示を切り替えます。flashvars で上書き可能です。既定値は true です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowSearch() {#getShowSearch--}
```
public abstract boolean getShowSearch()
```

検索セクションの表示/非表示を切り替えます。flashvars で上書き可能です。既定値は true です。

**戻り値:**
boolean

### setShowSearch(boolean value) {#setShowSearch-boolean-}
```
public abstract void setShowSearch(boolean value)
```

検索セクションの表示/非表示を切り替えます。flashvars で上書き可能です。既定値は true です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowTopPane() {#getShowTopPane--}
```
public abstract boolean getShowTopPane()
```

上部全体ペインの表示/非表示を切り替えます。flashvars で上書き可能です。既定値は true です。

**戻り値:**
boolean

### setShowTopPane(boolean value) {#setShowTopPane-boolean-}
```
public abstract void setShowTopPane(boolean value)
```

上部全体ペインの表示/非表示を切り替えます。flashvars で上書き可能です。既定値は true です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowBottomPane() {#getShowBottomPane--}
```
public abstract boolean getShowBottomPane()
```

下部ペインの表示/非表示を切り替えます。flashvars で上書き可能です。既定値は true です。

**戻り値:**
boolean

### setShowBottomPane(boolean value) {#setShowBottomPane-boolean-}
```
public abstract void setShowBottomPane(boolean value)
```

下部ペインの表示/非表示を切り替えます。flashvars で上書き可能です。既定値は true です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getShowLeftPane() {#getShowLeftPane--}
```
public abstract boolean getShowLeftPane()
```

左側ペインの表示/非表示を切り替えます。flashvars で上書き可能です。既定値は true です。

**戻り値:**
boolean

### setShowLeftPane(boolean value) {#setShowLeftPane-boolean-}
```
public abstract void setShowLeftPane(boolean value)
```

左側ペインの表示/非表示を切り替えます。flashvars で上書き可能です。既定値は true です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getStartOpenLeftPane() {#getStartOpenLeftPane--}
```
public abstract boolean getStartOpenLeftPane()
```

左側ペインを開いた状態で開始します。flashvars で上書き可能です。既定値は false です。

**戻り値:**
boolean

### setStartOpenLeftPane(boolean value) {#setStartOpenLeftPane-boolean-}
```
public abstract void setStartOpenLeftPane(boolean value)
```

左側ペインを開いた状態で開始します。flashvars で上書き可能です。既定値は false です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getEnableContextMenu() {#getEnableContextMenu--}
```
public abstract boolean getEnableContextMenu()
```

コンテキストメニューの有効化/無効化を切り替えます。既定値は true です。

**戻り値:**
boolean

### setEnableContextMenu(boolean value) {#setEnableContextMenu-boolean-}
```
public abstract void setEnableContextMenu(boolean value)
```

コンテキストメニューの有効化/無効化を切り替えます。既定値は true です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getLogoImageBytes() {#getLogoImageBytes--}
```
public abstract byte[] getLogoImageBytes()
```

ビューアの右上隅にロゴとして表示される画像です。画像は 32x64 ピクセルの PNG である必要があります。そうでない場合、ロゴが正しく表示されない可能性があります。

**戻り値:**
byte[]

### setLogoImageBytes(byte[] value) {#setLogoImageBytes-byte---}
```
public abstract void setLogoImageBytes(byte[] value)
```

ビューアの右上隅にロゴとして表示される画像です。画像は 32x64 ピクセルの PNG である必要があります。そうでない場合、ロゴが正しく表示されない可能性があります。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte[] |  |

### getLogoLink() {#getLogoLink--}
```
public abstract String getLogoLink()
```

ロゴの完全なハイパーリンクアドレスを取得または設定します。指定された場合にのみ効果があります（\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])）。

**戻り値:**
java.lang.String

### setLogoLink(String value) {#setLogoLink-java.lang.String-}
```
public abstract void setLogoLink(String value)
```

ロゴの完全なハイパーリンクアドレスを取得または設定します。指定された場合にのみ効果があります（\#getLogoImageBytes.getLogoImageBytes/\#setLogoImageBytes(byte[]).setLogoImageBytes(byte[])）。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getJpegQuality() {#getJpegQuality--}
```
public abstract int getJpegQuality()
```

JPEG画像の品質を指定します。既定値は 95 です。

**戻り値:**
int

### setJpegQuality(int value) {#setJpegQuality-int-}
```
public abstract void setJpegQuality(int value)
```

JPEG画像の品質を指定します。既定値は 95 です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | int |  |

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。このプロパティは [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) 型のオブジェクトの割り当てをサポートしません。

--------------------

> ```
> 例:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
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

プレゼンテーションをエクスポートする際にスライドがページ上に配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。このプロパティは [HandoutLayoutingOptions](../../com.aspose.slides/handoutlayoutingoptions) 型のオブジェクトの割り当てをサポートしません。

--------------------

> ```
> 例:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      NotesCommentsLayoutingOptions notesOptions = new NotesCommentsLayoutingOptions();
>      notesOptions.setCommentsPosition(CommentsPositions.Right);
> 
>      SwfOptions options = new SwfOptions();
>      options.setSlidesLayoutOptions(notesOptions);
> 
>      pres.save("pres.swf", SaveFormat.Swf, options);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |