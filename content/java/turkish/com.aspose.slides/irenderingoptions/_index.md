---
title: IRenderingOptions
second_title: Aspose.Slides for Java API Referansı
description: Bir sunum/slaytın nasıl render edildiğini kontrol eden seçenekler sağlar.
type: docs
url: /tr/com.aspose.slides/irenderingoptions/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IRenderingOptions extends ISaveOptions
```

Bir sunum/slaytın nasıl render edildiğini kontrol eden seçenekler sağlar.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      IRenderingOptions renderingOpts = new RenderingOptions();
>      NotesCommentsLayoutingOptions notesCommentsLayoutingOptions = new NotesCommentsLayoutingOptions();
>      notesCommentsLayoutingOptions.setNotesPosition(NotesPositions.BottomTruncated);
>      renderingOpts.setSlidesLayoutOptions(notesCommentsLayoutingOptions);
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

## Yöntemler

| Method | Description |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | Sunumu dışa aktarırken slaytların sayfada konumlandırıldığı modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | Sunumu dışa aktarırken slaytların sayfada konumlandırıldığı modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değeri alır veya ayarlar. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değeri alır veya ayarlar. |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

Sunumu dışa aktarırken slaytların sayfada konumlandırıldığı modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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


**Döndürür:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

Sunumu dışa aktarırken slaytların sayfada konumlandırıldığı modu alır veya ayarlar [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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


**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

Dışa aktarılan belgede Ink nesnelerinin görünümünü kontrol eden seçenekler sağlar. Yalnızca okuma [IInkOptions](../../com.aspose.slides/iinkoptions)

**Döndürür:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değeri alır veya ayarlar. True olarak ayarlandığında, render edilmiş çıktıdaki ligatürler devre dışı bırakılacaktır. Varsayılan olarak bu özellik false olarak ayarlanmıştır.

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


**Döndürür:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

Metnin ligatürler kullanılmadan render edilip edilmediğini gösteren bir değeri alır veya ayarlar. True olarak ayarlandığında, render edilmiş çıktıdaki ligatürler devre dışı bırakılacaktır. Varsayılan olarak bu özellik false olarak ayarlanmıştır.

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

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |