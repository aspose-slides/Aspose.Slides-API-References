---
title: BaseSlide
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: داده‌های مشترک برای تمام انواع اسلاید را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/baseslide/
---
**ارث‌برداری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), com.aspose.slides.IDOMObject, com.aspose.slides.IStyleColorOwner
```
public abstract class BaseSlide implements IBaseSlide, IDOMObject, IStyleColorOwner
```

نمایندهٔ داده‌های مشترک برای تمام انواع اسلاید.
## متدها

| Method | Description |
| --- | --- |
| [getShapes()](#getShapes--) | شکل‌های یک اسلاید را برمی‌گرداند. |
| [getControls()](#getControls--) | مجموعهٔ کنترل‌های ActiveX روی یک اسلاید را برمی‌گرداند. |
| [getName()](#getName--) | نام یک اسلاید را برمی‌گرداند یا تنظیم می‌کند. |
| [setName(String value)](#setName-java.lang.String-) | نام یک اسلاید را برمی‌گرداند یا تنظیم می‌کند. |
| [getSlideId()](#getSlideId--) | شناسهٔ یک اسلاید را برمی‌گرداند. |
| [equals(IBaseSlide slide)](#equals-com.aspose.slides.IBaseSlide-) | تعیین می‌کند که دو نمونهٔ IBaseSlide برابر هستند یا خیر. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | بخش‌های متنی با همان فرمت را در تمام پاراگراف‌ها و تمام شکل‌های قابل قبول ترکیب می‌کند. |
| [joinPortionsWithSameFormatting(IShapeCollection collection)](#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-) | بخش‌های متنی با همان فرمت را در تمام پاراگراف‌ها و تمام شکل‌های قابل قبول ترکیب می‌کند. |
| [createThemeEffective()](#createThemeEffective--) | یک تم مؤثر برای این اسلاید را برمی‌گرداند. |
| [getCustomData()](#getCustomData--) | دادهٔ سفارشی اسلاید را برمی‌گرداند. |
| [getTimeline()](#getTimeline--) | شیء زمان‌بندی انیمیشن را برمی‌گرداند. |
| [getSlideShowTransition()](#getSlideShowTransition--) | شیء Transition را برمی‌گرداند که شامل اطلاعاتی دربارهٔ نحوهٔ پیشرفت اسلاید مشخص‌شده در طول نمایش اسلاید است. |
| [getBackground()](#getBackground--) | پس‌زمینهٔ اسلاید را برمی‌گرداند. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | دسترسی آسان به لینک‌های موجود را فراهم می‌کند. |
| [getShowMasterShapes()](#getShowMasterShapes--) | مشخص می‌کند که آیا شکل‌ها در اسلاید اصلی باید روی اسلایدها نمایش داده شوند یا خیر. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | مشخص می‌کند که آیا شکل‌ها در اسلاید اصلی باید روی اسلایدها نمایش داده شوند یا خیر. |
| [findShapeByAltText(String altText)](#findShapeByAltText-java.lang.String-) | اولین رخداد یک شکل با متن جایگزین مشخص‌شده را پیدا می‌کند. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getPresentation()](#getPresentation--) | رابط IPresentation را برمی‌گرداند. |
| [getSlide()](#getSlide--) |  |
### getShapes() {#getShapes--}
```
public final IShapeCollection getShapes()
```


شکل‌های یک اسلاید را برمی‌گرداند. فقط‌خواندنی [IShapeCollection](../../com.aspose.slides/ishapecollection).

**بازمی‌گرداند:**
[IShapeCollection](../../com.aspose.slides/ishapecollection)
### getControls() {#getControls--}
```
public final IControlCollection getControls()
```


مجموعهٔ کنترل‌های ActiveX روی یک اسلاید را برمی‌گرداند. فقط‌خواندنی [IControlCollection](../../com.aspose.slides/icontrolcollection).

**بازمی‌گرداند:**
[IControlCollection](../../com.aspose.slides/icontrolcollection)
### getName() {#getName--}
```
public String getName()
```


نام یک اسلاید را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن و قابل‌نوشتن String.

**بازمی‌گرداند:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


نام یک اسلاید را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن و قابل‌نوشتن String.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | java.lang.String |  |
### getSlideId() {#getSlideId--}
```
public final long getSlideId()
```


شناسهٔ یک اسلاید را برمی‌گرداند. فقط‌خواندنی long.

**بازمی‌گرداند:**
long
### equals(IBaseSlide slide) {#equals-com.aspose.slides.IBaseSlide-}
```
public final boolean equals(IBaseSlide slide)
```


تعیین می‌کند که دو نمونهٔ IBaseSlide برابر هستند یا خیر. مقدار بازگشتی بر پایه ساختار اسلاید و محتوای ایستا محاسبه می‌شود. دو اسلاید برابر هستند اگر تمام شکل‌ها، سبک‌ها، متن‌ها، انیمیشن‌ها و دیگر تنظیمات و غیره برابر باشند. مقایسه مقادیر شناسهٔ یکتای مانند SlideId و محتوای پویا مانند مقدار تاریخ فعلی در Placeholder تاریخ را در نظر نمی‌گیرد.

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

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| slide | [IBaseSlide](../../com.aspose.slides/ibaseslide) | IBaseSlide برای مقایسه با IBaseSlide جاری. |

**بازمی‌گرداند:**
boolean -  **true**  اگر IBaseSlide مشخص‌شده برابر با IBaseSlide حال حاضر باشد؛ در غیر این صورت،  **false** .
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public void joinPortionsWithSameFormatting()
```


بخش‌های متنی با همان فرمت را در تمام پاراگراف‌ها و تمام شکل‌های قابل قبول ترکیب می‌کند.
### joinPortionsWithSameFormatting(IShapeCollection collection) {#joinPortionsWithSameFormatting-com.aspose.slides.IShapeCollection-}
```
public void joinPortionsWithSameFormatting(IShapeCollection collection)
```


بخش‌های متنی با همان فرمت را در تمام پاراگراف‌ها و تمام شکل‌های قابل قبول ترکیب می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| collection | [IShapeCollection](../../com.aspose.slides/ishapecollection) |  |
### createThemeEffective() {#createThemeEffective--}
```
public final IThemeEffectiveData createThemeEffective()
```


یک تم مؤثر برای این اسلاید را برمی‌گرداند.

**بازمی‌گرداند:**
[IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata)
### getCustomData() {#getCustomData--}
```
public final ICustomData getCustomData()
```


دادهٔ سفارشی اسلاید را برمی‌گرداند. فقط‌خواندنی [ICustomData](../../com.aspose.slides/icustomdata).

**بازمی‌گرداند:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getTimeline() {#getTimeline--}
```
public final IAnimationTimeLine getTimeline()
```


شیء زمان‌بندی انیمیشن را برمی‌گرداند. فقط‌خواندنی [IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline).

**بازمی‌گرداند:**
[IAnimationTimeLine](../../com.aspose.slides/ianimationtimeline)
### getSlideShowTransition() {#getSlideShowTransition--}
```
public ISlideShowTransition getSlideShowTransition()
```


شیء Transition را برمی‌گرداند که شامل اطلاعاتی دربارهٔ نحوهٔ پیشرفت اسلاید مشخص‌شده در طول نمایش اسلاید است. فقط‌خواندنی [ISlideShowTransition](../../com.aspose.slides/islideshowtransition).

**بازمی‌گرداند:**
[ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
### getBackground() {#getBackground--}
```
public final IBackground getBackground()
```


پس‌زمینهٔ اسلاید را برمی‌گرداند. فقط‌خواندنی [IBackground](../../com.aspose.slides/ibackground).

**بازمی‌گرداند:**
[IBackground](../../com.aspose.slides/ibackground)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public final IHyperlinkQueries getHyperlinkQueries()
```


دسترسی آسان به لینک‌های موجود را فراهم می‌کند. فقط‌خواندنی [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**بازمی‌گرداند:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getShowMasterShapes() {#getShowMasterShapes--}
```
public abstract boolean getShowMasterShapes()
```


مشخص می‌کند که آیا شکل‌ها در اسلاید اصلی باید روی اسلایدها نمایش داده شوند یا خیر. برای خود اسلاید اصلی این ویژگی همیشه false برمی‌گرداند. قابل‌خواندن و قابل‌نوشتن boolean.

**بازمی‌گرداند:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public abstract void setShowMasterShapes(boolean value)
```


مشخص می‌کند که آیا شکل‌ها در اسلاید اصلی باید روی اسلایدها نمایش داده شوند یا خیر. برای خود اسلاید اصلی این ویژگی همیشه false برمی‌گرداند. قابل‌خواندن و قابل‌نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| value | boolean |  |
### findShapeByAltText(String altText) {#findShapeByAltText-java.lang.String-}
```
public final IShape findShapeByAltText(String altText)
```


اولین رخداد یک شکل با متن جایگزین مشخص‌شده را پیدا می‌کند.

**پارامترها:**
| پارامتر | نوع | شرح |
| --- | --- | --- |
| altText | java.lang.String | متن جایگزین. |

**بازمی‌گرداند:**
[IShape](../../com.aspose.slides/ishape) - شیء Shape یا null.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


شیء Parent_Immediate را برمی‌گرداند. فقط‌خواندنی IDOMObject.

**بازمی‌گرداند:**
com.aspose.slides.IDOMObject
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


رابط IPresentation را برمی‌گرداند. فقط‌خواندنی [IPresentation](../../com.aspose.slides/ipresentation).

**بازمی‌گرداند:**
[IPresentation](../../com.aspose.slides/ipresentation)
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


اسلاید پایه را برمی‌گرداند. فقط‌خواندنی [IBaseSlide](../../com.aspose.slides/ibaseslide).

**بازمی‌گرداند:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)