---
title: IOleObjectFrame
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: یک شیء OLE را بر روی اسلاید نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/ioleobjectframe/
---
**همه رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

یک شیء OLE را بر روی اسلاید نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | شیء ویژگی‌های پر کردن تصویر OleObject را برمی‌گرداند. |
| [getObjectName()](#getObjectName--) | نام یک شیء را برمی‌گرداند یا تنظیم می‌کند. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | نام یک شیء را برمی‌گرداند یا تنظیم می‌کند. |
| [getEmbeddedData()](#getEmbeddedData--) | اطلاعات مربوط به داده‌های توکار OLE را به‌دست می‌آورد. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | اطلاعات مربوط به داده‌های توکار OLE را تنظیم می‌کند. |
| [getObjectProgId()](#getObjectProgId--) | ProgID یک شیء را برمی‌گرداند. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | ProgID یک شیء را برمی‌گرداند. |
| [getLinkFileName()](#getLinkFileName--) | مسیر کامل یک فایل پیوند شده را برمی‌گرداند. |
| [getLinkPathLong()](#getLinkPathLong--) | مسیر کامل یک فایل پیوند شده را برمی‌گرداند. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | مسیر کامل یک فایل پیوند شده را برمی‌گرداند. |
| [getLinkPathRelative()](#getLinkPathRelative--) | اگر موجود باشد مسیر نسبی یک فایل پیوند شده را برمی‌گرداند، در غیر اینصورت رشته خالی برمی‌گرداند. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | نام فایل شیء OLE توکار را برمی‌گرداند |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | مسیر شیء OLE توکار را برمی‌گرداند |
| [isObjectIcon()](#isObjectIcon--) | تعیین می‌کند آیا یک شیء به شکل آیکون قابل مشاهده است یا خیر. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | تعیین می‌کند آیا یک شیء به شکل آیکون قابل مشاهده است یا خیر. |
| [isObjectLink()](#isObjectLink--) | تعیین می‌کند آیا یک شیء به فایل خارجی پیوند دارد یا خیر. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | تعیین می‌کند آیا شیء توکار پیوند شده به‌صورت خودکار هنگام باز یا چاپ ارائه به‌روز می‌شود یا خیر. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | تعیین می‌کند آیا شیء توکار پیوند شده به‌صورت خودکار هنگام باز یا چاپ ارائه به‌روز می‌شود یا خیر. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | عنوان آیکون OleObject را برمی‌گرداند یا تنظیم می‌کند. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | عنوان آیکون OleObject را برمی‌گرداند یا تنظیم می‌کند. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

شیء ویژگی‌های پر کردن تصویر OleObject را برمی‌گرداند. فقط-خواندنی [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**بازگشت:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```

نام یک شیء را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```

نام یک شیء را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```

اطلاعات مربوط به داده‌های توکار OLE را به‌دست می‌آورد. فقط-خواندنی [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**بازگشت:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

اطلاعات مربوط به داده‌های توکار OLE را تنظیم می‌کند.

--------------------

> ```
> Following example demonstrates how to change OLE embedded data
>  and its type for existing [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) object 
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
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
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | داده توکار [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

--------------------

این متد ویژگی‌های شیء را برای انعکاس داده‌های جدید تغییر می‌دهد و پرچم IsObjectLink را به false تنظیم می‌کند، که نشان دهنده این است که شیء OLE توکار است. |
### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```

ProgID یک شیء را برمی‌گرداند. فقط-خواندنی String.

**بازگشت:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```

ProgID یک شیء را برمی‌گرداند. فقط-خواندنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```

مسیر کامل یک فایل پیوند شده را برمی‌گرداند. نام کوتاه فایل استفاده خواهد شد. فقط-خواندنی String.

**بازگشت:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```

مسیر کامل یک فایل پیوند شده را برمی‌گرداند. نام بلند فایل استفاده خواهد شد. خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```

مسیر کامل یک فایل پیوند شده را برمی‌گرداند. نام بلند فایل استفاده خواهد شد. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```

اگر موجود باشد مسیر نسبی یک فایل پیوند شده را برمی‌گرداند، در غیر اینصورت رشته خالی برمی‌گرداند. فقط-خواندنی String.

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


در ارائه‌های Ppt، برخی پیوندهای شیء Ole ممکن است دارای نمای نسبی باشند.

**بازگشت:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```

نام فایل شیء OLE توکار را برمی‌گرداند

**بازگشت:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```

مسیر شیء OLE توکار را برمی‌گرداند

**بازگشت:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```

تعیین می‌کند آیا یک شیء به شکل آیکون قابل مشاهده است یا خیر. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```

تعیین می‌کند آیا یک شیء به شکل آیکون قابل مشاهده است یا خیر. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```

تعیین می‌کند آیا یک شیء به فایل خارجی پیوند دارد یا خیر. فقط-خواندنی boolean.

**بازگشت:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```

تعیین می‌کند آیا شیء توکار پیوند شده به‌صورت خودکار هنگام باز یا چاپ ارائه به‌روز می‌شود یا خیر. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```

تعیین می‌کند آیا شیء توکار پیوند شده به‌صورت خودکار هنگام باز یا چاپ ارائه به‌روز می‌شود یا خیر. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```

عنوان آیکون OleObject را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

--------------------

زمانی که IsObjectIcon == false این مقدار نادیده گرفته می‌شود. رشته می‌تواند بر اساس اندازه آیکون OLE کوتاه شود.

**بازگشت:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```

عنوان آیکون OleObject را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

--------------------

زمانی که IsObjectIcon == false این مقدار نادیده گرفته می‌شود. رشته می‌تواند بر اساس اندازه آیکون OLE کوتاه شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |