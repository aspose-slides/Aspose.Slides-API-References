---
title: IAutoShape
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر یک AutoShape.
type: docs
url: /fa/com.aspose.slides/iautoshape/
---
**تمام واسط‌های پیاده‌سازی شده:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

نمایانگر یک AutoShape.
## متدها

| متد | توضیح |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | قفل‌های AutoShape را برمی‌گرداند. |
| [getTextFrame()](#getTextFrame--) | آبجکت TextFrame را برای AutoShape برمی‌گرداند. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | تعیین می‌کند که آیا این autoshape باید به‌جای مشخص‌شده توسط سبک یا فرمت پر، با پر-شدن پس‌زمینهٔ اسلاید پر شود یا نه. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | تعیین می‌کند که آیا این autoshape باید به‌جای مشخص‌شده توسط سبک یا فرمت پر، با پر-شدن پس‌زمینهٔ اسلاید پر شود یا نه. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | یک TextFrame جدید به شکل اضافه می‌کند. |
| [isTextBox()](#isTextBox--) | مشخص می‌کند که آیا شکل یک جعبهٔ متن است یا خیر. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```

قفل‌های AutoShape را برمی‌گرداند. فقط-خواندنی [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**بازگشت:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

آبجکت TextFrame را برای AutoShape برمی‌گرداند. فقط-خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**بازگشت:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```

تعیین می‌کند که آیا این autoshape باید به‌جای مشخص‌شده توسط سبک یا فرمت پر، با پر-شدن پس‌زمینهٔ اسلاید پر شود یا نه. بولی قابل خواندن/نوشتن.

**بازگشت:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```

تعیین می‌کند که آیا این autoshape باید به‌جای مشخص‌شده توسط سبک یا فرمت پر، با پر-شدن پس‌زمینهٔ اسلاید پر شود یا نه. بولی قابل خواندن/نوشتن.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```

یک TextFrame جدید به شکل اضافه می‌کند. اگر شکل قبلاً TextFrame داشته باشد، به سادگی متن آن را تغییر می‌دهد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن پیش‌فرض برای یک TextFrame جدید. |

**بازگشت:**
[ITextFrame](../../com.aspose.slides/itextframe) - New [ITextFrame](../../com.aspose.slides/itextframe) object.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```

مشخص می‌کند که آیا شکل یک جعبهٔ متن است یا خیر.

--------------------

اگر شکل به‌عنوان جعبهٔ متن مشخص نشده باشد، به این معنا نیست که نمی‌تواند متن داشته باشد. یک جعبهٔ متن صرفاً یک شکل ویژه با ویژگی‌های خاص است.

**بازگشت:**
boolean