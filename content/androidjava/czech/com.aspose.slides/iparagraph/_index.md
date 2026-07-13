---
title: IParagraph
second_title: Aspose.Slides pro Android přes Java API Reference
description: Představuje odstavec textu.
type: docs
url: /cs/com.aspose.slides/iparagraph/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.ISlideComponent](../../com.aspose.slides/islidecomponent)
```
public interface IParagraph extends ISlideComponent
```

Represents a paragraph of a text.
## Metody

| Metoda | Popis |
| --- | --- |
| [getPortions()](#getPortions--) | Vrací kolekci textových částí. |
| [getParagraphFormat()](#getParagraphFormat--) | Vrací objekt formátování pro tento odstavec. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Spojí úseky se stejným formátováním. |
| [getText()](#getText--) | Načte nebo nastaví prostý text odstavce. |
| [setText(String value)](#setText-java.lang.String-) | Načte nebo nastaví prostý text odstavce. |
| [getRect()](#getRect--) | Získá souřadnice obdélníku ohraničujícího odstavec. |
| [getLinesCount()](#getLinesCount--) | Získá počet řádků v odstavci. |
| [getEndParagraphPortionFormat()](#getEndParagraphPortionFormat--) | Určuje vlastnosti části, které mají být použity, pokud je po poslední vložena další část. |
| [setEndParagraphPortionFormat(IPortionFormat value)](#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-) | Určuje vlastnosti části, které mají být použity, pokud je po poslední vložena další část. |
### getPortions() {#getPortions--}
```
public abstract IPortionCollection getPortions()
```

Vrací kolekci textových částí. Pouze pro čtení [IPortionCollection](../../com.aspose.slides/iportioncollection).

**Vrací:**
[IPortionCollection](../../com.aspose.slides/iportioncollection)
### getParagraphFormat() {#getParagraphFormat--}
```
public abstract IParagraphFormat getParagraphFormat()
```

Vrací objekt formátování pro tento odstavec. Pouze pro čtení [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Vrací:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Spojí úseky se stejným formátováním.

### getText() {#getText--}
```
public abstract String getText()
```

Načte nebo nastaví prostý text odstavce. Čtení/zápis String.

Hodnota: Text.

**Vrací:**
java.lang.String
### setText(String value) {#setText-java.lang.String-}
```
public abstract void setText(String value)
```

Načte nebo nastaví prostý text odstavce. Čtení/zápis String.

Hodnota: Text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |
### getRect() {#getRect--}
```
public abstract RectF getRect()
```

Získá souřadnice obdélníku ohraničujícího odstavec. Obdélník zahrnuje všechny řádky textu v odstavci, včetně prázdných.

**Vrací:**
android.graphics.RectF - Obdélník ohraničující odstavec android.graphics.RectF
### getLinesCount() {#getLinesCount--}
```
public abstract int getLinesCount()
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
public abstract IPortionFormat getEndParagraphPortionFormat()
```

Určuje vlastnosti části, které mají být použity, pokud je po poslední vložena další část.

**Vrací:**
[IPortionFormat](../../com.aspose.slides/iportionformat)
### setEndParagraphPortionFormat(IPortionFormat value) {#setEndParagraphPortionFormat-com.aspose.slides.IPortionFormat-}
```
public abstract void setEndParagraphPortionFormat(IPortionFormat value)
```

Určuje vlastnosti části, které mají být použity, pokud je po poslední vložena další část.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IPortionFormat](../../com.aspose.slides/iportionformat) |  |