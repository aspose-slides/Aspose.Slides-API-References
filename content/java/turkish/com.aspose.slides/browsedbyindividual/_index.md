---
title: BrowsedByIndividual
second_title: Aspose.Slides için Java API Referansı
description: Bireysel pencerede göz atıldı
type: docs
url: /tr/com.aspose.slides/browsedbyindividual/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Browsed by individual (window)

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
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [BrowsedByIndividual()](#BrowsedByIndividual--) | BrowsedByIndividual sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Pencerede Kaydırma Çubuğunu Göster |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Pencerede Kaydırma Çubuğunu Göster |
### BrowsedByIndividual() {#BrowsedByIndividual--}
```
public BrowsedByIndividual()
```

BrowsedByIndividual sınıfının yeni bir örneğini başlatır.

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

Pencerede Kaydırma Çubuğunu Göster

**Dönen Değer:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```

Pencerede Kaydırma Çubuğunu Göster

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |