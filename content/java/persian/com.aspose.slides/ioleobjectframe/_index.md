---
title: IOleObjectFrame
second_title: Aspose.Slides برای Java API Reference
description: یک شی OLE را بر روی یک اسلاید نمایندگی می‌کند.
type: docs
url: /fa/com.aspose.slides/ioleobjectframe/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

شی OLE را بر روی یک اسلاید نمایندگی می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | شی خصوصیات پرکردن تصویر OleObject را باز می‌گرداند. |
| [getObjectName()](#getObjectName--) | نام یک شی را بر می‌گرداند یا تنظیم می‌کند. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | نام یک شی را بر می‌گرداند یا تنظیم می‌کند. |
| [getEmbeddedData()](#getEmbeddedData--) | اطلاعات درباره داده‌های جاسازی‌شده OLE را دریافت می‌کند. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | اطلاعات درباره داده‌های جاسازی‌شده OLE را تنظیم می‌کند. |
| [getObjectProgId()](#getObjectProgId--) | ProgID یک شی را باز می‌گرداند. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | ProgID یک شی را باز می‌گرداند. |
| [getLinkFileName()](#getLinkFileName--) | مسیر کامل یک فایل پیوندی را باز می‌گرداند. |
| [getLinkPathLong()](#getLinkPathLong--) | مسیر کامل یک فایل پیوندی را باز می‌گرداند. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | مسیر کامل یک فایل پیوندی را باز می‌گرداند. |
| [getLinkPathRelative()](#getLinkPathRelative--) | اگر موجود باشد مسیر نسبی یک فایل پیوندی را باز می‌گرداند، در غیر این صورت رشته خالی را باز می‌گرداند. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | نام فایل شی OLE جاسازی‌شده را باز می‌گرداند |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | مسیر شی OLE جاسازی‌شده را باز می‌گرداند |
| [isObjectIcon()](#isObjectIcon--) | تعیین می‌کند که آیا یک شی به‌عنوان نماد قابل مشاهده است یا خیر. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | تعیین می‌کند که آیا یک شی به‌عنوان نماد قابل مشاهده است یا خیر. |
| [isObjectLink()](#isObjectLink--) | تعیین می‌کند که آیا یک شی به فایل خارجی پیوند دارد یا خیر. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | تعیین می‌کند که آیا شی پیوندی جاسازی‌شده به‌صورت خودکار هنگام باز یا چاپ ارائه به‌روز می‌شود یا خیر. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | تعیین می‌کند که آیا شی پیوندی جاسازی‌شده به‌صورت خودکار هنگام باز یا چاپ ارائه به‌روز می‌شود یا خیر. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | عنوان نماد OleObject را باز می‌گرداند یا تنظیم می‌کند. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | عنوان نماد OleObject را باز می‌گرداند یا تنظیم می‌کند. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

شی خصوصیات پرکردن تصویر OleObject را باز می‌گرداند. فقط‌خواندنی [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**بازگشت:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

نام یک شی را بر می‌گرداند یا تنظیم می‌کند. قابل‌نوشتن/خواندن String.

**بازگشت:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

نام یک شی را بر می‌گرداند یا تنظیم می‌کند. قابل‌نوشتن/خواندن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

اطلاعات درباره داده‌های جاسازی‌شده OLE را دریافت می‌کند. فقط‌خواندنی [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**بازگشت:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

اطلاعات درباره داده‌های جاسازی‌شده OLE را تنظیم می‌کند.

--------------------

> ```
> مثال زیر نحوه تغییر داده‌های جاسازی‌شده OLE را نشان می‌دهد
>  و نوع آن برای شی موجود [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) 
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(Files.readAllBytes(Paths.get("Picture.png")), "png");
>          oof.setEmbeddedData(newData);
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | دادهٔ جاسازی‌شده [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

این متد ویژگی‌های شی را برای انعکاس داده‌های جدید تغییر می‌دهد و پرچم IsObjectLink را به false تنظیم می‌کند، به این معنی که شی OLE جاسازی‌شده است. |
### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

ProgID یک شی را باز می‌گرداند. فقط‌خواندنی String.

**بازگشت:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

ProgID یک شی را باز می‌گرداند. فقط‌خواندنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

مسیر کامل یک فایل پیوندی را باز می‌گرداند. نام کوتاه فایل استفاده می‌شود. فقط‌خواندنی String.

**بازگشت:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

مسیر کامل یک فایل پیوندی را باز می‌گرداند. نام بلند فایل استفاده می‌شود. قابل‌نوشتن/خواندن String.

**بازگشت:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

مسیر کامل یک فایل پیوندی را باز می‌گرداند. نام بلند فایل استفاده می‌شود. قابل‌نوشتن/خواندن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

اگر موجود باشد مسیر نسبی یک فایل پیوندی را باز می‌گرداند، در غیر این صورت رشته خالی را باز می‌گرداند. فقط‌خواندنی String.

--------------------

> ```
> Presentation presentation = new Presentation("demo.ppt");
>  try {
>      IOleObjectFrame oleFrame = (IOleObjectFrame)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oleFrame != null)
>      {
>          System.out.println("The relative path: " + oleFrame.getLinkPathRelative());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


--------------------

در ارائه‌های Ppt، برخی پیوندهای شی Ole ممکن است نمایانگر نسبی داشته باشند.

**بازگشت:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

نام فایل شی OLE جاسازی‌شده را باز می‌گرداند

**بازگشت:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

مسیر شی OLE جاسازی‌شده را باز می‌گرداند

**بازگشت:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

تعیین می‌کند که آیا یک شی به‌عنوان نماد قابل مشاهده است یا خیر. قابل‌نوشتن/خواندن boolean.

**بازگشت:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

تعیین می‌کند که آیا یک شی به‌عنوان نماد قابل مشاهده است یا خیر. قابل‌نوشتن/خواندن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

تعیین می‌کند که آیا یک شی به فایل خارجی پیوند دارد یا خیر. فقط‌خواندنی boolean.

**بازگشت:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

تعیین می‌کند که آیا شی پیوندی جاسازی‌شده به‌صورت خودکار هنگام باز یا چاپ ارائه به‌روز می‌شود یا خیر. قابل‌نوشتن/خواندن boolean.

**بازگشت:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

تعیین می‌کند که آیا شی پیوندی جاسازی‌شده به‌صورت خودکار هنگام باز یا چاپ ارائه به‌روز می‌شود یا خیر. قابل‌نوشتن/خواندن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

عنوان نماد OleObject را باز می‌گرداند یا تنظیم می‌کند. قابل‌نوشتن/خواندن String.

--------------------

زمانی که IsObjectIcon == false این مقدار نادیده گرفته می‌شود. رشته می‌تواند مطابق با اندازهٔ نماد OLE کوتاه شود.

**بازگشت:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

عنوان نماد OleObject را باز می‌گرداند یا تنظیم می‌کند. قابل‌نوشتن/خواندن String.

--------------------

زمانی که IsObjectIcon == false این مقدار نادیده گرفته می‌شود. رشته می‌تواند مطابق با اندازهٔ نماد OLE کوتاه شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |