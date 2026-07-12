---
title: IMasterSlide
second_title: Aspose.Slides for Android via Java API Referansı
description: Bir sunumdaki ana slaytı temsil eder.
type: docs
url: /tr/com.aspose.slides/imasterslide/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Bir sunumda ana slaytı temsil eder.
## Yöntemler

| Method | Açıklama |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Ana slaydın HeaderFooter yöneticisini döndürür. |
| [getTitleStyle()](#getTitleStyle--) | Başlık metninin stilini döndürür. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Mevcut olanı temel alarak yeni bir ana slayt oluşturur, dış bir temayı ona uygular ve oluşturulan ana slaytı tüm bağımlı slaytlara uygular. |
| [getBodyStyle()](#getBodyStyle--) | Gövde metninin stilini döndürür. |
| [getOtherStyle()](#getOtherStyle--) | Diğer bir metnin stilini döndürür. |
| [getLayoutSlides()](#getLayoutSlides--) | Bu ana slayt için alt düzen slaytlarının koleksiyonunu döndürür. |
| [getPreserve()](#getPreserve--) | İlgili ana slaydın, o ana slaytı izleyen tüm slaytlar silindiğinde silinip silinmeyeceğini belirler. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | İlgili ana slaydın, o ana slaytı izleyen tüm slaytlar silindiğinde silinip silinmeyeceğini belirler. |
| [hasDependingSlides()](#hasDependingSlides--) | Bu ana slayta bağımlı en az bir slayt varsa true döndürür. |
| [getDependingSlides()](#getDependingSlides--) | Bu ana slayta bağımlı tüm slaytları içeren bir dizi döndürür. |
| [getDrawingGuides()](#getDrawingGuides--) | Ana slayt için çizim kılavuzları koleksiyonunu döndürür. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Ana slaydın HeaderFooter yöneticisini döndürür. Salt okunur [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Döndürür:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

Başlık metninin stilini döndürür. Salt okunur [ITextStyle](../../com.aspose.slides/itextstyle).

**Döndürür:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Mevcut olanı temel alarak yeni bir ana slayt oluşturur, dış bir temayı ona uygular ve oluşturulan ana slaytı tüm bağımlı slaytlara uygular.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | java.lang.String | Dış tema dosyasının (.thmx) yolu. |

**Döndürür:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Yeni temalı MasterSlide.
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

Gövde metninin stilini döndürür. Salt okunur [ITextStyle](../../com.aspose.slides/itextstyle).

**Döndürür:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

Diğer bir metnin stilini döndürür. Salt okunur [ITextStyle](../../com.aspose.slides/itextstyle).

**Döndürür:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

Bu ana slayt için alt düzen slaytlarının koleksiyonunu döndürür. Salt okunur [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Ek düzen slaytlarını ekleme/ekleme/kaldırma/kopyalama için alternatif API'ye ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) özelliğini kullanarak erişebilirsiniz.

**Döndürür:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

İlgili ana slaydın, o ana slaytı izleyen tüm slaytlar silindiğinde silinip silinmeyeceğini belirler. Not: Aspose.Slides kendi kendine kullanılmayan bir ana slaytı asla kaldırmaz, kullanılmayan ana slaytları gerçekten kaldırmak için [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) çağırın. Salt-okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

İlgili ana slaydın, o ana slaytı izleyen tüm slaytlar silindiğinde silinip silinmeyeceğini belirler. Not: Aspose.Slides kendi kendine kullanılmayan bir ana slaytı asla kaldırmaz, kullanılmayan ana slaytları gerçekten kaldırmak için [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) çağırın. Okunur/Yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Bu ana slayta bağımlı en az bir slayt varsa true döndürür. Salt okunur boolean.

**Döndürür:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Bu ana slayta bağımlı tüm slaytları içeren bir dizi döndürür.

**Döndürür:**
com.aspose.slides.ISlide[] - Bu ana slayta bağımlı [ISlide](../../com.aspose.slides/islide) dizisi
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Ana slayt için çizim kılavuzları koleksiyonunu döndürür. Salt okunur [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Yeni dikey çizim kılavuzunu slayt merkezinin sağına ekleme
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)