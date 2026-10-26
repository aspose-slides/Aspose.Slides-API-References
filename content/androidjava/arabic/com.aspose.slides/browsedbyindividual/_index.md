---
title: BrowsedByIndividual
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: تم التصفح بواسطة نافذة فردية
type: docs
url: /ar/com.aspose.slides/browsedbyindividual/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)  
```
public class BrowsedByIndividual extends SlideShowType
```

التصفح بواسطة فرد (النافذة)

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
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | يُهيئ مثيلًا جديدًا من الفئة BrowsedByIndividual. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | إظهار شريط التمرير في النافذة |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | إظهار شريط التمرير في النافذة |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```

يُهيئ مثيلًا جديدًا من الفئة BrowsedByIndividual.

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

إظهار شريط التمرير في النافذة

**الإرجاع:**  
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```

إظهار شريط التمرير في النافذة

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |