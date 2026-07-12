---
title: MasterSlide
second_title: Aspose.Slides Androidra Java API hivatkozás
description: Egy prezentációban egy master diát reprezentál.
type: docs
url: /hu/com.aspose.slides/masterslide/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Minden implementált interfész:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

Egy mesterdiát reprezentál egy prezentációban.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a master diára vonatkozó HeaderFooter menedzsert. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Új master diát hoz létre az aktuális alapján, alkalmaz egy külső témát, majd a létrehozott master diát az összes függő diára alkalmazza. |
| [getTitleStyle()](#getTitleStyle--) | Visszaadja a cím szöveg stílusát. |
| [getBodyStyle()](#getBodyStyle--) | Visszaadja a törzsszöveg stílusát. |
| [getOtherStyle()](#getOtherStyle--) | Visszaadja egy másik szöveg stílusát. |
| [getLayoutSlides()](#getLayoutSlides--) | Visszaadja a gyerek elrendezési diák gyűjteményét ehhez a master diához. |
| [getPreserve()](#getPreserve--) | Meghatározza, hogy a megfelelő master törlődik-e, ha a master után következő összes dia törlésre kerül. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Meghatározza, hogy a megfelelő master törlődik-e, ha a master után következő összes dia törlésre kerül. |
| [getDependingSlides()](#getDependingSlides--) | Visszaad egy tömböt minden olyan diával, amely ettől a master diáltól függ. |
| [hasDependingSlides()](#hasDependingSlides--) | Igaz értéket ad vissza, ha létezik legalább egy dia, amely a master diára támaszkodik. |
| [getThemeManager()](#getThemeManager--) | Visszaadja a téma menedzsert. |
| [getName()](#getName--) | Visszaadja vagy beállítja a master dia nevét. |
| [setName(String value)](#setName-java.lang.String-) | Visszaadja vagy beállítja a master dia nevét. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Megadja, hogy a master dián lévő alakzatok megjelenjenek-e a diákon vagy sem. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Megadja, hogy a master dián lévő alakzatok megjelenjenek-e a diákon vagy sem. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszaadja a master diához tartozó rajz útmutatók gyűjteményét. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a master diára vonatkozó HeaderFooter menedzsert. Csak olvasható [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Visszaad:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Új master diát hoz létre az aktuális alapján, alkalmaz egy külső témát, majd a létrehozott master diát az összes függő diára alkalmazza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A külső téma fájl (.thmx) útvonala. |

**Visszaad:**
[IMasterSlide](../../com.aspose.slides/imasterslide) – Új témával ellátott MasterSlide.
### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

Visszaadja a cím szöveg stílusát. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszaad:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

Visszaadja a törzsszöveg stílusát. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszaad:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

Visszaadja egy másik szöveg stílusát. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszaad:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

Visszaadja a gyerek elrendezési diák gyűjteményét ehhez a master diához. Csak olvasható [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Hozzáférhet alternatív API-hoz a elrendezési diák hozzáadásához/beszúrásához/eltávolításához/klónozásához a ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) tulajdonság használatával.

**Visszaad:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

Meghatározza, hogy a megfelelő master törlődik-e, ha a master után következő összes dia törlésre kerül. Megjegyzés: az Aspose.Slides önmagától soha nem távolít el használaton kívüli master-t; a használaton kívüli master-k tényleges eltávolításához hívja meg a [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-). Olvasás/írás  boolean .

**Visszaad:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

Meghatározza, hogy a megfelelő master törlődik-e, ha a master után következő összes dia törlésre kerül. Megjegyzés: az Aspose.Slides önmagától soha nem távolít el használaton kívüli master-t; a használaton kívüli master-k tényleges eltávolításához hívja meg a [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-). Olvasás/írás  boolean .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Visszaad egy tömböt minden olyan diával, amely ettől a master diáltól függ.

**Visszaad:**
com.aspose.slides.ISlide[] – [ISlide](../../com.aspose.slides/islide) tömbje
### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Igaz értéket ad vissza, ha létezik legalább egy dia, amely a master diára támaszkodik. Csak olvasható  boolean .

**Visszaad:**
boolean
### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Visszaadja a téma menedzsert. Csak olvasható [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Visszaad:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)
### getName() {#getName--}
```
public String getName()
```

Visszaadja vagy beállítja a master dia nevét. Olvasás/írás String.

**Visszaad:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Visszaadja vagy beállítja a master dia nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Megadja, hogy a master dián lévő alakzatok megjelenjenek-e a diákon vagy sem. A master diához tartozó esetben ez a tulajdonság mindig  false  értéket ad. Olvasás/írás  boolean .

**Visszaad:**
boolean
### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Megadja, hogy a master dián lévő alakzatok megjelenjenek-e a diákon vagy sem. A master diához tartozó esetben ez a tulajdonság mindig  false  értéket ad. Olvasás/írás  boolean .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Visszaad egy gyűjteményt a master diához tartozó rajz útmutatókból. Csak olvasható [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Az új függőleges rajzútvonal hozzáadása a dia középpontja jobb oldalára
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszaad:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)