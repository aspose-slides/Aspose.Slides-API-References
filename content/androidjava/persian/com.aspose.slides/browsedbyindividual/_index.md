---
title: BrowsedByIndividual
second_title: Aspose.Slides برای Android از طریق Java API Reference
description: پنجره مرور توسط فرد
type: docs
url: /fa/com.aspose.slides/browsedbyindividual/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

مرور توسط فرد (پنجره)

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
| [getShowScrollbar()](#getShowScrollbar--) | نوار اسکرول را در پنجره نمایش می‌دهد |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | نوار اسکرول را در پنجره نمایش می‌دهد |
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

نوار اسکرول را در پنجره نمایش می‌دهد

**بازگرداندن:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```

نوار اسکرول را در پنجره نمایش می‌دهد

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |