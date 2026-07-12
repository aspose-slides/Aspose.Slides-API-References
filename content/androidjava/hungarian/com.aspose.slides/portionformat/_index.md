---
title: PortionFormat
second_title: Aspose.Slides Androidhoz a Java API hivatkozás
description: Ez az osztály a szövegrész formázási tulajdonságait tartalmazza.
type: docs
url: /hu/com.aspose.slides/portionformat/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.BasePortionFormat](../../com.aspose.slides/baseportionformat)

**Minden megvalósított interfész:**
[com.aspose.slides.IPortionFormat](../../com.aspose.slides/iportionformat)
```
public final class PortionFormat extends BasePortionFormat implements IPortionFormat
```

Ez az osztály a szövegrész formázási tulajdonságait tartalmazza. A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)-től eltérően az osztály minden tulajdonsága írható.

--------------------

> ```
> The following examples shows you how to assign the Latin font to a Paragraph's portion of PowerPoint Presentation.
>  
>  //Létrehoz egy prezentáció objektumot, amely egy prezentációs fájlt reprezentál
>  Presentation pres = new Presentation("demo.pptx");
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 10, 100, 100);
>      Paragraph paragraph = new Paragraph();
>      Portion portion = new Portion("Theme text format");
>      paragraph.getPortions().add(portion);
>      shape.getTextFrame().getParagraphs().add(paragraph);
>      // Az Aspose.Slides ezeket a speciális azonosítókat használja (hasonlóan a PowerPointban használtakhoz):
>      // +mn-lt - Test betűtípusa Latin (Kisebb Latin Betűtípus)
>      // +mj-lt -Címsor betűtípusa Latin (Nagy Latin Betűtípus)
>      // +mn-ea - Test betűtípusa Kelet-Ázsiai (Kisebb Kelet-Ázsiai Betűtípus)
>      // +mj-ea - Test betűtípusa Kelet-Ázsiai (Kisebb Kelet-Ázsiai Betűtípus)
>      portion.getPortionFormat().setLatinFont(new FontData("+mn-lt"));
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


--------------------

Ez az osztály a konkrét részhez meghatározott szövegrész formázási tulajdonságok visszaadására és manipulálására szolgál. Ez azt jelenti, hogy értékek lekérésekor nem alkalmazódik öröklődés, ezért a legtöbb esetben olyan értékeket kapunk, amelyek "undefined" jelentésűek.

Az öröklődéssel együtt a hatékony formázási paraméterértékek lekéréséhez használni kell a [getEffective](../../com.aspose.slides/portionformat\#getEffective) metódust, amely egy [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) példányt ad vissza.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [PortionFormat()](#PortionFormat--) | Új példányt inicializál a [PortionFormat](../../com.aspose.slides/portionformat) osztályban. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getBookmarkId()](#getBookmarkId--) | Visszaadja vagy beállítja a könyvjelző azonosítóját. |
| [setBookmarkId(String value)](#setBookmarkId-java.lang.String-) | Visszaadja vagy beállítja a könyvjelző azonosítóját. |
| [getSmartTagClean()](#getSmartTagClean--) | Megállapítja, hogy a smart tag-et tisztítani kell-e. |
| [setSmartTagClean(boolean value)](#setSmartTagClean-boolean-) | Megállapítja, hogy a smart tag-et tisztítani kell-e. |
| [getHyperlinkClick()](#getHyperlinkClick--) | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. |
| [setHyperlinkClick(IHyperlink value)](#setHyperlinkClick-com.aspose.slides.IHyperlink-) | Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. |
| [getHyperlinkMouseOver()](#getHyperlinkMouseOver--) | Visszaadja vagy beállítja az egérmutatásra definiált hiperhivatkozást. |
| [setHyperlinkMouseOver(IHyperlink value)](#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-) | Visszaadja vagy beállítja az egérmutatásra definiált hiperhivatkozást. |
| [getHyperlinkManager()](#getHyperlinkManager--) | Hiperhivatkozások kezelője. |
| [getEffective()](#getEffective--) | Lekéri a hatékony szövegrész formázási adatokat az öröklődés alkalmazásával. |
### PortionFormat() {#PortionFormat--}
```
public PortionFormat()
```


Új példányt inicializál a [PortionFormat](../../com.aspose.slides/portionformat) osztályban.

### getBookmarkId() {#getBookmarkId--}
```
public final String getBookmarkId()
```


Visszaadja vagy beállítja a könyvjelző azonosítóját. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setBookmarkId(String value) {#setBookmarkId-java.lang.String-}
```
public final void setBookmarkId(String value)
```


Visszaadja vagy beállítja a könyvjelző azonosítóját. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getSmartTagClean() {#getSmartTagClean--}
```
public final boolean getSmartTagClean()
```


Megállapítja, hogy a smart tag-et tisztítani kell-e. Nincs öröklődés alkalmazva. Olvasás/írás boolean.

**Visszatér:**
boolean
### setSmartTagClean(boolean value) {#setSmartTagClean-boolean-}
```
public final void setSmartTagClean(boolean value)
```


Megállapítja, hogy a smart tag-et tisztítani kell-e. Nincs öröklődés alkalmazva. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinkClick() {#getHyperlinkClick--}
```
public final IHyperlink getHyperlinkClick()
```


Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [IHyperlink](../../com.aspose.slides/ihyperlink).

**Visszatér:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkClick(IHyperlink value) {#setHyperlinkClick-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkClick(IHyperlink value)
```


Visszaadja vagy beállítja az egérkattintásra definiált hiperhivatkozást. Olvasás/írás [IHyperlink](../../com.aspose.slides/ihyperlink).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkMouseOver() {#getHyperlinkMouseOver--}
```
public final IHyperlink getHyperlinkMouseOver()
```


Visszaadja vagy beállítja az egérmutatásra definiált hiperhivatkozást. Olvasás/írás [IHyperlink](../../com.aspose.slides/ihyperlink).

**Visszatér:**
[IHyperlink](../../com.aspose.slides/ihyperlink)
### setHyperlinkMouseOver(IHyperlink value) {#setHyperlinkMouseOver-com.aspose.slides.IHyperlink-}
```
public final void setHyperlinkMouseOver(IHyperlink value)
```


Visszaadja vagy beállítja az egérmutatásra definiált hiperhivatkozást. Olvasás/írás [IHyperlink](../../com.aspose.slides/ihyperlink).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IHyperlink](../../com.aspose.slides/ihyperlink) |  |

### getHyperlinkManager() {#getHyperlinkManager--}
```
public final IHyperlinkManager getHyperlinkManager()
```


Hiperhivatkozások kezelője. Csak olvasható [IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager).

**Visszatér:**
[IHyperlinkManager](../../com.aspose.slides/ihyperlinkmanager)
### getEffective() {#getEffective--}
```
public final IPortionFormatEffectiveData getEffective()
```


Lekéri a hatékonic szövegrész formázási adatokat az öröklődés alkalmazásával.

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


**Visszatér:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata) - A [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).