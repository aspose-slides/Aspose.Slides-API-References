---
title: MasterSlide
second_title: Aspose.Slides för Java API-referens
description: Representerar en master-bild i en presentation.
type: docs
url: /sv/com.aspose.slides/masterslide/
---
**Arv:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Alla implementerade gränssnitt:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

Representerar en master-bild i en presentation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Returnerar HeaderFooter-hanteraren för master-bilden. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Skapar en ny master-bild baserad på den nuvarande, applicerar ett externt tema på den och applicerar den skapade master-bilden på alla beroende bilder. |
| [getTitleStyle()](#getTitleStyle--) | Returnerar stilen för en rubriktext. |
| [getBodyStyle()](#getBodyStyle--) | Returnerar stilen för brödtext. |
| [getOtherStyle()](#getOtherStyle--) | Returnerar stilen för annan text. |
| [getLayoutSlides()](#getLayoutSlides--) | Returnerar samlingen av underordnade layout-bilder för denna master-bild. |
| [getPreserve()](#getPreserve--) | Avgör om den motsvarande master-bilden tas bort när alla bilder som följer den master-bilden har raderats. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Avgör om den motsvarande master-bilden tas bort när alla bilder som följer den master-bilden har raderats. |
| [getDependingSlides()](#getDependingSlides--) | Returnerar en array med alla bilder som är beroende av denna master-bild. |
| [hasDependingSlides()](#hasDependingSlides--) | Returnerar true om det finns minst en bild som är beroende av denna master-bild. |
| [getThemeManager()](#getThemeManager--) | Returnerar tema-hanteraren. |
| [getName()](#getName--) | Returnerar eller anger namnet på en master-bild. |
| [setName(String value)](#setName-java.lang.String-) | Returnerar eller anger namnet på en master-bild. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Anger om former på master-bilden ska visas på bilder eller inte. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Anger om former på master-bilden ska visas på bilder eller inte. |
| [getDrawingGuides()](#getDrawingGuides--) | Returnerar en samling av ritningsguider för master-bilden. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Returnerar HeaderFooter-hanteraren för master-bilden. Skrivskyddad [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Returnerar:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Skapar en ny master-bild baserad på den nuvarande, applicerar ett externt tema på den och applicerar den skapade master-bilden på alla beroende bilder.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fname | java.lang.String | Sökväg till den externa temafilen (.thmx). |

**Returnerar:**
[IMasterSlide](../../com.aspose.slides/imasterslide) – Ny temainställd MasterSlide.
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

Returnerar stilen för en rubriktext. Skrivskyddad [ITextStyle](../../com.aspose.slides/itextstyle).

**Returnerar:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

Returnerar stilen för brödtext. Skrivskyddad [ITextStyle](../../com.aspose.slides/itextstyle).

**Returnerar:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

Returnerar stilen för annan text. Skrivskyddad [ITextStyle](../../com.aspose.slides/itextstyle).

**Returnerar:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

Returnerar samlingen av underordnade layout-bilder för denna master-bild. Skrivskyddad [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Du kan komma åt ett alternativt API för att lägga till/infoga/ta bort/klona layout-bilder genom att använda egenskapen ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Returnerar:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

Avgör om den motsvarande master-bilden tas bort när alla bilder som följer den master-bilden har raderats. Obs: Aspose.Slides kommer aldrig att ta bort någon oanvänd master själv, för att faktiskt ta bort oanvända master-bilder anropa [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Läs/skriv  boolean .

**Returnerar:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

Avgör om den motsvarande master-bilden tas bort när alla bilder som följer den master-bilden har raderats. Obs: Aspose.Slides kommer aldrig att ta bort någon oanvänd master själv, för att faktiskt ta bort oanvända master-bilder anropa [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Läs/skriv  boolean .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Returnerar en array med alla bilder som är beroende av denna master-bild.

**Returnerar:**
com.aspose.slides.ISlide[] – Array av [ISlide](../../com.aspose.slides/islide)
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Returnerar true om det finns minst en bild som är beroende av denna master-bild. Skrivskyddad  boolean .

**Returnerar:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Returnerar tema-hanteraren. Skrivskyddad [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Returnerar:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```

Returnerar eller anger namnet på en master-bild. Läs/skriv String.

**Returnerar:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Returnerar eller anger namnet på en master-bild. Läs/skriv String.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Anger om former på master-bilden ska visas på bilder eller inte. För själva master-bilden returnerar denna egenskap alltid  false . Läs/skriv  boolean .

**Returnerar:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Anger om former på master-bilden ska visas på bilder eller inte. För själva master-bilden returnerar denna egenskap alltid  false . Läs/skriv  boolean .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Returnerar en samling av ritningsguider för master-bilden. Skrivskyddad [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Lägger till den nya vertikala ritningsguiden till höger om bildens centrum
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)