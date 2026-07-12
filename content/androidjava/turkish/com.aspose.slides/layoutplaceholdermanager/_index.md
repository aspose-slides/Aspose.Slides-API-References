---
title: LayoutPlaceholderManager
second_title: Aspose.Slides for Android için Java API Referansı
description: Yerleşim slaytına yer tutucu eklemenizi sağlayan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/layoutplaceholdermanager/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Yerleşim slaytına yer tutucu eklemenizi sağlayan yöneticiyi temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Yeni bir yer tutucu şekli ekler, içerik tutmak için, örneğin bir resim, tablo, medya veya metin. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Yeni bir yer tutucu şekli ekler, içerik tutmak için, örneğin bir resim, tablo, medya veya metni dikey yönde. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Yeni bir yer tutucu şekli ekler, metin içeriğini tutmak için. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Yeni bir yer tutucu şekli ekler, metin içeriğini dikey yönde tutmak için. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Yeni bir yer tutucu şekli ekler, bir resmi tutmak için. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Yeni bir yer tutucu şekli ekler, bir grafik tutmak için. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Yeni bir yer tutucu şekli ekler, bir tablo tutmak için. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Yeni bir yer tutucu şekli ekler, bir SmartArt diyagramı tutmak için. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Yeni bir yer tutucu şekli ekler, bir medya nesnesi tutmak için. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Yeni bir yer tutucu şekli ekler, bir çevrimiçi görsel tutmak için. |

### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

Yeni bir yer tutucu şekli ekler, içerik tutmak için, örneğin bir resim, tablo, medya veya metin.

--------------------

> ```
> The following example shows how to add the Content placeholder shape to the layout slide.
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
| x | float | Yeni yer tutucu şeklinin X koordinatı. |
| y | float | Yeni yer tutucu şeklinin Y koordinatı. |
| width | float | Yeni yer tutucu şeklinin genişliği. |
| height | float | Yeni yer tutucu şeklinin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape) bir İçerik yer tutucusu ile.

### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Yeni bir yer tutucu şekli ekler, içerik tutmak için, örneğin bir resim, tablo, medya veya metni dikey yönde.

--------------------

> ```
> The following example shows how to add the Content (Vertical) placeholder shape to the layout slide.
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
| x | float | Yeni yer tutucu şeklinin X koordinatı. |
| y | float | Yeni yer tutucu şeklinin Y koordinatı. |
| width | float | Yeni yer tutucu şeklinin genişliği. |
| height | float | Yeni yer tutucu şeklinin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape) bir İçerik (Dikey) yer tutucusu ile.

### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Yeni bir yer tutucu şekli ekler, metin içeriğini tutmak için.

--------------------

> ```
> The following example shows how to add the Text placeholder shape to the layout slide.
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
| x | float | Yeni yer tutucu şeklinin X koordinatı. |
| y | float | Yeni yer tutucu şeklinin Y koordinatı. |
| width | float | Yeni yer tutucu şeklinin genişliği. |
| height | float | Yeni yer tutucu şeklinin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape) bir Metin yer tutucusu ile.

### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Yeni bir yer tutucu şekli ekler, metin içeriğini dikey yönde tutmak için.

--------------------

> ```
> The following example shows how to add the Text (Vertical) placeholder shape to the layout slide.
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
| x | float | Yeni yer tutucu şeklinin X koordinatı. |
| y | float | Yeni yer tutucu şeklinin Y koordinatı. |
| width | float | Yeni yer tutucu şeklinin genişliği. |
| height | float | Yeni yer tutucu şeklinin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape) bir Metin (Dikey) yer tutucusu ile.

### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Yeni bir yer tutucu şekli ekler, bir resmi tutmak için.

--------------------

> ```
> The following example shows how to add the Picture placeholder shape to the layout slide.
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
| x | float | Yeni yer tutucu şeklinin X koordinatı. |
| y | float | Yeni yer tutucu şeklinin Y koordinatı. |
| width | float | Yeni yer tutucu şeklinin genişliği. |
| height | float | Yeni yer tutucu şeklinin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape) bir Resim yer tutucusu ile.

### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

Yeni bir yer tutucu şekli ekler, bir grafik tutmak için.

--------------------

> ```
> The following example shows how to add the Chart placeholder shape to the layout slide.
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
| x | float | Yeni yer tutucu şeklinin X koordinatı. |
| y | float | Yeni yer tutucu şeklinin Y koordinatı. |
| width | float | Yeni yer tutucu şeklinin genişliği. |
| height | float | Yeni yer tutucu şeklinin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape) bir Grafik yer tutucusu ile.

### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

Yeni bir yer tutucu şekli ekler, bir tablo tutmak için.

--------------------

> ```
> The following example shows how to add the Table placeholder shape to the layout slide.
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
| x | float | Yeni yer tutucu şeklinin X koordinatı. |
| y | float | Yeni yer tutucu şeklinin Y koordinatı. |
| width | float | Yeni yer tutucu şeklinin genişliği. |
| height | float | Yeni yer tutucu şeklinin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape) bir Tablo yer tutucusu ile.

### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

Yeni bir yer tutucu şekli ekler, bir SmartArt diyagramı tutmak için.

--------------------

> ```
> Aşağıdaki örnek, SmartArt yer tutucu şeklinin yerleşim slaytına nasıl ekleneceğini gösterir.
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
| x | float | Yeni yer tutucu şeklinin X koordinatı. |
| y | float | Yeni yer tutucu şeklinin Y koordinatı. |
| width | float | Yeni yer tutucu şeklinin genişliği. |
| height | float | Yeni yer tutucu şeklinin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape) bir SmartArt yer tutucusu ile.

### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

Yeni bir yer tutucu şekli ekler, bir medya nesnesi tutmak için.

--------------------

> ```
> Media yer tutucu şeklinin yerleşim slaytına nasıl ekleneceğini gösteren aşağıdaki örnek.
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
| x | float | Yeni yer tutucu şeklinin X koordinatı. |
| y | float | Yeni yer tutucu şeklinin Y koordinatı. |
| width | float | Yeni yer tutucu şeklinin genişliği. |
| height | float | Yeni yer tutucu şeklinin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape) bir Medya yer tutucusu ile.

### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

Yeni bir yer tutucu şekli ekler, bir çevrimiçi görsel tutmak için.

--------------------

> ```
> Aşağıdaki örnek, Çevrimiçi Görsel yer tutucu şeklinin yerleşim slaytına nasıl ekleneceğini gösterir.
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
| x | float | Yeni yer tutucu şeklinin X koordinatı. |
| y | float | Yeni yer tutucu şeklinin Y koordinatı. |
| width | float | Yeni yer tutucu şeklinin genişliği. |
| height | float | Yeni yer tutucu şeklinin yüksekliği. |

**Döndürür:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Oluşturulan [IAutoShape](../../com.aspose.slides/iautoshape) bir Çevrimiçi Görsel yer tutucusu ile.