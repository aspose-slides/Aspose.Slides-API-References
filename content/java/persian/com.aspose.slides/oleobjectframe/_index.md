---
title: OleObjectFrame
second_title: Aspose.Slides برای Java API مرجع
description: یک شیء OLE را در اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/oleobjectframe/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

یک شیء OLE را در اسلاید نشان می‌دهد.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // فایل PPTX را به یک شیء presentation بارگذاری می‌کند
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // اسلاید اول را دسترسی می‌یابد
>      ISlide sld = pres.getSlides().get_Item(0);
>      // شکل را به OleObjectFrame تبدیل می‌کند
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // شیء OLE را می‌خواند و به دیسک می‌نویسد
>      if (oleObjectFrame != null) {
>          // داده‌های فایل جاسازی شده را دریافت می‌کند
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // پسوند فایل جاسازی شده را دریافت می‌کند
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // یک مسیر برای ذخیره‌سازی فایل استخراج‌شده ایجاد می‌کند
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // داده‌های استخراج‌شده را ذخیره می‌کند
>          Files.write(Paths.get(extractedPath), data);
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## متدها

| متد | توضیح |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | شیء ویژگی‌های پر کردن تصویر OleObject را برمی‌گرداند. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | عنوان نماد OleObject را برمی‌گرداند یا تنظیم می‌کند. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | عنوان نماد OleObject را برمی‌گرداند یا تنظیم می‌کند. |
| [getObjectName()](#getObjectName--) | نام یک شیء را برمی‌گرداند یا تنظیم می‌کند. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | نام یک شیء را برمی‌گرداند یا تنظیم می‌کند. |
| [getObjectProgId()](#getObjectProgId--) | ProgID شیء را برمی‌گرداند. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | ProgID شیء را برمی‌گرداند. |
| [getLinkFileName()](#getLinkFileName--) | مسیر کامل به فایل پیوند داده شده را برمی‌گرداند. |
| [getLinkPathLong()](#getLinkPathLong--) | مسیر کامل به فایل پیوند داده شده را برمی‌گرداند. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | مسیر کامل به فایل پیوند داده شده را برمی‌گرداند. |
| [getLinkPathRelative()](#getLinkPathRelative--) | در صورت وجود مسیر نسبی به فایل پیوند داده شده را برمی‌گرداند، در غیر این صورت رشته خالی برمی‌گرداند. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | نام فایل شیء OLE جاسازی شده را برمی‌گرداند |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | مسیر شیء OLE جاسازی شده را برمی‌گرداند |
| [getEmbeddedData()](#getEmbeddedData--) | اطلاعات درباره داده‌های جاسازی شده OLE را دریافت یا تنظیم می‌کند. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | اطلاعات درباره داده‌های جاسازی شده OLE را تنظیم می‌کند. |
| [isObjectIcon()](#isObjectIcon--) | تعیین می‌کند آیا شیء به صورت نماد قابل مشاهده است یا خیر. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | تعیین می‌کند آیا شیء به صورت نماد قابل مشاهده است یا خیر. |
| [isObjectLink()](#isObjectLink--) | تعیین می‌کند آیا شیء به فایل خارجی پیوند داده شده است یا خیر. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | تعیین می‌کند آیا شیء جاسازی شده پیوند داده شده به‌صورت خودکار هنگام باز یا چاپ ارائه به‌روزرسانی می‌شود یا خیر. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | تعیین می‌کند آیا شیء جاسازی شده پیوند داده شده به‌صورت خودکار هنگام باز یا چاپ ارائه به‌روزرسانی می‌شود یا خیر. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

شیء ویژگی‌های پر کردن تصویر OleObject را برمی‌گرداند. فقط-خواندنی [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**بازگشت:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

عنوان نماد OleObject را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

--------------------

اگر IsObjectIcon == false این مقدار نادیده گرفته می‌شود. رشته می‌تواند بر اساس اندازه نماد Ole کوتاه شود.

**بازگشت:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

عنوان نماد OleObject را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

--------------------

اگر IsObjectIcon == false این مقدار نادیده گرفته می‌شود. رشته می‌تواند بر اساس اندازه نماد Ole کوتاه شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

نام یک شیء را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

نام یک شیء را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

ProgID شیء را برمی‌گرداند. فقط-خواندنی String.

**بازگشت:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

ProgID شیء را برمی‌گرداند. فقط-خواندنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

مسیر کامل به فایل پیوند داده شده را برمی‌گرداند. نام فایل کوتاه استفاده می‌شود. فقط-خواندنی String.

**بازگشت:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

مسیر کامل به فایل پیوند داده شده را برمی‌گرداند. نام فایل طولانی استفاده می‌شود. خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

مسیر کامل به فایل پیوند داده شده را برمی‌گرداند. نام فایل طولانی استفاده می‌شود. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

در صورت وجود مسیر نسبی به فایل پیوند داده شده را برمی‌گرداند، در غیر این صورت رشته خالی برمی‌گرداند. فقط-خواندنی String.

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

در ارائه‌های Ppt، برخی پیوندهای شیء Ole ممکن است نمایه نسبی داشته باشند.

**بازگشت:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```

نام فایل شیء OLE جاسازی شده را برمی‌گرداند

**بازگشت:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

مسیر شیء OLE جاسازی شده را برمی‌گرداند

**بازگشت:**
java.lang.String
### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

اطلاعات درباره داده‌های جاسازی شده OLE را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**بازگشت:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

اطلاعات درباره داده‌های جاسازی شده OLE را تنظیم می‌کند.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
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
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | داده‌های جاسازی شده [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

این متد ویژگی‌های شیء را برای بازتاب داده‌های جدید تغییر می‌دهد و پرچم IsObjectLink را به false تنظیم می‌کند، به‌طوری که نشان دهد شیء OLE جاسازی شده است. |

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

تعیین می‌کند آیا شیء به صورت نماد قابل مشاهده است یا خیر. خواندنی/نوشتنی boolean .

**بازگشت:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

تعیین می‌کند آیا شیء به صورت نماد قابل مشاهده است یا خیر. خواندنی/نوشتنی boolean .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

تعیین می‌کند آیا شیء به فایل خارجی پیوند داده شده است یا خیر. فقط-خواندنی boolean .

**بازگشت:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

تعیین می‌کند آیا شیء جاسازی شده پیوند داده شده به‌صورت خودکار هنگام باز یا چاپ ارائه به‌روزرسانی می‌شود یا خیر. خواندنی/نوشتنی boolean .

**بازگشت:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

تعیین می‌کند آیا شیء جاسازی شده پیوند داده شده به‌صورت خودکار هنگام باز یا چاپ ارائه به‌روزرسانی می‌شود یا خیر. خواندنی/نوشتنی boolean .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |