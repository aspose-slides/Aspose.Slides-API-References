---
title: GroupShape
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک گروه از اشکال در یک اسلاید است.
type: docs
url: /fa/com.aspose.slides/groupshape/
---
**وراثت:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape)

**همهٔ رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGroupShape](../../com.aspose.slides/igroupshape)
```
public class GroupShape extends Shape implements IGroupShape
```

نمایانگر یک گروه از اشکال در یک اسلاید است.
## متدها

| متد | توضیح |
| --- | --- |
| [getLineFormat()](#getLineFormat--) | شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است باز می‌گرداند. |
| [getGroupShapeLock()](#getGroupShapeLock--) | قفل‌های شکل را باز می‌گرداند. |
| [getShapes()](#getShapes--) | مجموعهٔ اشکال داخل گروه را باز می‌گرداند. |
### getLineFormat() {#getLineFormat--}
```
public ILineFormat getLineFormat()
```

شیء LineFormat را که شامل ویژگی‌های قالب‌بندی خط برای یک شکل است باز می‌گرداند. توجه: برای اشیای GroupShape مقدار null باز می‌گردد چون آنها ویژگی خط ندارند. فقط-خواندنی [ILineFormat](../../com.aspose.slides/ilineformat).

**بازگشت:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getGroupShapeLock() {#getGroupShapeLock--}
```
public final IGroupShapeLock getGroupShapeLock()
```

قفل‌های شکل را باز می‌گرداند. فقط-خواندنی [IGroupShapeLock](../../com.aspose.slides/igroupshapelock).

**بازگشت:**
[IGroupShapeLock](../../com.aspose.slides/igroupshapelock)
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

مجموعهٔ اشکال داخل گروه را باز می‌گرداند. فقط-خواندنی [IShapeCollection](../../com.aspose.slides/ishapecollection).

**بازگشت:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)