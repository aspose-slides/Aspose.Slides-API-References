---
title: IParagraph
second_title: Aspose.Slides Java API referencia
description: Egy szöveg bekezdését reprezentálja.
type: docs
url: /hu/com.aspose.slides/iparagraph/
---
**Minden implementált interfész:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Egy szöveg bekezdését reprezentálja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getPortions()](#getPortions--) | Visszaadja a szövegrészek gyűjteményét. |
| [getParagraphFormat()](#getParagraphFormat--) | Visszaadja a formázási objektumot ehhez a bekezdéshez. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Egyesíti a formázásban egyező futamokat. |
| [getText()](#getText--) | Lekéri vagy beállítja a bekezdés egyszerű szövegét. |
| [setText(String value)](#setText-java.lang.String-) | Lekéri vagy beállítja a bekezdés egyszerű szövegét. |
| [getRect()](#getRect--) | Lekéri a bekezdést körülvevő téglalap koordinátáit. |
| [getLinesCount()](#getLinesCount--) | Lekéri a bekezdés sorainak számát. |
| [getImage()](#getImage--) | Visszaadja a bekezdés képét. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Visszaadja a bekezdés képét a megadott méretezéssel. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Megadja a rész tulajdonságait, amelyeket akkor kell használni, ha egy új rész kerül beillesztésre az utolsó után. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Megadja a rész tulajdonságait, amelyeket akkor kell használni, ha egy új rész kerül beillesztésre az utolsó után. |

### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```


Visszaadja a szövegrészek gyűjteményét. Csak olvasható [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Visszatér:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```


Visszaadja a formázási objektumot ehhez a bekezdéshez. Csak olvasható [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Visszatér:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Egyesíti a formázásban egyező futamokat.

### getText() {#getText--}
```
public abstract String getText()
```


Lekéri vagy beállítja a bekezdés egyszerű szövegét. Olvasás/írás String.

Érték: A szöveg.

**Visszatér:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```


Lekéri vagy beállítja a bekezdés egyszerű szövegét. Olvasás/írás String.

Érték: A szöveg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public abstract Rectangle2D.Float getRect()
```


Lekéri a bekezdést körülvevő téglalap koordinátáit. A téglalap tartalmazza a bekezdés összes szövegsorát, beleértve az üres sorokat is.

**Visszatér:**
java.awt.geom.Rectangle2D.Float - A bekezdést körülvevő téglalap java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
```


Lekéri a bekezdés sorainak számát.

--------------------

> ```
> Example:
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide sld = pres.getSlides().get_Item(0);
>      IAutoShape ashp = sld.getShapes().addAutoShape(ShapeType.Rectangle, 150, 75, 150, 50);
>      IParagraph para = ashp.getTextFrame().getParagraphs().get_Item(0);
>      IPortion portion = para.getPortions().get_Item(0);
>      portion.setText("Aspose Paragraph GetLinesCount() Example");
>      System.out.println("Lines Count = " + para.getLinesCount());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
int - Sorok száma egy bekezdésben
### getImage() {#getImage--}
```
public abstract IImage getImage()
```


Visszaadja a bekezdés képét.

--------------------

> ```
> The following example shows how to render a paragraph as an image:
>   
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape = pres.getSlides().get_Item(0).getShapes().addAutoShape(
>          ShapeType.Rectangle, 50, 50, 150, 50);
>      IParagraph paragraph = shape.getTextFrame().getParagraphs().get_Item(0);
>      paragraph.setText("Aspose Paragraph GetImage() Example");
>      IImage paragraphImage = paragraph.getImage();
>      try {
>          paragraphImage.save("paragraph.png");
>      } finally {
>          if (paragraphImage != null) paragraphImage.dispose();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - A megjelenített bekezdést tartalmazó kép, vagy null, ha a bekezdés nem található a szülő gyűjteményben, nincs érvényes megjelenítési határa, vagy hiba lép fel a kép renderelése közben.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public abstract IImage getImage(float scaleX, float scaleY)
```


Visszaadja a bekezdés képét a megadott méretezéssel.

--------------------

> ```
> The following example shows how to render each text box paragraph on a slide as an image with custom scaling:
>   
>  Presentation pres = new Presentation("sample.pptx");
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      int shapeIndex = 0;
>      for (IShape shape : slide.getShapes())
>      {
>          shapeIndex++;
>          if (shape instanceof IAutoShape) {
>              IAutoShape autoShape = (IAutoShape)shape;
>              int paragraphIndex = 0;
>              for (IParagraph paragraph : autoShape.getTextFrame().getParagraphs())
>              {
>                  paragraphIndex++;
>                  IImage paragraphImage = paragraph.getImage(2f, 2f);
>                  try {
>                      if (paragraphImage != null)
>                          paragraphImage.save("shape"+shapeIndex+"_paragraph"+paragraphIndex+".png");
> 
>                  } finally {
>                      if (paragraphImage != null) paragraphImage.dispose();
>                  }
>              }
>          }
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| scaleX | float | A bekezdés képére alkalmazott vízszintes méretezési faktor. |
| scaleY | float | A bekezdés képére alkalmazott függőleges méretezési faktor. |

**Visszatér:**
[IImage](../../com.aspose.slides/iimage) - A megjelenített bekezdést tartalmazó kép, vagy null, ha a bekezdés nem található a szülő gyűjteményben, nincs érvényes megjelenítési határa, vagy hiba lép fel a kép renderelése közben.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```


Megadja a rész tulajdonságait, amelyeket akkor kell használni, ha egy új rész kerül beillesztésre az utolsó után.

**Visszatér:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```


Megadja a rész tulajdonságait, amelyeket akkor kell használni, ha egy új rész kerül beillesztésre az utolsó után.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |