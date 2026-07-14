---
title: ISmartArtNode
second_title: Aspose.Slides for Android via Java API Reference
description: نماینده گره‌ای از یک نمودار SmartArt.
type: docs
url: /fa/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

نماینده گره‌ای از یک نمودار SmartArt.
## متدها

| متد | توضیح |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | مجموعه‌ای از تمام گره‌های فرزند گرهٔ فعلی را برمی‌گرداند. |
| [getShapes()](#getShapes--) | مجموعه‌ای از تمام اشکال مرتبط با گره را برمی‌گرداند. |
| [getTextFrame()](#getTextFrame--) | متن گره را برمی‌گرداند یا تنظیم می‌کند. |
| [isAssistant()](#isAssistant--) | گره را به عنوان دستیار برمی‌گرداند یا تنظیم می‌کند. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | گره را به عنوان دستیار برمی‌گرداند یا تنظیم می‌کند. |
| [getLevel()](#getLevel--) | سطح تو در توی گره را برمی‌گرداند. |
| [getBulletFillFormat()](#getBulletFillFormat--) | شیء FillFormat را که شامل ویژگی‌های فرمت پر برای گلولهٔ گره است، برمی‌گرداند. |
| [getPosition()](#getPosition--) | موقعیت صفر-پایهٔ گره را بین گره‌های هم‌سطح برمی‌گرداند یا تنظیم می‌کند. |
| [setPosition(int value)](#setPosition-int-) | موقعیت صفر-پایهٔ گره را بین گره‌های هم‌سطح برمی‌گرداند یا تنظیم می‌کند. |
| [isHidden()](#isHidden--) | در صورتی که این گره یک گره مخفی در مدل داده باشد، true را برمی‌گرداند. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | نوع طرح‌بندی نمودار سازمانی مرتبط با گرهٔ فعلی را برمی‌گرداند یا تنظیم می‌کند. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | نوع طرح‌بندی نمودار سازمانی مرتبط با گرهٔ فعلی را برمی‌گرداند یا تنظیم می‌کند. |
| [remove()](#remove--) | گرهٔ فعلی را حذف می‌کند. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```

مجموعه‌ای از تمام گره‌های فرزند گرهٔ فعلی را برمی‌گرداند. فقط‌خواندنی [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**بازگشت:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```

مجموعه‌ای از تمام اشکال مرتبط با گره را برمی‌گرداند. فقط‌خواندنی [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**بازگشت:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```

متن گره را برمی‌گرداند یا تنظیم می‌کند. فقط‌خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**بازگشت:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```

گره را به عنوان دستیار برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن boolean.

**بازگشت:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```

گره را به عنوان دستیار برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getLevel() {#getLevel--}
```
public abstract int getLevel()
```

سطح تو در توی گره را برمی‌گرداند. فقط‌خواندنی int.

**بازگشت:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```

شیء FillFormat را که شامل ویژگی‌های فرمت پر برای گلولهٔ گره است، برمی‌گرداند. نکته: ممکن است برای برخی انواع طرح‌بندی SmartArt که گلوله برای گره‌ها فراهم نمی‌کند، null برگرداند. فقط‌خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**بازگشت:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

موقعیت صفر-پایهٔ گره را بین گره‌های هم‌سطح برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن int.

**بازگشت:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

موقعیت صفر-پایهٔ گره را بین گره‌های هم‌سطح برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```

در صورتی که این گره یک گره مخفی در مدل داده باشد، true را برمی‌گرداند. فقط‌خواندنی boolean.

**بازگشت:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```

نوع طرح‌بندی نمودار سازمانی مرتبط با گرهٔ فعلی را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**بازگشت:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```

نوع طرح‌بندی نمودار سازمانی مرتبط با گرهٔ فعلی را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/نوشتن [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### remove() {#remove--}
```
public abstract boolean remove()
```

گرهٔ فعلی را حذف می‌کند.

**بازگشت:**
boolean - true اگر به‌طور موفق حذف شد، در غیر اینصورت false.