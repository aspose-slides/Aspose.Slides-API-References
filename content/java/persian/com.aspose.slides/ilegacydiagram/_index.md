---
title: ILegacyDiagram
second_title: مرجع API Aspose.Slides برای جاوا
description: نمایانگر یک شیء نمودار قدیمی
type: docs
url: /fa/com.aspose.slides/ilegacydiagram/
---
**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

نمایانگر یک شیء نمودار قدیمی

## متدها

| متد | توضیح |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | نمودار قدیمی را به شیء SmartArt قابل ویرایش تبدیل می‌کند. |
| [convertToGroupShape()](#convertToGroupShape--) | نمودار قدیمی را به شکل گروهی قابل ویرایش تبدیل می‌کند. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

نمودار قدیمی را به شیء SmartArt قابل ویرایش تبدیل می‌کند. شیء SmartArt ایجاد شده به شکل گروهی والد در همان موقعیت اضافه می‌شود.

**بازمی‌گرداند:**
[ISmartArt](../../com.aspose.slides/ismartart) - شیء SmartArt ایجاد شده.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

نمودار قدیمی را به شکل گروهی قابل ویرایش تبدیل می‌کند. شیء GroupShape ایجاد شده به شکل گروهی والد در همان موقعیت اضافه می‌شود.

**بازمی‌گرداند:**
[IGroupShape](../../com.aspose.slides/igroupshape) - شیء GroupShape ایجاد شده.