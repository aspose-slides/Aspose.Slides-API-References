---
title: HandoutLayoutingOptions
second_title: Aspose.Slides için Java API Referansı
description: Dışa aktarma için el ilanı sunum düzeni modunu temsil eder.
type: docs
url: /tr/com.aspose.slides/handoutlayoutingoptions/
---
**Kalıtım:**
java.lang.Object

**Tüm Gerçekleştirilen Arabirimler:**
[com.aspose.slides.ISlidesLayoutOptions](../../com.aspose.slides/islideslayoutoptions)
```
public class HandoutLayoutingOptions implements ISlidesLayoutOptions
```

Döküman dağıtım sunum düzeni modunu dışa aktarım için temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [HandoutLayoutingOptions()](#HandoutLayoutingOptions--) | Varsayılan değerleri başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHandout()](#getHandout--) | Sayfa [HandoutType](../../com.aspose.slides/handouttype) üzerine kaç slayt ve hangi sırada yerleştirileceğini belirtir. |
| [setHandout(int value)](#setHandout-int-) | Sayfa [HandoutType](../../com.aspose.slides/handouttype) üzerine kaç slayt ve hangi sırada yerleştirileceğini belirtir. |
| [getPrintSlideNumbers()](#getPrintSlideNumbers--) | Görüntülenen slayt numaralarının yazdırılıp yazdırılmayacağını belirtir. |
| [setPrintSlideNumbers(boolean value)](#setPrintSlideNumbers-boolean-) | Görüntülenen slayt numaralarının yazdırılıp yazdırılmayacağını belirtir. |
| [getPrintFrameSlide()](#getPrintFrameSlide--) | Görüntülenen slaytların etrafına çerçeve çizilip çizilmeyeceğini belirtir. |
| [setPrintFrameSlide(boolean value)](#setPrintFrameSlide-boolean-) | Görüntülenen slaytların etrafına çerçeve çizilip çizilmeyeceğini belirtir. |
| [getPrintComments()](#getPrintComments--) | Slaytlarda yorumların gösterilip gösterilmeyeceğini belirtir. |
| [setPrintComments(boolean value)](#setPrintComments-boolean-) | Slaytlarda yorumların gösterilip gösterilmeyeceğini belirtir. |
### HandoutLayoutingOptions() {#HandoutLayoutingOptions--}
```
public HandoutLayoutingOptions()
```

Varsayılan değerleri başlatır.

### getHandout() {#getHandout--}
```
public final int getHandout()
```

Sayfa [HandoutType](../../com.aspose.slides/handouttype) üzerine kaç slayt ve hangi sırada yerleştirileceğini belirtir.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Varsayılan değer **HandoutType.Handouts6Horizontal** .

**Döndürür:**
int
### setHandout(int value) {#setHandout-int-}
```
public final void setHandout(int value)
```

Sayfa [HandoutType](../../com.aspose.slides/handouttype) üzerine kaç slayt ve hangi sırada yerleştirileceğini belirtir.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Varsayılan değer **HandoutType.Handouts6Horizontal** .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPrintSlideNumbers() {#getPrintSlideNumbers--}
```
public final boolean getPrintSlideNumbers()
```

Görüntülenen slayt numaralarının yazdırılıp yazdırılıp yazdırılmayacağını belirtir.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Varsayılan değer **true** .

**Döndürür:**
boolean
### setPrintSlideNumbers(boolean value) {#setPrintSlideNumbers-boolean-}
```
public final void setPrintSlideNumbers(boolean value)
```

Görüntülenen slayt numaralarının yazdırılıp yazdırılıp yazdırılmayacağını belirtir.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintSlideNumbers(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Varsayılan değer **true** .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getPrintFrameSlide() {#getPrintFrameSlide--}
```
public final boolean getPrintFrameSlide()
```

Görüntülenen slaytların etrafına çerçeve çizilip çizilmeyeceğini belirtir.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintFrameSlide(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Varsayılan değer **true** .

**Döndürür:**
boolean
### setPrintFrameSlide(boolean value) {#setPrintFrameSlide-boolean-}
```
public final void setPrintFrameSlide(boolean value)
```

Görüntülenen slaytların etrafına çerçeve çizilip çizilmeyeceğini belirtir.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintFrameSlide(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Varsayılan değer **true** .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getPrintComments() {#getPrintComments--}
```
public final boolean getPrintComments()
```

Slaytlarda yorumların gösterilip gösterilmeyeceğini belirtir.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintComments(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Varsayılan değer **false** .

**Döndürür:**
boolean
### setPrintComments(boolean value) {#setPrintComments-boolean-}
```
public final void setPrintComments(boolean value)
```

Slaytlarda yorumların gösterilip gösterilmeyeceğini belirtir.

--------------------

> ```
> Example:
>   
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      RenderingOptions options = new RenderingOptions();
>      HandoutLayoutingOptions slidesLayoutOptions = new HandoutLayoutingOptions();
>      slidesLayoutOptions.setHandout(HandoutType.Handouts4Horizontal);
>      slidesLayoutOptions.setPrintComments(false);
>      options.setSlidesLayoutOptions(slidesLayoutOptions);
> 
>      ImageIO.write(pres.getSlides().get_Item(0).getThumbnail(options, new Dimension(1920, 1080)), "PNG", new java.io.File("pres-handout.png"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Varsayılan değer **false** .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |