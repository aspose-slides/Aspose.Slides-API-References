---
title: BrowsedByIndividual
second_title: مرجع API Aspose.Slides برای Java
description: پنجره مرور شده توسط فرد
type: docs
url: /fa/com.aspose.slides/browsedbyindividual/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

مرور شده توسط فرد (پنجره)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | یک نمونه جدید از کلاس BrowsedByIndividual را مقداردهی اولیه می‌کند. |
## متدها

| متد | توضیح |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | نمایش نوار اسکرول در پنجره |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | نمایش نوار اسکرول در پنجره |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```

یک نمونه جدید از کلاس BrowsedByIndividual را مقداردهی اولیه می‌کند.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getSlideShowSettings().setSlideShowType(new BrowsedByIndividual());
>      pres.save("pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


### getShowScrollbar() {#getShowScrollbar--}
```
public final boolean getShowScrollbar()
```

نمایش نوار اسکرول در پنجره

**بازگشت:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```

نمایش نوار اسکرول در پنجره

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |