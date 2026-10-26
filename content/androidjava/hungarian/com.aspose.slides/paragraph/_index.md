---
title: Paragraph
second_title: Aspose.Slides Androidra vonatkozó Java API-referencia
description: Egy szövegparagrafust reprezentál.
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

Egy szövegparagrafust reprezentál.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Paragraph()](#Paragraph--) | Inicializál egy új Paragraph példányt az alapértelmezett tulajdonságokkal. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Másoló konstruktor, amely egy új Paragraph példányt inicializál. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getPortions()](#getPortions--) | Visszaadja a szövegrészek gyűjteményét. |
| [getParagraphFormat()](#getParagraphFormat--) | Visszaadja ennek a paragrafusnak a formázási objektumát. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Összefűzi a formázásukban azonos futamokat. |
| [getText()](#getText--) | Lekéri vagy beállítja egy paragrafus egyszerű szövegét. |
| [setText(String value)](#setText-java.lang.String-) | Lekéri vagy beállítja egy paragrafus egyszerű szövegét. |
| [getRect()](#getRect--) | Lekéri a paragrafust körülvevő téglalap koordinátáit. |
| [getLinesCount()](#getLinesCount--) | Lekéri egy paragrafus sorainak számát. |
| [getImage()](#getImage--) | Visszaadja a paragrafus képét. |
| [getImage(float scaleX, float scaleY)](#getImage-float-float-) | Visszaadja a paragrafus képét a megadott méretezéssel. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Megadja a rész tulajdonságait, amelyeket akkor kell használni, ha egy másik rész kerül beillesztésre az utolsó után. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Megadja a rész tulajdonságait, amelyeket akkor kell használni, ha egy másik rész kerül beillesztésre az utolsó után. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Visszaadja egy paragrafus szülő diáját. |
| [getPresentation()](#getPresentation--) | Visszaadja egy paragrafus szülő prezentációját. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```


Inicializál egy új Paragraph példányt az alapértelmezett tulajdonságokkal.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```


Másoló konstruktor, amely egy új Paragraph példányt inicializál.

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


Visszaadja ennek a paragrafusnak a formázási objektumát. Csak olvasható [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

A formázási objektum csak az aktuális paragrafusra definiált formázási paramétereket tartalmazza, az örökölt adat nem kerül alkalmazásra.

Az örökölt értékeket is tartalmazó hatékony értékek lekéréséhez használja a [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) metódust.

**Visszatérési érték:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Összefűzi a formázásukban azonos futamokat.

### getText() {#getText--}
```
public final String getText()
```


Lekéri vagy beállítja egy paragrafus egyszerű szövegét. Olvasási/írási String.

Érték: A szöveg.

**Visszatérési érték:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Lekéri vagy beállítja egy paragrafus egyszerű szövegét. Olvasási/írási String.

Érték: A szöveg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```


Lekéri a paragrafust körülvevő téglalap koordinátáit. A téglalap tartalmazza a paragrafus összes szövegsorát, beleértve az üreseket is.

**Visszatérési érték:**
android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```


Lekéri egy paragrafus sorainak számát.

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
int - Sorok száma egy paragrafusban
### getImage() {#getImage--}
```
public final IImage getImage()
```


Visszaadja a paragrafus képét.

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
[IImage](../../com.aspose.slides/iimage) - A renderelt paragrafust tartalmazó kép, vagy null, ha a paragrafus nem található meg a szülő gyűjteményben, nincs érvényes renderelési határa, vagy hiba történt a kép renderelése közben.
### getImage(float scaleX, float scaleY) {#getImage-float-float-}
```
public final IImage getImage(float scaleX, float scaleY)
```


Visszaadja a paragrafus képét a megadott méretezéssel.

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
| scaleX | float | A vízszintes méretezési tényező, amely a paragrafus képre kerül alkalmazásra. |
| scaleY | float | A függőleges méretezési tényező, amely a paragrafus képre kerül alkalmazásra. |

**Visszatérési érték:**
[IImage](../../com.aspose.slides/iimage) - A renderelt paragrafust tartalmazó kép, vagy null, ha a paragrafus nem található meg a szülő gyűjteményben, nincs érvényes renderelési határa, vagy hiba történt a kép renderelése közben.
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```


Megadja a rész tulajdonságait, amelyeket akkor kell használni, ha egy másik rész kerül beillesztésre az utolsó után.

**Visszatérési érték:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```


Megadja a rész tulajdonságait, amelyeket akkor kell használni, ha egy másik rész kerül beillesztésre az utolsó után.

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


Visszaadja egy paragrafus szülő diáját. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatérési érték:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Visszaadja egy paragrafus szülő prezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation)