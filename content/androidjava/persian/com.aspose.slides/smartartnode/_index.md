---
title: SmartArtNode
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر گره‌ای از یک شیء SmartArt
type: docs
url: /fa/com.aspose.slides/smartartnode/
---
**وراثت:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)  
```
public final class SmartArtNode implements ISmartArtNode
```

نمایانگر گره‌ای از یک شیء SmartArt object

## متدها

| متد | توضیح |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | مجموعه‌ای از تمام گره‌های فرزند گره جاری را بازمی‌گرداند. |
| [getShapes()](#getShapes--) | مجموعه‌ای از تمام اشکال مرتبط با گره را بازمی‌گرداند. |
| [getTextFrame()](#getTextFrame--) | قاب متن گره را بازمی‌گرداند. |
| [isAssistant()](#isAssistant--) | گره را به‌عنوان دستیار بازمی‌گرداند یا تنظیم می‌کند. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | گره را به‌عنوان دستیار بازمی‌گرداند یا تنظیم می‌کند. |
| [getLevel()](#getLevel--) | سطح تو در توی گره را بازمی‌گرداند. |
| [getBulletFillFormat()](#getBulletFillFormat--) | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پر برای نقطه‌بند گره است، بازمی‌گرداند. |
| [getPosition()](#getPosition--) | موقعیت مبتنی بر صفر گره در میان گره‌های هم‌سطح را بازمی‌گرداند یا تنظیم می‌کند. |
| [setPosition(int value)](#setPosition-int-) | موقعیت مبتنی بر صفر گره در میان گره‌های هم‌سطح را بازمی‌گرداند یا تنظیم می‌کند. |
| [isHidden()](#isHidden--) | در صورت مخفی بودن این گره در مدل داده، true را بازمی‌گرداند. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | نوع چیدمان نمودار سازمانی مرتبط با گره جاری را بازمی‌گرداند یا تنظیم می‌کند. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | نوع چیدمان نمودار سازمانی مرتبط با گره جاری را بازمی‌گرداند یا تنظیم می‌کند. |
| [remove()](#remove--) | گره جاری را حذف می‌کند. |

### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```

مجموعه‌ای از تمام گره‌های فرزند گره جاری را بازمی‌گرداند. فقط‌خواندنی [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**بازمی‌گردد:**  
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)

### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```

مجموعه‌ای از تمام اشکال مرتبط با گره را بازمی‌گرداند. فقط‌خواندنی [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**بازمی‌گردد:**  
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)

### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```

قاب متن گره را بازمی‌گرداند. فقط‌خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**بازمی‌گردد:**  
[ITextFrame](../../com.aspose.slides/itextframe)

### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```

گره را به‌عنوان دستیار بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن و نوشتن boolean.

**بازمی‌گردد:**  
boolean

### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```

گره را به‌عنوان دستیار بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن و نوشتن boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLevel() {#getLevel--}
```
public final int getLevel()
```

سطح تو در توی گره را بازمی‌گرداند. فقط‌خواندنی int.

**بازمی‌گردد:**  
int

### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```

شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پر برای نقطه‌بند گره است، بازمی‌گرداند. توجه: برای برخی انواع چیدمان SmartArt که نقطه‌بند برای گره‌ها فراهم نمی‌کند، می‌تواند null برگرداند. فقط‌خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازمی‌گردد:**  
[IFillFormat](../../com.aspose.slides/ifillformat)

### getPosition() {#getPosition--}
```
public final int getPosition()
```

موقعیت مبتنی بر صفر گره در میان گره‌های هم‌سطح را بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن و نوشتن int .

**بازمی‌گردد:**  
int

### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

موقعیت مبتنی بر صفر گره در میان گره‌های هم‌سطح را بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن و نوشتن int .

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### isHidden() {#isHidden--}
```
public final boolean isHidden()
```

در صورت مخفی بودن این گره در مدل داده، true را بازمی‌گرداند. فقط‌خواندنی boolean.

**بازمی‌گردد:**  
boolean

### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```

نوع چیدمان نمودار سازمانی مرتبط با گره جاری را بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن و نوشتن [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**بازمی‌گردد:**  
int

### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```

نوع چیدمان نمودار سازمانی مرتبط با گره جاری را بازمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن و نوشتن [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### remove() {#remove--}
```
public final boolean remove()
```

گره جاری را حذف می‌کند.

**بازمی‌گردد:**  
boolean - true if removed succesfully, otherwise false