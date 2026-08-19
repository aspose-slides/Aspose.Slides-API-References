---
title: IAutoShape
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر یک AutoShape است.
type: docs
url: /fa/com.aspose.slides/iautoshape/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

نمایانگر یک AutoShape.

## متدها

| متد | توضیح |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | قفل‌های AutoShape را بازمی‌گرداند. |
| [getTextFrame()](#getTextFrame--) | شیء TextFrame را برای AutoShape بازمی‌گرداند. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | تعیین می‌کند که آیا این autoshape باید با پر کردن پس‌زمینه اسلاید پر شود به‌جای اینکه توسط سبک یا قالب پر شود. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | تعیین می‌کند که آیا این autoshape باید با پر کردن پس‌زمینه اسلاید پر شود به‌جای اینکه توسط سبک یا قالب پر شود. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | یک TextFrame جدید به شکل اضافه می‌کند. |
| [isTextBox()](#isTextBox--) | مشخص می‌کند که آیا شکل یک جعبه متن است. |

### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```

قفل‌های AutoShape را بازمی‌گرداند. فقط-خواندنی [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**بازگشت:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)

### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

شیء TextFrame را برای AutoShape بازمی‌گرداند. فقط-خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**بازگشت:**
[ITextFrame](../../com.aspose.slides/itextframe)

### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```

تعیین می‌کند که آیا این autoshape باید با پر کردن پس‌زمینه اسلاید پر شود به‌جای اینکه توسط سبک یا قالب پر شود. خواندنی/قابل‌نوشتن boolean.

**بازگشت:**
boolean

### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```

تعیین می‌کند که آیا این autoshape باید با پر کردن پس‌زمینه اسلاید پر شود به‌جای اینکه توسط سبک یا قالب پر شود. خواندنی/قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```

یک TextFrame جدید به شکل اضافه می‌کند. اگر شکل قبلاً TextFrame داشته باشد، متن آن را به سادگی تغییر می‌دهد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| text | java.lang.String | متن پیش‌فرض برای یک TextFrame جدید. |

**بازگشت:**
[ITextFrame](../../com.aspose.slides/itextframe) - شیء جدید [ITextFrame](../../com.aspose.slides/itextframe).

### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```

مشخص می‌کند که آیا شکل یک جعبه متن است.

--------------------

اگر شکل به‌صورت جعبه متن مشخص نشده باشد، به این معنا نیست که نمی‌تواند متن داشته باشد. جعبه متن صرفاً یک شکل تخصصی با ویژگی‌های خاص است.

**بازگشت:**
boolean