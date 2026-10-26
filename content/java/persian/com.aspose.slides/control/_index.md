---
title: Control
second_title: Aspose.Slides برای مرجع API جاوا
description: نماینده یک کنترل ActiveX است.
type: docs
url: /fa/com.aspose.slides/control/
---
**ارث‌بری:**
java.lang.Object, com.aspose.slides.DomObject

**تمام اینترفیس‌های پیاده‌سازی شده:**
[com.aspose.slides.IControl](../../com.aspose.slides/icontrol)
```
public class Control extends DomObject<ControlCollection> implements IControl
```

نماینده یک کنترل ActiveX است.
## متدها

| متد | توضیح |
| --- | --- |
| [getPersistence()](#getPersistence--) | متد استفاده‌شده برای ذخیرهٔ ویژگی‌های کنترل ActiveX را دریافت می‌کند. |
| [getName()](#getName--) | نام این کنترل را دریافت یا تنظیم می‌کند. |
| [setName(String value)](#setName-java.lang.String-) | نام این کنترل را دریافت یا تنظیم می‌کند. |
| [getClassId()](#getClassId--) | شناسهٔ کلاس این کنترل را دریافت می‌کند. |
| [setClassId(UUID value)](#setClassId-java.util.UUID-) | شناسهٔ کلاس این کنترل را دریافت می‌کند. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | شیء ویژگی‌های پر کردن تصویر کنترل را برمی‌گرداند. |
| [getFrame()](#getFrame--) | قاب کنترل را دریافت یا تنظیم می‌کند. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | قاب کنترل را دریافت یا تنظیم می‌کند. |
| [getProperties()](#getProperties--) | یک مجموعه از ویژگی‌های ActiveX را برمی‌گرداند. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | پایداری یک کنترل ActiveX را زمانی که متد استفاده‌شده برای حفظ آن PersistStream، PersistStreamInit یا PersistStorage باشد، مشخص می‌کند. |
| [getSlide()](#getSlide--) |  |
| [getPresentation()](#getPresentation--) |  |

### getPersistence() {#getPersistence--}
```
public final int getPersistence()
```

متد استفاده‌شده برای ذخیرهٔ ویژگی‌های کنترل ActiveX را دریافت می‌کند. فقط خواندنی [PersistenceType](../../com.aspose.slides/persistencetype).

--------------------

> ```
> Next example shows the using Persistence property for checking if properties of ActiveX object may be changed as XML based ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //Use your own method for managing ActiveX properties stored in its binary file
>  }
> ```

**باز می‌گرداند:**
int

### getName() {#getName--}
```
public final String getName()
```

نام این کنترل را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی String.

**باز می‌گرداند:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```

نام این کنترل را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public final UUID getClassId()
```

شناسهٔ کلاس این کنترل را دریافت می‌کند. فقط خواندنی java.util.UUID.

**باز می‌گرداند:**
java.util.UUID

### setClassId(UUID value) {#setClassId-java.util.UUID-}
```
public final void setClassId(UUID value)
```

شناسهٔ کلاس این کنترل را دریافت می‌کند. فقط خواندنی java.util.UUID.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.util.UUID |  |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

شیء ویژگی‌های پر کردن تصویر کنترل را برمی‌گرداند. فقط خواندنی [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**باز می‌گرداند:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getFrame() {#getFrame--}
```
public final IShapeFrame getFrame()
```

قاب کنترل را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی [IShapeFrame](../../com.aspose.slides/ishapeframe).

**باز می‌گرداند:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public final void setFrame(IShapeFrame value)
```

قاب کنترل را دریافت یا تنظیم می‌کند. خواندنی/نوشتنی [IShapeFrame](../../com.aspose.slides/ishapeframe).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public final IControlPropertiesCollection getProperties()
```

یک مجموعه از ویژگی‌های ActiveX را برمی‌گرداند. فقط خواندنی [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

--------------------

توجه: Aspose.Slides فقط ویژگی‌های ActiveX مبتنی بر XML را پشتیبانی می‌کند. اگر ویژگی‌ها به صورت باینری ذخیره شوند، این ویژگی مقدار null را برمی‌گرداند.

**باز می‌گرداند:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)

### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public final byte[] getActiveXControlBinary()
```

پایداری یک کنترل ActiveX را زمانی که متد استفاده‌شده برای حفظ آن PersistStream، PersistStreamInit یا PersistStorage باشد، مشخص می‌کند.

--------------------

> ```
> Next example shows the using ActiveXControlBinary property for changing ActiveX properties:
>  
>  if (control.getPersistence() == PersistenceType.PersistPropertyBag)
>  {
>      control.getProperties().set_Item("Value", value);
>  }
>  else
>  {
>      YourMethodHere(control.getActiveXControlBinary()); //از روش خود برای مدیریت ویژگی‌های ActiveX که در فایل باینری آن ذخیره شده‌اند استفاده کنید
>  }
> ```

**باز می‌گرداند:**
byte[]

### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید پایه را برمی‌گرداند. فقط خواندنی [IBaseSlide](../../com.aspose.slides/ibaseslide).

**باز می‌گرداند:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

ارائه را برمی‌گرداند. فقط خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**باز می‌گرداند:**
[IPresentation](../../com.aspose.slides/ipresentation)