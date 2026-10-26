---
title: BrowsedByIndividual
second_title: Aspose.Slides Android için Java API Referansı aracılığıyla
description: Bireysel pencere tarafından göz atıldı
type: docs
url: /tr/com.aspose.slides/browsedbyindividual/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.SlideShowType](../../com.aspose.slides/slideshowtype)
```
public class BrowsedByIndividual extends SlideShowType
```

Bireysel Tarafından Göz Atıldı (Pencere)

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
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getShowScrollbar()](#getShowScrollbar--) | Pencere içinde Kaydırma Çubuğunu Göster |
| [setShowScrollbar(boolean value)](#setShowScrollbar-boolean-) | Pencere içinde Kaydırma Çubuğunu Göster |
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


Pencere içinde Kaydırma Çubuğunu Göster

**Dönüş:**
boolean
### setShowScrollbar(boolean value) {#setShowScrollbar-boolean-}
```
public final void setShowScrollbar(boolean value)
```


Pencere içinde Kaydırma Çubuğunu Göster

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |