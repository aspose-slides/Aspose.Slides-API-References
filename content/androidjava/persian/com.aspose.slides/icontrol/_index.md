---
title: IControl
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر یک کنترل ActiveX است.
type: docs
url: /fa/com.aspose.slides/icontrol/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

نمایانگر یک کنترل ActiveX.

## متدها

| متد | توضیح |
| --- | --- |
| [getName()](#getName--) | نام این کنترل را باز می‌گرداند. |
| [setName(String value)](#setName-java.lang.String-) | نام این کنترل را باز می‌گرداند. |
| [getClassId()](#getClassId--) | شناسه کلاس این کنترل را دریافت می‌کند. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | شیء ویژگی‌های پر کردن تصویر ControlEx را باز می‌گرداند. |
| [getFrame()](#getFrame--) | قاب کنترل را باز می‌گرداند یا تنظیم می‌کند. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | قاب کنترل را باز می‌گرداند یا تنظیم می‌کند. |
| [getProperties()](#getProperties--) | مجموعه‌ای از ویژگی‌های ActiveX را باز می‌گرداند. |
| [getPersistence()](#getPersistence--) | روش استفاده شده برای ذخیره ویژگی‌های کنترل ActiveX را دریافت می‌کند. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | پایداری یک کنترل ActiveX را زمانی که روش استفاده شده برای حفظ آن PersistStream، PersistStreamInit یا PersistStorage باشد، مشخص می‌کند. |

### getName() {#getName--}
```
public abstract String getName()
```

نام این کنترل را باز می‌گرداند. خواندنی/نوشتنی String.

**باز می‌گرداند:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

نام این کنترل را باز می‌گرداند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```

شناسه کلاس این کنترل را دریافت می‌کند. فقط‌خواندنی java.util.UUID.

**باز می‌گرداند:**
java.util.UUID

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```

شیء ویژگی‌های پر کردن تصویر ControlEx را باز می‌گرداند. فقط‌خواندنی [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**باز می‌گرداند:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```

قاب کنترل را باز می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IShapeFrame](../../com.aspose.slides/ishapeframe).

**باز می‌گرداند:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)

### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```

قاب کنترل را باز می‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی [IShapeFrame](../../com.aspose.slides/ishapeframe).

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```

مجموعه‌ای از ویژگی‌های ActiveX را باز می‌گرداند. فقط‌خواندنی [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**باز می‌گرداند:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)

### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```

روش استفاده شده برای ذخیره ویژگی‌های کنترل ActiveX را دریافت می‌کند. فقط‌خواندنی [PersistenceType](../../com.aspose.slides/persistencetype).

**باز می‌گرداند:**
int

### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```

پایداری یک کنترل ActiveX را زمانی که روش استفاده شده برای حفظ آن PersistStream، PersistStreamInit یا PersistStorage باشد، مشخص می‌کند.

**باز می‌گرداند:**
byte[]