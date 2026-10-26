---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Android via Java API Reference
description: Layout slayta yer tutucular eklemenizi sağlayan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Layout slayta yer tutucular eklemenizi sağlayan yöneticiyi temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Layout slayta resim, tablo, medya veya metin gibi içerik tutmak için yeni bir yer tutucu şekil ekler. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Layout slayta dikey yönde resim, tablo, medya veya metin gibi içerik tutmak için yeni bir yer tutucu şekil ekler. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Layout slayta metin içeriği tutmak için yeni bir yer tutucu şekil ekler. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Layout slayta dikey yönde metin içeriği tutmak için yeni bir yer tutucu şekil ekler. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Layout slayta bir resim tutmak için yeni bir yer tutucu şekil ekler. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Layout slayta bir grafik tutmak için yeni bir yer tutucu şekil ekler. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Layout slayta bir tablo tutmak için yeni bir yer tutucu şekil ekler. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Layout slayta bir SmartArt diyagramı tutmak için yeni bir yer tutucu şekil ekler. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Layout slayta bir medya nesnesi tutmak için yeni bir yer tutucu şekil ekler. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Layout slayta çevrimiçi bir resim tutmak için yeni bir yer tutucu şekil ekler. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


Layout slayta resim, tablo, medya veya metin gibi içerik tutmak için yeni bir yer tutucu şekil ekler.

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addContentPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni yer tutucu şeklin X koordinatı. |
| y | float | Yeni yer tutucu şeklin Y koordinatı. |
| width | float | Yeni yer tutucu şeklin genişliği. |
| height | float | Yeni yer tutucu şeklin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Bir Content placeholder ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


Layout slayta dikey yönde resim, tablo, medya veya metin gibi içerik tutmak için yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Content (Vertical) placeholder şeklinin layout slayta nasıl ekleneceğini gösterir.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalContentPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni yer tutucu şeklin X koordinatı. |
| y | float | Yeni yer tutucu şeklin Y koordinatı. |
| width | float | Yeni yer tutucu şeklin genişliği. |
| height | float | Yeni yer tutucu şeklin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Bir Content (Vertical) placeholder ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


Layout slayta metin içeriği tutmak için yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Text placeholder şeklinin layout slayta nasıl ekleneceğini gösterir.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTextPlaceholder(20, 20, 500, 300);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni yer tutucu şeklin X koordinatı. |
| y | float | Yeni yer tutucu şeklin Y koordinatı. |
| width | float | Yeni yer tutucu şeklin genişliği. |
| height | float | Yeni yer tutucu şeklin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Bir Text placeholder ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


Layout slayta dikey yönde metin içeriği tutmak için yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Text (Vertical) placeholder şeklinin layout slayta nasıl ekleneceğini gösterir.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addVerticalTextPlaceholder(20, 20, 300, 500);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni yer tutucu şeklin X koordinatı. |
| y | float | Yeni yer tutucu şeklin Y koordinatı. |
| width | float | Yeni yer tutucu şeklin genişliği. |
| height | float | Yeni yer tutucu şeklin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Bir Text (Vertical) placeholder ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


Layout slayta bir resim tutmak için yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Picture placeholder şeklinin layout slayta nasıl ekleneceğini gösterir.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addPicturePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni yer tutucu şeklin X koordinatı. |
| y | float | Yeni yer tutucu şeklin Y koordinatı. |
| width | float | Yeni yer tutucu şeklin genişliği. |
| height | float | Yeni yer tutucu şeklin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Bir Picture placeholder ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


Layout slayta bir grafik tutmak için yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Chart placeholder şeklinin layout slayta nasıl ekleneceğini gösterir.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addChartPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni yer tutucu şeklin X koordinatı. |
| y | float | Yeni yer tutucu şeklin Y koordinatı. |
| width | float | Yeni yer tutucu şeklin genişliği. |
| height | float | Yeni yer tutucu şeklin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Bir Chart placeholder ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


Layout slayta bir tablo tutmak için yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Table placeholder şeklinin layout slayta nasıl ekleneceğini gösterir.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addTablePlaceholder(20, 20, 500, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni yer tutucu şeklin X koordinatı. |
| y | float | Yeni yer tutucu şeklin Y koordinatı. |
| width | float | Yeni yer tutucu şeklin genişliği. |
| height | float | Yeni yer tutucu şeklin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Bir Table placeholder ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


Layout slayta bir SmartArt diyagramı tutmak için yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, SmartArt placeholder şeklinin layout slayta nasıl ekleneceğini gösterir.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addSmartArtPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni yer tutucu şeklin X koordinatı. |
| y | float | Yeni yer tutucu şeklin Y koordinatı. |
| width | float | Yeni yer tutucu şeklin genişliği. |
| height | float | Yeni yer tutucu şeklin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Bir SmartArt placeholder ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


Layout slayta bir medya nesnesi tutmak için yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Media placeholder şeklinin layout slayta nasıl ekleneceğini gösterir.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addMediaPlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni yer tutucu şeklin X koordinatı. |
| y | float | Yeni yer tutucu şeklin Y koordinatı. |
| width | float | Yeni yer tutucu şeklin genişliği. |
| height | float | Yeni yer tutucu şeklin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Bir Media placeholder ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


Layout slayta çevrimiçi bir resim tutmak için yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Online Image placeholder şeklinin layout slayta nasıl ekleneceğini gösterir.
>  
>  Presentation pres = new Presentation();
>  try {
>      ILayoutSlide layout = pres.getLayoutSlides().getByType(SlideLayoutType.Blank);
>      IAutoShape placeholder = layout.getPlaceholderManager().addOnlineImagePlaceholder(20, 20, 200, 200);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| x | float | Yeni yer tutucu şeklin X koordinatı. |
| y | float | Yeni yer tutucu şeklin Y koordinatı. |
| width | float | Yeni yer tutucu şeklin genişliği. |
| height | float | Yeni yer tutucu şeklin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Bir Online Image placeholder ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.