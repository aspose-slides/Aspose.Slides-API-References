---
title: VideoPlayerHtmlController
second_title: Aspose.Slides برای Java - مرجع API
description: این کلاس امکان استخراج فایل‌های ویدئویی و صوتی به قالب HTML را فراهم می‌کند
type: docs
url: /fa/com.aspose.slides/videoplayerhtmlcontroller/
---
**ارث-برداری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IVideoPlayerHtmlController](../../com.aspose.slides/ivideoplayerhtmlcontroller)
```
public class VideoPlayerHtmlController implements IVideoPlayerHtmlController
```

این کلاس امکان صدور فایل‌های ویدئویی و صوتی به قالب HTML را فراهم می‌کند
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [VideoPlayerHtmlController(String path, String fileName, String baseUri)](#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-) | یک نمونه جدید از کنترل‌کننده ایجاد می‌کند |
## متدها

| متد | توضیح |
| --- | --- |
| [writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)](#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-) |  |
| [writeSlideStart(IHtmlGenerator generator, ISlide slide)](#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeSlideEnd(IHtmlGenerator generator, ISlide slide)](#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-) |  |
| [writeShapeStart(IHtmlGenerator generator, IShape shape)](#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [writeShapeEnd(IHtmlGenerator generator, IShape shape)](#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-) |  |
| [formatShape(ISvgShape svgShape, IShape shape)](#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-) |  |
| [getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)](#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-) |  |
| [getUrl(int id, int referrer)](#getUrl-int-int-) |  |
| [saveExternal(int id, byte[] entityData)](#saveExternal-int-byte---) |  |
### VideoPlayerHtmlController(String path, String fileName, String baseUri) {#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-}
```
public VideoPlayerHtmlController(String path, String fileName, String baseUri)
```


یک نمونه جدید از کنترل‌کننده ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیری که فایل‌های ویدئویی و صوتی در آن تولید می‌شوند |
| fileName | java.lang.String | نام فایل HTML |
| baseUri | java.lang.String | آدرس پایه‌ای که برای تولید لینک‌ها استفاده می‌شود |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


برای نوشتن سرصفحهٔ سند HTML فراخوانی می‌شود. یک بار برای هر تبدیل ارائه صدا زده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


برای نوشتن پاصفحهٔ سند HTML فراخوانی می‌شود. یک بار برای هر تبدیل ارائه صدا زده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


برای نوشتن سرصفحهٔ اسلاید HTML فراخوانی می‌شود. یک بار برای هر اسلاید صدا زده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


برای نوشتن پاصفحهٔ اسلاید HTML فراخوانی می‌شود. یک بار برای هر اسلاید صدا زده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


قبل از رندر شدن شکل فراخوانی می‌شود. یک بار برای هر شکل صدا زده می‌شود. اگر این تابع چیزی به generator بنویسد، تولید تصویر اسلاید جاری تمام می‌شود، بخش html اضافه‌شده درج می‌شود و تصویر جدید بر روی قبلی آغاز می‌گردد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


قبل از رندر شدن شکل فراخوانی می‌شود. یک بار برای هر شکل صدا زده می‌شود. اگر این تابع چیزی به generator بنویسد، تولید تصویر اسلاید جاری تمام می‌شود، بخش html اضافه‌شده درج می‌شود و تصویر جدید بر روی قبلی آغاز می‌گردد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public final void formatShape(ISvgShape svgShape, IShape shape)
```


این تابع پیش از رندر شدن شکل به SVG فراخوانی می‌شود تا به کاربر امکان کنترل SVG تولید‌شده را بدهد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public final int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


محلی را که شی باید در آن ذخیره شود تعیین می‌کند. این متد یک بار برای هر شناسهٔ شی صدا زده می‌شود. تضمینی وجود ندارد که دو شی با داده‌ها، semanticName و contentType یکسان ولی شناسه‌های متفاوت وجود نداشته باشند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |
| semanticName | java.lang.String |  |
| contentType | java.lang.String |  |
| recomendedExtension | java.lang.String |  |

**بازمی‌گرداند:**
int
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public final String getUrl(int id, int referrer)
```


یک URL برای شیء خارجی بازمی‌گرداند. این متد همیشه وقتی \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) مقدار [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) را برمی‌گرداند، فراخوانی می‌شود و ممکن است وقتی مقدار [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) برگردانده شود اما جاسازی امکان‌پذیر نیست، فراخوانی شود. می‌تواند برای همان شناسهٔ شی چندین بار صدا زده شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | int |  |
| referrer | int |  |

**بازمی‌گرداند:**
java.lang.String
### saveExternal(int id, byte[] entityData) {#saveExternal-int-byte---}
```
public final void saveExternal(int id, byte[] entityData)
```


شیء خارجی را ذخیره می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |