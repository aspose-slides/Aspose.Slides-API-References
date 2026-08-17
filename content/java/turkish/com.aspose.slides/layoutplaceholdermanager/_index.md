---
title: LayoutPlaceholderManager
second_title: Aspose.Slides for Java API Referansı
description: Düzen slaytına yer tutucular eklemenizi sağlayan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/layoutplaceholdermanager/
---
**Inheritance:**
java.lang.Object

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
```
public class LayoutPlaceholderManager implements ILayoutPlaceholderManager
```

Yer tutucuları düzen slaytına eklemenizi sağlayan yöneticiyi temsil eder.
## Methods

| Yöntem | Açıklama |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | İçerik (örneğin resim, table, media veya text) tutmak için düzen slaytına yeni bir yer tutucu şekil ekler. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Dikey yönde içerik (örneğin resim, table, media veya text) tutmak için düzen slaytına yeni bir yer tutucu şekil ekler. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Metin içeriği tutmak için düzen slaytına yeni bir yer tutucu şekil ekler. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Dikey yönde metin içeriği tutmak için düzen slaytına yeni bir yer tutucu şekil ekler. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Resim tutmak için düzen slaytına yeni bir yer tutucu şekil ekler. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | chart tutmak için düzen slaytına yeni bir yer tutucu şekil ekler. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | table tutmak için düzen slaytına yeni bir yer tutucu şekil ekler. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | SmartArt diagram tutmak için düzen slaytına yeni bir yer tutucu şekil ekler. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | media nesnesi tutmak için düzen slaytına yeni bir yer tutucu şekil ekler. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | online image tutmak için düzen slaytına yeni bir yer tutucu şekil ekler. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```

İçerik (örneğin resim, table, media veya text) tutmak için düzen slaytına yeni bir yer tutucu şekil ekler.

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
| x | float | Yeni yer tutucu şeklin X koordinatı. |
| y | float | Yeni yer tutucu şeklin Y koordinatı. |
| width | float | Yeni yer tutucu şeklin genişliği. |
| height | float | Yeni yer tutucu şeklin yüksekliği. |

**Dönüş Değeri:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Bir Content yer tutucu ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.
### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```

Dikey yönde içerik (örneğin resim, table, media veya text) tutmak için düzen slaytına yeni bir yer tutucu şekil ekler.

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
| x | float | Yeni yer tutucu şeklin X koordinatı. |
| y | float | Yeni yer tutucu şeklin Y koordinatı. |
| width | float | Yeni yer tutucu şeklin genişliği. |
| height | float | Yeni yer tutucu şeklin yüksekliği. |

**Dönüş Değeri:**
[IAutoShape](../../com.aspose.slides/iautoshape) - İçerik (Dikey) yer tutucu ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.
### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```

Metin içeriği tutmak için düzen slaytına yeni bir yer tutucu şekil ekler.

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
| x | float | Yeni yer tutucu şeklin X koordinatı. |
| y | float | Yeni yer tutucu şeklin Y koordinatı. |
| width | float | Yeni yer tutucu şeklin genişliği. |
| height | float | Yeni yer tutucu şeklin yüksekliği. |

**Dönüş Değeri:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Bir Text yer tutucu ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.
### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public final IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```

Dikey yönde metin içeriği tutmak için düzen slaytına yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Text (Vertical) yer tutucu şeklinin düzen slaytına nasıl ekleneceğini gösterir.
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

**Dönüş Değeri:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Metin (Dikey) yer tutucu ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.
### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public final IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```

Resim tutmak için düzen slaytına yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Picture yer tutucu şeklinin düzen slaytına nasıl ekleneceğini gösterir.
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

**Dönüş Değeri:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Bir Picture yer tutucu ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.
### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public final IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```

chart tutmak için düzen slaytına yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Chart yer tutucu şeklinin düzen slaytına nasıl ekleneceğini gösterir.
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

**Dönüş Değeri:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Bir chart yer tutucu ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.
### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public final IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```

table tutmak için düzen slaytına yeni bir yer tutucu şekil ekler.

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
| x | float | Yeni yer tutucu şeklin X koordinatı. |
| y | float | Yeni yer tutucu şeklin Y koordinatı. |
| width | float | Yeni yer tutucu şeklin genişliği. |
| height | float | Yeni yer tutucu şeklin yüksekliği. |

**Dönüş Değeri:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Bir table yer tutucu ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.
### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public final IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```

SmartArt diagram tutmak için düzen slaytına yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, SmartArt yer tutucu şeklinin düzen slaytına nasıl ekleneceğini gösterir.
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

**Dönüş Değeri:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Bir SmartArt yer tutucu ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.
### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public final IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```

media nesnesi tutmak için düzen slaytına yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Media yer tutucu şeklinin düzen slaytına nasıl ekleneceğini gösterir.
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

**Dönüş Değeri:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Bir Media yer tutucu ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.
### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public final IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```

online image tutmak için düzen slaytına yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Online Image yer tutucu şeklinin düzen slaytına nasıl ekleneceğini gösterir.
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

**Dönüş Değeri:**
[IAutoShape](../../com.aspose.slides/iautoshape) - Bir Online Image yer tutucu ile [IAutoShape](../../com.aspose.slides/iautoshape) oluşturuldu.