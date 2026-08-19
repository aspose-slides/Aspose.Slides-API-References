---
title: SmartArtNode
second_title: Aspose.Slides برای Java مرجع API
description: نشان‌دهندهٔ گره‌ای از یک شیء SmartArt
type: docs
url: /fa/com.aspose.slides/smartartnode/
---
**وراثت:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی شده:**
[com.aspose.slides.ISmartArtNode](../../com.aspose.slides/ismartartnode)
```
public final class SmartArtNode implements ISmartArtNode
```

نشان‌دهندهٔ گره‌ای از یک شیء SmartArt object
## متدها

| متد | توضیح |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | کلکسیون‌های تمام گره‌های فرزند گرهٔ فعلی را برمی‌گرداند. |
| [getShapes()](#getShapes--) | کلکسیون‌های تمام شکل‌های مرتبط با گره را برمی‌گرداند. |
| [getTextFrame()](#getTextFrame--) | قاب متن گره را برمی‌گرداند. |
| [isAssistant()](#isAssistant--) | گره را به عنوان دستیار برمی‌گرداند یا تنظیم می‌کند. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | گره را به عنوان دستیار برمی‌گرداند یا تنظیم می‌کند. |
| [getLevel()](#getLevel--) | سطح تو در توی گره را برمی‌گرداند. |
| [getBulletFillFormat()](#getBulletFillFormat--) | شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پر شدن برای گلولهٔ گره است برمی‌گرداند. |
| [getPosition()](#getPosition--) | موقعیت صفر-مبنا گره را در میان گره‌های هم‌سطح برمی‌گرداند یا تنظیم می‌کند. |
| [setPosition(int value)](#setPosition-int-) | موقعیت صفر-مبنا گره را در میان گره‌های هم‌سطح برمی‌گرداند یا تنظیم می‌کند. |
| [isHidden()](#isHidden--) | در صورتی که این گره یک گره پنهان در مدل داده باشد، true را برمی‌گرداند. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | نوع طرح بندی نمودار سازمانی مرتبط با گرهٔ فعلی را برمی‌گرداند یا تنظیم می‌کند. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | نوع طرح بندی نمودار سازمانی مرتبط با گرهٔ فعلی را برمی‌گرداند یا تنظیم می‌کند. |
| [remove()](#remove--) | گرهٔ فعلی را حذف می‌کند. |
### getChildNodes() {#getChildNodes--}
```
public final ISmartArtNodeCollection getChildNodes()
```


کلکسیون‌های تمام گره‌های فرزند گرهٔ فعلی را برمی‌گرداند. فقط-خواندنی [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**بازگشت:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public final ISmartArtShapeCollection getShapes()
```


کلکسیون‌های تمام شکل‌های مرتبط با گره را برمی‌گرداند. فقط-خواندنی [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**بازگشت:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public final ITextFrame getTextFrame()
```


قاب متن گره را برمی‌گرداند. فقط-خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**بازگشت:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public final boolean isAssistant()
```


گره را به عنوان دستیار برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن boolean.

**بازگشت:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public final void setAssistant(boolean value)
```


گره را به عنوان دستیار برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLevel() {#getLevel--}
```
public final int getLevel()
```


سطح تو در توی گره را برمی‌گرداند. فقط-خواندنی int.

**بازگشت:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public final IFillFormat getBulletFillFormat()
```


شیء FillFormat را که شامل ویژگی‌های قالب‌بندی پر شدن برای گلولهٔ گره است برمی‌گرداند. توجه: ممکن است برای برخی انواع طرح‌بندی SmartArt که گلوله برای گره‌ها فراهم نمی‌کند، null بازگرداند. فقط-خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازگشت:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public final int getPosition()
```


موقعیت صفر-مبنا گره را در میان گره‌های هم‌سطح برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن  int .

**بازگشت:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


موقعیت صفر-مبنا گره را در میان گره‌های هم‌سطح برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن  int .

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### isHidden() {#isHidden--}
```
public final boolean isHidden()
```


در صورتی که این گره یک گره پنهان در مدل داده باشد، true را برمی‌گرداند. فقط-خواندنی boolean.

**بازگشت:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public final int getOrganizationChartLayout()
```


نوع طرح بندی نمودار سازمانی مرتبط با گرهٔ فعلی را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**بازگشت:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public final void setOrganizationChartLayout(int value)
```


نوع طرح بندی نمودار سازمانی مرتبط با گرهٔ فعلی را برمی‌گرداند یا تنظیم می‌کند. قابل‌نوشتن [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### remove() {#remove--}
```
public final boolean remove()
```


گرهٔ فعلی را حذف می‌کند.

**بازگشت:**
boolean - true if removed succesfully, otherwise false