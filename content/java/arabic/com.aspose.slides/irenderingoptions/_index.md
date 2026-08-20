---
title: IRenderingOptions
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يوفر خيارات تتحكم في كيفية عرض العرض التقديمي/الشريحة.
type: docs
url: /ar/com.aspose.slides/irenderingoptions/
---
**كل الواجهات المُنفذة:**
[com.aspose.slides.ISaveOptions](../../com.aspose.slides/isaveoptions)
```
public interface IRenderingOptions extends ISaveOptions
```

يوفر خيارات تتحكم في كيفية عرض العرض التقديمي/الشريحة.

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

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | يحصل أو يضبط الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | يحصل أو يضبط الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدَّر. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | يحصل أو يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | يحصل أو يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. |
### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public abstract ISlidesLayoutOptions getSlidesLayoutOptions()
```

يحصل أو يضبط الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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


**القيمة المرجعة:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public abstract void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

يحصل أو يضبط الوضع الذي توضع فيه الشرائح على الصفحة عند تصدير عرض تقديمي [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public abstract IInkOptions getInkOptions()
```

يوفر خيارات تتحكم في مظهر كائنات الحبر في المستند المُصدَّر. قراءة فقط [IInkOptions](../../com.aspose.slides/iinkoptions)

**القيمة المرجعة:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public abstract boolean getDisableFontLigatures()
```

يحصل أو يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عند ضبطها على true، سيتم تعطيل الأحرف المتصلة في المخرجات المُعروضة. بشكل افتراضي، تكون هذه الخاصية مضبوطة على false.

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

**القيمة المرجعة:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public abstract void setDisableFontLigatures(boolean value)
```

يحصل أو يضبط قيمة تشير إلى ما إذا كان النص يُعرض دون استخدام الأحرف المتصلة. عند ضبطها على true، سيتم تعطيل الأحرف المتصلة في المخرجات المُعروضة. بشكل افتراضي، تكون هذه الخاصية مضبوطة على false.

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


**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |