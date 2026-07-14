---
title: IShapeCollection
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: نمایانگر مجموعه‌ای از اشکال.
type: docs
url: /fa/com.aspose.slides/ishapecollection/
---
**تمام اینترفیس‌های پیاده‌سازی شده:**  
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

نمایانگر مجموعه‌ای از اشکال است.

## متدها

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصری که در اندیس مشخص شده قرار دارد را دریافت می‌کند. |
| [getParentGroup()](#getParentGroup--) | شیء شکل گروه والد را برای مجموعه اشکال دریافت می‌کند. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | یک دیاگرام SmartArt ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند و در اندیس مشخص شده در مجموعه اشکال درج می‌نماید. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند و در اندیس مشخص شده در مجموعه اشکال درج می‌نماید. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | یک قاب شیء OLE جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | یک قاب شیء OLE جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | یک قاب شیء OLE جدید ایجاد می‌کند و در اندیس مشخص شده در مجموعه اشکال درج می‌نماید. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | یک قاب شیء OLE جدید ایجاد می‌کند و در اندیس مشخص شده در مجموعه اشکال درج می‌نماید. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | یک قاب زوم جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | یک قاب زوم جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | یک قاب زوم جدید ایجاد می‌کند و در اندیس مشخص شده در مجموعه اشکال درج می‌نماید. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | یک قاب زوم جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و در اندیس مشخص شده در مجموعه اشکال درج می‌نماید. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | یک قاب Zoom بخش جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | یک قاب Zoom بخش جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | یک قاب Zoom بخش جدید ایجاد می‌کند و در اندیس مشخص شده در مجموعه اشکال درج می‌نماید. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | یک قاب Zoom بخش جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و در اندیس مشخص شده در مجموعه اشکال درج می‌نماید. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | یک قاب Zoom خلاصه جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | یک قاب Zoom خلاصه جدید ایجاد می‌کند و در اندیس مشخص شده در مجموعه اشکال درج می‌نماید. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | یک قاب ویدئویی جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | یک قاب ویدئویی جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | یک قاب ویدئویی جدید ایجاد می‌کند و در اندیس مشخص شده در مجموعه اشکال درج می‌نماید. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | یک قاب صوتی جدید که به یک ترک CD متصل است ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | یک قاب صوتی جدید که به یک ترک CD متصل است ایجاد می‌کند و در اندیس مشخص شده در مجموعه اشکال درج می‌نماید. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | یک قاب صوتی جدید که به یک فایل صوتی خارجی متصل است ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | یک قاب صوتی جدید که به یک فایل صوتی خارجی متصل است ایجاد می‌کند و در اندیس مشخص شده در مجموعه اشکال درج می‌نماید. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | یک قاب صوتی جدید با فایل WAV نهفته ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | یک قاب صوتی جدید ایجاد می‌کند و با استفاده از شیء صوتی موجود در لیست Presentation.Audios به انتهای مجموعه اشکال اضافه می‌نماید. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | یک قاب صوتی جدید با فایل WAV نهفته ایجاد می‌کند و در اندیس مشخص شده در مجموعه اشکال درج می‌نماید. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | یک قاب صوتی جدید ایجاد می‌کند و با استفاده از شیء صوتی موجود در لیست Presentation.Audios در اندیس مشخص شده در مجموعه اشکال درج می‌نماید. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | اندیس صفر-پایه اولین وقوع شکل مشخص‌شده در مجموعه را برمی‌گرداند. |
| [toArray()](#toArray--) | آرایه‌ای شامل تمام اشکال را ایجاد و برمی‌گرداند. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | آرایه‌ای شامل تمام اشکال در بازهٔ مشخص‌شده را ایجاد و برمی‌گرداند. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | شکل مشخص‌شده را به موقعیت جدیدی درون مجموعه اشکال جابه‌جا می‌کند. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | اشکال مشخص‌شده را درون مجموعه اشکال جابه‌جا می‌کند به‌طوری که از اندیس داده‌شده شروع شوند. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | یک شکل خودکار جدید با قالب‌بندی پیش‌فرض ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | یک شکل خودکار جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید؛ به‌اختیار می‌توانید آن را با قالب پیش‌فرض قالب‌بندی کنید. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | یک شکل خودکار مستطیلی جدید برای نگهداری محتوای ریاضی ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | یک شکل خودکار جدید ایجاد می‌کند و با قالب پیش‌فرض قالب‌بندی، در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | یک شکل خودکار جدید ایجاد می‌کند و به‌اختیار می‌توانید آن را با استایل پیش‌فرض قالب‌بندی کنید؛ سپس در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید. |
| [addGroupShape()](#addGroupShape--) | یک گروه شکل خالی جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | یک گروه شکل جدید ایجاد می‌کند، تصویر SVG مشخص‌شده را به اشکال جداگانه تبدیل می‌نماید و گروه به‌دست‌آمده را به انتهای مجموعه اشکال اضافه می‌کند. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | یک گروه شکل خالی جدید ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | یک شکل متصل‌کننده جدید با استایل پیش‌فرض قالب ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | یک شکل متصل‌کننده جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید؛ به‌اختیار می‌توانید استایل پیش‌فرض قالب را اعمال کنید. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | یک شکل متصل‌کننده جدید ایجاد می‌کند و با استایل پیش‌فرض قالب، در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | یک شکل متصل‌کننده جدید ایجاد می‌کند و به‌اختیار می‌توانید استایل پیش‌فرض قالب را اعمال کنید؛ سپس در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | یک قاب تصویر جدید شامل تصویر مشخص‌شده ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | یک قاب تصویر جدید شامل تصویر مشخص‌شده ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | یک جدول جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | یک جدول جدید ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید. |
| [removeAt(int index)](#removeAt-int-) | شکل موجود در اندیس مشخص‌شده را از مجموعه اشکال حذف می‌کند. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | اولین وقوع شکل مشخص‌شده را از مجموعه اشکال حذف می‌کند. |
| [clear()](#clear--) | تمام اشکال را از مجموعه اشکال حذف می‌کند. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

عنصری که در اندیس مشخص شده قرار دارد را دریافت می‌کند. فقط-خواندنی [IShape](../../com.aspose.slides/ishape).

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**بازگشت:**  
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

شیء شکل گروه والد را برای مجموعه اشکال دریافت می‌کند. فقط-خواندنی [IGroupShape](../../com.aspose.slides/igroupshape).

**بازگشت:**  
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | نوع نمودار برای افزودن. |
| x | float | مختصات X نمودار جدید، بر حسب پوینت. |
| y | float | مختصات Y نمودار جدید، بر حسب پوینت. |
| width | float | عرض نمودار، بر حسب پوینت. |
| height | float | ارتفاع نمودار، بر حسب پوینت. |

**بازگشت:**  
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) تازه‌ساخته.

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | نوع نمودار برای افزودن. |
| x | float | مختصات X نمودار جدید، بر حسب پوینت. |
| y | float | مختصات Y نمودار جدید، بر حسب پوینت. |
| width | float | عرض نمودار، بر حسب پوینت. |
| height | float | ارتفاع نمودار، بر حسب پوینت. |
| initWithSample | boolean | True برای مقداردهی اولیه نمودار با داده‌های نمونه؛ false برای ایجاد نمودار بدون سری و فقط تنظیمات حداقلی، که سرعت ایجاد را افزایش می‌دهد. |

**بازگشت:**  
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) تازه‌ساخته.

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

یک دیاگرام SmartArt ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>       ISlide slide = pres.getSlides().get_Item(0);
>       ISmartArt smart = slide.getShapes().addSmartArt(0, 0, 400, 400, SmartArtLayoutType.BasicBlockList);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X چارچوب دیاگرام، بر حسب پوینت. |
| y | float | مختصات Y چارچوب دیاگرام، بر حسب پوینت. |
| width | float | عرض چارچوب دیاگرام، بر حسب پوینت. |
| height | float | ارتفاع چارچوب دیاگرام، بر حسب پوینت. |
| layoutType | int | نوع طرح‌بندی SmartArt. |

**بازگشت:**  
[ISmartArt](../../com.aspose.slides/ismartart) - [ISmartArt](../../com.aspose.slides/ismartart) تازه‌ساخته.

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | نوع نموداری که باید ایجاد شود. |
| x | float | مختصات X نمودار جدید، بر حسب پوینت. |
| y | float | مختصات Y نمودار جدید، بر حسب پوینت. |
| width | float | عرض نمودار، بر حسب پوینت. |
| height | float | ارتفاع نمودار، بر حسب پوینت. |
| index | int | اندیس صفر-پایه‌ای که نمودار جدید در آن درج می‌شود. |

**بازگشت:**  
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) تازه‌ساخته.

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات اولیه می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | نوع نموداری که باید ایجاد شود. |
| x | float | مختصات X نمودار جدید، بر حسب پوینت. |
| y | float | مختصات Y نمودار جدید، بر حسب پوینت. |
| width | float | عرض نمودار، بر حسب پوینت. |
| height | float | ارتفاع نمودار، بر حسب پوینت. |
| index | int | اندیس صفر-پایه‌ای که نمودار جدید در آن درج می‌شود. |
| initWithSample | boolean | True برای مقداردهی اولیه نمودار با داده‌های نمونه؛ false برای ایجاد نمودار بدون سری و فقط تنظیمات حداقلی. |

**بازگشت:**  
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) تازه‌ساخته.

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

یک قاب شیء OLE جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X قاب OLE جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب OLE جدید، بر حسب پوینت. |
| width | float | عرض قاب OLE جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب OLE جدید، بر حسب پوینت. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | اطلاعات دادهٔ نهفتهٔ OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**بازگشت:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) تازه‌ساخته.

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

یک قاب شیء OLE جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X قاب OLE جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب OLE جدید، بر حسب پوینت. |
| width | float | عرض قاب OLE جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب OLE جدید، بر حسب پوینت. |
| className | java.lang.String | نام کلاس شیء OLE. |
| path | java.lang.String | مسیر فایل مرتبط.

این مسیر به‌صورت همان‌گونه در ارائه ذخیره می‌شود. اگر مسیر نسبی باشد، هنگام باز کردن ارائه از مسیر دیگری دسترسی به فایل امکان‌پذیر نخواهد بود. |

**بازگشت:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) تازه‌ساخته.

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

یک قاب شیء OLE جدید ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که قاب OLE در آن درج می‌شود. |
| x | float | مختصات X قاب OLE جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب OLE جدید، بر حسب پوینت. |
| width | float | عرض قاب OLE جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب OLE جدید، بر حسب پوینت. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | اطلاعات دادهٔ نهفتهٔ OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**بازگشت:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) تازه‌ساخته.

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

یک قاب شیء OLE جدید ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که قاب OLE در آن درج می‌شود. |
| x | float | مختصات X قاب OLE جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب OLE جدید، بر حسب پوینت. |
| width | float | عرض قاب OLE جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب OLE جدید، بر حسب پوینت. |
| className | java.lang.String | نام کلاس شیء OLE. |
| path | java.lang.String | مسیر فایل مرتبط.

این مسیر به‌صورت همان‌گونه در ارائه ذخیره می‌شود. اگر مسیر نسبی باشد، هنگام باز کردن ارائه از مسیر دیگری دسترسی به فایل امکان‌پذیر نخواهد بود. |

**بازگشت:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) تازه‌ساخته.

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

یک قاب Zoom جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

--------------------

> ```
> این مثال افزودن یک شیء Zoom به انتهای یک مجموعه را نشان می‌دهد
>  (فرض کنید که در ارائه "Presentation.pptx" حداقل دو اسلاید وجود دارد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X قاب Zoom جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب Zoom جدید، بر حسب پوینت. |
| width | float | عرض قاب Zoom جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب Zoom جدید، بر حسب پوینت. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) ای که توسط قاب Zoom اشاره می‌شود؛ باید متعلق به این ارائه باشد. |

**بازگشت:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) تازه‌ساخته.

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

یک قاب Zoom جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

--------------------

> ```
> این مثال افزودن یک شیء Zoom به انتهای یک مجموعه را نشان می‌دهد
>  (فرض کنید که در ارائه "Presentation.pptx" حداقل دو اسلاید وجود دارد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X قاب Zoom جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب Zoom جدید، بر حسب پوینت. |
| width | float | عرض قاب Zoom جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب Zoom جدید، بر حسب پوینت. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) ای که توسط قاب Zoom اشاره می‌شود؛ باید متعلق به این ارائه باشد. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | تصویر برای [IPPImage](../../com.aspose.slides/ippimage) اسلاید اشاره‌شده. |

**بازگشت:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) تازه‌ساخته.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

یک قاب Zoom جدید ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید.

--------------------

> ```
> این مثال ایجاد و درج یک شیء Zoom در اندیس مشخص‌شدهٔ یک مجموعه را نشان می‌دهد
>  (فرض کنید که در ارائه "Presentation.pptx" حداقل دو اسلاید وجود دارد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که قاب Zoom در آن درج می‌شود. |
| x | float | مختصات X قاب Zoom جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب Zoom جدید، بر حسب پوینت. |
| width | float | عرض قاب Zoom جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب Zoom جدید، بر حسب پوینت. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) ای که توسط قاب Zoom اشاره می‌شود. |

**بازگشت:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) تازه‌ساخته.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

یک قاب Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید.

--------------------

> ```
> این مثال ایجاد و درج یک شیء Zoom در اندیس مشخص‌شدهٔ یک مجموعه را نشان می‌دهد
>  (فرض کنید که در ارائه "Presentation.pptx" حداقل دو اسلاید وجود دارد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(imageBytes);
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که قاب Zoom در آن درج می‌شود. |
| x | float | مختصات X قاب Zoom جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب Zoom جدید، بر حسب پوینت. |
| width | float | عرض قاب Zoom جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب Zoom جدید، بر حسب پوینت. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) ای که توسط قاب Zoom اشاره می‌شود. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | تصویر برای [IPPImage](../../com.aspose.slides/ippimage) اسلاید اشاره‌شده. |

**بازگشت:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) تازه‌ساخته.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

یک قاب Zoom بخش جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

--------------------

> ```
> این مثال افزودن یک شیء Section Zoom به انتهای یک مجموعه را نشان می‌دهد
>  (فرض کنید که در ارائه "Presentation.pptx" حداقل دو بخش وجود دارد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X قاب Zoom بخش جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب Zoom بخش جدید، بر حسب پوینت. |
| width | float | عرض قاب Zoom بخش جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب Zoom بخش جدید، بر حسب پوینت. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) ای که توسط قاب Zoom بخش اشاره می‌شود؛ باید متعلق به این ارائه باشد و حداقل یک اسلاید داشته باشد. |

**بازگشت:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) تازه‌ساخته.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

یک قاب Zoom بخش جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

--------------------

> ```
> این مثال افزودن یک شیء Section Zoom به انتهای یک مجموعه را نشان می‌دهد
>  (فرض کنید که در ارائه "Presentation.pptx" حداقل دو بخش وجود دارد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X قاب Zoom بخش جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب Zoom بخش جدید، بر حسب پوینت. |
| width | float | عرض قاب Zoom بخش جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب Zoom بخش جدید، بر حسب پوینت. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) ای که توسط قاب Zoom بخش اشاره می‌شود؛ باید متعلق به این ارائه باشد و حداقل یک اسلاید داشته باشد. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) برای نمایش در قاب Zoom بخش. |

**بازگشت:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) تازه‌ساخته.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

یک قاب Zoom بخش جدید ایجاد می‌کند و به‌صورت نادرست به مجموعه اشکال در اندیس مشخص‌شده درج می‌نماید.

--------------------

> ```
> این مثال ایجاد و درج یک شیء Section Zoom در اندیس مشخص‌شدهٔ یک مجموعه را نشان می‌دهد
>  (فرض کنید که در ارائه "Presentation.pptx" حداقل دو بخش وجود دارد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که قاب Zoom بخش در آن درج می‌شود. |
| x | float | مختصات X قاب Zoom بخش جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب Zoom بخش جدید، بر حسب پوینت. |
| width | float | عرض قاب Zoom بخش جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب Zoom بخش جدید، بر حسب پوینت. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) ای که توسط قاب Zoom بخش اشاره می‌شود؛ باید متعلق به این ارائه باشد و حداقل یک اسلاید داشته باشد. |

**بازگشت:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) تازه‌ساخته.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

یک قاب Zoom بخش جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و به‌صورت نادرست به مجموعه اشکال در اندیس مشخص‌شده درج می‌نماید.

--------------------

> ```
> این مثال ایجاد و درج یک شیء Section Zoom در اندیس مشخص‌شدهٔ یک مجموعه را نشان می‌دهد
>  (فرض کنید که در ارائه "Presentation.pptx" حداقل دو بخش وجود دارد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      FileInputStream fos = null;
>      try {
>          fos = new FileInputStream("image.png");
>          IPPImage image = pres.getImages().addImage(fos);
>          ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>      } finally {
>          if (fos != null) fos.close();
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که قاب Zoom بخش در آن درج می‌شود. |
| x | float | مختصات X قاب Zoom بخش جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب Zoom بخش جدید، بر حسب پوینت. |
| width | float | عرض قاب Zoom بخش جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب Zoom بخش جدید، بر حسب پوینت. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) ای که توسط قاب Zoom بخش اشاره می‌شود؛ باید متعلق به این ارائه باشد و حداقل یک اسلاید داشته باشد. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | تصویر برای نمایش در قاب Zoom بخش. |

**بازگشت:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) تازه‌ساخته.

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

یک قاب Zoom خلاصه جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

--------------------

> ```
> این مثال افزودن یک شیء Summary Zoom به انتهای یک مجموعه را نشان می‌دهد
>  (فرض کنید که در ارائه "Presentation.pptx" حداقل دو بخش وجود دارد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X قاب Zoom خلاصه جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب Zoom خلاصه جدید، بر حسب پوینت. |
| width | float | عرض قاب Zoom خلاصه جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب Zoom خلاصه جدید، بر حسب پوینت. |

این متد یک قاب Zoom خلاصه ایجاد می‌کند که لینک‌های خلاصه را برای تمام بخش‌های ارائه جمع‌آوری می‌کند.  

**بازگشت:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) تازه‌ساخته.

### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

یک قاب Zoom خلاصه جدید ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید.

--------------------

> ```
> This example demonstrates creation and inserting a Summary Zoom object at the specified index of a collection
>  (assume that there are at least two sections in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که قاب Zoom خلاصه در آن درج می‌شود. |
| x | float | مختصات X قاب Zoom خلاصه جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب Zoom خلاصه جدید، بر حسب پوینت. |
| width | float | عرض قاب Zoom خلاصه جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب Zoom خلاصه جدید، بر حسب پوینت. |

این متد یک قاب Zoom خلاصه ایجاد می‌کند که لینک‌های خلاصه را برای تمام بخش‌های ارائه جمع‌آوری می‌کند.  

**بازگشت:**  
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) تازه‌ساخته.

### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

یک قاب ویدئویی جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X قاب ویدئویی جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب ویدئویی جدید، بر حسب پوینت. |
| width | float | عرض قاب ویدئویی جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب ویدئویی جدید، بر حسب پوینت. |
| fname | java.lang.String | مسیر یا نام فایل ویدئویی برای درج. |

**بازگشت:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) تازه‌ساخته.

### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

یک قاب ویدئویی جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X قاب ویدئویی جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب ویدئویی جدید، بر حسب پوینت. |
| width | float | عرض قاب ویدئویی جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب ویدئویی جدید، بر حسب پوینت. |
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) برای درج در قاب ویدئویی. |

**بازگشت:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) تازه‌ساخته.

### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

یک قاب ویدئویی جدید ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که قاب ویدئویی در آن درج می‌شود. |
| x | float | مختصات X قاب ویدئویی جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب ویدئویی جدید، بر حسب پوینت. |
| width | float | عرض قاب ویدئویی جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب ویدئویی جدید، بر حسب پوینت. |
| fname | java.lang.String | مسیر یا نام فایل ویدئویی برای درج. |

**بازگشت:**  
[IVideoFrame](../../com.aspose.slides/ivideoframe) - [IVideoFrame](../../com.aspose.slides/ivideoframe) تازه‌ساخته.

### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

یک قاب صوتی جدید که به یک ترک CD متصل است ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X قاب صوتی جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب صوتی جدید، بر حسب پوینت. |
| width | float | عرض قاب صوتی جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب صوتی جدید، بر حسب پوینت. |

**بازگشت:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه‌ساخته.

### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

یک قاب صوتی جدید که به یک ترک CD متصل است ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که قاب صوتی در آن درج می‌شود. |
| x | float | مختصات X قاب صوتی جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب صوتی جدید، بر حسب پوینت. |
| width | float | عرض قاب صوتی جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب صوتی جدید، بر حسب پوینت. |

**بازگشت:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه‌ساخته.

### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

یک قاب صوتی جدید که به یک فایل صوتی خارجی متصل است ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X قاب صوتی جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب صوتی جدید، بر حسب پوینت. |
| width | float | عرض قاب صوتی جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب صوتی جدید، بر حسب پوینت. |
| fname | java.lang.String | مسیر یا نام فایل صوتی خارجی برای لینک. |

**بازگشت:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه‌ساخته.

### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

یک قاب صوتی جدید که به یک فایل صوتی خارجی متصل است ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که قاب صوتی در آن درج می‌شود. |
| x | float | مختصات X قاب صوتی جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب صوتی جدید، بر حسب پوینت. |
| width | float | عرض قاب صوتی جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب صوتی جدید، بر حسب پوینت. |
| fname | java.lang.String | مسیر یا نام فایل صوتی خارجی برای لینک. |

**بازگشت:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه‌ساخته.

### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

یک قاب صوتی جدید با فایل WAV نهفته ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. صوت نهفته به مجموعه Presentation.Audios اضافه می‌شود.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X قاب صوتی جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب صوتی جدید، بر حسب پوینت. |
| width | float | عرض قاب صوتی جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب صوتی جدید، بر حسب پوینت. |
| audio_stream | java.io.InputStream | جریان ورودی شامل داده‌های صوتی WAV برای نهفته‌سازی. |

**بازگشت:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه‌ساخته.

### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

یک قاب صوتی جدید ایجاد می‌کند و با استفاده از شیء صوتی موجود در لیست Presentation.Audios به انتهای مجموعه اشکال اضافه می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X قاب صوتی جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب صوتی جدید، بر حسب پوینت. |
| width | float | عرض قاب صوتی جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب صوتی جدید، بر حسب پوینت. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | یک نمونهٔ [IAudio](../../com.aspose.slides/iaudio) از مجموعه Presentation.Audios. |

**بازگشت:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه‌ساخته.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

یک قاب صوتی جدید با فایل WAV نهفته ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید. صوت نهفته به مجموعه Presentation.Audios اضافه می‌شود.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که قاب صوتی در آن درج می‌شود. |
| x | float | مختصات X قاب صوتی جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب صوتی جدید، بر حسب پوینت. |
| width | float | عرض قاب صوتی جدید, بر حسب پوینت. |
| height | float | ارتفاع قاب صوتی جدید, بر حسب پوینت. |
| audio_stream | java.io.InputStream | جریان ورودی شامل داده‌های صوتی WAV برای نهفته‌سازی. |

**بازگشت:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه‌ساخته.

### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

یک قاب صوتی جدید ایجاد می‌کند و با استفاده از شیء صوتی موجود در لیست Presentation.Audios در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که قاب صوتی در آن درج می‌شود. |
| x | float | مختصات X قاب صوتی جدید، بر حسب پوینت. |
| y | float | مختصات Y قاب صوتی جدید، بر حسب پوینت. |
| width | float | عرض قاب صوتی جدید، بر حسب پوینت. |
| height | float | ارتفاع قاب صوتی جدید، بر حسب پوینت. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | یک نمونهٔ [IAudio](../../com.aspose.slides/iaudio) از مجموعه Presentation.Audios برای نهفته‌سازی. |

**بازگشت:**  
[IAudioFrame](../../com.aspose.slides/iaudioframe) - [IAudioFrame](../../com.aspose.slides/iaudioframe) تازه‌ساخته.

### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

اندیس صفر-پایه‌ای اولین وقوع شکل مشخص‌شده در مجموعه را برمی‌گرداند.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | شکلی که باید در مجموعه پیدا شود. |

**بازگشت:**  
int - اندیس صفر-پایه‌ای اولین وقوع شکل در مجموعه‌ اشکال؛ اگر یافت نشد، \\u20131.

### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

یک آرایه که شامل تمام اشکال است ایجاد و برمی‌گرداند.

**بازگشت:**  
com.aspose.slides.IShape[] - آرایه‌ای از اشیاء [IShape](../../com.aspose.slides/ishape).

### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

یک آرایه که شامل تمام اشکال در بازهٔ مشخص‌شده است ایجاد و برمی‌گرداند.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| startIndex | int | اندیس اولین شکلی که باید برگردانده شود. |
| count | int | تعداد اشکالی که باید برگردانده شود. |

**بازگشت:**  
com.aspose.slides.IShape[] - آرایه‌ای از اشیاء [IShape](../../com.aspose.slides/ishape).

### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

شکل مشخص‌شده را به موقعیت جدیدی درون مجموعه اشکال جابه‌جا می‌کند.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس هدف صفر-پایه‌ای که شکل در آن قرار می‌گیرد. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape)ی که باید در مجموعه جابه‌جا شود. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

اشکال مشخص‌شده را درون مجموعه اشکال جابه‌جا می‌کند به‌طوری که از اندیس داده‌شده شروع شوند.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس هدف صفر-پایه‌ای که اولین شکل مشخص‌شده در آن قرار می‌گیرد؛ شکل‌های بعدی به ترتیب ارائه‌شده دنبال می‌شوند. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | یک یا چند نمونهٔ [IShape](../../com.aspose.slides/ishape) برای جابه‌جایی درون مجموعه. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

یک شکل خودکار جدید با قالب‌بندی پیش‌فرض ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) شکل خودکار برای افزودن. |
| x | float | مختصات X چارچوب شکل، بر حسب پوینت. |
| y | float | مختصات Y چارچوب شکل، بر حسب پوینت. |
| width | float | عرض چارچوب شکل، بر حسب پوینت. |
| height | float | ارتفاع چارچوب شکل، بر حسب پوینت. |

**بازگشت:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) تازه‌ساخته.

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

یک شکل خودکار جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند؛ به‌اختیار می‌توانید آن را با قالب پیش‌فرض قالب‌بندی کنید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) شکل خودکار برای افزودن. |
| x | float | مختصات X چارچوب شکل، بر حسب پوینت. |
| y | float | مختصات Y چارچوب شکل، بر حسب پوینت. |
| width | float | عرض چارچوب شکل، بر حسب پوینت. |
| height | float | ارتفاع چارچوب شکل، بر حسب پوینت. |
| createFromTemplate | boolean | True برای اعمال استایل پیش‌فرض قالب (سبک ساده، متن‌مرکزی و نام غیرخالی)؛ false برای ایجاد شکلی با تمام خصوصیات پیش‌فرض. |

**بازگشت:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) تازه‌ساخته.

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

یک شکل خودکار مستطیلی جدید برای میزبانی محتوای ریاضی ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X چارچوب شکل، بر حسب پوینت. |
| y | float | مختصات Y چارچوب شکل، بر حسب پوینت. |
| width | float | عرض چارچوب شکل، بر حسب پوینت. |
| height | float | ارتفاع چارچوب شکل، بر حسب پوینت. |

**بازگشت:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) تازه‌ساخته.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

یک شکل خودکار جدید ایجاد می‌کند و با اعمال قالب پیش‌فرض، در اندیس مشخص‌شده در مجموعه اشکال درج می‌کند.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که شکل خودکار جدید در آن درج می‌شود. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) شکل خودکار برای درج. |
| x | float | مختصات X چارچوب شکل، بر حسب پوینت. |
| y | float | مختصات Y چارچوب شکل، بر حسب پوینت. |
| width | float | عرض چارچوب شکل، بر حسب پوینت. |
| height | float | ارتفاع چارچوب شکل، بر حسب پوینت. |

**بازگشت:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) تازه‌ساخته.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

یک شکل خودکار جدید ایجاد می‌کند و به‌اختیار می‌توانید آن را با قالب پیش‌فرض قالب‌بندی کنید؛ سپس در اندیس مشخص‌شده در مجموعه اشکال درج می‌کند.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که شکل خودکار در آن درج می‌شود. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) شکل خودکار برای درج. |
| x | float | مختصات X چارچوب شکل، بر حسب پوینت. |
| y | float | مختصات Y چارچوب شکل، بر حسب پوینت. |
| width | float | عرض چارچوب شکل، بر حسب پوینت. |
| height | float | ارتفاع چارچوب شکل، بر حسب پوینت. |
| createFromTemplate | boolean | True برای اعمال استایل پیش‌فرض قالب (نام غیرخالی، سبک ساده، متن‌مرکزی)؛ false برای ایجاد شکلی با تمام خصوصیات پیش‌فرض. |

**بازگشت:**  
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) تازه‌ساخته.

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

یک گروه شکل خالی جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید. قاب گروه به‌صورت خودکار برای دربرگیری هر شکلی که به آن اضافه می‌شود، تنظیم می‌شود.

**بازگشت:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) تازه‌ساخته.

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

یک گروه شکل جدید ایجاد می‌کند، تصویر SVG مشخص‌شده را به اشکال جداگانه تبدیل می‌کند و گروه حاصل را به انتهای مجموعه اشکال اضافه می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage) حاوی محتویات برداری برای تبدیل به اشکال. |
| x | float | مختصات X قاب گروه، بر حسب پوینت. |
| y | float | مختصات Y قاب گروه، بر حسب پوینت. |
| width | float | عرض قاب گروه، بر حسب پوینت. |
| height | float | ارتفاع قاب گروه، بر حسب پوینت. |

**بازگشت:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) تازه‌ساخته.

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

یک گروه شکل خالی جدید ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید. قاب گروه به‌صورت خودکار برای دربرگیری هر شکلی که به آن اضافه می‌شود، تنظیم می‌شود.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که گروه شکل در آن درج می‌شود. |

**بازگشت:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) تازه‌ساخته.

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

یک شکل متصل‌کننده جدید با استایل قالب پیش‌فرض ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) شکل متصل‌کننده برای افزودن. |
| x | float | مختصات X چارچوب متصل‌کننده، بر حسب پوینت. |
| y | float | مختصات Y چارچوب متصل‌کننده، بر حسب پوینت. |
| width | float | عرض چارچوب متصل‌کننده، بر حسب پوینت. |
| height | float | ارتفاع چارچوب متصل‌کننده، بر حسب پوینت. |

**بازگشت:**  
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) تازه‌ساخته.

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

یک شکل متصل‌کننده جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند؛ به‌اختیار می‌توانید استایل قالب پیش‌فرض را اعمال کنید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) شکل متصل‌کننده برای ایجاد. |
| x | float | مختصات X چارچوب متصل‌کننده، بر حسب پوینت. |
| y | float | مختصات Y چارچوب متصل‌کننده، بر حسب پوینت. |
| width | float | عرض چارچوب متصل‌کننده، بر حسب پوینت. |
| height | float | ارتفاع چارچوب متصل‌کننده، بر حسب پوینت. |
| createFromTemplate | boolean | True برای اعمال استایل قالب پیش‌فرض (نام غیرخالی، سبک ساده)؛ false برای ایجاد متصل‌کننده با مقادیر پیش‌فرض. |

**بازگشت:**  
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) تازه‌ساخته.

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

یک شکل متصل‌کننده جدید ایجاد می‌کند و با اعمال استایل قالب پیش‌فرض، در اندیس مشخص‌شده در مجموعه اشکال درج می‌کند.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که متصل‌کننده در آن درج می‌شود. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) شکل متصل‌کننده برای درج. |
| x | float | مختصات X چارچوب متصل‌کننده، بر حسب پوینت. |
| y | float | مختصات Y چارچوب متصل‌کننده، بر حسب پوینت. |
| width | float | عرض چارچوب متصل‌کننده، بر حسب پوینت. |
| height | float | ارتفاع چارچوب متصل‌کننده، بر حسب پوینت. |

**بازگشت:**  
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) تازه‌ساخته.

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

یک شکل متصل‌کننده جدید ایجاد می‌کند و به‌اختیار می‌توانید استایل قالب پیش‌فرض را اعمال کنید؛ سپس در اندیس مشخص‌شده در مجموعه اشکال درج می‌کند.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که متصل‌کننده در آن درج می‌شود. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) شکل متصل‌کننده برای درج. |
| x | float | مختصات X چارچوب متصل‌کننده، بر حسب پوینت. |
| y | float | مختصات Y چارچوب متصل‌کننده، بر حسب پوینت. |
| width | float | عرض چارچوب متصل‌کننده، بر حسب پوینت. |
| height | float | ارتفاع چارچوب متصل‌کننده، بر حسب پوینت. |
| createFromTemplate | boolean | True برای اعمال استایل قالب پیش‌فرض (نام غیرخالی، سبک ساده)؛ false برای ایجاد متصل‌کننده با مقادیر پیش‌فرض. |

**بازگشت:**  
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) تازه‌ساخته.

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

یک قاب تصویر جدید حاوی تصویر مشخص‌شده ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | int | نوع شکلی که در [ShapeType](../../com.aspose.slides/shapetype) قرار می‌گیرد، به‌جز تمام انواع خطوط: ShapeType.Line, ShapeType.StraightConnector1, … |
| x | float | مختصات X قاب تصویر، بر حسب پوینت. |
| y | float | مختصات Y قاب تصویر، بر حسب پوینت. |
| width | float | عرض قاب تصویر، بر حسب پوینت. |
| height | float | ارتفاع قاب تصویر، بر حسب پوینت. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) برای نمایش در قاب تصویر. |

**بازگشت:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) تازه‌ساخته.

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

یک قاب تصویر جدید حاوی تصویر مشخص‌شده ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که قاب تصویر در آن درج می‌شود. |
| shapeType | int | نوع شکلی که در [ShapeType](../../com.aspose.slides/shapetype) قرار می‌گیرد، به‌جز تمام انواع خطوط: ShapeType.Line, ShapeType.StraightConnector1, … |
| x | float | مختصات X قاب تصویر، بر حسب پوینت. |
| y | float | مختصات Y قاب تصویر، بر حسب پوینت. |
| width | float | عرض قاب تصویر، بر حسب پوینت. |
| height | float | ارتفاع قاب تصویر، بر حسب پوینت. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) برای نمایش در قاب تصویر. |

**بازگشت:**  
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) تازه‌ساخته.

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

یک جدول جدید ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| x | float | مختصات X جدول، بر حسب پوینت. |
| y | float | مختصات Y جدول، بر حسب پوینت. |
| columnWidths | double[] | آرایه‌ای از مقادیر دوگانه برای عرض ستون‌های جدول، بر حسب پوینت. |
| rowHeights | double[] | آرایه‌ای از مقادیر دوگانه برای ارتفاع ردیف‌های جدول، بر حسب پوینت. |

**بازگشت:**  
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) تازه‌ساخته.

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```

یک جدول جدید ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که جدول در آن درج می‌شود. |
| x | float | مختصات X جدول، بر حسب پوینت. |
| y | float | مختصات Y جدول، بر حسب پوینت. |
| columnWidths | double[] | آرایه‌ای از مقادیر دوگانه برای عرض ستون‌های جدول، بر حسب پوینت. |
| rowHeights | double[] | آرایه‌ای از مقادیر دوگانه برای ارتفاع ردیف‌های جدول، بر حسب پوینت. |

**بازگشت:**  
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) تازه‌ساخته.

### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

شکل موجود در اندیس مشخص‌شده را از مجموعه اشکال حذف می‌کند.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای شکل برای حذف. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

اولین وقوع شکل مشخص‌شده را از مجموعه اشکال حذف می‌کند.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای حذف. |

### clear() {#clear--}
```
public abstract void clear()
```

تمام اشکال را از مجموعه اشکال حذف می‌کند.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

یک کپی از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌نماید.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | شکلی که باید کلون شود. |
| x | float | مختصات X قاب شکل کلون‌شده، بر حسب پوینت. |
| y | float | مختصات Y قاب شکل کلون‌شده، بر حسب پوینت. |
| width | float | عرض قاب شکل کلون‌شده، بر حسب پوینت. |
| height | float | ارتفاع قاب شکل کلون‌شده، بر حسب پوینت. |

**بازگشت:**  
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) تازه‌ساخته.

### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

یک کپی از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند. شکل جدید عرض و ارتفاع shape اصلی را حفظ می‌کند.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای کلون. |
| x | float | مختصات X قاب شکل کلون‌شده، بر حسب پوینت. |
| y | float | مختصات Y قاب شکل کلون‌شده، برحسب پوینت. |

**بازگشت:**  
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) تازه‌ساخته.

### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

یک کپی از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعه اشکال اضافه می‌کند. شکل کلون‌شده موقعیت و ابعاد اصلی را حفظ می‌کند.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای کلون. |

**بازگشت:**  
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) تازه‌ساخته.

### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

یک کپی از شکل مشخص‌شده ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌کند.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که شکل کلون‌شده در آن درج می‌شود. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای کلون. |
| x | float | مختصات X قاب شکل کلون‌شده، بر حسب پوینت. |
| y | float | مختصات Y قاب شکل کلون‌شده، بر حسب پوینت. |
| width | float | عرض قاب شکل کلون‌شده، بر حسب پوینت. |
| height | float | ارتفاع قاب شکل کلون‌شده، بر حسب پوینت. |

**بازگشت:**  
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) تازه‌ساخته.

### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

یک کپی از شکل مشخص‌شده ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌کند؛ شکل جدید عرض و ارتفاع shape اصلی را حفظ می‌کند.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که شکل کلون‌شده در آن درج می‌شود. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای کلون. |
| x | float | مختصات X قاب شکل کلون‌شده، بر حسب پوینت. |
| y | float | مختصات Y قاب شکل کلون‌شده، بر حسب پوینت. |

**بازگشت:**  
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) تازه‌ساخته.

### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

یک کپی از شکل مشخص‌شده ایجاد می‌کند و در اندیس مشخص‌شده در مجموعه اشکال درج می‌کند؛ شکل کلون‌شده موقعیت و ابعاد اصلی را حفظ می‌کند.

**پارامترها:**  
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | اندیس صفر-پایه‌ای که شکل کلون‌شده در آن درج می‌شود. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای کلون. |

**بازگشت:**  
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) تازه‌ساخته.