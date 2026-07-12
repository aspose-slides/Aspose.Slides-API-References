---
title: ILayoutSlide
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir yerleşim slaytını temsil eder.
type: docs
url: /tr/com.aspose.slides/ilayoutslide/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IOverrideThemeable](../../com.aspose.slides/ioverridethemeable)
```
public interface ILayoutSlide extends IBaseSlide, IOverrideThemeable
```

Bir yerleşim slaytını temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | layout slaytının HeaderFooter yöneticisini döndürür. |
| [getPlaceholderManager()](#getPlaceholderManager--) | layout slaytının yer tutucu yöneticisini döndürür. |
| [getMasterSlide()](#getMasterSlide--) | bir yerleşim için ana slaytı döndürür veya ayarlar. |
| [setMasterSlide(IMasterSlide value)](#setMasterSlide-com.aspose.slides.IMasterSlide-) | bir yerleşim için ana slaytı döndürür veya ayarlar. |
| [getLayoutType()](#getLayoutType--) | bu layout slaytının yerleşim tipini döndürür. |
| [hasDependingSlides()](#hasDependingSlides--) | bu layout slaytına bağımlı olan en az bir slayt varsa true döndürür. |
| [getDependingSlides()](#getDependingSlides--) | bu layout slaytına bağımlı olan tüm slaytları içeren bir dizi döndürür. |
| [remove()](#remove--) | yerleşimi sunumdan kaldırır. |
| [getDrawingGuides()](#getDrawingGuides--) | layout slaytı için çizim kılavuzlarının bir koleksiyonunu döndürür. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract ILayoutSlideHeaderFooterManager getHeaderFooterManager()
```

layout slaytının HeaderFooter yöneticisini döndürür. Salt okunur [ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager).

**Döndürür:**
[ILayoutSlideHeaderFooterManager](../../com.aspose.slides/ilayoutslideheaderfootermanager)
### getPlaceholderManager() {#getPlaceholderManager--}
```
public abstract ILayoutPlaceholderManager getPlaceholderManager()
```

layout slaytının yer tutucu yöneticisini döndürür. Salt okunur [ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager).

**Döndürür:**
[ILayoutPlaceholderManager](../../com.aspose.slides/ilayoutplaceholdermanager)
### getMasterSlide() {#getMasterSlide--}
```
public abstract IMasterSlide getMasterSlide()
```

bir yerleşim için ana slaytı döndürür veya ayarlar. Okunur/yazılabilir [IMasterSlide](../../com.aspose.slides/imasterslide).

**Döndürür:**
[IMasterSlide](../../com.aspose.slides/imasterslide)
### setMasterSlide(IMasterSlide value) {#setMasterSlide-com.aspose.slides.IMasterSlide-}
```
public abstract void setMasterSlide(IMasterSlide value)
```

bir yerleşim için ana slaytı döndürür veya ayarlar. Okunur/yazılabilir [IMasterSlide](../../com.aspose.slides/imasterslide).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IMasterSlide](../../com.aspose.slides/imasterslide) |  |
### getLayoutType() {#getLayoutType--}
```
public abstract byte getLayoutType()
```

bu layout slaytının yerleşim tipini döndürür. Salt okunur [SlideLayoutType](../../com.aspose.slides/slidelayouttype).

**Döndürür:**
byte
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

bu layout slaytına bağımlı olan en az bir slayt varsa true döndürür. Salt okunur boolean.

**Döndürür:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

bu layout slaytına bağımlı olan tüm slaytları içeren bir dizi döndürür.

**Döndürür:**
com.aspose.slides.ISlide[] - Bu layout slaytına bağımlı olan tüm slaytların dizisi
### remove() {#remove--}
```
public abstract void remove()
```

yerleşimi sunumdan kaldırır.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

layout slaytı için çizim kılavuzlarının bir koleksiyonunu döndürür. Salt okunur [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

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