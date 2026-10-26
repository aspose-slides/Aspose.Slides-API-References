---
title: GroupShape
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک گروه از اشکال در یک اسلاید است.
type: docs
url: /fa/com.aspose.slides/groupshape/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

نمایانگر یک گروه از اشکال در یک اسلاید است.
## متدها

| متد | توضیح |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | شیء LineFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است. |
| [getGroupShapeLock()](#getGroupShapeLock--) | قفل‌های شکل را برمی‌گرداند. |
| [getShapes()](#getShapes--) | مجموعه‌ای از اشکال داخل گروه را برمی‌گرداند. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

شیء LineFormat را برمی‌گرداند که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است. نکته: برای اشیاء GroupShape مقدار null برمی‌گرداند زیرا آن‌ها ویژگی خط ندارند. فقط خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**بازگرداندن:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```

قفل‌های شکل را برمی‌گرداند. فقط خواندنی [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**بازگرداندن:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

مجموعه‌ای از اشکال داخل گروه را برمی‌گرداند. فقط خواندنی [IShapeCollection](../../com.aspose.slides/ishapecollection).

**بازگرداندن:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)