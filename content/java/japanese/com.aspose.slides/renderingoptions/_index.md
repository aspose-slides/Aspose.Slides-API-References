---
title: RenderingOptions
second_title: Aspose.Slides for Java API リファレンス
description: プレゼンテーション/スライドの描画方法を制御するオプションを提供します。
type: docs
url: /ja/com.aspose.slides/renderingoptions/
---
**継承:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IRenderingOptions](../../com.aspose.slides/irenderingoptions)
```
public class RenderingOptions extends SaveOptions implements IRenderingOptions
```

エクスポートされたプレゼンテーション/スライドの描画方法を制御するオプションを提供します。

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      IRenderingOptions renderingOpts = new RenderingOptions();
>      renderingOpts.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomTruncated);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(renderingOpts), "PNG", new File("pres-Original.png"));
> 
>      renderingOpts.setDefaultRegularFont("Arial Black");
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(renderingOpts), "PNG", new File("pres-ArialBlackDefault.png"));
> 
>      renderingOpts.setDefaultRegularFont("Arial Narrow");
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(renderingOpts), "PNG", new File("pres-ArialNarrowDefault.png"));
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [RenderingOptions()](#RenderingOptions--) | デフォルトコンストラクタ。 |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | プレゼンテーションをエクスポートする際にスライドがページに配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | プレゼンテーションをエクスポートする際にスライドがページに配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。 |
| [getInkOptions()](#getInkOptions--) | エクスポートされたドキュメントのインクオブジェクトの外観を制御するオプションを提供します。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | テキストが合字を使用せずに描画されるかどうかを示す値を取得または設定します。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | テキストが合字を使用せずに描画されるかどうかを示す値を取得または設定します。 |
### RenderingOptions() {#RenderingOptions--}
```
public RenderingOptions()
```


デフォルトコンストラクタ。

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


プレゼンテーションをエクスポートする際にスライドがページに配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
> 
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      BufferedImage[] handoutSlides = pres.getThumbnails(options);
>      for (int index = 0; index < handoutSlides.length; index++)
>      {
>          ImageIO.write(handoutSlides[index], "PNG", new java.io.File("handout-" + index + ".png"));
>      }
>  } catch (IOException e) {
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


プレゼンテーションをエクスポートする際にスライドがページに配置されるモードを取得または設定します [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
> 
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      BufferedImage[] handoutSlides = pres.getThumbnails(options);
>      for (int index = 0; index < handoutSlides.length; index++)
>      {
>          ImageIO.write(handoutSlides[index], "PNG", new java.io.File("handout-" + index + ".png"));
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


エクスポートされたドキュメントのインクオブジェクトの外観を制御するオプションを提供します。読み取り専用 [IInkOptions](../../com.aspose.slides/iinkoptions)

**戻り値:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


テキストが合字を使用せずに描画されるかどうかを示す値を取得または設定します。true に設定すると、描画出力で合字が無効になります。デフォルトでは、このプロパティは false に設定されています。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      options.setDisableFontLigatures(true);
> 
>      IImage[] renderedSlides = pres.getImages(options);
>      for (int index = 0; index < renderedSlides.length; index++)
>      {
>          IImage slideImage = renderedSlides[index];
>          slideImage.save("slide-" + index + ".png");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**戻り値:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```


テキストが合字を使用せずに描画されるかどうかを示す値を取得または設定します。true に設定すると、描画出力で合字が無効になります。デフォルトでは、このプロパティは false に設定されています。

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      options.setDisableFontLigatures(true);
> 
>      IImage[] renderedSlides = pres.getImages(options);
>      for (int index = 0; index < renderedSlides.length; index++)
>      {
>          IImage slideImage = renderedSlides[index];
>          slideImage.save("slide-" + index + ".png");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |