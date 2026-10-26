---
title: BaseSlide
second_title: Aspose.Slides برای Java مرجع API
description: داده‌های عمومی برای تمام انواع اسلاید را نمایندگی می‌کند.
type: docs
url: /fa/com.aspose.slides/baseslide/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

داده‌های عمومی برای همه انواع اسلاید را نمایندگی می‌کند.
## متدها

| Method | Description |
| --- | --- |
| [getShapes()](#getShapes--) | شکل‌های یک اسلاید را برمی‌گرداند. |
| [getControls()](#getControls--) | مجموعه‌ی کنترل‌های ActiveX روی یک اسلاید را برمی‌گرداند. |
| [getName()](#getName--) | نام یک اسلاید را برمی‌گرداند یا تنظیم می‌کند. |
| [setName(String value)](#setName-java.lang.String-) | نام یک اسلاید را برمی‌گرداند یا تنظیم می‌کند. |
| [getSlideId()](#getSlideId--) | شناسه یک اسلاید را برمی‌گرداند. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | تعیین می‌کند آیا دو نمونه‌ی IBaseSlide برابر هستند یا نه. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | بخش‌های متن را با قالب‌بندی یکسان در تمام پاراگراف‌ها و تمام شکل‌های قابل قبول ترکیب می‌کند. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | بخش‌های متن را با قالب‌بندی یکسان در تمام پاراگراف‌ها و تمام شکل‌های قابل قبول ترکیب می‌کند. |
| [createThemeEffective()](#createThemeEffective--) | یک تم مؤثر برای این اسلاید را برمی‌گرداند. |
| [getCustomData()](#getCustomData--) | داده‌های سفارشی اسلاید را برمی‌گرداند. |
| [getTimeline()](#getTimeline--) | شیء جدول زمانی انیمیشن را برمی‌گرداند. |
| [getSlideShowTransition()](#getSlideShowTransition--) | شیء Transition را برمی‌گرداند که شامل اطلاعات دربارهٔ نحوه پیشروی اسلاید مشخص در طول نمایش اسلاید است. |
| [getBackground()](#getBackground--) | پس‌زمینهٔ اسلاید را برمی‌گرداند. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | دسترسی آسان به پیوندهای داخل‌شده را فراهم می‌کند. |
| [getShowMasterShapes()](#getShowMasterShapes--) | مشخص می‌کند آیا شکل‌ها در اسلاید اصلی باید در اسلایدها نمایش داده شوند یا نه. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | مشخص می‌کند آیا شکل‌ها در اسلاید اصلی باید در اسلایدها نمایش داده شوند یا نه. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | اولین رخداد شکلی با متن جایگزین مشخص را پیدا می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | رابط IPresentation را برمی‌گرداند. |
| [getSlide()](#getSlide--) |  |

### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```

شکل‌های یک اسلاید را برمی‌گرداند. فقط-خواندنی [IShapeCollection](../../com.aspose.slides/ishapecollection).

**Returns:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```

مجموعه‌ی کنترل‌های ActiveX روی یک اسلاید را برمی‌گرداند. فقط-خواندنی [IControlCollection](../../com.aspose.slides/icontrolcollection).

**Returns:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```

نام یک اسلاید را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**Returns:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

نام یک اسلاید را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```

شناسه یک اسلاید را برمی‌گرداند. فقط-خواندنی long.

**Returns:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```

تعیین می‌کند آیا دو نمونه‌ی IBaseSlide برابر هستند یا نه. مقدار بازگشتی بر اساس ساختار اسلاید و محتوای ثابت محاسبه می‌شود. دو اسلاید برابر هستند اگر تمام شکل‌ها، سبک‌ها، متن‌ها، انیمیشن و سایر تنظیمات و غیره برابر باشند. در مقایسه مقادیر شناسه‌های یکتا مثل SlideId و محتوای پویا مثل مقدار تاریخ جاری در Date Placeholder در نظر گرفته نمی‌شود.

--------------------

> ```
> The following example shows how to compare two slides.
>  
>  Presentation presentation1 = new Presentation("AccessSlides.pptx");
>  try {
>      Presentation presentation2 = new Presentation("HelloWorld.pptx");
>      try {
>          for (int i = 0; i < presentation1.getMasters().size(); i++)
>          {
>              for (int j = 0; j < presentation2.getMasters().size(); j++)
>              {
>                  if (presentation1.getMasters().get_Item(i).equals(presentation2.getMasters().get_Item(j)))
>                      System.out.println(String.format("SomePresentation1 MasterSlide#%d is equal to SomePresentation2 MasterSlide#%d", i, j));
>              }
>          }
>      } finally {
>          if (presentation2 != null) presentation2.dispose();
>      }
>  } finally {
>      if (presentation1 != null) presentation1.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | IBaseSlide برای مقایسه با IBaseSlide فعلی. |

**Returns:**
boolean -  **true**  اگر IBaseSlide مشخص برابر با IBaseSlide فعلی باشد؛ در غیر این صورت،  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```

بخش‌های متن را با قالب‌بندی یکسان در تمام پاراگراف‌ها و تمام شکل‌های قابل قبول ترکیب می‌کند.

### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```

بخش‌های متن را با قالب‌بندی یکسان در تمام پاراگراف‌ها و تمام شکل‌های قابل قبول ترکیب می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```

یک تم مؤثر برای این اسلاید را برمی‌گرداند.

**Returns:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```

داده‌های سفارشی اسلاید را برمی‌گرداند. فقط-خواندنی [ICustomData](../../com.aspose.slides/icustomdata).

**Returns:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```

شیء جدول زمانی انیمیشن را برمی‌گرداند. فقط-خواندنی [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**Returns:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```

شیء Transition را برمی‌گرداند که شامل اطلاعات دربارهٔ نحوه پیشروی اسلاید مشخص در طول نمایش اسلاید است. فقط-خواندنی [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**Returns:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```

پس‌زمینهٔ اسلاید را برمی‌گرداند. فقط-خواندنی [IBackground](../../com.aspose.slides/ibackground).

**Returns:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```

دسترسی آسان به پیوندهای داخل‌شده را فراهم می‌کند. فقط-خواندنی [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Returns:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```

مشخص می‌کند آیا شکل‌ها در اسلاید اصلی باید در اسلایدها نمایش داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه false برمی‌گرداند. خواندنی/نوشتنی boolean.

**Returns:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```

مشخص می‌کند آیا شکل‌ها در اسلاید اصلی باید در اسلایدها نمایش داده شوند یا نه. برای خود اسلاید اصلی این ویژگی همیشه false برمی‌گرداند. خواندنی/نوشتنی boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```

اولین رخداد شکلی با متن جایگزین مشخص را پیدا می‌کند.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| altText | java.lang.String | متن جایگزین. |

**Returns:**
[IShape](../../com.aspose.slides/ishape) - شیء Shape یا null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شیء Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**Returns:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

رابط IPresentation را برمی‌گرداند. فقط-خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**Returns:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

اسلاید پایه را برمی‌گرداند. فقط-خواندنی [IBaseSlide](../../com.aspose.slides/ibaseslide).

**Returns:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)