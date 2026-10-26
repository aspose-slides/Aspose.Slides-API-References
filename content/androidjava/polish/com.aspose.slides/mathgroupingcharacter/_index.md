---
title: MathGroupingCharacter
second_title: Aspose.Slides dla Androida - odwołanie do Java API
description: Określa znak grupujący powyżej lub poniżej wyrażenia, zwykle w celu podkreślenia zależności między elementami
type: docs
url: /pl/com.aspose.slides/mathgroupingcharacter/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

Określa znak grupujący powyżej lub poniżej wyrażenia, zwykle w celu podkreślenia zależności między elementami

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | Inicjalizuje nową instancję klasy MathGroupingCharacter z domyślnym znakiem grupującym U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Inicjalizuje nową instancję klasy MathGroupingCharacter. |
## Metody

| Metoda | Opis |
| --- | --- |
| [getBase()](#getBase--) | Argument bazowy |
| [getCharacter()](#getCharacter--) | Domyślna wartość znaku grupującego: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Domyślna wartość znaku grupującego: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Pozycja znaku grupującego. |
| [setPosition(int value)](#setPosition-int-) | Pozycja znaku grupującego. |
| [getVerticalJustification()](#getVerticalJustification--) | Wyrównanie pionowe znaku grupującego. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Wyrównanie pionowe znaku grupującego. |
| [getChildren()](#getChildren--) | Pobiera elementy potomne |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Właściwości znaku kontrolnego |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```


Inicjalizuje nową instancję klasy MathGroupingCharacter z domyślnym znakiem grupującym U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Podstawowy element, do którego zastosowano kreskę |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Inicjalizuje nową instancję klasy MathGroupingCharacter.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Podstawowy element, do którego zastosowano kreskę |
| character | char | Znak grupujący |
| position | int | Pozycja znaku grupującego |
| verticalJustification | int | Wyrównanie pionowe znaku grupującego |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argument bazowy

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
public final char getCharacter()
```


Domyślna wartość znaku grupującego: U+23DF (BOTTOM CURLY BRACKET)

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
public final void setCharacter(char value)
```


Domyślna wartość znaku grupującego: U+23DF (BOTTOM CURLY BRACKET)

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
public final int getPosition()
```


Pozycja znaku grupującego. Domyślnie: Bottom

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
public final void setPosition(int value)
```


Pozycja znaku grupującego. Domyślnie: Bottom

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
public final int getVerticalJustification()
```


Wyrównanie pionowe znaku grupującego. Określa wyrównanie obiektu względem linii bazowej. Na przykład, gdy znak grupujący znajduje się powyżej obiektu, wyrównanie pionowe „Top” oznacza, że górna część obiektu znajduje się na linii bazowej; gdy wyrównanie pionowe jest ustawione na „Bottom”, dolna część obiektu znajduje się na linii bazowej. Domyślnie: Bottom dla Position=Top oraz Top dla Position=Bottom

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
public final void setVerticalJustification(int value)
```


Wyrównanie pionowe znaku grupującego. Określa wyrównanie obiektu względem linii bazowej. Na przykład, gdy znak grupujący znajduje się powyżej obiektu, wyrównanie pionowe „Top” oznacza, że górna część obiektu znajduje się na linii bazowej; gdy wyrównanie pionowe jest ustawione na „Bottom”, dolna część obiektu znajduje się na linii bazowej. Domyślnie: Bottom dla Position=Top oraz Top dla Position=Bottom

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Pobiera elementy potomne

**Zwraca:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Właściwości znaku kontrolnego

**Zwraca:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps