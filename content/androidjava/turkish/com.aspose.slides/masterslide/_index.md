---
title: MasterSlide
second_title: Aspose.Slides for Android üzerinden Java API Referansı
description: Bir sunumda master slaytı temsil eder.
type: docs
url: /tr/com.aspose.slides/masterslide/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

Bir sunumda master slaytı temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Master slaytının HeaderFooter yöneticisini döndürür. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Mevcut slayta dayanarak yeni bir master slayt oluşturur, harici bir temayı uygulayarak oluşturulan master slaytı tüm bağlı slaytlara uygular. |
| [getTitleStyle()](#getTitleStyle--) | Başlık metninin stilini döndürür. |
| [getBodyStyle()](#getBodyStyle--) | Gövde metninin stilini döndürür. |
| [getOtherStyle()](#getOtherStyle--) | Diğer metnin stilini döndürür. |
| [getLayoutSlides()](#getLayoutSlides--) | Bu master slayt için alt yerleşim slaytlarının koleksiyonunu döndürür. |
| [getPreserve()](#getPreserve--) | İlgili masterın, onu izleyen tüm slaytlar silindiğinde silinip silinmeyeceğini belirler. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | İlgili masterın, onu izleyen tüm slaytlar silindiğinde silinip silinmeyeceğini belirler. |
| [getDependingSlides()](#getDependingSlides--) | Bu master slayta bağımlı tüm slaytları içeren bir dizi döndürür. |
| [hasDependingSlides()](#hasDependingSlides--) | Bu master slayta bağımlı en az bir slayt varsa true döndürür. |
| [getThemeManager()](#getThemeManager--) | Tema yöneticisini döndürür. |
| [getName()](#getName--) | Bir master slaytın adını döndürür veya ayarlar. |
| [setName(String value)](#setName-java.lang.String-) | Bir master slaytın adını döndürür veya ayarlar. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Master slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Master slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. |
| [getDrawingGuides()](#getDrawingGuides--) | Master slayt için çizim kılavuzlarının bir koleksiyonunu döndürür. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Master slaytının HeaderFooter yöneticisini döndürür. Salt okunur [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Döndürür:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Mevcut slayta dayanarak yeni bir master slayt oluşturur, harici bir temayı uygulayarak oluşturulan master slaytı tüm bağlı slaytlara uygular.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | java.lang.String | Harici tema dosyasının (.thmx) yolu. |

**Döndürür:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Yeni temalı MasterSlide.
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

Başlık metninin stilini döndürür. Salt okunur [ITextStyle](../../com.aspose.slides/itextstyle).

**Döndürür:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

Gövde metninin stilini döndürür. Salt okunur [ITextStyle](../../com.aspose.slides/itextstyle).

**Döndürür:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

Diğer metnin stilini döndürür. Salt okunur [ITextStyle](../../com.aspose.slides/itextstyle).

**Döndürür:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

Bu master slayt için alt yerleşim slaytlarının koleksiyonunu döndürür. Salt okunur [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Düzen yerleşim slaytlarını eklemek/girmek/kaldırmak/kopyalamak için alternatif API'ye ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) özelliğini kullanarak erişebilirsiniz.

**Döndürür:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

İlgili masterın, onu izleyen tüm slaytlar silindiğinde silinip silinmeyeceğini belirler. Not: Aspose.Slides hiçbir zaman kullanılmayan bir masterı kendi başına kaldırmaz, kullanılmayan masterları gerçekten kaldırmak için [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Okuma/yazma boolean çağrısında bulunun.

**Döndürür:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

İlgili masterın, onu izleyen tüm slaytlar silindiğinde silinip silinmeyeceğini belirler. Not: Aspose.Slides hiçbir zaman kullanılmayan bir masterı kendi başına kaldırmaz, kullanılmayan masterları gerçekten kaldırmak için [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Okuma/yazma boolean çağrısında bulunun.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Bu master slayta bağımlı tüm slaytları içeren bir dizi döndürür.

**Döndürür:**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) dizisi
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Bu master slayta bağımlı en az bir slayt varsa true döndürür. Salt okunur boolean.

**Döndürür:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Tema yöneticisini döndürür. Salt okunur [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Döndürür:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```

Bir master slaytın adını döndürür veya ayarlar. Okuma/yazma String.

**Döndürür:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Bir master slaytın adını döndürür veya ayarlar. Okuma/yazma String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Master slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Master slayt için bu özellik her zaman false döndürür. Okuma/yazma boolean.

**Döndürür:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Master slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Master slayt için bu özellik her zaman false döndürür. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Master slayt için çizim kılavuzlarının bir koleksiyonunu döndürür. Salt okunur [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Yeni dikey çizim kılavuzunu slayt merkezinin sağına ekliyor
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)