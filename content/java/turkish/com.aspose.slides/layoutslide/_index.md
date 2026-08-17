---
title: LayoutSlide
second_title: Aspose.Slides için Java API Referansı
description: Bir düzen slaytını temsil eder.
type: docs
url: /tr/com.aspose.slides/layoutslide/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Bir düzen slaytını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Bu düzen slaytının HeaderFooter yöneticisini döndürür. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Bu düzen slaytının yer tutucu yöneticisini döndürür. |
| [getMasterSlide()](#getMasterSlide--) | Bir düzen için ana slaytı döndürür veya ayarlar. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Bir düzen için ana slaytı döndürür veya ayarlar. |
| [remove()](#remove--) | Düzeni sunumdan kaldırır. |
| [getThemeManager()](#getThemeManager--) | Üstüne yazılan tema yöneticisini döndürür. |
| [getLayoutType()](#getLayoutType--) | Bu düzen slaytının düzen türünü döndürür. |
| [getDependingSlides()](#getDependingSlides--) | Bu düzen slaytına bağımlı olan tüm slaytları içeren bir dizi döndürür. |
| [hasDependingSlides()](#hasDependingSlides--) | Bu düzen slaytına bağımlı en az bir slayt varsa true döndürür. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. |
| [getDrawingGuides()](#getDrawingGuides--) | Düzen slaytı için çizim kılavuzları koleksiyonunu döndürür. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

Bu düzen slaytının HeaderFooter yöneticisini döndürür. Yalnızca okuma [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Dönüş:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)

### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```

Bu düzen slaytının yer tutucu yöneticisini döndürür. Yalnızca okuma [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Dönüş:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)

### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```

Bir düzen için ana slaytı döndürür veya ayarlar. Okunur/yazılır [IMasterSlide](../../com.aspose.slides/imasterslide).

**Dönüş:**
[IMasterSlide](../../com.aspose.slides/imasterslide)

### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```

Bir düzen için ana slaytı döndürür veya ayarlar. Okunur/yazılır [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### remove() {#remove--}
```
public final void remove()
```

Düzeni sunumdan kaldırır.

### getThemeManager() {#getThemeManager--}
```
public final IOverrideThemeManager getThemeManager()
```

Üstüne yazılan tema yöneticisini döndürür. Yalnızca okuma [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Dönüş:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)

### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```

Bu düzen slaytının düzen türünü döndürür. Yalnızca okuma [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Dönüş:**
byte

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Bu düzen slaytına bağımlı olan tüm slaytları içeren bir dizi döndürür.

**Dönüş:**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) dizisi

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Bu düzen slaytına bağımlı en az bir slayt varsa true döndürür. Yalnızca okuma  boolean .

**Dönüş:**
boolean

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Okunur/yazılır  boolean .

**Dönüş:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Okunur/yazılır  boolean .

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Düzen slaytı için çizim kılavuzları koleksiyonunu döndürür. Yalnızca okuma [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Yeni dikey çizim kılavuzunu slayt merkezinin soluna ekliyor
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Dönüş:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)