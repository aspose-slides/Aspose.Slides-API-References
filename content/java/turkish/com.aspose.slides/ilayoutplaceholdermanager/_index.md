---
title: ILayoutPlaceholderManager
second_title: Aspose.Slides for Java API Referansı
description: Düzen slaytına yer tutucular eklemenizi sağlayan yöneticiyi temsil eder.
type: docs
url: /tr/com.aspose.slides/ilayoutplaceholdermanager/
---```
public interface ILayoutPlaceholderManager
```

Düzen slaytına yer tutucular eklemenizi sağlayan yöneticiyi temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addContentPlaceholder(float x, float y, float width, float height)](#addContentPlaceholder-float-float-float-float-) | Düzen slaytına içerik tutmak için, örneğin bir resim, tablo, medya veya metin gibi yeni bir yer tutucu şekil ekler. |
| [addVerticalContentPlaceholder(float x, float y, float width, float height)](#addVerticalContentPlaceholder-float-float-float-float-) | Düzen slaytına dikey yönde içerik tutmak için, örneğin bir resim, tablo, medya veya metin gibi yeni bir yer tutucu şekil ekler. |
| [addTextPlaceholder(float x, float y, float width, float height)](#addTextPlaceholder-float-float-float-float-) | Düzen slaytına metin içeriği tutmak için yeni bir yer tutucu şekil ekler. |
| [addVerticalTextPlaceholder(float x, float y, float width, float height)](#addVerticalTextPlaceholder-float-float-float-float-) | Düzen slaytına dikey yönde metin içeriği tutmak için yeni bir yer tutucu şekil ekler. |
| [addPicturePlaceholder(float x, float y, float width, float height)](#addPicturePlaceholder-float-float-float-float-) | Düzen slaytına bir resim tutmak için yeni bir yer tutucu şekil ekler. |
| [addChartPlaceholder(float x, float y, float width, float height)](#addChartPlaceholder-float-float-float-float-) | Düzen slaytına bir grafik tutmak için yeni bir yer tutucu şekil ekler. |
| [addTablePlaceholder(float x, float y, float width, float height)](#addTablePlaceholder-float-float-float-float-) | Düzen slaytına bir tablo tutmak için yeni bir yer tutucu şekil ekler. |
| [addSmartArtPlaceholder(float x, float y, float width, float height)](#addSmartArtPlaceholder-float-float-float-float-) | Düzen slaytına bir SmartArt diyagramı tutmak için yeni bir yer tutucu şekil ekler. |
| [addMediaPlaceholder(float x, float y, float width, float height)](#addMediaPlaceholder-float-float-float-float-) | Düzen slaytına bir medya nesnesi tutmak için yeni bir yer tutucu şekil ekler. |
| [addOnlineImagePlaceholder(float x, float y, float width, float height)](#addOnlineImagePlaceholder-float-float-float-float-) | Düzen slaytına bir çevrimiçi resim tutmak için yeni bir yer tutucu şekil ekler. |
### addContentPlaceholder(float x, float y, float width, float height) {#addContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addContentPlaceholder(float x, float y, float width, float height)
```


Düzen slaytına içerik tutmak için, örneğin bir resim, tablo, medya veya metin gibi yeni bir yer tutucu şekil ekler.

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

**Dönüş:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) bir İçerik yer tutucusuyla oluşturuldu.

### addVerticalContentPlaceholder(float x, float y, float width, float height) {#addVerticalContentPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalContentPlaceholder(float x, float y, float width, float height)
```


Dikey yönde içerik tutmak için, örneğin bir resim, tablo, medya veya metin gibi yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, İçerik (Dikey) yer tutucu şeklinin düzen slaytına nasıl ekleneceğini gösterir.
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

**Dönüş:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) bir İçerik (Dikey) yer tutucusuyla oluşturuldu.

### addTextPlaceholder(float x, float y, float width, float height) {#addTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTextPlaceholder(float x, float y, float width, float height)
```


Metin içeriği tutmak için yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Metin yer tutucu şeklinin düzen slaytına nasıl ekleneceğini gösterir.
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

**Dönüş:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) bir Metin yer tutucusuyla oluşturuldu.

### addVerticalTextPlaceholder(float x, float y, float width, float height) {#addVerticalTextPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addVerticalTextPlaceholder(float x, float y, float width, float height)
```


Dikey yönde metin içeriği tutmak için yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Metin (Dikey) yer tutucu şeklinin düzen slaytına nasıl ekleneceğini gösterir.
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

**Dönüş:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) bir Metin (Dikey) yer tutucusuyla oluşturuldu.

### addPicturePlaceholder(float x, float y, float width, float height) {#addPicturePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addPicturePlaceholder(float x, float y, float width, float height)
```


Bir resim tutmak için yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Resim yer tutucu şeklinin düzen slaytına nasıl ekleneceğini gösterir.
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

**Dönüş:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) bir Resim yer tutucusuyla oluşturuldu.

### addChartPlaceholder(float x, float y, float width, float height) {#addChartPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addChartPlaceholder(float x, float y, float width, float height)
```


Bir grafik tutmak için yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Grafik yer tutucu şeklinin düzen slaytına nasıl ekleneceğini gösterir.
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

**Dönüş:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) bir Grafik yer tutucusuyla oluşturuldu.

### addTablePlaceholder(float x, float y, float width, float height) {#addTablePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addTablePlaceholder(float x, float y, float width, float height)
```


Bir tablo tutmak için yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Tablo yer tutucu şeklinin düzen slaytına nasıl ekleneceğini gösterir.
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

**Dönüş:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) bir Tablo yer tutucusuyla oluşturuldu.

### addSmartArtPlaceholder(float x, float y, float width, float height) {#addSmartArtPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addSmartArtPlaceholder(float x, float y, float width, float height)
```


Bir SmartArt diyagramı tutmak için yeni bir yer tutucu şekil ekler.

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

**Dönüş:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) bir SmartArt yer tutucusuyla oluşturuldu.

### addMediaPlaceholder(float x, float y, float width, float height) {#addMediaPlaceholder-float-float-float-float-}
```
public abstract IAutoShape addMediaPlaceholder(float x, float y, float width, float height)
```


Bir medya nesnesi tutmak için yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Medya yer tutucu şeklinin düzen slaytına nasıl ekleneceğini gösterir.
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

**Dönüş:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) bir Medya yer tutucusuyla oluşturuldu.

### addOnlineImagePlaceholder(float x, float y, float width, float height) {#addOnlineImagePlaceholder-float-float-float-float-}
```
public abstract IAutoShape addOnlineImagePlaceholder(float x, float y, float width, float height)
```


Bir çevrimiçi resim tutmak için yeni bir yer tutucu şekil ekler.

--------------------

> ```
> Aşağıdaki örnek, Çevrimiçi Resim yer tutucu şeklinin düzen slaytına nasıl ekleneceğini gösterir.
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

**Dönüş:**
[IAutoShape](../../com.aspose.slides/iautoshape) - [IAutoShape](../../com.aspose.slides/iautoshape) bir Çevrimiçi Resim yer tutucusuyla oluşturuldu.