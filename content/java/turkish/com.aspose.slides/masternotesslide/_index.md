---
title: MasterNotesSlide
second_title: Aspose.Slides for Java API Referansı
description: Notlar için ana slaytı temsil eder.
type: docs
url: /tr/com.aspose.slides/masternotesslide/
---
**Kalıtım:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Tüm Uygulanan Arayüzler:**  
[com.aspose.slides.IMasterNotesSlide](../../com.aspose.slides/imasternotesslide)  
```
public class MasterNotesSlide extends BaseSlide implements IMasterNotesSlide
```

Notlar için ana slaytı temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Ana not slaytının HeaderFooter yöneticisini döndürür. |
| [getThemeManager()](#getThemeManager--) | Tema yöneticisini döndürür. |
| [getNotesStyle()](#getNotesStyle--) | Not metninin stilini döndürür. |
| [getDrawingGuides()](#getDrawingGuides--) | Ana not slaytı için çizim kılavuzları koleksiyonunu döndürür. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. Ana slayt için bu özellik her zaman false döndürür. Okunabilir/yazılabilir boolean.

**Döndürür:**  
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirler. Ana slayt için bu özellik her zaman false döndürür. Okunabilir/yazılabilir boolean.

**Parametreler:**  
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterNotesSlideHeaderFooterManager getHeaderFooterManager()
```

Ana not slaytının HeaderFooter yöneticisini döndürür. Salt okunur [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Döndürür:**  
[IMasterNotesSlideHeaderFooterManager](../../com.aspose.slides/imasternotesslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Tema yöneticisini döndürür. Salt okunur [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Döndürür:**  
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getNotesStyle() {#getNotesStyle--}
```
public final ITextStyle getNotesStyle()
```

Not metninin stilini döndürür. Salt okunur [ITextStyle](../../com.aspose.slides/itextstyle).

**Döndürür:**  
[ITextStyle](../../com.aspose.slides/itextstyle)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Ana not slaytı için çizim kılavuzları koleksiyonunu döndürür. Salt okunur [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```markdown
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterNotesSlideManager().setDefaultMasterNotesSlide().getDrawingGuides();
>      // Yeni yatay çizim rehberini slayt merkezinin altına ekle
>      guides.add(Orientation.Horizontal, (float)notesSize.getHeight() / 2 + 50f);
> 
>      pres.save("MasterNotesDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Döndürür:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)