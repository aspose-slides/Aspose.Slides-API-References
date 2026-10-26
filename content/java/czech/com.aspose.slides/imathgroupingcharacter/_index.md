---
title: IMathGroupingCharacter
second_title: Aspose.Slides pro Java API Reference
description: Určuje skupinový symbol nad nebo pod výrazem, obvykle k zvýraznění vztahu mezi prvky
type: docs
url: /cs/com.aspose.slides/imathgroupingcharacter/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Určuje skupinový symbol nad nebo pod výrazem, obvykle k zdůraznění vztahu mezi prvky

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Základní argument |
| [getCharacter()](#getCharacter--) | Skupinový znak Výchozí hodnota: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Skupinový znak Výchozí hodnota: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Pozice skupinového znaku. |
| [setPosition(int value)](#setPosition-int-) | Pozice skupinového znaku. |
| [getVerticalJustification()](#getVerticalJustification--) | Vertikální zarovnání skupinového znaku. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Vertikální zarovnání skupinového znaku. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
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
public abstract char getCharacter()
```

Skupinový znak Výchozí hodnota: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Dolní závorka
> ```

**Vrací:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Skupinový znak Výchozí hodnota: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Dolní závorka
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Pozice skupinového znaku. Výchozí: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Vrací:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Pozice skupinového znaku. Výchozí: Bottom

--------------------

> ```
> Example:
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
public abstract int getVerticalJustification()
```

Vertikální zarovnání skupinového znaku. Určuje zarovnání objektu vzhledem k základní linii. Například když je skupinový znak nad objektem, Vertikální zarovnání Top znamená, že horní část objektu leží na základní linii; když je Vertikální zarovnání nastaveno na Bottom, spodní část objektu je na základní linii. Výchozí: Bottom pro Position=Top a Top pro Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Vrací:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```

Vertikální zarovnání skupinového znaku. Určuje zarovnání objektu vzhledem k základní linii. Například když je skupinový znak nad objektem, Vertikální zarovnání Top znamená, že horní část objektu leží na základní linii; když je Vertikální zarovnání nastaveno na Bottom, spodní část objektu je na základní linii. Výchozí: Bottom pro Position=Top a Top pro Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |