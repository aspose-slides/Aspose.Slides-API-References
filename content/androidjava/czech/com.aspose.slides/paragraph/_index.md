---
title: Paragraph
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje odstavec textu.
type: docs
url: /cs/com.aspose.slides/paragraph/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IParagraph](../../com.aspose.slides/iparagraph), com.aspose.slides.IDOMObject
```
public final class Paragraph implements IParagraph, IDOMObject
```

Represents a paragraph of text.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [Paragraph()](#Paragraph--) | Inicializuje novou instanci třídy Paragraph s výchozími vlastnostmi. |
| [Paragraph(Paragraph para)](#Paragraph-com.aspose.slides.Paragraph-) | Kopírovací konstruktor, který inicializuje novou instanci třídy Paragraph. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getPortions()](#getPortions--) | Vrací kolekci textových částí. |
| [getParagraphFormat()](#getParagraphFormat--) | Vrací objekt formátování pro tento odstavec. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Spojí úseky se stejným formátováním. |
| [getText()](#getText--) | Získá nebo nastaví prostý text odstavce. |
| [setText(String value)](#setText-java.lang.String-) | Získá nebo nastaví prostý text odstavce. |
| [getRect()](#getRect--) | Získá souřadnice obdélníku ohraničujícího odstavec. |
| [getLinesCount()](#getLinesCount--) | Získá počet řádků v odstavci. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Určuje vlastnosti úseku, které se použijí, pokud je po posledním úseku vložen další úsek. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Určuje vlastnosti úseku, které se použijí, pokud je po posledním úseku vložen další úsek. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getSlide()](#getSlide--) | Vrací nadřazený snímek odstavce. |
| [getPresentation()](#getPresentation--) | Vrací nadřazenou prezentaci odstavce. |
### Paragraph() {#Paragraph--}
```
public Paragraph()
```


Inicializuje novou instanci třídy Paragraph s výchozími vlastnostmi.

### Paragraph(Paragraph para) {#Paragraph-com.aspose.slides.Paragraph-}
```
public Paragraph(Paragraph para)
```


Kopírovací konstruktor, který inicializuje novou instanci třídy Paragraph.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| para | [Paragraph](../../com.aspose.slides/paragraph) |  |

### getPortions() {#getPortions--}
```
public final IPortionCollection getPortions()
```


Vrací kolekci textových částí. Pouze pro čtení [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Vrací:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public final IParagraphFormat getParagraphFormat()
```


Vrací objekt formátování pro tento odstavec. Pouze pro čtení [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

--------------------

Objekt formátování obsahuje parametry formátování definované pouze pro aktuální odstavec, zděděná data nejsou použita.

Pro získání efektivních hodnot včetně zděděných použijte metodu [ParagraphFormat.getEffective](../../com.aspose.slides/paragraphformat\#getEffective).

**Vrací:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public final void joinPortionsWithSameFormatting()
```


Spojí úseky se stejným formátováním.

### getText() {#getText--}
```
public final String getText()
```


Získá nebo nastaví prostý text odstavce. Čtení/zápis String.

Hodnota: Text.

**Vrací:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public final void setText(String value)
```


Získá nebo nastaví prostý text odstavce. Čtení/zápis String.

Hodnota: Text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getRect() {#getRect--}
```
public final RectF getRect()
```


Získá souřadnice obdélníku ohraničujícího odstavec. Obdélník zahrnuje všechny řádky textu v odstavci, včetně prázdných.

**Vrací:**
android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public final int getLinesCount()
```


Získá počet řádků v odstavci.

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


**Vrací:**
int - Počet řádků v odstavci
### getEndParagraphPortionFormat() {#getEndParagraphPortionFormat--}
```
public final IPortionFormat getEndParagraphPortionFormat()
```


Určuje vlastnosti úseku, které se použijí, pokud je po posledním úseku vložen další úsek.

**Vrací:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public final void setEndParagraphPortionFormat(IPortionFormat value)
```


Určuje vlastnosti úseku, které se použijí, pokud je po posledním úseku vložen další úsek.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Vrací objekt Parent_Immediate. Pouze pro čtení IDOMObject.

**Vrací:**
com.aspose.slides.IDOMObject
### getSlide() {#getSlide--}
```
public final IBaseSlide getSlide()
```


Vrací nadřazený snímek odstavce. Pouze pro čtení [BaseSlide](../../com.aspose.slides/baseslide).

**Vrací:**
[IBaseSlide](../../com.aspose.slides/ibaseslide)
### getPresentation() {#getPresentation--}
```
public final IPresentation getPresentation()
```


Vrací nadřazenou prezentaci odstavce. Pouze pro čtení [IPresentation](../../com.aspose.slides/ipresentation).

**Vrací:**
[IPresentation](../../com.aspose.slides/ipresentation)