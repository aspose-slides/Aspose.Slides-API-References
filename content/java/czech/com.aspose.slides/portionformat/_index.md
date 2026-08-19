---
title: PortionFormat
second_title: Aspose.Slides pro Java API Reference
description: Tato třída obsahuje vlastnosti formátování textových částí.
type: docs
url: /cs/com.aspose.slides/portionformat/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Všechny implementované rozhraní:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

Třída obsahuje vlastnosti formátování textových částí. Na rozdíl od [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //Vytvořte objekt prezentace, který představuje soubor prezentace
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides používá tyto speciální identifikátory (podobně jako v PowerPointu):
>      // +mn-lt - Písmo těla Latin (Minor Latin Font)
>      // +mj-lt - Písmo nadpisu Latin (Major Latin Font)
>      // +mn-ea - Písmo těla East Asian (Minor East Asian Font)
>      // +mj-ea - Písmo těla East Asian (Minor East Asian Font)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování textových částí definovanými pro konkrétní část. To znamená, že při získávání hodnot se nepoužije dědičnost, takže ve většině případů získáte hodnoty označující „undefined“.

Pro získání efektivních hodnot parametrů formátování včetně zděděných je potřeba použít metodu [getEffective](../../com.aspose.slides/portionformat\#getEffective), která vrací instance [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | Inicializuje novou instanci třídy [PortionFormat](../../com.aspose.slides/portionformat). |
## Metody

| Metoda | Popis |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Vrací nebo nastavuje identifikátor záložky. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Vrací nebo nastavuje identifikátor záložky. |
| [getSmartTagClean()](#getSmartTagClean--) | Určuje, zda má být inteligentní značka vyčištěna. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Určuje, zda má být inteligentní značka vyčištěna. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Vrací nebo nastavuje hypertextový odkaz definovaný pro přechod myší. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Vrací nebo nastavuje hypertextový odkaz definovaný pro přechod myší. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Správce hypertextových odkazů. |
| [getEffective()](#getEffective--) | Získá efektivní data formátování částí s aplikovanou dědičností. |
### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```


Inicializuje novou instanci třídy [PortionFormat](../../com.aspose.slides/portionformat).

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```


Vrací nebo nastavuje identifikátor záložky. Čtení/zápis String.

**Vrací:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```


Vrací nebo nastavuje identifikátor záložky. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```


Určuje, zda má být inteligentní značka vyčištěna. Není použita dědičnost. Čtení/zápis boolean .

**Vrací:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```


Určuje, zda má být inteligentní značka vyčištěna. Není použita dědičnost. Čtení/zápis boolean .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```


Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší. Čtení/zápis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Vrací:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```


Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší. Čtení/zápis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```


Vrací nebo nastavuje hypertextový odkaz definovaný pro přechod myší. Čtení/zápis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Vrací:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```


Vrací nebo nastavuje hypertextový odkaz definovaný pro přechod myší. Čtení/zápis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```


Správce hypertextových odkazů. Pouze pro čtení [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Vrací:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```


Získá efektivní data formátování částí s aplikovanou dědičností.

--------------------

> ```
> This example demonstrates getting some effective portion format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>  	IPortionFormatEffectiveData effectivePortionFormat = shape.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getEffective();
>  	System.out.println("Latin font: " + effectivePortionFormat.getLatinFont().getFontName());
>  	System.out.println("Font height: " + effectivePortionFormat.getFontHeight());
>  	System.out.println("Fill type: " + effectivePortionFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).