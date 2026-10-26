---
title: IShapeCollection
second_title: مرجع API Aspose.Slides برای جاوا
description: یک مجموعه از اشکال را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/ishapecollection/
---
**تمام رابط‌های پیاده‌سازی شده:**  
com.aspose.slides.IGenericCollection
```
public interface IShapeCollection extends IGenericCollection<IShape>
```

نمایانگر یک مجموعه از اشکال است.

## متدها

| متد | توضیح |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | عنصر را در اندیس مشخص شده دریافت می‌کند. |
| [getParentGroup()](#getParentGroup--) | شیء گروه والد شکل‌ها را برای مجموعهٔ اشکال دریافت می‌کند. |
| [addChart(int type, float x, float y, float width, float height)](#addChart-int-float-float-float-float-) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات مقداردهی اولیه می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [addChart(int type, float x, float y, float width, float height, boolean initWithSample)](#addChart-int-float-float-float-float-boolean-) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات مقداردهی اولیه می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [addSmartArt(float x, float y, float width, float height, int layoutType)](#addSmartArt-float-float-float-float-int-) | یک نمودار SmartArt ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [insertChart(int type, float x, float y, float width, float height, int index)](#insertChart-int-float-float-float-float-int-) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات مقداردهی اولیه می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)](#insertChart-int-float-float-float-float-int-boolean-) | یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات مقداردهی اولیه می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | یک چارچوب شیء OLE جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [addOleObjectFrame(float x, float y, float width, float height, String className, String path)](#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-) | یک چارچوب شیء OLE جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)](#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-) | یک چارچوب شیء OLE جدید ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)](#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-) | یک چارچوب شیء OLE جدید ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-) | یک چارچوب Zoom جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)](#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | یک چارچوب Zoom جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-) | یک چارچوب Zoom جدید ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)](#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-) | یک چارچوب Zoom جدید با تصویری از پیش تعیین‌شده ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-) | یک چارچوب Section Zoom جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)](#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | یک چارچوب Section Zoom جدید با تصویری از پیش تعیین‌شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-) | یک چارچوب Section Zoom جدید ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)](#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-) | یک چارچوب Section Zoom جدید با تصویری از پیش تعیین‌شده ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [addSummaryZoomFrame(float x, float y, float width, float height)](#addSummaryZoomFrame-float-float-float-float-) | یک چارچوب Summary Zoom جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [insertSummaryZoomFrame(int index, float x, float y, float width, float height)](#insertSummaryZoomFrame-int-float-float-float-float-) | یک چارچوب Summary Zoom جدید ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [addVideoFrame(float x, float y, float width, float height, String fname)](#addVideoFrame-float-float-float-float-java.lang.String-) | یک چارچوب ویدئویی جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [addVideoFrame(float x, float y, float width, float height, IVideo video)](#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-) | یک چارچوب ویدئویی جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [insertVideoFrame(int index, float x, float y, float width, float height, String fname)](#insertVideoFrame-int-float-float-float-float-java.lang.String-) | یک چارچوب ویدئویی جدید ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [addAudioFrameCD(float x, float y, float width, float height)](#addAudioFrameCD-float-float-float-float-) | یک چارچوب صوتی جدید مرتبط با یک ترک CD ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [insertAudioFrameCD(int index, float x, float y, float width, float height)](#insertAudioFrameCD-int-float-float-float-float-) | یک چارچوب صوتی جدید مرتبط با یک ترک CD ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [addAudioFrameLinked(float x, float y, float width, float height, String fname)](#addAudioFrameLinked-float-float-float-float-java.lang.String-) | یک چارچوب صوتی جدید مرتبط با یک فایل صوتی خارجی ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)](#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-) | یک چارچوب صوتی جدید مرتبط با یک فایل صوتی خارجی ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)](#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-) | یک چارچوب صوتی جدید با فایل WAV تعبیه‌شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)](#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-) | یک چارچوب صوتی جدید ایجاد می‌کند و با استفاده از شیء صوتی موجود در لیست Presentation.Audios به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)](#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-) | یک چارچوب صوتی جدید با فایل WAV تعبیه‌شده ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)](#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-) | یک چارچوب صوتی جدید ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند؛ در صورت تمایل از شیء صوتی موجود در لیست Presentation.Audios استفاده می‌کند. |
| [indexOf(IShape shape)](#indexOf-com.aspose.slides.IShape-) | شاخص مبتنی بر صفر اولین رخداد شکل مشخص‌شده را در مجموعه برمی‌گرداند. |
| [toArray()](#toArray--) | یک آرایه شامل تمام اشکال ایجاد و برمی‌گرداند. |
| [toArray(int startIndex, int count)](#toArray-int-int-) | یک آرایه شامل تمام اشکال در بازهٔ مشخص‌شده ایجاد و برمی‌گرداند. |
| [reorder(int index, IShape shape)](#reorder-int-com.aspose.slides.IShape-) | شکل مشخص‌شده را به موقعیت جدیدی درون مجموعهٔ اشکال منتقل می‌کند. |
| [reorder(int index, IShape[] shapes)](#reorder-int-com.aspose.slides.IShape...-) | اشکال مشخص‌شده را درون مجموعهٔ اشکال حرکت می‌دهد و آن‌ها را از اندیس داده‌شده آغاز می‌کند. |
| [addAutoShape(int shapeType, float x, float y, float width, float height)](#addAutoShape-int-float-float-float-float-) | یک شکل خودکار جدید با قالب‌بندی پیش‌فرض ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addAutoShape-int-float-float-float-float-boolean-) | یک شکل خودکار جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد؛ در صورت تمایل با قالب‌بندی پیش‌فرض قالب اولیه مقداردهی می‌کند. |
| [addMathShape(float x, float y, float width, float height)](#addMathShape-float-float-float-float-) | یک شکل خودکار مستطیلی جدید برای محتویات ریاضی ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height)](#insertAutoShape-int-int-float-float-float-float-) | یک شکل خودکار جدید ایجاد می‌کند و با اعمال قالب‌بندی پیش‌فرض قالب، در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertAutoShape-int-int-float-float-float-float-boolean-) | یک شکل خودکار جدید ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند؛ در صورت تمایل با سبک پیش‌فرض قالب مقداردهی می‌کند. |
| [addGroupShape()](#addGroupShape--) | یک شکل گروهی خالی جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)](#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-) | یک شکل گروهی جدید ایجاد می‌کند، تصویر SVG مشخص‌شده را به اشکال منفرد تبدیل می‌کند و گروه حاصل را به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [insertGroupShape(int index)](#insertGroupShape-int-) | یک شکل گروهی خالی جدید ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [addConnector(int shapeType, float x, float y, float width, float height)](#addConnector-int-float-float-float-float-) | یک شکل اتصال جدید با سبک پیش‌فرض قالب ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#addConnector-int-float-float-float-float-boolean-) | یک شکل اتصال جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد؛ در صورت تمایل سبک پیش‌فرض قالب را اعمال می‌کند. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height)](#insertConnector-int-int-float-float-float-float-) | یک شکل اتصال جدید ایجاد می‌کند و سبک پیش‌فرض قالب را اعمال کرده و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)](#insertConnector-int-int-float-float-float-float-boolean-) | یک شکل اتصال جدید ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند؛ در صورت تمایل سبک پیش‌فرض قالب را اعمال می‌کند. |
| [addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)](#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-) | یک چارچوب تصویر جدید شامل تصویر مشخص‌شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)](#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-) | یک چارچوب تصویر جدید شامل تصویر مشخص‌شده ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [addTable(float x, float y, double[] columnWidths, double[] rowHeights)](#addTable-float-float-double---double---) | یک جدول جدید ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)](#insertTable-int-float-float-double---double---) | یک جدول جدید ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [removeAt(int index)](#removeAt-int-) | شکل را در اندیس مشخص از مجموعهٔ اشکال حذف می‌کند. |
| [remove(IShape shape)](#remove-com.aspose.slides.IShape-) | اولین رخداد شکل مشخص‌شده را از مجموعهٔ اشکال حذف می‌کند. |
| [clear()](#clear--) | تمامی اشکال را از مجموعهٔ اشکال حذف می‌کند. |
| [addClone(IShape sourceShape, float x, float y, float width, float height)](#addClone-com.aspose.slides.IShape-float-float-float-float-) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [addClone(IShape sourceShape, float x, float y)](#addClone-com.aspose.slides.IShape-float-float-) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [addClone(IShape sourceShape)](#addClone-com.aspose.slides.IShape-) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد. |
| [insertClone(int index, IShape sourceShape, float x, float y, float width, float height)](#insertClone-int-com.aspose.slides.IShape-float-float-float-float-) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [insertClone(int index, IShape sourceShape, float x, float y)](#insertClone-int-com.aspose.slides.IShape-float-float-) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |
| [insertClone(int index, IShape sourceShape)](#insertClone-int-com.aspose.slides.IShape-) | یک کپی از شکل مشخص‌شده ایجاد می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند. |

### get_Item(int index) {#get-Item-int-}
```
public abstract IShape get_Item(int index)
```

عنصر را در اندیس مشخص دریافت می‌کند. فقط-خواندنی [IShape](../../com.aspose.slides/ishape).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int |  |

**بازگشت:**
[IShape](../../com.aspose.slides/ishape)

### getParentGroup() {#getParentGroup--}
```
public abstract IGroupShape getParentGroup()
```

شیء گروه والد شکل‌ها را برای مجموعهٔ اشکال دریافت می‌کند. فقط-خواندنی [IGroupShape](../../com.aspose.slides/igroupshape).

**بازگشت:**
[IGroupShape](../../com.aspose.slides/igroupshape)

### addChart(int type, float x, float y, float width, float height) {#addChart-int-float-float-float-float-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height)
```

یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات مقداردهی اولیه می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع نموداری که باید اضافه شود. |
| x | float | مختصات x نمودار جدید، به پوینت. |
| y | float | مختصات y نمودار جدید، به پوینت. |
| width | float | عرض نمودار، به پوینت. |
| height | float | ارتفاع نمودار، به پوینت. |

**بازگشت:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) جدیداً ایجاد شده.

### addChart(int type, float x, float y, float width, float height, boolean initWithSample) {#addChart-int-float-float-float-float-boolean-}
```
public abstract IChart addChart(int type, float x, float y, float width, float height, boolean initWithSample)
```

یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات مقداردهی اولیه می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع نموداری که باید اضافه شود. |
| x | float | مختصات x نمودار جدید، به پوینت. |
| y | float | مختصات y نمودار جدید، به پوینت. |
| width | float | عرض نمودار، به پوینت. |
| height | float | ارتفاع نمودار، به پوینت. |
| initWithSample | boolean | True برای مقداردهی اولیه نمودار جدید با داده‌ها و تنظیمات نمونه؛ false برای ایجاد نمودار بدون سری و فقط با تنظیمات مینیمال، که ساخت را سریع‌تر می‌کند. |

**بازگشت:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) جدیداً ایجاد شده.

### addSmartArt(float x, float y, float width, float height, int layoutType) {#addSmartArt-float-float-float-float-int-}
```
public abstract ISmartArt addSmartArt(float x, float y, float width, float height, int layoutType)
```

یک نمودار SmartArt ایجاد می‌کند و به انتهای مجموعهٔ اشکال اضافه می‌دارد.

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
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x چارچوب نمودار، به پوینت. |
| y | float | مختصات y چارچوب نمودار، به پوینت. |
| width | float | عرض چارچوب نمودار، به پوینت. |
| height | float | ارتفاع چارچوب نمودار، به پوینت. |
| layoutType | int | نوع چیدمان SmartArt. |

**بازگشت:**
[ISmartArt](../../com.aspose.slides/ismartart) - [ISmartArt](../../com.aspose.slides/ismartart) جدیداً ایجاد شده.

### insertChart(int type, float x, float y, float width, float height, int index) {#insertChart-int-float-float-float-float-int-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index)
```

یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات مقداردهی اولیه می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع نموداری که باید ایجاد شود. |
| x | float | مختصات x نمودار جدید، به پوینت. |
| y | float | مختصات y نمودار جدید، به پوینت. |
| width | float | عرض نمودار جدید، به پوینت. |
| height | float | ارتفاع نمودار جدید، به پوینت. |
| index | int | شاخص صفر مبنا که در آن نمودار جدید در مجموعهٔ اشکال وارد می‌شود. |

**بازگشت:**
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) جدیداً ایجاد شده.

### insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample) {#insertChart-int-float-float-float-float-int-boolean-}
```
public abstract IChart insertChart(int type, float x, float y, float width, float height, int index, boolean initWithSample)
```

یک نمودار جدید ایجاد می‌کند، آن را با داده‌های نمونه سری و تنظیمات مقداردهی اولیه می‌کند و در اندیس مشخص به مجموعهٔ اشکال وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| type | int | نوع نموداری که باید ایجاد شود. |
| x | float | مختصات x نمودار جدید، به پوینت. |
| y | float | مختصات y نمودار جدید، به پوینت. |
| width | float | عرض نمودار جدید، به پوینت. |
| height | float | ارتفاع نمودار جدید، به پوینت. |
| index | int | شاخص صفر مبنا که در آن نمودار جدید در مجموعهٔ اشکال وارد می‌شود. |
| initWithSample | boolean | True برای مقداردهی اولیه نمودار جدید با داده‌ها و تنظیمات نمونه؛ false برای ایجاد نمودار بدون سری و فقط با تنظیمات مینیمال، که ساخت را سریع‌تر می‌کند. |
| initWithSample | boolean | True برای مقداردهی اولیهٔ نمودار جدید با داده‌ها و تنظیمات نمونه‌سری؛ false برای ایجاد نمودار بدون سری و تنها تنظیمات حداقل، که ساخت آن را سریع‌تر می‌کند. |

**بازگشت:**  
[IChart](../../com.aspose.slides/ichart) - [IChart](../../com.aspose.slides/ichart) جدید ایجاد شده.

### addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#addOleObjectFrame-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

یک قاب شیء OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x قاب OLE جدید، بر حسب نقطه. |
| y | float | مختصات y قاب OLE جدید، بر حسب نقطه. |
| width | float | عرض قاب OLE جدید، بر حسب نقطه. |
| height | float | ارتفاع قاب OLE جدید، بر حسب نقطه. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | اطلاعات داده‌های توکار OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**بازگشت:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) جدید ایجاد شده.

### addOleObjectFrame(float x, float y, float width, float height, String className, String path) {#addOleObjectFrame-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame addOleObjectFrame(float x, float y, float width, float height, String className, String path)
```

یک قاب شیء OLE جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x قاب OLE جدید، بر حسب نقطه. |
| y | float | مختصات y قاب OLE جدید، بر حسب نقطه. |
| width | float | عرض قاب OLE جدید، بر حسب نقطه. |
| height | float | ارتفاع قاب OLE جدید، بر حسب نقطه. |
| className | java.lang.String | نام کلاس شیء OLE. |
| path | java.lang.String | مسیر فایل پیوست شده. این مسیر به‌صورت کلمه به کلمه در ارائه ذخیره می‌شود. اگر مسیری نسبی مشخص شود، هنگام باز کردن ارائه از دایرکتوری متفاوت، فایل در دسترس نخواهد بود. |

**بازگشت:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) جدید ایجاد شده.

### insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo) {#insertOleObjectFrame-int-float-float-float-float-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, IOleEmbeddedDataInfo dataInfo)
```

یک قاب شیء OLE جدید ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در ایندکس مشخص‌شده درج می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای که قاب OLE در آن درج می‌شود. |
| x | float | مختصات x قاب OLE جدید، بر حسب نقطه. |
| y | float | مختصات y قاب OLE جدید، بر حسب نقطه. |
| width | float | عرض قاب OLE جدید، بر حسب نقطه. |
| height | float | ارتفاع قاب OLE جدید، بر حسب نقطه. |
| dataInfo | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | اطلاعات داده‌های توکار OLE ([IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)). |

**بازگشت:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) جدید ایجاد شده.

### insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path) {#insertOleObjectFrame-int-float-float-float-float-java.lang.String-java.lang.String-}
```
public abstract IOleObjectFrame insertOleObjectFrame(int index, float x, float y, float width, float height, String className, String path)
```

یک قاب شیء OLE جدید ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در ایندکس مشخص‌شده درج می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای که قاب OLE در آن درج می‌شود. |
| x | float | مختصات x قاب OLE جدید، بر حسب نقطه. |
| y | float | مختصات y قاب OLE جدید، بر حسب نقطه. |
| width | float | عرض قاب OLE جدید، بر حسب نقطه. |
| height | float | ارتفاع قاب OLE جدید، بر حسب نقطه. |
| className | java.lang.String | نام کلاس شیء OLE. |
| path | java.lang.String | مسیر فایل پیوست شده. این مسیر به‌صورت کلمه به کلمه در ارائه ذخیره می‌شود. اگر مسیری نسبی مشخص شود، هنگام باز کردن ارائه از دایرکتوری متفاوت، فایل در دسترس نخواهد بود. |

**بازگشت:**  
[IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) - [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) جدید ایجاد شده.

### addZoomFrame(float x, float y, float width, float height, ISlide slide) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide)
```

یک قاب Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.

--------------------

> ```
> This example demonstrates adding a Zoom object to the end of a collection
>  (assume that there are at least two slides in the "Presentation.pptx" presentation):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addZoomFrame(150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x قاب Zoom جدید، بر حسب نقطه. |
| y | float | مختصات y قاب Zoom جدید، بر حسب نقطه. |
| width | float | عرض قاب Zoom جدید، بر حسب نقطه. |
| height | float | ارتفاع قاب Zoom جدید، بر حسب نقطه. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) ارجاع داده‌شده توسط قاب Zoom؛ باید متعلق به این ارائه باشد. |

**بازگشت:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) جدید ایجاد شده.

### addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image) {#addZoomFrame-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame addZoomFrame(float x, float y, float width, float height, ISlide slide, IPPImage image)
```

یک قاب Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.

--------------------

> ```
> این مثال اضافه کردن یک شی Zoom به انتهای یک مجموعه را نشان می‌دهد
>  (فرض کنید در ارائه "Presentation.pptx" حداقل دو اسلاید وجود دارد):
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
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x قاب Zoom جدید، بر حسب نقطه. |
| y | float | مختصات y قاب Zoom جدید، بر حسب نقطه. |
| width | float | عرض قاب Zoom جدید، بر حسب نقطه. |
| height | float | ارتفاع قاب Zoom جدید، بر حسب نقطه. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) ارجاع داده‌شده توسط قاب Zoom؛ باید متعلق به این ارائه باشد. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | تصویر برای [IPPImage](../../com.aspose.slides/ippimage) اسلاید ارجاع‌شده. |

**بازگشت:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) جدید ایجاد شده.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide)
```

یک قاب Zoom جدید ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در ایندکس مشخص‌شده درج می‌نماید.

--------------------

> ```
> این مثال ایجاد و درج یک شی Zoom در اندیس مشخصی از یک مجموعه را نشان می‌دهد
>  (فرض کنید در ارائه "Presentation.pptx" حداقل دو اسلاید وجود دارد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertZoomFrame(2, 150, 20, 50, 50, pres.getSlides().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای که قاب Zoom در آن درج می‌شود. |
| x | float | مختصات x قاب Zoom جدید، بر حسب نقطه. |
| y | float | مختصات y قاب Zoom جدید، بر حسب نقطه. |
| width | float | عرض قاب Zoom جدید، بر حسب نقطه. |
| height | float | ارتفاع قاب Zoom جدید، بر حسب نقطه. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) ارجاع داده‌شده توسط قاب Zoom. |

**بازگشت:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) جدید ایجاد شده.

### insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image) {#insertZoomFrame-int-float-float-float-float-com.aspose.slides.ISlide-com.aspose.slides.IPPImage-}
```
public abstract IZoomFrame insertZoomFrame(int index, float x, float y, float width, float height, ISlide slide, IPPImage image)
```

یک قاب Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در ایندکس مشخص‌شده درج می‌نماید.

--------------------

> ```
> این مثال ایجاد و درج یک شی Zoom در ایندکس مشخصی از یک مجموعه را نشان می‌دهد
>  (فرض کنید در ارائه "Presentation.pptx" حداقل دو اسلاید وجود دارد):
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
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای که قاب Zoom در آن درج می‌شود. |
| x | float | مختصات x قاب Zoom جدید، بر حسب نقطه. |
| y | float | مختصات y قاب Zoom جدید، بر حسب نقطه. |
| width | float | عرض قاب Zoom جدید، بر حسب نقطه. |
| height | float | ارتفاع قاب Zoom جدید، بر حسب نقطه. |
| slide | [ISlide](../../com.aspose.slides/islide) | [ISlide](../../com.aspose.slides/islide) ارجاع داده‌شده توسط قاب Zoom. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | تصویر برای [IPPImage](../../com.aspose.slides/ippimage) اسلاید ارجاع‌شده. |

**بازگشت:**  
[IZoomFrame](../../com.aspose.slides/izoomframe) - [IZoomFrame](../../com.aspose.slides/izoomframe) جدید ایجاد شده.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section)
```

یک قاب Section Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.

--------------------

> ```
> این مثال اضافه کردن یک شی Section Zoom به انتهای یک مجموعه را نشان می‌دهد
>  (فرض کنید در ارائه "Presentation.pptx" حداقل دو بخش وجود دارد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x قاب Section Zoom جدید، بر حسب نقطه. |
| y | float | مختصات y قاب Section Zoom جدید، بر حسب نقطه. |
| width | float | عرض قاب Section Zoom جدید، بر حسب نقطه. |
| height | float | ارتفاع قاب Section Zoom جدید، بر حسب نقطه. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) ارجاع داده‌شده توسط قاب Section Zoom؛ باید متعلق به این ارائه باشد و حداقل شامل یک اسلاید باشد. |

**بازگشت:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) جدید ایجاد شده.

### addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image) {#addSectionZoomFrame-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame addSectionZoomFrame(float x, float y, float width, float height, ISection section, IPPImage image)
```

یک قاب Section Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.

--------------------

> ```
> این مثال اضافه کردن یک شی Section Zoom به انتهای یک مجموعه را نشان می‌دهد
>  (فرض کنید در ارائه "Presentation.pptx" حداقل دو بخش وجود دارد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSectionZoomFrame(150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x قاب Section Zoom جدید، بر حسب نقطه. |
| y | float | مختصات y قاب Section Zoom جدید، بر حسب نقطه. |
| width | float | عرض قاب Section Zoom جدید، بر حسب نقطه. |
| height | float | ارتفاع قاب Section Zoom جدید، بر حسب نقطه. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) ارجاع داده‌شده توسط قاب Section Zoom؛ باید متعلق به این ارائه باشد و حداقل شامل یک اسلاید باشد. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage)ی که در قاب Section Zoom نمایش داده می‌شود. |

**بازگشت:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) جدید ایجاد شده.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section)
```

یک قاب Section Zoom جدید ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در ایندکس مشخص‌شده درج می‌نماید.

--------------------

> ```
> این مثال ایجاد و درج یک شی Section Zoom در ایندکس مشخصی از یک مجموعه را نشان می‌دهد
>  (فرض کنید در ارائه "Presentation.pptx" حداقل دو بخش وجود دارد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای که قاب Section Zoom در آن درج می‌شود. |
| x | float | مختصات x قاب Section Zoom جدید، بر حسب نقطه. |
| y | float | مختصات y قاب Section Zoom جدید، بر حسب نقطه. |
| width | float | عرض قاب Section Zoom جدید، بر حسب نقطه. |
| height | float | ارتفاع قاب Section Zoom جدید، بر حسب نقطه. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) ارجاع داده‌شده توسط قاب Section Zoom؛ باید متعلق به این ارائه باشد و حداقل شامل یک اسلاید باشد. |

**بازگشت:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) جدید ایجاد شده.

### insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image) {#insertSectionZoomFrame-int-float-float-float-float-com.aspose.slides.ISection-com.aspose.slides.IPPImage-}
```
public abstract ISectionZoomFrame insertSectionZoomFrame(int index, float x, float y, float width, float height, ISection section, IPPImage image)
```

یک قاب Section Zoom جدید با تصویر پیش‌تعریف‌شده ایجاد می‌کند و آن را در مجموعهٔ شکل‌ها در ایندکس مشخص‌شده درج می‌نماید.

--------------------

> ```
> این مثال ایجاد و درج یک شی Section Zoom در ایندکس مشخصی از یک مجموعه را نشان می‌دهد
>  (فرض کنید در ارائه "Presentation.pptx" حداقل دو بخش وجود دارد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      IPPImage image = pres.getImages().addImage(Files.readAllBytes(Paths.get("image.png")));
>      ISectionZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSectionZoomFrame(2, 150, 20, 50, 50, pres.getSections().get_Item(1), image);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای که قاب Section Zoom در آن درج می‌شود. |
| x | float | مختصات x قاب Section Zoom جدید، بر حسب نقطه. |
| y | float | مختصات y قاب Section Zoom جدید، بر حسب نقطه. |
| width | float | عرض قاب Section Zoom جدید، بر حسب نقطه. |
| height | float | ارتفاع قاب Section Zoom جدید، بر حسب نقطه. |
| section | [ISection](../../com.aspose.slides/isection) | [ISection](../../com.aspose.slides/isection) ارجاع داده‌شده توسط قاب Section Zoom؛ باید متعلق به این ارائه باشد و حداقل شامل یک اسلاید باشد. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | تصویر برای نمایش در قاب Section Zoom. |

**بازگشت:**  
[ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) - [ISectionZoomFrame](../../com.aspose.slides/isectionzoomframe) جدید ایجاد شده.

### addSummaryZoomFrame(float x, float y, float width, float height) {#addSummaryZoomFrame-float-float-float-float-}
```
public abstract ISummaryZoomFrame addSummaryZoomFrame(float x, float y, float width, float height)
```

یک قاب Summary Zoom جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ شکل‌ها اضافه می‌نماید.

--------------------

> ```
> این مثال اضافه کردن یک شی Summary Zoom به انتهای یک مجموعه را نشان می‌دهد
>  (فرض کنید در ارائه "Presentation.pptx" حداقل دو بخش وجود دارد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().addSummaryZoomFrame(150, 20, 500, 250);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x قاب Summary Zoom جدید، بر حسب نقطه. |
| y | float | مختصات y قاب Summary Zoom جدید، بر حسب نقطه. |
| width | float | عرض قاب Summary Zoom جدید، بر حسب نقطه. |
| height | float | ارتفاع قاب Summary Zoom جدید، بر حسب نقطه. |

--------------------
This method creates a Summary Zoom frame that aggregates summary links for all sections in the presentation. |

**بازمی‌گرداند:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - شیء تازه ایجاد شده [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### insertSummaryZoomFrame(int index, float x, float y, float width, float height) {#insertSummaryZoomFrame-int-float-float-float-float-}
```
public abstract ISummaryZoomFrame insertSummaryZoomFrame(int index, float x, float y, float width, float height)
```

یک فریم Summary Zoom جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص شده وارد می‌نماید.

--------------------

> ```
> این مثال ایجاد و درج یک شی Summary Zoom در ایندکس مشخصی از یک مجموعه را نشان می‌دهد
>  (فرض کنید در ارائه "Presentation.pptx" حداقل دو بخش وجود دارد):
>  
>  Presentation pres = new Presentation("Presentation.pptx");
>  try {
>      ISummaryZoomFrame zoomFrame = pres.getSlides().get_Item(0).getShapes().insertSummaryZoomFrame(2, 150, 20, 50, 50);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای که فریم Summary Zoom در آن وارد می‌شود. |
| x | float | مختصات x فریم Summary Zoom جدید، بر حسب نقطه. |
| y | float | مختصات y فریم Summary Zoom جدید، بر حسب نقطه. |
| width | float | عرض فریم Summary Zoom جدید، بر حسب نقطه. |
| height | float | ارتفاع فریم Summary Zoom جدید، بر حسب نقطه. |

--------------------

This method creates a Summary Zoom frame that aggregates summary links for all sections in the presentation. |

**بازمی‌گرداند:**
[ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe) - شیء تازه ایجاد شده [ISummaryZoomFrame](../../com.aspose.slides/isummaryzoomframe).
### addVideoFrame(float x, float y, float width, float height, String fname) {#addVideoFrame-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, String fname)
```

یک فریم ویدئویی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x فریم ویدئویی جدید، بر حسب نقطه. |
| y | float | مختصات y فریم ویدئویی جدید، بر حسب نقطه. |
| width | float | عرض فریم ویدئویی جدید، بر حسب نقطه. |
| height | float | ارتفاع فریم ویدئویی جدید، بر حسب نقطه. |
| fname | java.lang.String | مسیر یا نام فایل ویدئویی برای جاسازی. |

**بازمی‌گرداند:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - شیء تازه ایجاد شده [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addVideoFrame(float x, float y, float width, float height, IVideo video) {#addVideoFrame-float-float-float-float-com.aspose.slides.IVideo-}
```
public abstract IVideoFrame addVideoFrame(float x, float y, float width, float height, IVideo video)
```

یک فریم ویدئویی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x فریم ویدئویی جدید، بر حسب نقطه. |
| y | float | مختصات y فریم ویدئویی جدید، بر حسب نقطه. |
| width | float | عرض فریم ویدئویی جدید، بر حسب نقطه. |
| height | float | ارتفاع فریم ویدئویی جدید، بر حسب نقطه. |
| video | [IVideo](../../com.aspose.slides/ivideo) | [IVideo](../../com.aspose.slides/ivideo) برای جاسازی در فریم ویدئویی. |

**بازمی‌گرداند:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - شیء تازه ایجاد شده [IVideoFrame](../../com.aspose.slides/ivideoframe).
### insertVideoFrame(int index, float x, float y, float width, float height, String fname) {#insertVideoFrame-int-float-float-float-float-java.lang.String-}
```
public abstract IVideoFrame insertVideoFrame(int index, float x, float y, float width, float height, String fname)
```

یک فریم ویدئویی جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص شده وارد می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای که فریم ویدئویی در آن وارد می‌شود. |
| x | float | مختصات x فریم ویدئویی جدید، بر حسب نقطه. |
| y | float | مختصات y فریم ویدئویی جدید، بر حسب نقطه. |
| width | float | عرض فریم ویدئویی جدید، بر حسب نقطه. |
| height | float | ارتفاع فریم ویدئویی جدید، بر حسب نقطه. |
| fname | java.lang.String | مسیر یا نام فایل ویدئویی برای جاسازی. |

**بازمی‌گرداند:**
[IVideoFrame](../../com.aspose.slides/ivideoframe) - شیء تازه ایجاد شده [IVideoFrame](../../com.aspose.slides/ivideoframe).
### addAudioFrameCD(float x, float y, float width, float height) {#addAudioFrameCD-float-float-float-float-}
```
public abstract IAudioFrame addAudioFrameCD(float x, float y, float width, float height)
```

یک فریم صوتی جدید مرتبط با ترک CD ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x فریم صوتی جدید، بر حسب نقطه. |
| y | float | مختصات y فریم صوتی جدید، بر حسب نقطه. |
| width | float | عرض فریم صوتی جدید، بر حسب نقطه. |
| height | float | ارتفاع فریم صوتی جدید، بر حسب نقطه. |

**بازمی‌گرداند:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - شیء تازه ایجاد شده [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameCD(int index, float x, float y, float width, float height) {#insertAudioFrameCD-int-float-float-float-float-}
```
public abstract IAudioFrame insertAudioFrameCD(int index, float x, float y, float width, float height)
```

یک فریم صوتی جدید مرتبط با ترک CD ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص شده وارد می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای که فریم صوتی در آن وارد می‌شود. |
| x | float | مختصات x فریم صوتی جدید، بر حسب نقطه. |
| y | float | مختصات y فریم صوتی جدید، بر حسب نقطه. |
| width | float | عرض فریم صوتی جدید، بر حسب نقطه. |
| height | float | ارتفاع فریم صوتی جدید، بر حسب نقطه. |

**بازمی‌گرداند:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - شیء تازه ایجاد شده [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameLinked(float x, float y, float width, float height, String fname) {#addAudioFrameLinked-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame addAudioFrameLinked(float x, float y, float width, float height, String fname)
```

یک فریم صوتی جدید مرتبط با فایل صوتی خارجی ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x فریم صوتی جدید، بر حسب نقطه. |
| y | float | مختصات y فریم صوتی جدید، بر حسب نقطه. |
| width | float | عرض فریم صوتی جدید، بر حسب نقطه. |
| height | float | ارتفاع فریم صوتی جدید، بر حسب نقطه. |
| fname | java.lang.String | مسیر یا نام فایل صوتی خارجی برای لینک. |

**بازمی‌گرداند:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - شیء تازه ایجاد شده [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname) {#insertAudioFrameLinked-int-float-float-float-float-java.lang.String-}
```
public abstract IAudioFrame insertAudioFrameLinked(int index, float x, float y, float width, float height, String fname)
```

یک فریم صوتی جدید مرتبط با فایل صوتی خارجی ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص شده وارد می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای که فریم صوتی در آن وارد می‌شود. |
| x | float | مختصات x فریم صوتی جدید، بر حسب نقطه. |
| y | float | مختصات y فریم صوتی جدید، بر حسب نقطه. |
| width | float | عرض فریم صوتی جدید، بر حسب نقطه. |
| height | float | ارتفاع فریم صوتی جدید، بر حسب نقطه. |
| fname | java.lang.String | مسیر یا نام فایل صوتی خارجی برای لینک. |

**بازمی‌گرداند:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - شیء تازه ایجاد شده [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream) {#addAudioFrameEmbedded-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, InputStream audio_stream)
```

یک فریم صوتی جدید با فایل WAV جاسازی شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید. صوت جاسازی شده به مجموعهٔ Presentation.Audios افزوده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x فریم صوتی جدید، بر حسب نقطه. |
| y | float | مختصات y فریم صوتی جدید، بر حسب نقطه. |
| width | float | عرض فریم صوتی جدید، بر حسب نقطه. |
| height | float | ارتفاع فریم صوتی جدید، بر حسب نقطه. |
| audio_stream | java.io.InputStream | یک جریان ورودی شامل داده‌های صوتی WAV برای جاسازی. |

**بازمی‌گرداند:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - شیء تازه ایجاد شده [IAudioFrame](../../com.aspose.slides/iaudioframe).
### addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio) {#addAudioFrameEmbedded-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame addAudioFrameEmbedded(float x, float y, float width, float height, IAudio audio)
```

یک فریم صوتی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید با استفاده از شیء صوتی موجود در لیست Presentation.Audios.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x فریم صوتی جدید، بر حسب نقطه. |
| y | float | مختصات y فریم صوتی جدید، بر حسب نقطه. |
| width | float | عرض فریم صوتی جدید، بر حسب نقطه. |
| height | float | ارتفاع فریم صوتی جدید، بر حسب نقطه. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | یک نمونهٔ [IAudio](../../com.aspose.slides/iaudio) از مجموعهٔ Presentation.Audios. |

**بازمی‌گرداند:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - شیء تازه ایجاد شده [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream) {#insertAudioFrameEmbedded-int-float-float-float-float-java.io.InputStream-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, InputStream audio_stream)
```

یک فریم صوتی جدید با فایل WAV جاسازی شده ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص شده وارد می‌نماید. صوت جاسازی شده به مجموعهٔ Presentation.Audios افزوده می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای که فریم صوتی در آن وارد می‌شود. |
| x | float | مختصات x فریم صوتی جدید، بر حسب نقطه. |
| y | float | مختصات y فریم صوتی جدید، بر حسب نقطه. |
| width | float | عرض فریم صوتی جدید، بر حسب نقطه. |
| height | float | ارتفاع فریم صوتی جدید، بر حسب نقطه. |
| audio_stream | java.io.InputStream | یک جریان ورودی شامل داده‌های صوتی WAV برای جاسازی. |

**بازمی‌گرداند:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - شیء تازه ایجاد شده [IAudioFrame](../../com.aspose.slides/iaudioframe).
### insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio) {#insertAudioFrameEmbedded-int-float-float-float-float-com.aspose.slides.IAudio-}
```
public abstract IAudioFrame insertAudioFrameEmbedded(int index, float x, float y, float width, float height, IAudio audio)
```

یک فریم صوتی جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در ایندکس مشخص شده وارد می‌نماید با استفاده از شیء صوتی موجود در لیست Presentation.Audios.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس صفر-پایه‌ای که فریم صوتی در آن وارد می‌شود. |
| x | float | مختصات x فریم صوتی جدید، بر حسب نقطه. |
| y | float | مختصات y فریم صوتی جدید، بر حسب نقطه. |
| width | float | عرض فریم صوتی جدید، بر حسب نقطه. |
| height | float | ارتفاع فریم صوتی جدید، بر حسب نقطه. |
| audio | [IAudio](../../com.aspose.slides/iaudio) | یک نمونهٔ [IAudio](../../com.aspose.slides/iaudio) از مجموعهٔ Presentation.Audios برای جاسازی. |

**بازمی‌گرداند:**
[IAudioFrame](../../com.aspose.slides/iaudioframe) - شیء تازه ایجاد شده [IAudioFrame](../../com.aspose.slides/iaudioframe).
### indexOf(IShape shape) {#indexOf-com.aspose.slides.IShape-}
```
public abstract int indexOf(IShape shape)
```

ایندکس صفر-پایه‌ای اولین رخداد شکل مشخص شده در مجموعه را برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | شکلی که باید در مجموعه پیدا شود. |

**بازمی‌گرداند:**
int - ایندکس صفر-پایه‌ای اولین رخداد شکل در مجموعهٔ اشکال اگر پیدا شود؛ در غیر این صورت، \\u20131.
### toArray() {#toArray--}
```
public abstract IShape[] toArray()
```

یک آرایه شامل تمام اشکال ایجاد و برمی‌گرداند.

**بازمی‌گرداند:**
com.aspose.slides.IShape[] - یک آرایه از اشیاء [IShape](../../com.aspose.slides/ishape).
### toArray(int startIndex, int count) {#toArray-int-int-}
```
public abstract IShape[] toArray(int startIndex, int count)
```

یک آرایه شامل تمام اشکال در بازهٔ مشخص شده ایجاد و برمی‌گرداند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| startIndex | int | ایندکس اولین شکل برای بازگرداندن. |
| count | int | تعداد شکل‌ها برای بازگرداندن. |

**بازمی‌گرداند:**
com.aspose.slides.IShape[] - یک آرایه از اشیاء [IShape](../../com.aspose.slides/ishape).
### reorder(int index, IShape shape) {#reorder-int-com.aspose.slides.IShape-}
```
public abstract void reorder(int index, IShape shape)
```

شکل مشخص شده را به موقعیت جدیدی در مجموعهٔ اشکال منتقل می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس هدف صفر-پایه‌ای که شکل در آن قرار می‌گیرد. |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای جابجایی در مجموعه. |

### reorder(int index, IShape[] shapes) {#reorder-int-com.aspose.slides.IShape...-}
```
public abstract void reorder(int index, IShape[] shapes)
```

شکل‌های مشخص شده را در مجموعهٔ اشکال جابجا می‌کند، به طوری که از ایندکس داده شده شروع می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | ایندکس هدف صفر-پایه‌ای که اولین شکل مشخص شده در آن قرار می‌گیرد؛ اشکال بعدی به ترتیب در ادامه قرار می‌گیرند. |
| shapes | [IShape\[\]](../../com.aspose.slides/ishape) | یک یا چند نمونهٔ [IShape](../../com.aspose.slides/ishape) برای جابجایی در مجموعه. |

### addAutoShape(int shapeType, float x, float y, float width, float height) {#addAutoShape-int-float-float-float-float-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height)
```

یک شکل خودکار جدید با قالب‌بندی پیش‌فرض ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌نماید.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) شکل خودکار برای افزودن. |

| x | float | مختصات x فریم شکل، در نقاط. |
| y | float | مختصات y فریم شکل، در نقاط. |
| width | float | عرض فریم شکل، در نقاط. |
| height | float | ارتفاع فریم شکل، در نقاط. |

**بازگرداندن:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) تازه ایجاد شده.

### addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addAutoShape-int-float-float-float-float-boolean-}
```
public abstract IAutoShape addAutoShape(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

یک شکل خودکار جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌دارد، در صورت تمایل با قالب‌بندی پیش‌فرض الگو مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) شکل خودکار برای افزودن. |
| x | float | مختصات x فریم شکل، در نقاط. |
| y | float | مختصات y فریم شکل، در نقاط. |
| width | float | عرض فریم شکل، در نقاط. |
| height | float | ارتفاع فریم شکل، در نقاط. |
| createFromTemplate | boolean | True برای اعمال قالب‌بندی پیش‌فرض الگو (سبک ساده، متن مرکز‌چین و نام غیر خالی) به شکل جدید؛ false برای ایجاد شکل با تمام خصوصیات تنظیم‌شده به مقادیر پیش‌فرض. |

**بازگرداندن:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) جدید ایجاد شده.

### addMathShape(float x, float y, float width, float height) {#addMathShape-float-float-float-float-}
```
public abstract IAutoShape addMathShape(float x, float y, float width, float height)
```

یک شکل خودکار مستطیل جدید برای میزبانی محتوای ریاضی ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x فریم شکل، در نقاط. |
| y | float | مختصات y فریم شکل، در نقاط. |
| width | float | عرض فریم شکل، در نقاط. |
| height | float | ارتفاع فریم شکل، در نقاط. |

**بازگرداندن:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) جدید ایجاد شده.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height) {#insertAutoShape-int-int-float-float-float-float-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height)
```

یک شکل خودکار جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیس مشخص شده وارد می‌کند، با قالب‌بندی پیش‌فرض الگو.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-مبنا که در آن شکل خودکار جدید وارد می‌شود. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) شکل خودکار برای وارد کردن. |
| x | float | مختصات x فریم شکل، در نقاط. |
| y | float | مختصات y فریم شکل، در نقاط. |
| width | float | عرض فریم شکل، در نقاط. |
| height | float | ارتفاع فریم شکل، در نقاط. |

**بازگرداندن:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) جدید ایجاد شده.

### insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertAutoShape-int-int-float-float-float-float-boolean-}
```
public abstract IAutoShape insertAutoShape(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

یک شکل خودکار جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیس مشخص شده وارد می‌کند، در صورت تمایل با قالب‌بندی پیش‌فرض الگو مقداردهی اولیه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-مبنا که در آن شکل خودکار وارد می‌شود. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) شکل خودکار برای وارد کردن. |
| x | float | مختصات x فریم شکل، در نقاط. |
| y | float | مختصات y فریم شکل، در نقاط. |
| width | float | عرض فریم شکل، در نقاط. |
| height | float | ارتفاع فریم شکل، در نقاط. |
| createFromTemplate | boolean | True برای اعمال قالب‌بندی پیش‌فرض الگو (شامل نام غیر خالی، سبک ساده و متن مرکز‌چین)؛ false برای ایجاد شکل با تمام خصوصیات تنظیم‌شده به مقادیر پیش‌فرض. |

**بازگرداندن:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) جدید ایجاد شده.

### addGroupShape() {#addGroupShape--}
```
public abstract IGroupShape addGroupShape()
```

یک شکل گروه خالی جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌دارد. قاب گروه به‌صورت خودکار برای سازگار شدن با هر شکل اضافه‌شده تنظیم می‌شود.

**بازگرداندن:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) جدید ایجاد شده.

### addGroupShape(ISvgImage svgImage, float x, float y, float width, float height) {#addGroupShape-com.aspose.slides.ISvgImage-float-float-float-float-}
```
public abstract IGroupShape addGroupShape(ISvgImage svgImage, float x, float y, float width, float height)
```

یک شکل گروه جدید ایجاد می‌کند، تصویر SVG مشخص‌شده را به اشکال منفرد تبدیل می‌کند و گروه حاصل را به انتهای مجموعهٔ اشکال اضافه می‌دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| svgImage | [ISvgImage](../../com.aspose.slides/isvgimage) | [ISvgImage](../../com.aspose.slides/isvgimage) حاوی محتوای برداری برای تبدیل به اشکال. |
| x | float | مختصات x قاب گروه، در نقاط. |
| y | float | مختصات y قاب گروه، در نقاط. |
| width | float | عرض قاب گروه، در نقاط. |
| height | float | ارتفاع قاب گروه، در نقاط. |

**بازگرداندن:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) جدید ایجاد شده.

### insertGroupShape(int index) {#insertGroupShape-int-}
```
public abstract IGroupShape insertGroupShape(int index)
```

یک شکل گروه خالی جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیس مشخص شده وارد می‌کند. قاب گروه به‌صورت خودکار برای سازگار شدن با هر شکل اضافه‌شده تنظیم می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-مبنا که در آن شکل گروه وارد می‌شود. |

**بازگرداندن:**
[IGroupShape](../../com.aspose.slides/igroupshape) - [IGroupShape](../../com.aspose.slides/igroupshape) جدید ایجاد شده.

### addConnector(int shapeType, float x, float y, float width, float height) {#addConnector-int-float-float-float-float-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height)
```

یک شکل اتصال‌دهنده جدید با قالب‌بندی پیش‌فرض الگو ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) اتصال‌دهنده برای افزودن. |
| x | float | مختصات x قاب اتصال‌دهنده، در نقاط. |
| y | float | مختصات y قاب اتصال‌دهنده، در نقاط. |
| width | float | عرض قاب اتصال‌دهنده، در نقاط. |
| height | float | ارتفاع قاب اتصال‌دهنده، در نقاط. |

**بازگرداندن:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) جدید ایجاد شده.

### addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#addConnector-int-float-float-float-float-boolean-}
```
public abstract IConnector addConnector(int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

یک شکل اتصال‌دهنده جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌دارد، به‌صورت اختیاری با قالب‌بندی پیش‌فرض الگو.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) اتصال‌دهنده برای ایجاد. |
| x | float | مختصات x قاب اتصال‌دهنده، در نقاط. |
| y | float | مختصات y قاب اتصال‌دهنده، در نقاط. |
| width | float | عرض قاب اتصال‌دهنده، در نقاط. |
| height | float | ارتفاع قاب اتصال‌دهنده، در نقاط. |
| createFromTemplate | boolean | True برای اعمال قالب‌بندی پیش‌فرض الگو (نام غیر خالی، سبک ساده)؛ false برای ایجاد اتصال‌دهنده با مقادیر پیش‌فرض خصوصیات. |

**بازگرداندن:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) جدید ایجاد شده.

### insertConnector(int index, int shapeType, float x, float y, float width, float height) {#insertConnector-int-int-float-float-float-float-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height)
```

یک شکل اتصال‌دهنده جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیس مشخص شده وارد می‌کند، با قالب‌بندی پیش‌فرض الگو.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-مبنا که در آن شکل اتصال‌دهنده وارد می‌شود. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) اتصال‌دهنده برای وارد کردن. |
| x | float | مختصات x قاب اتصال‌دهنده، در نقاط. |
| y | float | مختصات y قاب اتصال‌دهنده، در نقاط. |
| width | float | عرض قاب اتصال‌دهنده، در نقاط. |
| height | float | ارتفاع قاب اتصال‌دهنده، در نقاط. |

**بازگرداندن:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) جدید ایجاد شده.

### insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate) {#insertConnector-int-int-float-float-float-float-boolean-}
```
public abstract IConnector insertConnector(int index, int shapeType, float x, float y, float width, float height, boolean createFromTemplate)
```

یک شکل اتصال‌دهنده جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیس مشخص شده وارد می‌کند، به‌صورت اختیاری با قالب‌بندی پیش‌فرض الگو.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-مبنا که در آن شکل اتصال‌دهنده وارد می‌شود. |
| shapeType | int | [ShapeType](../../com.aspose.slides/shapetype) اتصال‌دهنده برای وارد کردن. |
| x | float | مختصات x قاب اتصال‌دهنده، در نقاط. |
| y | float | مختصات y قاب اتصال‌دهنده، در نقاط. |
| width | float | عرض قاب اتصال‌دهنده، در نقاط. |
| height | float | ارتفاع قاب اتصال‌دهنده، در نقاط. |
| createFromTemplate | boolean | True برای اعمال قالب‌بندی پیش‌فرض الگو (نام غیر خالی، سبک ساده)؛ false برای ایجاد اتصال‌دهنده با مقادیر پیش‌فرض خصوصیات. |

**بازگرداندن:**
[IConnector](../../com.aspose.slides/iconnector) - [IConnector](../../com.aspose.slides/iconnector) جدید ایجاد شده.

### addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image) {#addPictureFrame-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame addPictureFrame(int shapeType, float x, float y, float width, float height, IPPImage image)
```

یک فریم تصویر جدید حاوی تصویر مشخص‌شده ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shapeType | int | نوع شکل موجود در [ShapeType](../../com.aspose.slides/shapetype) را مشخص می‌کند، به‌جز تمام انواع خطوط: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | مختصات x فریم تصویر، در نقاط. |
| y | float | مختصات y فریم تصویر، در نقاط. |
| width | float | عرض فریم تصویر، در نقاط. |
| height | float | ارتفاع فریم تصویر، در نقاط. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) برای نمایش در فریم تصویر. |

**بازگرداندن:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) جدید ایجاد شده.

### insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image) {#insertPictureFrame-int-int-float-float-float-float-com.aspose.slides.IPPImage-}
```
public abstract IPictureFrame insertPictureFrame(int index, int shapeType, float x, float y, float width, float height, IPPImage image)
```

یک فریم تصویر جدید ایجاد می‌کند و آن را در مجموعهٔ اشکال در اندیس مشخص شده وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | اندیس صفر-مبنا که در آن فریم تصویر وارد می‌شود. |
| shapeType | int | نوع شکل موجود در [ShapeType](../../com.aspose.slides/shapetype) را مشخص می‌کند، به‌جز تمام انواع خطوط: ShapeType.Line, ShapeType.StraightConnector1, ShapeType.BentConnector2, ShapeType.BentConnector3, ShapeType.BentConnector4, ShapeType.BentConnector5, ShapeType.CurvedConnector2, ShapeType.CurvedConnector3, ShapeType.CurvedConnector4, ShapeType.CurvedConnector5. |
| x | float | مختصات x فریم تصویر، در نقاط. |
| y | float | مختصات y فریم تصویر، در نقاط. |
| width | float | عرض فریم تصویر، در نقاط. |
| height | float | ارتفاع فریم تصویر، در نقاط. |
| image | [IPPImage](../../com.aspose.slides/ippimage) | [IPPImage](../../com.aspose.slides/ippimage) برای نمایش در فریم تصویر. |

**بازگرداندن:**
[IPictureFrame](../../com.aspose.slides/ipictureframe) - [IPictureFrame](../../com.aspose.slides/ipictureframe) جدید ایجاد شده.

### addTable(float x, float y, double[] columnWidths, double[] rowHeights) {#addTable-float-float-double---double---}
```
public abstract ITable addTable(float x, float y, double[] columnWidths, double[] rowHeights)
```

یک جدول جدید ایجاد می‌کند و آن را به انتهای مجموعهٔ اشکال اضافه می‌دارد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| x | float | مختصات x جدول، در نقاط. |
| y | float | مختصات y جدول، در نقاط. |
| columnWidths | double[] | آرایه‌ای از مقادیر double که عرض ستون‌های جدول را نشان می‌دهد، در نقاط. |
| rowHeights | double[] | آرایه‌ای از مقادیر double که ارتفاع ردیف‌های جدول را نشان می‌دهد، در نقاط. |

**بازگرداندن:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) جدید ایجاد شده.

### insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights) {#insertTable-int-float-float-double---double---}
```
public abstract ITable insertTable(int index, float x, float y, double[] columnWidths, double[] rowHeights)
```
Creates a new table and inserts it into the shape collection at the specified index.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر مبنا که جدول در آن درج می‌شود. |
| x | float | مختصات x جدول، بر حسب نقطه. |
| y | float | مختصات y جدول، بر حسب نقطه. |
| columnWidths | double[] | آرایه‌ای از doubleها که عرض ستون‌های جدول را، بر حسب نقطه، نشان می‌دهد. |
| rowHeights | double[] | آرایه‌ای از doubleها که ارتفاع ردیف‌های جدول را، بر حسب نقطه، نشان می‌دهد. |

**بازگرداندن:**
[ITable](../../com.aspose.slides/itable) - [ITable](../../com.aspose.slides/itable) جدید ایجاد شده.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

شکل را در ایندکس مشخص شده از مجموعه شکل‌ها حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر مبنا که شکل در آن حذف می‌شود. |

### remove(IShape shape) {#remove-com.aspose.slides.IShape-}
```
public abstract void remove(IShape shape)
```

اولین رخداد شکل مشخص شده را از مجموعه شکل‌ها حذف می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| shape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای حذف. |

### clear() {#clear--}
```
public abstract void clear()
```

تمام شکل‌ها را از مجموعه شکل‌ها حذف می‌کند.

### addClone(IShape sourceShape, float x, float y, float width, float height) {#addClone-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y, float width, float height)
```

یک کپی از شکل مشخص شده ایجاد می‌کند و آن را به انتهای مجموعه شکل‌ها اضافه می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | شکل برای کلون کردن. |
| x | float | مختصات x قاب شکل کلون‌شده، بر حسب نقطه. |
| y | float | مختصات y قاب شکل کلون‌شده، بر حسب نقطه. |
| width | float | عرض قاب شکل کلون‌شده، بر حسب نقطه. |
| height | float | ارتفاع قاب شکل کلون‌شده، بر حسب نقطه. |

**بازگرداندن:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) جدید ایجاد شده.
### addClone(IShape sourceShape, float x, float y) {#addClone-com.aspose.slides.IShape-float-float-}
```
public abstract IShape addClone(IShape sourceShape, float x, float y)
```

یک کپی از شکل مشخص شده ایجاد می‌کند و آن را به انتهای مجموعه شکل‌ها اضافه می‌کند. شکل جدید عرض و ارتفاع  sourceShape را حفظ می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای کلون کردن. |
| x | float | مختصات x قاب شکل کلون‌شده، بر حسب نقطه. |
| y | float | مختصات y قاب شکل کلون‌شده، بر حسب نقطه. |

**بازگرداندن:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) جدید ایجاد شده.
### addClone(IShape sourceShape) {#addClone-com.aspose.slides.IShape-}
```
public abstract IShape addClone(IShape sourceShape)
```

یک کپی از شکل مشخص شده ایجاد می‌کند و آن را به انتهای مجموعه شکل‌ها اضافه می‌کند. شکل کلون‌شده موقعیت و اندازهٔ اصلی را حفظ می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای کلون کردن. |

**بازگرداندن:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) جدید ایجاد شده.
### insertClone(int index, IShape sourceShape, float x, float y, float width, float height) {#insertClone-int-com.aspose.slides.IShape-float-float-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y, float width, float height)
```

یک کپی از شکل مشخص شده ایجاد می‌کند و آن را در مجموعه شکل‌ها در ایندکس مشخص شده وارد می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر مبنا که شکل کلون‌شده در آن وارد می‌شود. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای کلون کردن. |
| x | float | مختصات x قاب شکل کلون‌شده، بر حسب نقطه. |
| y | float | مختصات y قاب شکل کلون‌شده، بر حسب نقطه. |
| width | float | عرض قاب شکل کلون‌شده، بر حسب نقطه. |
| height | float | ارتفاع قاب شکل کلون‌شده، بر حسب نقطه. |

**بازگرداندن:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) جدید ایجاد شده.
### insertClone(int index, IShape sourceShape, float x, float y) {#insertClone-int-com.aspose.slides.IShape-float-float-}
```
public abstract IShape insertClone(int index, IShape sourceShape, float x, float y)
```

یک کپی از شکل مشخص شده ایجاد می‌کند و آن را در مجموعه شکل‌ها در ایندکس مشخص شده وارد می‌کند. شکل جدید عرض و ارتفاع  sourceShape را حفظ می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر مبنا که شکل کلون‌شده در آن وارد می‌شود. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای کلون کردن. |
| x | float | مختصات x قاب شکل کلون‌شده، بر حسب نقطه. |
| y | float | مختصات y قاب شکل کلون‌شده، بر حسب نقطه. |

**بازگرداندن:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) جدید ایجاد شده.
### insertClone(int index, IShape sourceShape) {#insertClone-int-com.aspose.slides.IShape-}
```
public abstract IShape insertClone(int index, IShape sourceShape)
```

یک کپی از شکل مشخص شده ایجاد می‌کند و آن را در مجموعه شکل‌ها در ایندکس مشخص شده وارد می‌کند. شکل کلون‌شده موقعیت و اندازهٔ اصلی را حفظ می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| index | int | شاخص صفر مبنا که شکل کلون‌شده در آن وارد می‌شود. |
| sourceShape | [IShape](../../com.aspose.slides/ishape) | [IShape](../../com.aspose.slides/ishape) برای کلون کردن. |

**بازگرداندن:**
[IShape](../../com.aspose.slides/ishape) - [IShape](../../com.aspose.slides/ishape) جدید ایجاد شده.