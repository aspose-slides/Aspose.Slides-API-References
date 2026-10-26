---
title: MasterSlide
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje hlavní snímek v prezentaci.
type: docs
url: /cs/com.aspose.slides/masterslide/
---
**Dědičnost:**  
java.lang.Object, [com.aspose.slides.BaseSlide](../../com.aspose.slides/baseslide)

**Všechna implementovaná rozhraní:**  
[com.aspose.slides.IMasterSlide](../../com.aspose.slides/imasterslide)  
```
public class MasterSlide extends BaseSlide implements IMasterSlide
```

Představuje hlavní snímek v prezentaci.

## Metody

| Metoda | Popis |
| --- | --- |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Vrací správce HeaderFooter hlavního snímku. |
| [applyExternalThemeToDependingSlides(String fname)](#applyExternalThemeToDependingSlides-java.lang.String-) | Vytvoří nový hlavní snímek na základě aktuálního, aplikuje na něj externí motiv a použije vytvořený hlavní snímek na všechny závislé snímky. |
| [getTitleStyle()](#getTitleStyle--) | Vrací styl titulkového textu. |
| [getBodyStyle()](#getBodyStyle--) | Vrací styl těla textu. |
| [getOtherStyle()](#getOtherStyle--) | Vrací styl jiného textu. |
| [getLayoutSlides()](#getLayoutSlides--) | Vrací kolekci podřízených rozložení snímků pro tento hlavní snímek. |
| [getPreserve()](#getPreserve--) | Určuje, zda je odpovídající hlavní snímek smazán, když jsou smazány všechny snímky následující tento hlavní snímek. |
| [setPreserve(boolean value)](#setPreserve-boolean-) | Určuje, zda je odpovídající hlavní snímek smazán, když jsou smazány všechny snímky následující tento hlavní snímek. |
| [getDependingSlides()](#getDependingSlides--) | Vrací pole se všemi snímky, které závisí na tomto hlavním snímku. |
| [hasDependingSlides()](#hasDependingSlides--) | Vrací true, pokud existuje alespoň jeden snímek, který závisí na tomto hlavním snímku. |
| [getThemeManager()](#getThemeManager--) | Vrací správce motivu. |
| [getName()](#getName--) | Vrací nebo nastavuje název hlavního snímku. |
| [setName(String value)](#setName-java.lang.String-) | Vrací nebo nastavuje název hlavního snímku. |
| [getShowMasterShapes()](#getShowMasterShapes--) | Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích nebo ne. |
| [setShowMasterShapes(boolean value)](#setShowMasterShapes-boolean-) | Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích nebo ne. |
| [getDrawingGuides()](#getDrawingGuides--) | Vrací kolekci vodicích čar pro hlavní snímek. |

### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public final IMasterSlideHeaderFooterManager getHeaderFooterManager()
```

Vrací správce HeaderFooter hlavního snímku. Pouze pro čtení [IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager).

**Vrací:**  
[IMasterSlideHeaderFooterManager](../../com.aspose.slides/imasterslideheaderfootermanager)

### applyExternalThemeToDependingSlides(String fname) {#applyExternalThemeToDependingSlides-java.lang.String-}
```
public final IMasterSlide applyExternalThemeToDependingSlides(String fname)
```

Vytvoří nový hlavní snímek na základě aktuálního, aplikuje na něj externí motiv a použije vytvořený hlavní snímek na všechny závislé snímky.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| fname | java.lang.String | Cesta k souboru externího motivu (.thmx). |

**Vrací:**  
[IMasterSlide](../../com.aspose.slides/imasterslide) - Nový tematizovaný MasterSlide.

### getTitleStyle() {#getTitleStyle--}
```
public final ITextStyle getTitleStyle()
```

Vrací styl titulkového textu. Pouze pro čtení [ITextStyle](../../com.aspose.slides/itextstyle).

**Vrací:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getBodyStyle() {#getBodyStyle--}
```
public final ITextStyle getBodyStyle()
```

Vrací styl těla textu. Pouze pro čtení [ITextStyle](../../com.aspose.slides/itextstyle).

**Vrací:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getOtherStyle() {#getOtherStyle--}
```
public final ITextStyle getOtherStyle()
```

Vrací styl jiného textu. Pouze pro čtení [ITextStyle](../../com.aspose.slides/itextstyle).

**Vrací:**  
[ITextStyle](../../com.aspose.slides/itextstyle)

### getLayoutSlides() {#getLayoutSlides--}
```
public final IMasterLayoutSlideCollection getLayoutSlides()
```

Vrací kolekci podřízených rozložení snímků pro tento hlavní snímek. Pouze pro čtení [IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection).

--------------------

K alternativnímu API pro přidávání/vkládání/odstraňování/klonování rozložení snímků můžete přistupovat pomocí vlastnosti ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Vrací:**  
[IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)

### getPreserve() {#getPreserve--}
```
public final boolean getPreserve()
```

Určuje, zda je odpovídající hlavní snímek smazán, když jsou smazány všechny snímky následující tento hlavní snímek. Poznámka: Aspose.Slides nikdy samo neodstraní nepoužívaný hlavní snímek, k jeho skutečnému odstranění zavolejte [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Čtení/Zápis  boolean .

**Vrací:**  
boolean

### setPreserve(boolean value) {#setPreserve-boolean-}
```
public final void setPreserve(boolean value)
```

Určuje, zda je odpovídající hlavní snímek smazán, když jsou smazány všechny snímky následující tento hlavní snímek. Poznámka: Aspose.Slides nikdy samo neodstraní nepoužívaný hlavní snímek, k jeho skutečnému odstranění zavolejte [MasterSlideCollection.removeUnused(boolean)](../../com.aspose.slides/masterslidecollection\#removeUnused-boolean-) Čtení/Zápis  boolean .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getDependingSlides() {#getDependingSlides--}
```
public final ISlide[] getDependingSlides()
```

Vrací pole se všemi snímky, které závisí na tomto hlavním snímku.

**Vrací:**  
com.aspose.slides.ISlide[] - Pole typu [ISlide](../../com.aspose.slides/islide)

### hasDependingSlides() {#hasDependingSlides--}
```
public final boolean hasDependingSlides()
```

Vrací true, pokud existuje alespoň jeden snímek, který závisí na tomto hlavním snímku. Pouze pro čtení  boolean .

**Vrací:**  
boolean

### getThemeManager() {#getThemeManager--}
```
public final IMasterThemeManager getThemeManager()
```

Vrací správce motivu. Pouze pro čtení [IMasterThemeManager](../../com.aspose.slides/imasterthememanager).

**Vrací:**  
[IMasterThemeManager](../../com.aspose.slides/imasterthememanager)

### getName() {#getName--}
```
public String getName()
```

Vrací nebo nastavuje název hlavního snímku. Čtení/Zápis String.

**Vrací:**  
java.lang.String

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```

Vrací nebo nastavuje název hlavního snímku. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getShowMasterShapes() {#getShowMasterShapes--}
```
public boolean getShowMasterShapes()
```

Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích nebo ne. Pro samotný hlavní snímek tato vlastnost vždy vrací  false . Čtení/Zápis  boolean .

**Vrací:**  
boolean

### setShowMasterShapes(boolean value) {#setShowMasterShapes-boolean-}
```
public void setShowMasterShapes(boolean value)
```

Určuje, zda mají být tvary na hlavním snímku zobrazeny na snímcích nebo ne. Pro samotný hlavní snímek tato vlastnost vždy vrací  false . Čtení/Zápis  boolean .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getDrawingGuides() {#getDrawingGuides--}
```
public final IDrawingGuidesCollection getDrawingGuides()
```

Vrací kolekci vodicích čar pro hlavní snímek. Pouze pro čtení [IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      Dimension2D slideSize = pres.getSlideSize().getSize();
> 
>      IDrawingGuidesCollection guides = pres.getMasters().get_Item(0).getDrawingGuides();
>      // Přidání nového svislého vodícího čáry vpravo od středu snímku
>      guides.add(Orientation.Vertical, (float) slideSize.getWidth() / 2 + 20f);
> 
>      pres.save("MasterSlideDrawingGuides_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**  
[IDrawingGuidesCollection](../../com.aspose.slides/idrawingguidescollection)