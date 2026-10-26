---
title: Paragraph
second_title: Aspose.Slides for Java API referencia
description: Egy szövegbekezdés.
type: docs
url: /hu/com.aspose.slides/paragraph/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

Egy szövegbekezdés.
## Constructors

| Konstruktor | Leírás |
| --- | --- |
| [Paragraph()](#Paragraph--) | Inicializál egy új példányt a Paragraph osztályból az alapértelmezett tulajdonságokkal. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Másoló konstruktor, amely egy új példányt inicializál a Paragraph osztályból. |
## Methods

| Metódus | Leírás |
| --- | --- |
| [getPortions()](#getPortions--) | Visszaadja a szövegrészek gyűjteményét. |
| [getParagraphFormat()](#getParagraphFormat--) | Visszaadja ennek a bekezdésnek a formázási objektumát. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Összefűzi a futamokat azonos formázással. |
| [getText()](#getText--) | Lekéri vagy beállítja a bekezdés egyszerű szövegét. |
| [setText(String value)](#setText-java.lang.String-) | Lekéri vagy beállítja a bekezdés egyszerű szövegét. |
| [getRect()](#getRect--) | Lekéri a bekezdést körülvevő téglalap koordinátáit. |
| [getLinesCount()](#getLinesCount--) | Lekéri a bekezdés sorainak számát. |
| [getImage()](#getImage--) | Visszaadja a bekezdés képét. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Visszaadja a bekezdés képét a megadott mérettel. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Meghatározza a részegység tulajdonságait, amelyeket használni kell, ha egy új részegységet illesztünk be az utolsó után. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Meghatározza a részegység tulajdonságait, amelyeket használni kell, ha egy új részegységet illesztünk be az utolsó után. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Visszaadja a bekezdés szülő diáit. |
| [getPresentation()](#getPresentation--) | Visszaadja a bekezdés szülő prezentációját. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Inicializál egy új példányt a Paragraph osztályból az alapértelmezett tulajdonságokkal.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

Másoló konstruktor, amely egy új példányt inicializál a Paragraph osztályból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```

Visszaadja a szövegrészek gyűjteményét. Csak olvasható [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Visszatérési érték:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```

Visszaadja ennek a bekezdésnek a formázási objektumát. Csak olvasható [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

A formázási objektum csak az aktuális bekezdéshez definiált formázási paramétereket tartalmazza, a örökölt adatok nem kerülnek alkalmazásra.

Az örökölt értékeket is tartalmazó hatékony értékek lekéréséhez használja a [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) metódust.

**Visszatérési érték:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Összefűzi a futamokat azonos formázással.

### getText() {#getText--}
```
public final String getText()
```

Lekéri vagy beállítja a bekezdés egyszerű szövegét. Olvasható/írható String.

Érték: A szöveg.

**Visszatérési érték:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Lekéri vagy beállítja a bekezdés egyszerű szövegét. Olvasható/írható String.

Érték: A szöveg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final Rectangle2D.Float getRect()
```

Lekéri a bekezdést körülvevő téglalap koordinátáit. A téglalap tartalmazza a bekezdés összes szövegsorát, beleértve az üres sorokat is.

**Visszatérési érték:**
java.awt.geom.Rectangle2D.Float
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
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

**Visszatérési érték:**
int - A bekezdés sorainak száma
### getImage() {#getImage--}
```
public final IImage getImage()
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

**Visszatérési érték:**
[IImage](../../com.aspose.slides/iimage) - Egy kép, amely a megjelenített bekezdést tartalmazza, vagy null, ha a bekezdés nem található meg a szülő gyűjteményben, nincs érvényes megjelenítési határa, vagy hiba lép fel a kép megjelenítése közben.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```

Visszaadja a bekezdés képét a megadott mérettel.

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
| scaleX | float | A bekezdés képre alkalmazott vízszintes méretezési tényező. |
| scaleY | float | A bekezdés képre alkalmazott függőleges méretezési tényező. |

**Visszatérési érték:**
[IImage](../../com.aspose.slides/iimage) - Egy kép, amely a megjelenített bekezdést tartalmazza, vagy null, ha a bekezdés nem található meg a szülő gyűjteményben, nincs érvényes megjelenítési határa, vagy hiba lép fel a kép megjelenítése közben.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

Meghatározza a részegység tulajdonságait, amelyeket használni kell, ha egy új részegységet illesztünk be az utolsó után.

**Visszatérési érték:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

Meghatározza a részegység tulajdonságait, amelyeket használni kell, ha egy új részegységet illesztünk be az utolsó után.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Visszaadja a Parent_Immediate objektumot. Csak olvasható IDOMObject.

**Visszatérési érték:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```

Visszaadja a bekezdés szülő diaját. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatérési érték:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a bekezdés szülő prezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation)