---
title: IMathGroupingCharacter
second_title: Aspose.Slides dla Androida – dokumentacja API Java
description: Określa symbol grupujący powyżej lub poniżej wyrażenia, zwykle w celu podkreślenia zależności między elementami
type: docs
url: /pl/com.aspose.slides/imathgroupingcharacter/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Określa symbol grupowania powyżej lub poniżej wyrażenia, zazwyczaj w celu podkreślenia zależności między elementami

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
>  ```

## Metody

| Metoda | Opis |
| --- | --- |
| [getBase()](#getBase--) | Argument Base |
| [getCharacter()](#getCharacter--) | Grouping Character Domyślna wartość: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Grouping Character Domyślna wartość: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Pozycja grouping character. |
| [setPosition(int value)](#setPosition-int-) | Pozycja grouping character. |
| [getVerticalJustification()](#getVerticalJustification--) | Wyrównanie pionowe group character. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Wyrównanie pionowe group character. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argument Base

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```


**Zwraca:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Grouping Character Domyślna wartość: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Dolny nawias
> ```

**Zwraca:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Grouping Character Domyślna wartość: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Dolny nawias
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Pozycja grouping character. Domyślnie: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Zwraca:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Pozycja grouping character. Domyślnie: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```

Vertical justification of group character. Określa wyrównanie obiektu względem linii bazowej. Na przykład, gdy group character znajduje się nad obiektem, VerticalJustification ustawione na Top oznacza, że górna część obiektu znajduje się na linii bazowej; gdy VerticalJustification jest ustawione na Bottom, dolna część obiektu znajduje się na linii bazowej Domyślnie: Bottom dla Position=Top oraz Top dla Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Zwraca:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```

Vertical justification of group character. Określa wyrównanie obiektu względem linii bazowej. Na przykład, gdy group character znajduje się nad obiektem, VerticalJustification ustawione na Top oznacza, że górna część obiektu znajduje się na linii bazowej; gdy VerticalJustification jest ustawione na Bottom, dolna część obiektu znajduje się na linii bazowej Domyślnie: Bottom dla Position=Top oraz Top dla Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```


**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |