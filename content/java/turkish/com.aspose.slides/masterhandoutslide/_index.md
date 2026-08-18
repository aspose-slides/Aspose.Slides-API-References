---
title: MasterHandoutSlide
second_title: Aspose.Slides for Java API Referansı
description: El ilanları için ana slaytı temsil eder.
type: docs
url: /tr/com.aspose.slides/masterhandoutslide/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IMasterHandoutSlide](../../com.aspose.slides/imasterhandoutslide)
```
public class MasterHandoutSlide extends BaseSlide implements IMasterHandoutSlide
```

Ana el ilanları için ana slaytı temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getShowMasterShapes()](#getShowMasterShapes--) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Ana el ilanı slaytının HeaderFooter yöneticisini döndürür. |
| [getThemeManager()](#getThemeManager--) | Tema yöneticisini döndürür. |
| [getDrawingGuides()](#getDrawingGuides--) | Ana el ilanı slaytı için bir çizim kılavuzu koleksiyonunu döndürür. |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Ana slayt kendisi için bu özellik her zaman false döndürür. Okunabilir/yazılabilir boolean.

**Döndürür:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Ana slayttaki şekillerin slaytlarda gösterilip gösterilmeyeceğini belirtir. Ana slayt kendisi için bu özellik her zaman false döndürür. Okunabilir/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterHandoutSlideHeaderFooterManager getHeaderFooterManager()
```

Ana el ilanı slaytının HeaderFooter yöneticisini döndürür. Yalnızca okunur [IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager).

**Döndürür:**
[IMasterHandoutSlideHeaderFooterManager](../../com.aspose.slides/imasterhandoutslideheaderfootermanager)
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Tema yöneticisini döndürür. Yalnızca okunur [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Döndürür:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Ana el ilanı slaytı için bir çizim kılavuzu koleksiyonunu döndürür. Yalnızca okunur [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D notesSize = pres.getNotesSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasterHandoutSlideManager().setDefaultMasterHandoutSlide().getDrawingGuides();
>      // Yeni yatay çizim kılavuzunu slayt merkezinin üzerine ekleme
>      guides.add(Orientation.Horizontal, (float) notesSize.getHeight() / 2 - 50f);
> 
>      pres.save("MasterHandoutDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Döndürür:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)