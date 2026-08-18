---
title: IMathGroupingCharacter
second_title: Aspose.Slides dla Java – dokumentacja API
description: Określa symbol grupujący nad lub pod wyrażeniem, zwykle w celu podkreślenia zależności między elementami
type: docs
url: /pl/com.aspose.slides/imathgroupingcharacter/
---
**All Implemented Interfaces:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Określa symbol grupujący nad lub pod wyrażeniem, zwykle w celu podkreślenia związku między elementami

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Argument bazowy |
| [getCharacter()](#getCharacter--) | Domyślna wartość znaku grupującego: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Domyślna wartość znaku grupującego: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Pozycja znaku grupującego. |
| [setPosition(int value)](#setPosition-int-) | Pozycja znaku grupującego. |
| [getVerticalJustification()](#getVerticalJustification--) | Pionowe justowanie znaku grupującego. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Pionowe justowanie znaku grupującego. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Argument bazowy

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**Returns:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Domyślna wartość znaku grupującego: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Dolny nawias
> ```

**Returns:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Domyślna wartość znaku grupującego: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Dolny nawias
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |
### getPosition() {#getPosition--}
```
public abstract int getPosition()
```

Pozycja znaku grupującego. Domyślnie: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Returns:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

Pozycja znaku grupującego. Domyślnie: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```

Pionowe justowanie znaku grupującego. Określa wyrównanie obiektu względem linii bazowej. Na przykład, gdy znak grupujący znajduje się nad obiektem, pionowe justowanie Top oznacza, że górna krawędź obiektu leży na linii bazowej; gdy pionowe justowanie ustawione jest na Bottom, dolna krawędź obiektu leży na linii bazowej. Domyślnie: Bottom dla Position=Top i Top dla Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Returns:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```

Pionowe justowanie znaku grupującego. Określa wyrównanie obiektu względem linii bazowej. Na przykład, gdy znak grupujący znajduje się nad obiektem, pionowe justowanie Top oznacza, że górna krawędź obiektu leży na linii bazowej; gdy pionowe justowanie ustawione jest na Bottom, dolna krawędź obiektu leży na linii bazowej. Domyślnie: Bottom dla Position=Top i Top dla Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |