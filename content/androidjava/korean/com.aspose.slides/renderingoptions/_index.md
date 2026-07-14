---
title: RenderingOptions
second_title: Java API 레퍼런스를 통한 Android용 Aspose.Slides
description: 프레젠테이션/슬라이드가 렌더링되는 방식을 제어하는 옵션을 제공합니다.
type: docs
url: /ko/com.aspose.slides/renderingoptions/
---
**상속:**
java.lang.Object, [com.aspose.slides.SaveOptions](../../com.aspose.slides/saveoptions)

**구현된 모든 인터페이스:**
[com.aspose.slides.IRenderingOptions](../../com.aspose.slides/irenderingoptions)
```
public class RenderingOptions extends SaveOptions implements IRenderingOptions
```

프레젠테이션/슬라이드가 렌더링되는 방식을 제어하는 옵션을 제공합니다.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      IRenderingOptions renderingOpts = new RenderingOptions();
>      renderingOpts.getNotesCommentsLayouting().setNotesPosition(NotesPositions.BottomTruncated);
>      FileOutputStream out = new FileOutputStream("pres-Original.png");
>      pres.getSlides().get_Item(0).getThumbnail(renderingOpts).compress(android.graphics.Bitmap.CompressFormat.JPEG, 100, out);
>      out.flush();
>      out.close();
>      renderingOpts.setDefaultRegularFont("Arial Black");
>      FileOutputStream out = new FileOutputStream("pres-ArialBlackDefault.png");
>      pres.getSlides().get_Item(0).getThumbnail(renderingOpts).compress(android.graphics.Bitmap.CompressFormat.JPEG, 100, out);
>      out.flush();
>      out.close();
>      renderingOpts.setDefaultRegularFont("Arial Narrow");
>      FileOutputStream out = new FileOutputStream("pres-ArialNarrowDefault.png");
>      pres.getSlides().get_Item(0).getThumbnail(renderingOpts).compress(android.graphics.Bitmap.CompressFormat.JPEG, 100, out);
>      out.flush();
>      out.close();
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## 생성자

| 생성자 | 설명 |
| --- | --- |
| [RenderingOptions()](#RenderingOptions--) | 기본 생성자. |
## 메서드

| 메서드 | 설명 |
| --- | --- |
| [getSlidesLayoutOptions()](#getSlidesLayoutOptions--) | 프레젠테이션을 내보낼 때 페이지에 슬라이드가 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [setSlidesLayoutOptions(ISlidesLayoutOptions value)](#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-) | 프레젠테이션을 내보낼 때 페이지에 슬라이드가 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions). |
| [getInkOptions()](#getInkOptions--) | 내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다. |
| [getDisableFontLigatures()](#getDisableFontLigatures--) | 텍스트가 합자(ligature)를 사용하지 않고 렌더링되는지를 나타내는 값을 가져오거나 설정합니다. |
| [setDisableFontLigatures(boolean value)](#setDisableFontLigatures-boolean-) | 텍스트가 합자(ligature)를 사용하지 않고 렌더링되는지를 나타내는 값을 가져오거나 설정합니다. |
### RenderingOptions() {#RenderingOptions--}
```
public RenderingOptions()
```

기본 생성자.

### getSlidesLayoutOptions() {#getSlidesLayoutOptions--}
```
public final ISlidesLayoutOptions getSlidesLayoutOptions()
```

프레젠테이션을 내보낼 때 페이지에 슬라이드가 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
>      android.graphics.Bitmap[] handoutSlides = pres.getThumbnails(options);
>      for (int index = 0; index < handoutSlides.length; index++)
>      {
>          FileOutputStream out = new FileOutputStream("handout-" + index + ".png");
>          handoutSlides[index].compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**반환값:**
[ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
### setSlidesLayoutOptions(ISlidesLayoutOptions value) {#setSlidesLayoutOptions-com.aspose.slides.ISlidesLayoutOptions-}
```
public final void setSlidesLayoutOptions(ISlidesLayoutOptions value)
```

프레젠테이션을 내보낼 때 페이지에 슬라이드가 배치되는 모드를 가져오거나 설정합니다 [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions).

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
>      android.graphics.Bitmap[] handoutSlides = pres.getThumbnails(options);
>      for (int index = 0; index < handoutSlides.length; index++)
>      {
>          FileOutputStream out = new FileOutputStream("handout-" + index + ".png");
>          handoutSlides[index].compress(android.graphics.Bitmap.CompressFormat.PNG, 100, out);
>          out.flush();
>          out.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | [ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions) |  |

### getInkOptions() {#getInkOptions--}
```
public final IInkOptions getInkOptions()
```

내보낸 문서에서 Ink 객체의 모양을 제어하는 옵션을 제공합니다. 읽기 전용 [IInkOptions](../../com.aspose.slides/iinkoptions)

**반환값:**
[IInkOptions](../../com.aspose.slides/iinkoptions)
### getDisableFontLigatures() {#getDisableFontLigatures--}
```
public final boolean getDisableFontLigatures()
```

텍스트가 합자를 사용하지 않고 렌더링되는지를 나타내는 값을 가져오거나 설정합니다. true로 설정하면 렌더링 결과에서 합자가 비활성화됩니다. 기본값은 false입니다.

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

**반환값:**
boolean
### setDisableFontLigatures(boolean value) {#setDisableFontLigatures-boolean-}
```
public final void setDisableFontLigatures(boolean value)
```

텍스트가 합자를 사용하지 않고 렌더링되는지를 나타내는 값을 가져오거나 설정합니다. true로 설정하면 렌더링 결과에서 합자가 비활성화됩니다. 기본값은 false입니다.

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

**매개변수:**
| 매개변수 | 유형 | 설명 |
| --- | --- | --- |
| value | boolean |  |