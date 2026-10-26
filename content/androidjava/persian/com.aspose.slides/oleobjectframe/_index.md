---
title: OleObjectFrame
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: یک شیء OLE را در یک اسلاید نمایش می‌دهد.
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

یک شیء OLE را در یک اسلاید نمایش می‌دهد.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
  
>  // فایل PPTX را به یک شیء Presentation بارگذاری می‌کند
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // به اسلاید اول دسترسی پیدا می‌کند
>      ISlide sld = pres.getSlides().get_Item(0);
>      // شکل را به OleObjectFrame تبدیل می‌کند
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // شیء OLE را می‌خواند و بر روی دیسک می‌نویسد
>      if (oleObjectFrame != null) {
>          // داده‌های فایل تعبیه‌شده را دریافت می‌کند
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // پسوند فایل تعبیه‌شده را دریافت می‌کند
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // مسیر ذخیره‌سازی فایل استخراج‌شده را ایجاد می‌کند
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // داده‌های استخراج‌شده را ذخیره می‌کند
>          FileOutputStream fos = null;
>          try {
>              fos = new FileOutputStream(extractedPath);
>              fos.write(data);
>          } finally {
>              if (fos != null) fos.close();
>          }
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## متدها

| متد | توضیح |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | شیء ویژگی‌های پر کردن تصویر OleObject را باز می‌گرداند. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | عنوان نماد OleObject را باز می‌گرداند یا تنظیم می‌کند. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | عنوان نماد OleObject را باز می‌گرداند یا تنظیم می‌کند. |
| [getObjectName()](#getObjectName--) | نام یک شیء را باز می‌گرداند یا تنظیم می‌کند. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | نام یک شیء را باز می‌گرداند یا تنظیم می‌کند. |
| [getObjectProgId()](#getObjectProgId--) | ProgID یک شیء را باز می‌گرداند. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | ProgID یک شیء را باز می‌گرداند. |
| [getLinkFileName()](#getLinkFileName--) | مسیر کامل به یک فایل پیوند شده را باز می‌گرداند. |
| [getLinkPathLong()](#getLinkPathLong--) | مسیر کامل به یک فایل پیوند شده را باز می‌گرداند. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | مسیر کامل به یک فایل پیوند شده را باز می‌گرداند. |
| [getLinkPathRelative()](#getLinkPathRelative--) | در صورت وجود، مسیر نسبی یک فایل پیوند شده را باز می‌گرداند؛ در غیر این صورت یک رشته خالی را برمی‌گرداند. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | نام فایل شیء OLE تعبیه‌شده را باز می‌گرداند |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | مسیر شیء OLE تعبیه‌شده را باز می‌گرداند |
| [getEmbeddedData()](#getEmbeddedData--) | اطلاعات مربوط به داده‌های تعبیه‌شده OLE را دریافت یا تنظیم می‌کند. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | اطلاعات مربوط به داده‌های تعبیه‌شده OLE را تنظیم می‌کند. |
| [isObjectIcon()](#isObjectIcon--) | مشخص می‌کند که آیا شیء به‌صورت نماد قابل مشاهده است یا خیر. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | مشخص می‌کند که آیا شیء به‌صورت نماد قابل مشاهده است یا خیر. |
| [isObjectLink()](#isObjectLink--) | مشخص می‌کند که آیا شیء به‌فایل خارجی پیوند داده شده است یا خیر. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | مشخص می‌کند که آیا شیء تعبیه‌شدهٔ پیوند‌شده هنگام باز یا چاپ ارائه به‌صورت خودکار به‌روزرسانی می‌شود یا خیر. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | مشخص می‌کند که آیا شیء تعبیه‌شدهٔ پیوند‌شده هنگام باز یا چاپ ارائه به‌صورت خودکار به‌روزرسانی می‌شود یا خیر. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

شیء ویژگی‌های پر کردن تصویر OleObject را باز می‌گرداند. فقط‌خواندنی [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**باز می‌گرداند:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

عنوان نماد OleObject را باز می‌گرداند یا تنظیم می‌کند. قابل‌نوشتن String.

**باز می‌گرداند:**
java.lang.String

--------------------

هنگامی که IsObjectIcon == false این مقدار نادیده گرفته می‌شود. رشته می‌تواند بر اساس اندازه نماد Ole کوتاه شود.

**باز می‌گرداند:**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

عنوان نماد OleObject را باز می‌گرداند یا تنظیم می‌کند. قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

نام یک شیء را باز می‌گرداند یا تنظیم می‌کند. قابل‌نوشتن String.

**باز می‌گرداند:**
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

نام یک شیء را باز می‌گرداند یا تنظیم می‌کند. قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

ProgID یک شیء را باز می‌گرداند. فقط‌خواندنی String.

**باز می‌گرداند:**
java.lang.String

### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

ProgID یک شیء را باز می‌گرداند. فقط‌خواندنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

مسیر کامل به یک فایل پیوند شده را باز می‌گرداند. نام کوتاه فایل استفاده می‌شود. فقط‌خواندنی String.

**باز می‌گرداند:**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

مسیر کامل به یک فایل پیوند شده را باز می‌گرداند. نام طولانی فایل استفاده می‌شود. قابل‌نوشتن String.

**باز می‌گرداند:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

مسیر کامل به یک فایل پیوند شده را باز می‌گرداند. نام طولانی فایل استفاده می‌شود. قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
```

در صورت وجود، مسیر نسبی یک فایل پیوند شده را باز می‌گرداند؛ در غیر این صورت یک رشته خالی را برمی‌گرداند. فقط‌خواندنی String.

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

در ارائه‌های Ppt، برخی پیوندهای شیء OLE ممکن است نمایهٔ نسبی داشته باشند.

**باز می‌گرداند:**
java.lang.String

### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public final String getEmbeddedFileLabel()
```

نام فایل شیء OLE تعبیه‌شده را باز می‌گرداند

**باز می‌گرداند:**
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

مسیر شیء OLE تعبیه‌شده را باز می‌گرداند

**باز می‌گرداند:**
java.lang.String

### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

اطلاعات درباره داده‌های تعبیه‌شده OLE را دریافت یا تنظیم می‌کند. قابل‌نوشتن [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**باز می‌گرداند:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

اطلاعات درباره داده‌های تعبیه‌شده OLE را تنظیم می‌کند.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          BufferedInputStream bis = null;
>          DataInputStream dis = null;
>          try {
>              File file = new File("Picture.png");
>              byte[] bytes = new byte[(int) file.length()];
>              bis = new BufferedInputStream(new FileInputStream(file));
>              dis = new DataInputStream(bis);
>              dis.readFully(bytes);
>              IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(bytes, "png");
>              oof.setEmbeddedData(newData);
>          } finally {
>              if (dis != null) {
>                  dis.close();
>              if (bis != null)
>                  bis.close();
>              }
>          }
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | داده‌های تعبیه‌شده [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

این متد خصوصیات شیء را برای منعکس‌کردن داده‌های جدید تغییر می‌دهد و پرچم IsObjectLink را به false تنظیم می‌کند، نشان‌دهنده این است که شیء OLE تعبیه‌شده است. |

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

مشخص می‌کند که آیا شیء به‌صورت نماد قابل مشاهده است یا خیر. قابل‌نوشتن boolean .

**باز می‌گرداند:**
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

مشخص می‌کند که آیا شیء به‌صورت نماد قابل مشاهده است یا خیر. قابل‌نوشتن boolean .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

مشخص می‌کند که آیا شیء به‌فایل خارجی پیوند داده شده است یا خیر. فقط‌خواندنی boolean .

**باز می‌گرداند:**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

مشخص می‌کند که آیا شیء تعبیه‌شدهٔ پیوند‌شده هنگام باز یا چاپ ارائه به‌صورت خودکار به‌روزرسانی می‌شود یا خیر. قابل‌نوشتن boolean .

**باز می‌گرداند:**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

مشخص می‌کند که آیا شیء تعبیه‌شدهٔ پیوند‌شده هنگام باز یا چاپ ارائه به‌صورت خودکار به‌روزرسانی می‌شود یا خیر. قابل‌نوشتن boolean .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |