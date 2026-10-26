---
title: IBaseSlide
second_title: Aspose.Slides برای اندروید از طریق API جاوا
description: داده‌های عمومی برای تمام انواع اسلاید.
type: docs
url: /fa/com.aspose.slides/ibaseslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IThemeable](../../com.aspose.slides/ithemeable)
```
public interface IBaseSlide extends IThemeable
```

Represents common data for all slide types.
## متدها

| متد | توضیح |
| --- | --- |
| [getShapes()](#getShapes--) | شکل‌های اسلاید را برمی‌گرداند. |
| [getControls()](#getControls--) | مجموعهٔ کنترل‌های ActiveX موجود در یک اسلاید را برمی‌گرداند. |
| [getName()](#getName--) | نام یک اسلاید را برمی‌گرداند یا تنظیم می‌کند. |
| [setName(String value)](#setName-java.lang.String-) | نام یک اسلاید را برمی‌گرداند یا تنظیم می‌کند. |
| [getSlideId()](#getSlideId--) | شناسهٔ یک اسلاید را برمی‌گرداند. |
| [getCustomData()](#getCustomData--) | داده‌های سفارشی اسلاید را برمی‌گرداند. |
| [getTimeline()](#getTimeline--) | شیء زمان‌بندی انیمیشن را برمی‌گرداند. |
| [getSlideShowTransition()](#getSlideShowTransition--) | شیء TransitionEx را برمی‌گرداند که شامل اطلاعاتی دربارهٔ چگونگی پیشروی اسلاید مشخص شده در نمایش اسلاید است. |
| [getBackground()](#getBackground--) | پس‌زمینه اسلاید را برمی‌گرداند. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | دسترسی آسان به پیوندهای موجود را فراهم می‌کند. |
| [getShowMasterShapes()](#getShowMasterShapes--) | مشخص می‌کند آیا شکل‌ها در اسلاید اصلی باید در اسلایدها نشان داده شوند یا نه. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | مشخص می‌کند آیا شکل‌ها در اسلاید اصلی باید در اسلایدها نشان داده شوند یا نه. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | اولین رخداد شکلی با متن جایگزین مشخص‌شده را پیدا می‌کند. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | قطعات متن با قالب‌بندی یکسان را در تمام پاراگراف‌ها در تمام شکل‌های قابل قبول ترکیب می‌کند. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | تشخیص می‌دهد آیا دو نمونهٔ IBaseSlide برابر هستند یا نه. |

### getShapes() {#getShapes--}
```
public abstract IShapeCollection getShapes()
```

شکل‌های اسلاید را برمی‌گرداند. فقط-خواندنی [IShapeCollection](../../com.aspose.slides/ishapecollection).

**بازگشت:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)

### getControls() {#getControls--}
```
public abstract IControlCollection getControls()
```

مجموعهٔ کنترل‌های ActiveX موجود در یک اسلاید را برمی‌گرداند. فقط-خواندنی [IControlCollection](../../com.aspose.slides/icontrolcollection).

**بازگشت:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)

### getName() {#getName--}
```
public abstract String getName()
```

نام یک اسلاید را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**بازگشت:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

نام یک اسلاید را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |

### getSlideId() {#getSlideId--}
```
public abstract long getSlideId()
```

شناسهٔ یک اسلاید را برمی‌گرداند. فقط-خواندنی long.

**بازگشت:**
long

### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

داده‌های سفارشی اسلاید را برمی‌گرداند. فقط-خواندنی [ICustomData](../../com.aspose.slides/icustomdata).

**بازگشت:**
[ICustomData](../../com.aspose.slides/icustomdata)

### getTimeline() {#getTimeline--}
```
public abstract IAnimationTimeLine getTimeline()
```

شیء زمان‌بندی انیمیشن را برمی‌گرداند. فقط-خواندنی [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**بازگشت:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)

### getSlideShowTransition() {#getSlideShowTransition--}
```
public abstract ISlideShowTransition getSlideShowTransition()
```

شیء TransitionEx را برمی‌گرداند که شامل اطلاعاتی دربارهٔ چگونگی پیشروی اسلاید مشخص شده در نمایش اسلاید است. فقط-خواندنی [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**بازگشت:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)

### getBackground() {#getBackground--}
```
public abstract IBackground getBackground()
```

پس‌زمینهٔ اسلاید را برمی‌گرداند. فقط-خواندنی [IBackground](../../com.aspose.slides/ibackground).

**بازگشت:**
[IBackground](../../com.aspose.slides/ibackground)

### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

دسترسی آسان به پیوندهای موجود را فراهم می‌کند. فقط-خواندنی [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**بازگشت:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)

### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

مشخص می‌کند آیا شکل‌ها در اسلاید اصلی باید در اسلایدها نشان داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه false برمی‌گرداند. خواندنی/نوشتنی boolean.

**بازگشت:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

مشخص می‌کند آیا شکل‌ها در اسلاید اصلی باید در اسلایدها نشان داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه false برمی‌گرداند. خواندنی/نوشتنی boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public abstract IShape findShapeByAltText(String altText)
```

اولین رخداد شکلی با متن جایگزین مشخص‌شده را پیدا می‌کند.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| altText | java.lang.String | متن جایگزین. |

**بازگشت:**
[IShape](../../com.aspose.slides/ishape) - شیء ShapeEx یا null.

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

قطعات متن با قالب‌بندی یکسان را در تمام پاراگراف‌ها در تمام شکل‌های قابل قبول ترکیب می‌کند.

### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public abstract boolean equals(IBaseSlide slide)
```

تشخیص می‌دهد آیا دو نمونهٔ IBaseSlide برابر هستند یا نه. مقدار بازگشتی بر اساس ساختار اسلاید و محتویات ثابت محاسبه می‌شود. دو اسلاید برابر هستند اگر تمام شکل‌ها، سبک‌ها، متن‌ها، انیمیشن و سایر تنظیمات و غیره برابر باشند. مقایسه مقادیر شناسهٔ یکتا مانند SlideId و محتویات پویا مانند مقدار تاریخ فعلی در نگه‌دارنده تاریخ را در نظر نمی‌گیرد.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | The IBaseSlide to compare with the current IBaseSlide. |

**بازگشت:**
boolean - **true** اگر IBaseSlide مشخص‌شده برابر با IBaseSlide جاری باشد؛ در غیر این صورت **false**.