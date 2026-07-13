---
title: IMasterSlide
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje hlavní snímek v prezentaci.
type: docs
url: /cs/com.aspose.slides/imasterslide/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBaseSlide](../../com.aspose.slides/ibaseslide), [com.aspose.slides.IMasterThemeable](../../com.aspose.slides/imasterthemeable)
```
public interface IMasterSlide extends IBaseSlide, IMasterThemeable
```

Represents a master slide in a presentation.
## Metody

| Metoda | Popis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací správce HeaderFooter hlavního snímku. |
| [getTitleStyle()](#getTitleStyle--) | Vrací styl textu titulku. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Vytvoří nový hlavní snímek na základě aktuálního, použije na něj externí motiv a použije vytvořený hlavní snímek pro všechny závislé snímky. |
| [getBodyStyle()](#getBodyStyle--) | Vrací styl těla textu. |
| [getOtherStyle()](#getOtherStyle--) | Vrací styl jiného textu. |
| [getLayoutSlides()](#getLayoutSlides--) | Vrací kolekci podřízených rozložení snímků pro tento hlavní snímek. |
| [getPreserve()](#getPreserve--) | Určuje, zda je odpovídající hlavní snímek smazán, když jsou smazány všechny snímky, které tento hlavní snímek následují. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Určuje, zda je odpovídající hlavní snímek smazán, když jsou smazány všechny snímky, které tento hlavní snímek následují. |
| [hasDependingSlides()](#hasDependingSlides--) | Vrací true, pokud existuje alespoň jeden snímek, který závisí na tomto hlavním snímku. |
| [getDependingSlides()](#getDependingSlides--) | Vrací pole se všemi snímky, které závisí na tomto hlavním snímku. |
| [getDrawingGuides()](#getDrawingGuides--) | Vrací kolekci kreslicích vodítek pro hlavní snímek. |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IMasterSlideHeaderFooterManager getHeaderFooterManager()
```


Vrací správce HeaderFooter hlavního snímku. Jen pro čtení [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Vrací:**
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)
### getTitleStyle() {#getTitleStyle--}
```
public abstract ITextStyle getTitleStyle()
```


Vrací styl textu titulku. Jen pro čtení [ITextStyle](../../com.aspose.slides/itextstyle).

**Vrací:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public abstract IMasterSlide applyExternalThemeToDependingSlides(String fname)
```


Vytvoří nový hlavní snímek na základě aktuálního, použije na něj externí motiv a použije vytvořený hlavní snímek pro všechny závislé snímky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | java.lang.String | Cesta k souboru externího motivu (.thmx). |

**Vrací:**
[IMasterSlide](../../com.aspose.slides/imasterslide) - New themed MasterSlide.
### getBodyStyle() {#getBodyStyle--}
```
public abstract ITextStyle getBodyStyle()
```


Vrací styl těla textu. Jen pro čtení [ITextStyle](../../com.aspose.slides/itextstyle).

**Vrací:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getOtherStyle() {#getOtherStyle--}
```
public abstract ITextStyle getOtherStyle()
```


Vrací styl jiného textu. Jen pro čtení [ITextStyle](../../com.aspose.slides/itextstyle).

**Vrací:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IMasterLayoutSlideCollection getLayoutSlides()
```


Vrací kolekci podřízených rozložení snímků pro tento hlavní snímek. Jen pro čtení [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

K alternativnímu API pro přidávání/vkládání/odstraňování/klonování rozložení snímků můžete přistupovat pomocí vlastnosti ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Vrací:**
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
### getPreserve() {#getPreserve--}
```
public abstract boolean getPreserve()
```


Určuje, zda je odpovídající hlavní snímek smazán, když jsou smazány všechny snímky, které tento hlavní snímek následují. Poznámka: Aspose.Slides nikdy neodstraní nepoužívaný hlavní snímek sám, pro skutečné odstranění nepoužívaných hlavních snímků zavolejte [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Čtení/zápis boolean.

**Vrací:**
boolean
### setPreserve(boolean value) {#setPreserve-boolean-}
```
public abstract void setPreserve(boolean value)
```


Určuje, zda je odpovídající hlavní snímek smazán, když jsou smazány všechny snímky, které tento hlavní snímek následují. Poznámka: Aspose.Slides nikdy neodstraní nepoužívaný hlavní snímek sám, pro skutečné odstranění nepoužívaných hlavních snímků zavolejte [IMasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/imasterslidecollection\#removeUnused-boolean-) Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### hasDependingSlides() {#hasDependingSlides--}
```
public abstract boolean hasDependingSlides()
```


Vrací true, pokud existuje alespoň jeden snímek, který závisí na tomto hlavním snímku. Jen pro čtení boolean.

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


Vrací kolekci kreslicích vodítek pro hlavní snímek. Jen pro čtení [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      SizeF slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Přidání nového svislého kreslicího vodítka napravo od středu snímku
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)