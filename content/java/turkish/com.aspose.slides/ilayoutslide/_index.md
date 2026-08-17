---
title: ILayoutSlide
second_title: Aspose.Slides for Java API Referansı
description: Bir düzen slaytını temsil eder.
type: docs
url: /tr/com.aspose.slides/ilayoutslide/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Bir düzen slaytını temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Düzen slaytının HeaderFooter yöneticisini döndürür. |
| [getPlaceholderManager()](#getPlaceholderManager--) | Düzen slaytının placeholder yöneticisini döndürür. |
| [getMasterSlide()](#getMasterSlide--) | Bir düzen için master slide'ı döndürür veya ayarlar. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | Bir düzen için master slide'ı döndürür veya ayarlar. |
| [getLayoutType()](#getLayoutType--) | Bu düzen slaytının layout türünü döndürür. |
| [hasDependingSlides()](#hasDependingSlides--) | Bu düzen slaytına bağımlı en az bir slayt varsa true döndürür. |
| [getDependingSlides()](#getDependingSlides--) | Bu düzen slaytına bağımlı olan tüm slaytları içeren bir dizi döndürür. |
| [remove()](#remove--) | Sunumdan düzeni kaldırır. |
| [getDrawingGuides()](#getDrawingGuides--) | Düzen slaytı için çizim kılavuzları koleksiyonunu döndürür. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```


Düzen slaytının HeaderFooter yöneticisini döndürür. Yalnızca okuma [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Döndürür:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```


Düzen slaytının placeholder yöneticisini döndürür. Yalnızca okuma [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Döndürür:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```


Bir düzen için master slide'ı döndürür veya ayarlar. Okuma/yazma [IMasterSlide](../../com.aspose.slides/imasterslide).

**Döndürür:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```


Bir düzen için master slide'ı döndürür veya ayarlar. Okuma/yazma [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |

### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```


Bu düzen slaytının layout türünü döndürür. Yalnızca okuma [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Döndürür:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


Bu düzen slaytına bağımlı en az bir slayt varsa true döndürür. Yalnızca okuma boolean.

**Döndürür:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```


Bu düzen slaytına bağımlı olan tüm slaytları içeren bir dizi döndürür.

**Döndürür:**
com.aspose.slides.ISlide[] - Bu düzen slaytına bağımlı olan tüm slaytları içeren dizi
### remove() {#remove--}
```
public abstract void remove()
```


Sunumdan düzeni kaldırır.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```


Düzen slaytı için çizim kılavuzları koleksiyonunu döndürür. Yalnızca okuma [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getLayoutSlides().get_Item(0).getDrawingGuides();
>      // Yeni dikey çizim kılavuzunu slayt merkezinin soluna ekleme
>      guides.add(Orientation.Vertical, (float)slideSize.getWidth() / 2 - 20f);
> 
>      pres.save("LayoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)