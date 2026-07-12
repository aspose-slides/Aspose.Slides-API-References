---
title: IParagraph
second_title: Aspose.Slides Androidhoz Java API hivatkozás
description: Egy szöveg bekezdését ábrázolja.
type: docs
url: /hu/com.aspose.slides/iparagraph/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Egy szöveg bekezdését ábrázolja.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getPortions()](#getPortions--) | Visszaadja a szövegrészek gyűjteményét. |
| [getParagraphFormat()](#getParagraphFormat--) | Visszaadja a bekezdés formázási objektumát. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Azonos formázású futamokat egyesíti. |
| [getText()](#getText--) | Lekéri vagy beállítja a bekezdés egyszerű szövegét. |
| [setText(String value)](#setText-java.lang.String-) | Lekéri vagy beállítja a bekezdés egyszerű szövegét. |
| [getRect()](#getRect--) | Lekéri a bekezdést körülvevő téglalap koordinátáit. |
| [getLinesCount()](#getLinesCount--) | Lekéri a bekezdés sorainak számát. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Megadja a rész tulajdonságait, amelyeket akkor kell használni, ha egy újabb részt illesztenek az utolsó után. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Megadja a rész tulajdonságait, amelyeket akkor kell használni, ha egy újabb részt illesztenek az utolsó után. |
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


Visszaadja a bekezdés formázási objektumát. Csak olvasható [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Visszatér:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```


Azonos formázású futamokat egyesíti.

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
public abstract RectF getRect()
```


Lekéri a bekezdést körülvevő téglalap koordinátáit. A téglalap tartalmazza a bekezdés összes szövegsorát, beleértve az üres sorokat is.

**Visszatér:**
android.graphics.RectF - A bekezdést körülvevő téglalap android.graphics.RectF
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
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public abstract IPortionFormat getEndParagraphPortionFormat()
```


Megadja a rész tulajdonságait, amelyeket akkor kell használni, ha egy újabb részt illesztenek az utolsó után.

**Visszatér:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```


Megadja a rész tulajdonságait, amelyeket akkor kell használni, ha egy újabb részt illesztenek az utolsó után.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |