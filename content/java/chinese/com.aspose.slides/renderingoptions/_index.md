---
title: RenderingOptions
second_title: Aspose.Slides for Java API 参考
description: 提供控制演示文稿/幻灯片渲染方式的选项。
type: docs
url: /zh/com.aspose.slides/renderingoptions/
---
**继承：**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**所有已实现的接口：**
[com.aspose.slides.IRenderingOptions](../../com.aspose.slides/irenderingoptions)
```
public class RenderingOptions extends SaveOptions implements IRenderingOptions
```

提供控制演示文稿/幻灯片渲染方式的选项。

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

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [RenderingOptions()](#RenderingOptions--) | 默认构造函数。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 获取或设置在导出演示文稿 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) 时幻灯片在页面上的放置模式。 |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 获取或设置在导出演示文稿 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) 时幻灯片在页面上的放置模式。 |
| [getInkOptions()](#getInkOptions--) | 提供控制导出文档中 Ink 对象外观的选项。 |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | 获取或设置一个值，指示文本是否在渲染时不使用连字。 |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | 获取或设置一个值，指示文本是否在渲染时不使用连字。 |
### RenderingOptions() {#RenderingOptions--}
```
public RenderingOptions()
```


默认构造函数。

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```


获取或设置在导出演示文稿 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) 时幻灯片在页面上的放置模式。

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

**返回：**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```


获取或设置在导出演示文稿 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) 时幻灯片在页面上的放置模式。

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


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```


提供控制导出文档中 Ink 对象外观的选项。只读 [IInkOptions](../../com.aspose.slides/iinkoptions)

**返回：**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```


获取或设置一个值，指示文本是否在渲染时不使用连字。当设置为 true 时，渲染输出中将禁用连字。默认情况下，此属性为 false。

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


**返回：**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```


获取或设置一个值，指示文本是否在渲染时不使用连字。当设置为 true 时，渲染输出中将禁用连字。默认情况下，此属性为 false。

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


**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |