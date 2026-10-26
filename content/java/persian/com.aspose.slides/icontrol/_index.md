---
title: IControl
second_title: Aspose.Slides برای جاوا مرجع API
description: یک کنترل ActiveX را نمایش می‌دهد.
type: docs
url: /fa/com.aspose.slides/icontrol/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IControl extends ISlideComponent
```

یک کنترل ActiveX را نمایش می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getName()](#getName--) | نام این کنترل را برمی‌گرداند. |
| [setName(String value)](#setName-java.lang.String-) | نام این کنترل را برمی‌گرداند. |
| [getClassId()](#getClassId--) | شناسه کلاس این کنترل را دریافت می‌کند. |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | شیء ویژگی‌های پر کردن تصویر ControlEx را برمی‌گرداند. |
| [getFrame()](#getFrame--) | قاب کنترل را برمی‌گرداند یا تنظیم می‌کند. |
| [setFrame(IShapeFrame value)](#setFrame-com.aspose.slides.IShapeFrame-) | قاب کنترل را برمی‌گرداند یا تنظیم می‌کند. |
| [getProperties()](#getProperties--) | یک مجموعه از ویژگی‌های ActiveX را برمی‌گرداند. |
| [getPersistence()](#getPersistence--) | روش استفاده‌شده برای ذخیره‌سازی ویژگی‌های کنترل ActiveX را دریافت می‌کند. |
| [getActiveXControlBinary()](#getActiveXControlBinary--) | پایداری یک کنترل ActiveX را زمانی که روش استفاده‌شده برای نگهداری PersistStream، PersistStreamInit یا PersistStorage باشد، مشخص می‌کند. |
### getName() {#getName--}
```
public abstract String getName()
```


نام این کنترل را برمی‌گرداند. قابل خواندن/نوشتن String.

**بازگشت:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


نام این کنترل را برمی‌گرداند. قابل خواندن/نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getClassId() {#getClassId--}
```
public abstract UUID getClassId()
```


شناسه کلاس این کنترل را دریافت می‌کند. فقط‌خواندنی java.util.UUID.

**بازگشت:**
java.util.UUID
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


شیء ویژگی‌های پر کردن تصویر ControlEx را برمی‌گرداند. فقط‌خواندنی [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**بازگشت:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getFrame() {#getFrame--}
```
public abstract IShapeFrame getFrame()
```


قاب کنترل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IShapeFrame](../../com.aspose.slides/ishapeframe).

**بازگشت:**
[IShapeFrame](../../com.aspose.slides/ishapeframe)
### setFrame(IShapeFrame value) {#setFrame-com.aspose.slides.IShapeFrame-}
```
public abstract void setFrame(IShapeFrame value)
```


قاب کنترل را برمی‌گرداند یا تنظیم می‌کند. قابل خواندن/نوشتن [IShapeFrame](../../com.aspose.slides/ishapeframe).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IShapeFrame](../../com.aspose.slides/ishapeframe) |  |

### getProperties() {#getProperties--}
```
public abstract IControlPropertiesCollection getProperties()
```


یک مجموعه از ویژگی‌های ActiveX را برمی‌گرداند. فقط‌خواندنی [IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection).

**بازگشت:**
[IControlPropertiesCollection](../../com.aspose.slides/icontrolpropertiescollection)
### getPersistence() {#getPersistence--}
```
public abstract int getPersistence()
```


روش استفاده‌شده برای ذخیره‌سازی ویژگی‌های کنترل ActiveX را دریافت می‌کند. فقط‌خواندنی [PersistenceType](../../com.aspose.slides/persistencetype).

**بازگشت:**
int
### getActiveXControlBinary() {#getActiveXControlBinary--}
```
public abstract byte[] getActiveXControlBinary()
```


پایداری یک کنترل ActiveX را زمانی که روش استفاده‌شده برای نگهداری PersistStream، PersistStreamInit یا PersistStorage باشد، مشخص می‌کند.

**بازگشت:**
byte[]