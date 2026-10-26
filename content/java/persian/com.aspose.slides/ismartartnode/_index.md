---
title: ISmartArtNode
second_title: Aspose.Slides for Java API Reference
description: Represents node of a SmartArt diagram.
type: docs
url: /fa/com.aspose.slides/ismartartnode/
---```
public interface ISmartArtNode
```

نمایشگر گره‌ای از یک نمودار SmartArt.
## متدها

| متد | توضیح |
| --- | --- |
| [getChildNodes()](#getChildNodes--) | مجموعه‌ای از همهٔ گره‌های فرزند گرهٔ کنونی را برمی‌گرداند. |
| [getShapes()](#getShapes--) | مجموعه‌ای از همهٔ اشکال مرتبط با گره را برمی‌گرداند. |
| [getTextFrame()](#getTextFrame--) | متن گره را دریافت یا تنظیم می‌کند. |
| [isAssistant()](#isAssistant--) | گره را به عنوان دستیار دریافت یا تنظیم می‌کند. |
| [setAssistant(boolean value)](#setAssistant-boolean-) | گره را به عنوان دستیار دریافت یا تنظیم می‌کند. |
| [getLevel()](#getLevel--) | سطح تو در توی گره را برمی‌گرداند. |
| [getBulletFillFormat()](#getBulletFillFormat--) | شیء FillFormat که شامل ویژگی‌های قالب‌بندی پر کردن برای نقطهٔ گلولهٔ گره است را برمی‌گرداند. |
| [getPosition()](#getPosition--) | موقعیت صفر-مبنای گره را میان گره‌های خواهر‌برادر دریافت یا تنظیم می‌کند. |
| [setPosition(int value)](#setPosition-int-) | موقعیت صفر-مبنای گره را میان گره‌های خواهر‌برادر دریافت یا تنظیم می‌کند. |
| [isHidden()](#isHidden--) | اگر این گره در مدل داده یک گره پنهان باشد، true را برمی‌گرداند. |
| [getOrganizationChartLayout()](#getOrganizationChartLayout--) | نوع چیدمان نمودار سازمانی مرتبط با گرهٔ کنونی را دریافت یا تنظیم می‌کند. |
| [setOrganizationChartLayout(int value)](#setOrganizationChartLayout-int-) | نوع چیدمان نمودار سازمانی مرتبط با گرهٔ کنونی را دریافت یا تنظیم می‌کند. |
| [remove()](#remove--) | گرهٔ فعلی را حذف می‌کند. |
### getChildNodes() {#getChildNodes--}
```
public abstract ISmartArtNodeCollection getChildNodes()
```


مجموعه‌ای از همهٔ گره‌های فرزند گرهٔ کنونی را برمی‌گرداند. فقط خواندنی [ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection).

**باز می‌گردد:**
[ISmartArtNodeCollection](../../com.aspose.slides/ismartartnodecollection)
### getShapes() {#getShapes--}
```
public abstract ISmartArtShapeCollection getShapes()
```


مجموعه‌ای از همهٔ اشکال مرتبط با گره را برمی‌گرداند. فقط خواندنی [ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection).

**باز می‌گردد:**
[ISmartArtShapeCollection](../../com.aspose.slides/ismartartshapecollection)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


متن گره را دریافت یا تنظیم می‌کند. فقط خواندنی [ITextFrame](../../com.aspose.slides/itextframe).

**باز می‌گردد:**
[ITextFrame](../../com.aspose.slides/itextframe)
### isAssistant() {#isAssistant--}
```
public abstract boolean isAssistant()
```


گره را به عنوان دستیار دریافت یا تنظیم می‌کند. قابلیت خواندن/نوشتن بولی.

**باز می‌گردد:**
boolean
### setAssistant(boolean value) {#setAssistant-boolean-}
```
public abstract void setAssistant(boolean value)
```


گره را به عنوان دستیار دریافت یا تنظیم می‌کند. قابلیت خواندن/نوشتن بولی.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getLevel() {#getLevel--}
```
public abstract int getLevel()
```


سطح تو در توی گره را برمی‌گرداند. فقط خواندنی int.

**باز می‌گردد:**
int
### getBulletFillFormat() {#getBulletFillFormat--}
```
public abstract IFillFormat getBulletFillFormat()
```


شیء FillFormat که شامل ویژگی‌های قالب‌بندی پر کردن برای نقطهٔ گلولهٔ گره است را برمی‌گرداند. توجه: برای برخی انواع چیدمان SmartArt که گلوله برای گره‌ها فراهم نمی‌کند، می‌تواند مقدار null را برگرداند. فقط خواندنی [IFillFormat](../../com.aspose.slides/ifillformat).

**باز می‌گردد:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


موقعیت صفر-مبنای گره را میان گره‌های خواهر‌برادر دریافت یا تنظیم می‌کند. قابلیت خواندن/نوشتن int.

**باز می‌گردد:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


موقعیت صفر-مبنای گره را میان گره‌های خواهر‌برادر دریافت یا تنظیم می‌کند. قابلیت خواندن/نوشتن int.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### isHidden() {#isHidden--}
```
public abstract boolean isHidden()
```


اگر این گره در مدل داده یک گره پنهان باشد، true را برمی‌گرداند. فقط خواندنی بولی.

**باز می‌گردد:**
boolean
### getOrganizationChartLayout() {#getOrganizationChartLayout--}
```
public abstract int getOrganizationChartLayout()
```


نوع چیدمان نمودار سازمانی مرتبط با گرهٔ کنونی را دریافت یا تنظیم می‌کند. قابلیت خواندن/نوشتن [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**باز می‌گردد:**
int
### setOrganizationChartLayout(int value) {#setOrganizationChartLayout-int-}
```
public abstract void setOrganizationChartLayout(int value)
```


نوع چیدمان نمودار سازمانی مرتبط با گرهٔ کنونی را دریافت یا تنظیم می‌کند. قابلیت خواندن/نوشتن [OrganizationChartLayoutType](../../com.aspose.slides/organizationchartlayouttype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### remove() {#remove--}
```
public abstract boolean remove()
```


گرهٔ فعلی را حذف می‌کند.

**باز می‌گردد:**
boolean - true اگر با موفقیت حذف شد، در غیر این صورت false.