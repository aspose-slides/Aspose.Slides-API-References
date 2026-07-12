---
title: LayoutSlide
second_title: Aspose.Slides for Android, Java API Referansı
description: Bir düzen slaytını temsil eder.
type: docs
url: /tr/com.aspose.slides/layoutslide/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.ILayoutSlide](../../com.aspose.slides/ilayoutslide)
```
public final class LayoutSlide extends BaseSlide implements ILayoutSlide
```

Bir düzen slaytını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Düzen slaytının HeaderFooter yöneticisini döndürür. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Düzen slaytının yer tutucu yöneticisini döndürür. |
| [getMasterSlide()](#getMasterSlide--) | Bir düzen için ana slaytı döndürür veya ayarlar. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Bir düzen için ana slaytı döndürür veya ayarlar. |
| [remove()](#remove--) | Düzeni sunumdan kaldırır. |
| [getThemeManager()](#getThemeManager--) | Geçersiz kılan tema yöneticisini döndürür. |
| [getLayoutType()](#getLayoutType--) | Bu düzen slaytının düzen türünü döndürür. |
| [getDependingSlides()](#getDependingSlides--) | Bu düzen slaytına bağımlı olan tüm slaytları içeren bir dizi döndürür. |
| [hasDependingSlides()](#hasDependingSlides--) | Bu düzen slaytına bağımlı en az bir slayt varsa true döndürür. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. |
| [getDrawingGuides()](#getDrawingGuides--) | Düzen slaytı için çizim kılavuzlarının bir koleksiyonunu döndürür. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Düzen slaytının HeaderFooter yöneticisini döndürür. Salt okunur [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Döndürür:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public final ILayoutPlaceholderManager getPlaceholderManager()
```


Düzen slaytının yer tutucu yöneticisini döndürür. Salt okunur [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Döndürür:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public final IMasterSlide getMasterSlide()
```


Bir düzen için ana slaytı döndürür veya ayarlar. Okunur/yazılabilir [IMasterSlide](../../com.aspose.slides/imasterslide).

**Döndürür:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public final void setMasterSlide(IMasterSlide value)
```


Bir düzen için ana slaytı döndürür veya ayarlar. Okunur/yazılabilir [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parametreler:**
| Parametre | Tip | Açıklama |
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


Geçersiz kılan tema yöneticisini döndürür. Salt okunur [IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager).

**Döndürür:**
[IOverrideThemeManager](../../com.aspose.slides/ioverridethememanager)
### getLayoutType() {#getLayoutType--}
```
public final byte getLayoutType()
```


Bu düzen slaytının düzen türünü döndürür. Salt okunur [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Döndürür:**
byte
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```


Bu düzen slaytına bağımlı olan tüm slaytları içeren bir dizi döndürür.

**Döndürür:**
com.aspose.slides.ISlide[] - Array of [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```


Bu düzen slaytına bağımlı en az bir slayt varsa true döndürür. Salt okunur  boolean .

**Döndürür:**
boolean
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```


Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Okunur/yazılabilir  boolean .

**Döndürür:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```


Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Okunur/yazılabilir  boolean .

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```


Düzen slaytı için çizim kılavuzlarının bir koleksiyonunu döndürür. Salt okunur [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
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


**Döndürür:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)