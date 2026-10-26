---
title: IMathGroupingCharacter
second_title: Aspose.Slides pro Android přes Java API Reference
description: Určuje skupinový symbol nad nebo pod výrazem, obvykle za účelem zvýraznění vztahu mezi prvky
type: docs
url: /cs/com.aspose.slides/imathgroupingcharacter/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Určuje skupinový symbol nad nebo pod výrazem, obvykle pro zvýraznění vztahu mezi prvky

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
```
## Metody

| Metoda | Popis |
| --- | --- |
| [getBase()](#getBase--) | Základní argument |
| [getCharacter()](#getCharacter--) | Výchozí hodnota znaku skupiny: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Výchozí hodnota znaku skupiny: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Pozice znaku skupiny. |
| [setPosition(int value)](#setPosition-int-) | Pozice znaku skupiny. |
| [getVerticalJustification()](#getVerticalJustification--) | Vertikální zarovnání znaku skupiny. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Vertikální zarovnání znaku skupiny. |
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


Výchozí hodnota znaku skupiny: U+23DF (BOTTOM CURLY BRACKET)

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
public abstract void setCharacter(char value)
```


Výchozí hodnota znaku skupiny: U+23DF (BOTTOM CURLY BRACKET)

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
public abstract int getPosition()
```


Pozice znaku skupiny. Výchozí: Bottom

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


Pozice znaku skupiny. Výchozí: Bottom

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


Vertikální zarovnání znaku skupiny. Určuje zarovnání objektu vzhledem k základní linii. Například když je znak skupiny nad objektem, VerticalJustification hodnoty Top znamená, že horní část objektu leží na základní linii; když je VerticalJustification nastaveno na Bottom, spodní část objektu leží na základní linii. Výchozí: Bottom pro Position=Top a Top pro Position=Bottom

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


Vertikální zarovnání znaku skupiny. Určuje zarovnání objektu vzhledem k základní linii. Například když je znak skupiny nad objektem, VerticalJustification hodnoty Top znamená, že horní část objektu leží na základní linii; když je VerticalJustification nastaveno na Bottom, spodní část objektu leží na základní linii. Výchozí: Bottom pro Position=Top a Top pro Position=Bottom

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