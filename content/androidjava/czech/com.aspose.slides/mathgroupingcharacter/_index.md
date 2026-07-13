---
title: MathGroupingCharacter
second_title: Aspose.Slides pro Android přes Java API Reference
description: Určuje seskupovací symbol nad nebo pod výrazem, obvykle k zvýraznění vztahu mezi prvky
type: docs
url: /cs/com.aspose.slides/mathgroupingcharacter/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

Určuje seskupovací znak nad nebo pod výrazem, obvykle pro zvýraznění vztahu mezi prvky

--------------------

> ```
> Příklad:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | Inicializuje novou instanci třídy MathGroupingCharacter s výchozím seskupovacím znakem U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Inicializuje novou instanci třídy MathGroupingCharacter. |
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Základní argument |
| [getCharacter()](#getCharacter--) | Znak seskupování. Výchozí hodnota: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Znak seskupování. Výchozí hodnota: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Pozice seskupovacího znaku. |
| [setPosition(int value)](#setPosition-int-) | Pozice seskupovacího znaku. |
| [getVerticalJustification()](#getVerticalJustification--) | Vertikální zarovnání seskupovacího znaku. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Vertikální zarovnání seskupovacího znaku. |
| [getChildren()](#getChildren--) | Získat podřízené prvky |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vlastnosti řídícího znaku |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```


Inicializuje novou instanci třídy MathGroupingCharacter s výchozím seskupovacím znakem U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Příklad:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Základní prvek, na který se aplikuje čára |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Inicializuje novou instanci třídy MathGroupingCharacter.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Základní prvek, na který se aplikuje čára |
| character | char | Znak seskupování |
| position | int | Pozice seskupovacího znaku |
| verticalJustification | int | Vertikální zarovnání seskupovacího znaku |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Základní argument

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**Vrací:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


Znak seskupování. Výchozí hodnota: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Spodní závorka
> ```

**Vrací:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```


Znak seskupování. Výchozí hodnota: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Spodní závorka
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


Pozice seskupovacího znaku. Výchozí: Bottom

--------------------

> ```
> Příklad:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Vrací:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


Pozice seskupovacího znaku. Výchozí: Bottom

--------------------

> ```
> Příklad:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```


Vertikální zarovnání seskupovacího znaku. Určuje zarovnání objektu vzhledem k základní lince. Například když je seskupovací znak nad objektem, Vertikální zarovnání Top znamená, že horní část objektu leží na základní lince; když je Vertikální zarovnání nastaveno na Bottom, spodní část objektu leží na základní lince. Výchozí: Bottom pro Position=Top a Top pro Position=Bottom

--------------------

> ```
> Příklad:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```


**Vrací:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```


Vertikální zarovnání seskupovacího znaku. Určuje zarovnání objektu vzhledem k základní lince. Například když je seskupovací znak nad objektem, Vertikální zarovnání Top znamená, že horní část objektu leží na základní lince; když je Vertikální zarovnání nastaveno na Bottom, spodní část objektu leží na základní lince. Výchozí: Bottom pro Position=Top a Top pro Position=Bottom

--------------------

> ```
> Příklad:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Získat podřízené prvky

**Vrací:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Vlastnosti řídícího znaku

**Vrací:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps