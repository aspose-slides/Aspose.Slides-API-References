---
title: IMasterSlide
second_title: Aspose.Slides Java API referencia
description: Egy prezentációban egy mester diát képvisel.
type: docs
url: /hu/com.aspose.slides/imasterslide/
---
**Összes megvalósított interfész:**  
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)  
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Egy prezentációban a mester diát képviseli.

## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a mester dia HeaderFooter menedzserét. |
| [getTitleStyle()](#getTitleStyle--) | Visszaadja a címszöveg stílusát. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Új mester diát hoz létre az aktuális alapján, külső sablont alkalmaz rá, és alkalmazza a létrehozott mester diát az összes függő diára. |
| [getBodyStyle()](#getBodyStyle--) | Visszaadja a törzsszöveg stílusát. |
| [getOtherStyle()](#getOtherStyle--) | Visszaadja egy másik szöveg stílusát. |
| [getLayoutSlides()](#getLayoutSlides--) | Visszaadja a gyermek elrendezési diák gyűjteményét ehhez a mester diához. |
| [getPreserve()](#getPreserve--) | Megállapítja, hogy a megfelelő mester törlésre kerül-e, amikor az összes, a mester után következő dia törlésre kerül. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Megállapítja, hogy a megfelelő mester törlésre kerül-e, amikor az összes, a mester után következő dia törlésre kerül. |
| [hasDependingSlides()](#hasDependingSlides--) | Igaz értéket ad vissza, ha létezik legalább egy dia, amely ettől a mester diától függ. |
| [getDependingSlides()](#getDependingSlides--) | Visszaad egy tömböt az összes diával, amely a mester diától függ. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszaadja a mester dia rajzoló segédvonalainak gyűjteményét. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a mester dia HeaderFooter menedzserét. Csak olvasható [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Visszatérési érték:**  
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

Visszaadja a címszöveg stílusát. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatérési érték:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Új mester diát hoz létre az aktuális alapján, külső sablont alkalmaz rá, és alkalmazza a létrehozott mester diát az összes függő diára.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | Az külső sablon fájl (.thmx) elérési útja. |

**Visszatérési érték:**  
[IMasterSlide](../../com.aspose.slides/imasterslide) - Új tematikus MasterSlide.

### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

Visszaadja a törzsszöveg stílusát. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatérési érték:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

Visszaadja egy másik szöveg stílusát. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatérési érték:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

Visszaadja a gyermek elrendezési diák gyűjteményét ehhez a mester diához. Csak olvasható [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Alternatív API-hoz hozzáférhet a layout diák hozzáadásához/beszúrásához/eltávolításához/klónozásához a ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) tulajdonság használatával.

**Visszatérési érték:**  
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

Megállapítja, hogy a megfelelő mester törlésre kerül-e, amikor az összes, a mester után következő dia törlésre kerül. Megjegyzés: Az Aspose.Slides soha nem távolít el egy használaton kívüli mestert önmagától; a használaton kívüli mesterek tényleges eltávolításához hívja meg [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Olvasás/írás boolean.

**Visszatérési érték:**  
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

Megállapítja, hogy a megfelelő mester törlésre kerül-e, amikor az összes, a mester után következő dia törlésre kerül. Megjegyzés: Az Aspose.Slides soha nem távolít el egy használaton kívüli mestert önmagától; a használaton kívüli mesterek tényleges eltávolításához hívja meg [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Igaz értéket ad vissza, ha létezik legalább egy dia, amely ettől a mester diától függ. Csak olvasható boolean.

**Visszatérési érték:**  
boolean

### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Visszaad egy tömböt az összes diával, amely a mester diától függ.

**Visszatérési érték:**  
com.aspose.slides.ISlide[] - A [ISlide](../../com.aspose.slides/islide) tömbje, amelyek a mester diától függnek.

### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Visszaadja a mester dia rajzoló segédvonalainak gyűjteményét. Csak olvasható [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Új függőleges rajzolósegédvonal hozzáadása a dia középpontjának jobb oldalához
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatérési érték:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)