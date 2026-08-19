---
title: IMasterSlide
second_title: Aspose.Slides pro Java – referenční příručka API
description: Reprezentuje hlavní snímek v prezentaci.
type: docs
url: /cs/com.aspose.slides/imasterslide/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Reprezentuje hlavní snímek v prezentaci.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací správce HeaderFooter hlavního snímku. |
| [getTitleStyle()](#getTitleStyle--) | Vrací styl textu titulu. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Vytvoří nový hlavní snímek na základě aktuálního, aplikuje na něj externí motiv a použije vytvořený hlavní snímek na všechny závislé snímky. |
| [getBodyStyle()](#getBodyStyle--) | Vrací styl těla textu. |
| [getOtherStyle()](#getOtherStyle--) | Vrací styl jiného textu. |
| [getLayoutSlides()](#getLayoutSlides--) | Vrací kolekci podřízených rozvržovacích snímků pro tento hlavní snímek. |
| [getPreserve()](#getPreserve--) | Určuje, zda je odpovídající hlavní snímek smazán, když jsou smazány všechny snímky následující tento hlavní snímek. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Určuje, zda je odpovídající hlavní snímek smazán, když jsou smazány všechny snímky následující tento hlavní snímek. |
| [hasDependingSlides()](#hasDependingSlides--) | Vrací true, pokud existuje alespoň jeden snímek, který závisí na tomto hlavním snímku. |
| [getDependingSlides()](#getDependingSlides--) | Vrací pole se všemi snímky, které závisí na tomto hlavním snímku. |
| [getDrawingGuides()](#getDrawingGuides--) | Vrací kolekci návodů pro kreslení pro hlavní snímek. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Vrací správce HeaderFooter hlavního snímku. Pouze pro čtení [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Vrací:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```

Vrací styl textu titulu. Pouze pro čtení [ITextStyle](../../com.aspose.slides/itextstyle).

**Vrací:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Vytvoří nový hlavní snímek na základě aktuálního, aplikuje na něj externí motiv a použije vytvořený hlavní snímek na všechny závislé snímky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | java.lang.String | Cesta k souboru externího motivu (.thmx). |

**Vrací:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - Nový motivovaný MasterSlide.
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```

Vrací styl těla textu. Pouze pro čtení [ITextStyle](../../com.aspose.slides/itextstyle).

**Vrací:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```

Vrací styl jiného textu. Pouze pro čtení [ITextStyle](../../com.aspose.slides/itextstyle).

**Vrací:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```

Vrací kolekci podřízených rozvržovacích snímků pro tento hlavní snímek. Pouze pro čtení [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

Můžete přistupovat k alternativnímu API pro přidávání/vkládání/odstraňování/klonování rozvržovacích snímků pomocí vlastnosti ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Vrací:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```

Určuje, zda je odpovídající hlavní snímek smazán, když jsou smazány všechny snímky následující tento hlavní snímek. Poznámka: Aspose.Slides nikdy neodstraní žádný nepoužívaný hlavní snímek automaticky; pro skutečné odstranění nepoužívaných hlavních snímků zavolejte [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Čtení/zápis boolean.

**Vrací:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```

Určuje, zda je odpovídající hlavní snímek smazán, když jsou smazány všechny snímky následující tento hlavní snímek. Poznámka: Aspose.Slides nikdy neodstraní žádný nepoužívaný hlavní snímek automaticky; pro skutečné odstranění nepoužívaných hlavních snímků zavolejte [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```

Vrací true, pokud existuje alespoň jeden snímek, který závisí na tomto hlavním snímku. Pouze pro čtení boolean.

**Vrací:**
boolean
### getDependingSlides() {#getDependingSlides--}
```
public abstract ISlide[] getDependingSlides()
```

Vrací pole se všemi snímky, které závisí na tomto hlavním snímku.

**Vrací:**
com.aspose.slides.ISlide[] - Pole [ISlide](../../com.aspose.slides/islide), které závisí na tomto hlavním snímku
### getDrawingGuides() {#getDrawingGuides--}
```
public abstract IDrawingGuidesCollection getDrawingGuides()
```

Vrací kolekci návodů pro kreslení pro hlavní snímek. Pouze pro čtení [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Přidání nového vertikálního kreslicího vodítka napravo od středu snímku
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)