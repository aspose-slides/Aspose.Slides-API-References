---
title: IChartWall
second_title: Aspose.Slides for Android via Java API Reference
description: Represents walls on 3d charts.
type: docs
url: /fa/com.aspose.slides/ichartwall/
---```
public interface IChartWall
```

نمایانگر دیوارها در نمودارهای سه‌بعدی است.
## متدها

| متد | توضیحات |
| --- | --- |
| [getThickness()](#getThickness--) | ضخامت دیوارها را به عنوان درصدی از بزرگ‌ترین بعد حجم نمودار برمی‌گرداند یا تنظیم می‌کند. |
| [setThickness(int value)](#setThickness-int-) | ضخامت دیوارها را به عنوان درصدی از بزرگ‌ترین بعد حجم نمودار برمی‌گرداند یا تنظیم می‌کند. |
| [getFormat()](#getFormat--) | پرکننده دیوار، خط، اثر و سبک‌های سه‌بعدی را برمی‌گرداند. |
| [getPictureType()](#getPictureType--) | نوع تصویر را برمی‌گرداند یا تنظیم می‌کند. |
| [setPictureType(int value)](#setPictureType-int-) | نوع تصویر را برمی‌گرداند یا تنظیم می‌کند. |
### getThickness() {#getThickness--}
```
public abstract int getThickness()
```


ضخامت دیوارها را به عنوان درصدی از بزرگ‌ترین بعد حجم نمودار برمی‌گرداند یا تنظیم می‌کند. Read/write int.

**بازگشت:**  
int
### setThickness(int value) {#setThickness-int-}
```
public abstract void setThickness(int value)
```


ضخامت دیوارها را به عنوان درصدی از بزرگ‌ترین بعد حجم نمودار برمی‌گرداند یا تنظیم می‌کند. Read/write int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


پرکننده دیوار، خط، اثر و سبک‌های سه‌بعدی را برمی‌گرداند. Read-only [IFormat](../../com.aspose.slides/iformat).

**بازگشت:**  
[IFormat](../../com.aspose.slides/iformat)
### getPictureType() {#getPictureType--}
```
public abstract int getPictureType()
```


نوع تصویر را برمی‌گرداند یا تنظیم می‌کند. Read/write [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**بازگشت:**  
int
### setPictureType(int value) {#setPictureType-int-}
```
public abstract void setPictureType(int value)
```


نوع تصویر را برمی‌گرداند یا تنظیم می‌کند. Read/write [PictureType](../../com.aspose.slides/picturetype)(\#getPictureType.getPictureType/\#setPictureType(int).setPictureType(int)).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |