---
title: VideoPlayerHtmlController
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: این کلاس امکان صدور فایل‌های ویدئویی و صوتی به فرمت HTML را فراهم می‌کند
type: docs
url: /fa/com.aspose.slides/videoplayerhtmlcontroller/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IVideoPlayerHtmlController](../../com.aspose.slides/ivideoplayerhtmlcontroller)
```
public class VideoPlayerHtmlController implements IVideoPlayerHtmlController
```

این کلاس امکان صدور فایل‌های ویدئویی و صوتی به فرمت HTML را فراهم می‌کند
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [VideoPlayerHtmlController(String path, String fileName, String baseUri)](#VideoPlayerHtmlController-java.lang.String-java.lang.String-java.lang.String-) | یک نمونه جدید از کنترلر ایجاد می‌کند |
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


یک نمونه جدید از کنترلر ایجاد می‌کند

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| path | java.lang.String | مسیری که فایل‌های ویدئویی و صوتی در آن تولید خواهند شد |
| fileName | java.lang.String | نام فایل HTML |
| baseUri | java.lang.String | URI پایه‌ای که برای تولید لینک‌ها استفاده خواهد شد |

### writeDocumentStart(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentStart(IHtmlGenerator generator, IPresentation presentation)
```


برای نوشتن سرصفحهٔ سند HTML فراخوانی می‌شود. یک‌بار برای هر تبدیل ارائه فراخوانی می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation) {#writeDocumentEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IPresentation-}
```
public final void writeDocumentEnd(IHtmlGenerator generator, IPresentation presentation)
```


برای نوشتن پاورقی سند HTML فراخوانی می‌شود. یک‌بار برای هر تبدیل ارائه فراخوانی می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| presentation | [IPresentation](../../com.aspose.slides/ipresentation) |  |

### writeSlideStart(IHtmlGenerator generator, ISlide slide) {#writeSlideStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideStart(IHtmlGenerator generator, ISlide slide)
```


برای نوشتن سرصفحهٔ اسلاید HTML فراخوانی می‌شود. یک‌بار برای هر اسلاید فراخوانی می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeSlideEnd(IHtmlGenerator generator, ISlide slide) {#writeSlideEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.ISlide-}
```
public final void writeSlideEnd(IHtmlGenerator generator, ISlide slide)
```


برای نوشتن پاورقی اسلاید HTML فراخوانی می‌شود. یک‌بار برای هر اسلاید فراخوانی می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| slide | [ISlide](../../com.aspose.slides/islide) |  |

### writeShapeStart(IHtmlGenerator generator, IShape shape) {#writeShapeStart-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeStart(IHtmlGenerator generator, IShape shape)
```


قبل از رندر کردن شکل فراخوانی می‌شود. یک‌بار برای هر شکل فراخوانی می‌شود. اگر این تابع چیزی به ژنراتور بنویسد، تولید تصویر اسلاید جاری تمام می‌شود، بخش HTML اضافه‌شده درج می‌شود و تصویر جدیدی بالای قبلی شروع خواهد شد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### writeShapeEnd(IHtmlGenerator generator, IShape shape) {#writeShapeEnd-com.aspose.slides.IHtmlGenerator-com.aspose.slides.IShape-}
```
public final void writeShapeEnd(IHtmlGenerator generator, IShape shape)
```


قبل از رندر کردن شکل فراخوانی می‌شود. یک‌بار برای هر شکل فراخوانی می‌شود. اگر این تابع چیزی به ژنراتور بنویسد، تولید تصویر اسلاید جاری تمام می‌شود، بخش HTML اضافه‌شده درج می‌شود و تصویر جدیدی بالای قبلی شروع خواهد شد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| generator | [IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### formatShape(ISvgShape svgShape, IShape shape) {#formatShape-com.aspose.slides.ISvgShape-com.aspose.slides.IShape-}
```
public final void formatShape(ISvgShape svgShape, IShape shape)
```


این تابع قبل از رندر کردن شکل به SVG فراخوانی می‌شود تا به کاربر اجازه دهد SVG حاصل را کنترل کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| svgShape | [ISvgShape](../../com.aspose.slides/isvgshape) |  |
| shape | [IShape](../../com.aspose.slides/ishape) |  |

### getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension) {#getObjectStoringLocation-int-byte---java.lang.String-java.lang.String-java.lang.String-}
```
public final int getObjectStoringLocation(int id, byte[] entityData, String semanticName, String contentType, String recomendedExtension)
```


مشخص می‌کند که شیء در کجا باید ذخیره شود. این متد یک‌بار برای هر شناسهٔ شیء فراخوانی می‌شود. تضمینی نیست که دو شیء با داده، semanticName و contentType یکسان ولی شناسهٔ متفاوت وجود نداشته باشند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | int |  |
| entityData | byte[] |  |
| semanticName | java.lang.String |  |
| contentType | java.lang.String |  |
| recomendedExtension | java.lang.String |  |

**باز می‌گرداند:**
int
### getUrl(int id, int referrer) {#getUrl-int-int-}
```
public final String getUrl(int id, int referrer)
```


یک URL به یک شیء خارجی برمی‌گرداند. این متد همیشه فراخوانی می‌شود اگر \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) مقدار [LinkEmbedDecision.Link](../../com.aspose.slides/linkembeddecision\#Link) بازگرداند و ممکن است فراخوانی شود اگر \#getObjectStoringLocation(int,byte[],String,String,String).getObjectStoringLocation(int,byte[],String,String,String) مقدار [LinkEmbedDecision.Embed](../../com.aspose.slides/linkembeddecision\#Embed) بازگرداند اما جاسازی امکان‌پذیر نیست. می‌تواند برای همان شناسهٔ شیء چندین بار فراخوانی شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| id | int |  |
| referrer | int |  |

**باز می‌گرداند:**
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