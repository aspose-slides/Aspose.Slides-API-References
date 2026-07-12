---
title: Paragraph
second_title: Aspose.Slides Androidra Java API hivatkozás
description: Egy szövegbeli bekezdést ábrázol.
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

Egy szövegbeli bekezdést reprezentál.

## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [Paragraph()](#Paragraph--) | Új példányt hoz létre a Paragraph osztályból alapértelmezett tulajdonságokkal. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Másoló konstruktor, amely új példányt hoz létre a Paragraph osztályból. |

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getPortions()](#getPortions--) | Visszaadja a szövegrészek gyűjteményét. |
| [getParagraphFormat()](#getParagraphFormat--) | Visszaadja a formázási objektumot ehhez a bekezdéshez. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Összevonja a hasonló formázású futamokat. |
| [getText()](#getText--) | Lekéri vagy beállítja egy bekezdés egyszerű szövegét. |
| [setText(String value)](#setText-java.lang.String-) | Lekéri vagy beállítja egy bekezdés egyszerű szövegét. |
| [getRect()](#getRect--) | Lekéri a bekezdést körülvevő téglalap koordinátáit. |
| [getLinesCount()](#getLinesCount--) | Lekéri egy bekezdés sorainak számát. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Megadja a rész tulajdonságait, amelyeket egy újabb rész beillesztése után használnak. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Megadja a rész tulajdonságait, amelyeket egy újabb rész beillesztése után használnak. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Visszaadja a bekezdés szülő diavetételt. |
| [getPresentation()](#getPresentation--) | Visszaadja a bekezdés szülő prezentációját. |

### Paragraph() {#Paragraph--}
```
public Paragraph()
```

Új példányt hoz létre a Paragraph osztályból alapértelmezett tulajdonságokkal.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```

Másoló konstruktor, amely új példányt hoz létre a Paragraph osztályból.

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

Visszaadja a formázási objektumot ehhez a bekezdéshez. Csak olvasható [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

A formázási objektum csak a jelenlegi bekezdéshez definiált formázási paramétereket tartalmazza, az örökölt adatokat nem alkalmazza.

Az effektív értékek, beleértve az örökölt értékeket is, lekéréséhez használja a [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective) metódust.

**Visszatérési érték:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)

### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```

Összevonja a hasonló formázású futamokat.

### getText() {#getText--}
```
public final String getText()
```

Lekéri vagy beállítja egy bekezdés egyszerű szövegét. Olvasható/írható String.

Érték: A szöveg.

**Visszatérési érték:**
java.lang.String

### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```

Lekéri vagy beállítja egy bekezdés egyszerű szövegét. Olvasható/írható String.

Érték: A szöveg.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```

Lekéri a bekezdést körülvevő téglalap koordinátáit. A téglalap tartalmazza a bekezdés összes szövegsorát, beleértve az üres sorokat is.

**Visszatérési érték:**
android.graphics.RectF

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

**Visszatér:** int – A bekezdés sorainak száma

### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```

Megadja a rész tulajdonságait, amelyeket egy újabb rész beillesztése után használnak.

**Visszatérési érték:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```

Megadja a rész tulajdonságait, amelyeket egy újabb rész beillesztése után használnak.

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

Visszaadja a bekezdés szülő diavetítését. Csak olvasható [BaseSlide](../../com.aspose.slides/baseslide).

**Visszatérési érték:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)

### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```

Visszaadja a bekezdés szülő prezentációját. Csak olvasható [IPresentation](../../com.aspose.slides/ipresentation).

**Visszatérési érték:**
[IPresentation](../../com.aspose.slides/ipresentation)