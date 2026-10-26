---
title: PortionFormat
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
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

Tato třída obsahuje vlastnosti formátování textových částí. Na rozdíl od [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) jsou všechny vlastnosti této třídy zapisovatelné.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //Instancujte objekt prezentace, který představuje soubor prezentace
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Aspose.Slides používá tyto speciální identifikátory (podobně jako v PowerPointu):
>      // +mn-lt - Tělo písmo Latin (menší Latin písmo)
>      // +mj-lt -Nadpis písmo Latin (hlavní Latin písmo)
>      // +mn-ea - Tělo písmo East Asian (menší Východoasijské písmo)
>      // +mj-ea - Tělo písmo East Asian (menší Východoasijské písmo)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
```

--------------------

Tato třída se používá k vracení a manipulaci s vlastnostmi formátování textových částí definovanými pro konkrétní část. To znamená, že při získávání hodnot se nepoužije žádná dědičnost, takže ve většině případů obdržíte hodnoty označující „undefined“.

Chcete-li získat efektivní hodnoty parametrů formátování včetně zděděných, musíte použít metodu [getEffective](../../com.aspose.slides/portionformat\#getEffective), která vrací instanci [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | Inicializuje novou instanci třídy [PortionFormat](../../com.aspose.slides/portionformat). |

## Metody

| Metoda | Popis |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Vrací nebo nastavuje identifikátor záložky. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Vrací nebo nastavuje identifikátor záložky. |
| [getSmartTagClean()](#getSmartTagClean--) | Určuje, zda má být smart tag vyčištěn. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Určuje, zda má být smart tag vyčištěn. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Vrací nebo nastavuje hypertextový odkaz definovaný pro přejetí myší. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Vrací nebo nastavuje hypertextový odkaz definovaný pro přejetí myší. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Správce hypertextových odkazů. |
| [getEffective()](#getEffective--) | Získává data efektivního formátování částí s aplikovanou dědičností. |

### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```

Inicializuje novou instanci třídy [PortionFormat](../../com.aspose.slides/portionformat).

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```

Vrací nebo nastavuje identifikátor záložky. Čtení/Zápis String.

**Vrací:**
java.lang.String

### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```

Vrací nebo nastavuje identifikátor záložky. Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```

Určuje, zda má být smart tag vyčištěn. Nepoužita dědičnost. Čtení/Zápis boolean.

**Vrací:**
boolean

### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```

Určuje, zda má být smart tag vyčištěn. Nepoužita dědičnost. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```

Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší. Čtení/Zápis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Vrací:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```

Vrací nebo nastavuje hypertextový odkaz definovaný pro kliknutí myší. Čtení/Zápis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```

Vrací nebo nastavuje hypertextový odkaz definovaný pro přejetí myší. Čtení/Zápis [IHyperlink](../../com.aspose.slides/ihyperlink).

**Vrací:**
[IHyperlink](../../com.aspose.slides/ihyperlink)

### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```

Vrací nebo nastavuje hypertextový odkaz definovaný pro přejetí myší. Čtení/Zápis [IHyperlink](../../com.aspose.slides/ihyperlink).

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

Získává data efektivního formátování částí s aplikovanou dědičností.

--------------------

> ```
> Tento příklad ukazuje získání některých efektivních vlastností formátu části.
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
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) – [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).