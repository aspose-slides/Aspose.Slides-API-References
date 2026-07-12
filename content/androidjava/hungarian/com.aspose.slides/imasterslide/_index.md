---
title: IMasterSlide
second_title: Aspose.Slides Androidra a Java API-referencia
description: Egy prezentáció master-diáját képviseli.
type: docs
url: /hu/com.aspose.slides/imasterslide/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Egy master-diát képvisel egy prezentációban.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Visszaadja a master dia HeaderFooter kezelőjét. |
| [getTitleStyle()](#getTitleStyle--) | Visszaadja egy cím szöveg stílusát. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Létrehoz egy új master-diat a jelenlegi alapján, alkalmaz egy külső témát rá, és a létrehozott master-diat minden függő diára alkalmazza. |
| [getBodyStyle()](#getBodyStyle--) | Visszaadja a törzsszöveg stílusát. |
| [getOtherStyle()](#getOtherStyle--) | Visszaadja egy másik szöveg stílusát. |
| [getLayoutSlides()](#getLayoutSlides--) | Visszaadja a gyermek elrendezési diák gyűjteményét ehhez a master diához. |
| [getPreserve()](#getPreserve--) | Meghatározza, hogy a megfelelő master törlésre kerül-e, ha az összes, azt követő dia törlésre kerül. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Meghatározza, hogy a megfelelő master törlésre kerül-e, ha az összes, azt követő dia törlésre kerül. |
| [hasDependingSlides()](#hasDependingSlides--) | Igaz értéket ad vissza, ha létezik legalább egy dia, amely függ a master diától. |
| [getDependingSlides()](#getDependingSlides--) | Visszaad egy tömböt az összes olyan diával, amely függ a master diától. |
| [getDrawingGuides()](#getDrawingGuides--) | Visszaad egy gyűjteményt a master dia rajzoló útmutatóiról. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Visszaadja a master dia HeaderFooter kezelőjét. Csak olvasható [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Visszatér:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

Visszaadja egy cím szöveg stílusát. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatér:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Létrehoz egy új master-diat a jelenlegi alapján, alkalmaz egy külső témát rá, és a létrehozott master-diat minden függő diára alkalmazza.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| fname | java.lang.String | A külső témafájl (.thmx) elérési útja. |

**Visszatér:**
[IMasterSlide](../../com.aspose.slides/imasterslide) – Új témával ellátott MasterSlide.
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

Visszaadja a törzsszöveg stílusát. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatér:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

Visszaadja egy másik szöveg stílusát. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatér:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

Visszaadja a gyermek elrendezési diák gyűjteményét ehhez a master diához. Csak olvasható [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

A layout-diák hozzáadásához/beszúrásához/eltávolításához/klónozásához alternatív API-hoz a ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) tulajdonság használatával férhet hozzá.

**Visszatér:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

Meghatározza, hogy a megfelelő master törlésre kerül-e, ha az összes, azt követő dia törlésre kerül. Megjegyzés: az Aspose.Slides soha nem távolít el egyetlen használaton kívüli master-t sem magától, a használaton kívüli master-k tényleges eltávolításához hívja meg a [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Olvasás/írás boolean értéket.

**Visszatér:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

Meghatározza, hogy a megfelelő master törlésre kerül-e, ha az összes, azt követő dia törlésre kerül. Megjegyzés: az Aspose.Slides soha nem távolít el egyetlen használaton kívüli master-t sem magától, a használaton kívüli master-k tényleges eltávolításához hívja meg a [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Olvasás/írás boolean értéket.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Igaz értéket ad vissza, ha létezik legalább egy dia, amely függ a master diától. Csak olvasható boolean.

**Visszatér:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Visszaad egy tömböt az összes olyan diával, amely függ a master diától.

**Visszatér:**
com.aspose.slides.ISlide[] - [ISlide](../../com.aspose.slides/islide) tömbje, amely a master diától függ
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Visszaad egy gyűjteményt a master dia rajzoló útmutatóiról. Csak olvasható [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Új függőleges rajzoló útmutató hozzáadása a dia középpontjának jobb oldalához
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)