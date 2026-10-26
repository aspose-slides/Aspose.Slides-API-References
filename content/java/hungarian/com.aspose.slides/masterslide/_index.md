---
title: MasterSlide
second_title: Aspose.Slides Java API referencia
description: Egy prezentáció mesterdiáját reprezentálja.
type: docs
url: /hu/com.aspose.slides/masterslide/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Minden megvalósított interfész:**
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

Egy mesterdia a prezentációban képviselője.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a mesterdia HeaderFooter kezelőjét. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Létrehoz egy új mesterdiát a jelenlegi alapján, külső témát alkalmaz rá, és a létrehozott mesterdiát minden függő diára alkalmazza. |
| [getTitleStyle()](#getTitleStyle--) | Visszaadja a címszöveg stílusát. |
| [getBodyStyle()](#getBodyStyle--) | Visszaadja a törzsszöveg stílusát. |
| [getOtherStyle()](#getOtherStyle--) | Visszaadja egy egyéb szöveg stílusát. |
| [getLayoutSlides()](#getLayoutSlides--) | Visszaadja ennek a mesterdiának a gyermek elrendezési diák gyűjteményét. |
| [getPreserve()](#getPreserve--) | Megállapítja, hogy a megfelelő mester törlésre kerül-e, amikor a mester után következő összes dia törlésre kerül. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Megállapítja, hogy a megfelelő mester törlésre kerül-e, amikor a mester után következő összes dia törlésre kerül. |
| [getDependingSlides()](#getDependingSlides--) | Visszaad egy tömböt az összes diával, amelyek e mesterdiától függenek. |
| [hasDependingSlides()](#hasDependingSlides--) | Igaz értéket ad vissza, ha létezik legalább egy dia, amely e mesterdiától függ. |
| [getThemeManager()](#getThemeManager--) | Visszaadja a téma kezelőt. |
| [getName()](#getName--) | Visszaadja vagy beállítja egy mesterdia nevét. |
| [setName(String value)](#setName-java.lang.String-) | Visszaadja vagy beállítja egy mesterdia nevét. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Megadja, hogy a mesterdián lévő alakzatok megjelenjenek-e a diákon vagy sem. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Megadja, hogy a mesterdián lévő alakzatok megjelenjenek-e a diákon vagy sem. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszaadja a mesterdia rajzoló segédvonalak gyűjteményét. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a mesterdia HeaderFooter kezelőjét. Csak olvasható [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Visszatérési érték:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Létrehoz egy új mesterdiát a jelenlegi alapján, külső témát alkalmaz rá, és a létrehozott mesterdiát minden függő diára alkalmazza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | Külső téma fájl (.thmx) elérési útja. |

**Visszatérési érték:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Új témázott MasterSlide.

### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

Visszaadja a címszöveg stílusát. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatérési érték:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

Visszaadja a törzsszöveg stílusát. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatérési érték:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

Visszaadja egy egyéb szöveg stílusát. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatérési érték:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

Visszaadja ennek a mesterdiának a gyermek elrendezési diák gyűjteményét. Csak olvasható [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Alternatív API-hez hozzáférhet a layout diák hozzáadásához/beillesztéséhez/eltávolításához/klónozásához a ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) tulajdonság használatával.

**Visszatérési érték:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

Megállapítja, hogy a megfelelő mester törlésre kerül-e, amikor a mester után következő összes dia törlésre kerül. Megjegyzés: az Aspose.Slides soha nem távolít el egy nem használt mestert magától; a nem használt mesterek tényleges eltávolításához hívja a [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) metódust. Olvasás/írás  boolean .

**Visszatérési érték:**
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

Megállapítja, hogy a megfelelő mester törlésre kerül-e, amikor a mester után következő összes dia törlésre kerül. Megjegyzés: az Aspose.Slides soha nem távolít el egy nem használt mestert magától; a nem használt mesterek tényleges eltávolításához hívja a [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) metódust. Olvasás/írás  boolean .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Visszaad egy tömböt az összes diával, amelyek e mesterdiától függenek.

**Visszatérési érték:**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) tömbje

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Igaz értéket ad vissza, ha létezik legalább egy dia, amely e mesterdiától függ. Csak olvasható  boolean .

**Visszatérési érték:**
boolean

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Visszaadja a téma kezelőt. Csak olvasható [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Visszatérési érték:**
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getName() {#getName--}
```
public String getName()
```

Visszaadja vagy beállítja egy mesterdia nevét. Olvasás/írás String.

**Visszatérési érték:**
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Visszaadja vagy beállítja egy mesterdia nevét. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Megadja, hogy a mesterdián lévő alakzatok megjelenjenek-e a diákon vagy sem. A mesterdia esetében ez a tulajdonság mindig false értéket ad vissza. Olvasás/írás  boolean .

**Visszatérési érték:**
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Megadja, hogy a mesterdián lévő alakzatok megjelenjenek-e a diákon vagy sem. A mesterdia esetében ez a tulajdonság mindig false értéket ad vissza. Olvasás/írás  boolean .

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Visszaadja a mesterdia rajzolási segédvonalak gyűjteményét. Csak olvasható [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Az új függőleges rajzolási segédvonal hozzáadása a dia középpontjának jobb oldalához
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)