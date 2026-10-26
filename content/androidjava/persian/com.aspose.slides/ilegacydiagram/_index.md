---
title: ILegacyDiagram
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر یک شیء دیاگرام قدیمی
type: docs
url: /fa/com.aspose.slides/ilegacydiagram/
---
**تمام اینترفیس‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface ILegacyDiagram extends IGraphicalObject
```

نمایانگر یک شیء دیاگرام قدیمی
## متدها

| متد | توضیح |
| --- | --- |
| [convertToSmartArt()](#convertToSmartArt--) | دیاگرام قدیمی را به شیء قابل ویرایش SmartArt تبدیل می‌کند. |
| [convertToGroupShape()](#convertToGroupShape--) | دیاگرام قدیمی را به شکل گروهی قابل ویرایش تبدیل می‌کند. |
### convertToSmartArt() {#convertToSmartArt--}
```
public abstract ISmartArt convertToSmartArt()
```

دیاگرام قدیمی را به شیء قابل ویرایش SmartArt تبدیل می‌کند. شیء SmartArt ایجاد شده به شکل گروهی والد در همان موقعیت افزوده می‌شود.

**بازگشت:**  
[ISmartArt](../../com.aspose.slides/ismartart) - شیء SmartArt ایجاد شده.
### convertToGroupShape() {#convertToGroupShape--}
```
public abstract IGroupShape convertToGroupShape()
```

دیاگرام قدیمی را به شکل گروهی قابل ویرایش تبدیل می‌کند. شیء GroupShape ایجاد شده به شکل گروهی والد در همان موقعیت افزوده می‌شود.

**بازگشت:**  
[IGroupShape](../../com.aspose.slides/igroupshape) - شیء GroupShape ایجاد شده.