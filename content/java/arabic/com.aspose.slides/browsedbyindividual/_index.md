---
title: BrowsedByIndividual
second_title: Aspose.Slides لـ Java مرجع API
description: نافذة تصفح حسب الفرد
type: docs
url: /ar/com.aspose.slides/browsedbyindividual/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

تم التصفح بواسطة فرد (النافذة)

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

## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | يُنشئ مثالًا جديدًا من الفئة BrowsedByIndividual. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | إظهار شريط التمرير في النافذة |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | إظهار شريط التمرير في النافذة |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```


يُنشئ مثالًا جديدًا من الفئة BrowsedByIndividual.

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


إظهار شبار التمرير في النافذة

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | boolean |  |