---
title: MathDelimiter
second_title: Aspose.Slides Java API Referenciája
description: Megadja a delimiter objektumot, amely nyitó és záró karakterekből (például zárójelek, kapcsos zárójelek, szögletes zárójelek és függőleges vonalak) áll, és egy vagy több matematikai elemet tartalmaz, amelyeket egy megadott karakterrel választanak el.
type: docs
url: /hu/com.aspose.slides/mathdelimiter/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Minden megvalósított interfész:**
[com.aspose.slides.IMathDelimiter](../../com.aspose.slides/imathdelimiter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathDelimiter extends MathElementBase implements IMathDelimiter, IHasControlCharacterProperties
```

Meghatározza a delimiter objektumot, amely nyitó és záró karakterekből (például zárójelek, kapcsos zárójelek, szögletes zárójelek és függőleges vonalak) áll, és egy vagy több matematikai elemet tartalmaz, amelyeket egy megadott karakterrel választanak el. Példák: (\\ud835\\udc652); [\\ud835\\udc652|\\ud835\\udc662]

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathDelimiter(IMathElement element)](#MathDelimiter-com.aspose.slides.IMathElement-) | Inicializálja a MathDelimiter-t a megadott elemmel, egyetlen alap argumentumként |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getArguments()](#getArguments--) | Egy vagy több matematikai elem, amelyet delimiter karakterek választanak el |
| [getBeginningCharacter()](#getBeginningCharacter--) | A Delimiter Beginning Character megadja a delimiter kezdő, vagy nyitó karakterét. |
| [setBeginningCharacter(char value)](#setBeginningCharacter-char-) | A Delimiter Beginning Character megadja a delimiter kezdő, vagy nyitó karakterét. |
| [getSeparatorCharacter()](#getSeparatorCharacter--) | A Delimiter Separator Character megadja azt a karaktert, amely a delimiter objektumban elválasztja az argumentumokat. |
| [setSeparatorCharacter(char value)](#setSeparatorCharacter-char-) | A Delimiter Separator Character megadja azt a karaktert, amely a delimiter objektumban elválasztja az argumentumokat. |
| [getEndingCharacter()](#getEndingCharacter--) | A Delimiter Ending Character megadja a delimiter befejező, vagy záró karakterét. |
| [setEndingCharacter(char value)](#setEndingCharacter-char-) | A Delimiter Ending Character megadja a delimiter befejező, vagy záró karakterét. |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Megadja a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését. Ha igaz, a delimiterok függőlegesen nőnek, hogy illeszkedjenek az operandus magasságához. |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Megadja a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését. Ha igaz, a delimiterok függőlegesen nőnek, hogy illeszkedjenek az operandus magasságához. |
| [getDelimiterShape()](#getDelimiterShape--) | Megadja a delimiterok alakját a delimiter objektumban. |
| [setDelimiterShape(int value)](#setDelimiterShape-int-) | Megadja a delimiterok alakját a delimiter objektumban. |
| [delimit(char separatorCharacter)](#delimit-char-) | A megadott delimiter karakterrel választja el az argumentumokat. |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Egy matematikai elemet a megadott karakterekkel, például zárójelekkel vagy egyéb karakterekkel keretez. |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Control Character Properties |
### MathDelimiter(IMathElement element) {#MathDelimiter-com.aspose.slides.IMathElement-}
```
public MathDelimiter(IMathElement element)
```

Inicializálja a MathDelimiter-t a megadott elemmel, egyetlen alap argumentumként

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  MathDelimiter delimiter = new MathDelimiter(element);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Az alap elem, amelyre a delimiter alkalmazásra kerül. Lehet null. |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Egy vagy több matematikai elem, amelyet delimiter karakterek választanak el

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  IMathElementCollection arguments = delimiter.getArguments();
> ```

**Visszatérési érték:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBeginningCharacter() {#getBeginningCharacter--}
```
public final char getBeginningCharacter()
```

A Delimiter Beginning Character megadja a delimiter kezdő, vagy nyitó karakterét. Matematikai delimiterek olyan befoglaló karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Visszatérési érték:**
char
### setBeginningCharacter(char value) {#setBeginningCharacter-char-}
```
public final void setBeginningCharacter(char value)
```

A Delimiter Beginning Character megadja a delimiter kezdő, vagy nyitó karakterét. Matematikai delimiterek olyan befoglaló karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett: '('.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setBeginningCharacter('[');
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char |  |
### getSeparatorCharacter() {#getSeparatorCharacter--}
```
public final char getSeparatorCharacter()
```

A Delimiter Separator Character megadja azt a karaktert, amely a delimiter objektumban elválasztja az argumentumokat. Alapértelmezett: '|'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Visszatérési érték:**
char
### setSeparatorCharacter(char value) {#setSeparatorCharacter-char-}
```
public final void setSeparatorCharacter(char value)
```

A Delimiter Separator Character megadja azt a karaktert, amely a delimiter objektumban elválasztja az argumentumokat. Alapértelmezett: '|'.

--------------------

> ```
> Példa:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setSeparatorCharacter('$');
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char |  |
### getEndingCharacter() {#getEndingCharacter--}
```
public final char getEndingCharacter()
```

A Delimiter Ending Character megadja a delimiter befejező, vagy záró karakterét. Matematikai delimiterek olyan befoglaló karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett: ')'.

--------------------

> ```
> Példa:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Visszatérési érték:**
char
### setEndingCharacter(char value) {#setEndingCharacter-char-}
```
public final void setEndingCharacter(char value)
```

A Delimiter Ending Character megadja a delimiter befejező, vagy záró karakterét. Matematikai delimiterek olyan befoglaló karakterek, mint a zárójelek, szögletes zárójelek és kapcsos zárójelek. Alapértelmezett: ')'.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").join("y").enclose();
>  delimiter.setEndingCharacter(']');
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char |  |
### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public final boolean getGrowToMatchOperandHeight()
```

Megadja a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését. Ha igaz, a delimiterok függőlegesen nőnek, hogy illeszkedjenek az operandus magasságához. Alapértelmezett érték: true

--------------------

> ```
> Példa:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```


**Visszatérési érték:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public final void setGrowToMatchOperandHeight(boolean value)
```

Megadja a BeginningCharacter, SeparatorCharacter, EndingCharacter növekedését. Ha igaz, a delimiterok függőlegesen nőnek, hogy illeszkedjenek az operandus magasságához. Alapértelmezett érték: true

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setGrowToMatchOperandHeight(false);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### getDelimiterShape() {#getDelimiterShape--}
```
public final int getDelimiterShape()
```

Megadja a delimiterok alakját a delimiter objektumban. Ha a MathDelimiterShape.Centered, a delimiterok a matematikai szöveg tengelye köré vannak középre helyezve, de úgy is illeszkedhetnek, hogy a tartalmuk teljes magasságát lefedjék. Ha a MathDelimiterShape.Match, magasságuk és alakjuk pontosan a tartalomhoz igazodik.

--------------------

> ```
> Példa:
>  
  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```


**Visszatérési érték:**
int
### setDelimiterShape(int value) {#setDelimiterShape-int-}
```
public final void setDelimiterShape(int value)
```

Megadja a delimiterok alakját a delimiter objektumban. Ha a MathDelimiterShape.Centered, a delimiterok a matematikai szöveg tengelye köré vannak középre helyezve, de úgy is illeszkedhetnek, hogy a tartalmuk teljes magasságát lefedjék. Ha a MathDelimiterShape.Match, magasságuk és alakjuk pontosan a tartalomhoz igazodik.

--------------------

> ```
> Example:
>  
>  IMathDelimiter delimiter = new MathematicalText("x").divide("y").enclose();
>  delimiter.setDelimiterShape(MathDelimiterShape.Match);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |
### delimit(char separatorCharacter) {#delimit-char-}
```
public final IMathDelimiter delimit(char separatorCharacter)
```

A megadott delimiter karakterrel választja el az argumentumokat

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| separatorCharacter | char | delimiter karakter |
**Visszatérési érték:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Ez az objektum a delimiter karakter alkalmazása után

### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Egy matematikai elemet a megadott karakterekkel, például zárójelekkel vagy egyéb karakterekkel keretez

--------------------

> ```
> Example:
>  
>  IMathDelimiter innerDelimiter = new MathematicalText("x").join(",y").enclose('{', '}');
>  IMathDelimiter outerDelimiter = innerDelimiter.enclose('[', ']');
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| beginningCharacter | char | Kezdő karakter (általában bal zárójel) |
| endingCharacter | char | Záró karakter (általában jobb zárójel) |
**Visszatérési érték:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Ha a beginningCharacter és endingCharacter null, csak a megfelelő tulajdonságok kapnak értéket, és nem jön létre új objektum (a jelenlegi példányt adja vissza). Egyébként új Delimiter típusú math elem jön létre, amely a megadott karakterekkel keretezi és a [MathDelimiter](../../com.aspose.slides/mathdelimiter) példányt tartalmazza.

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Gyermekelemek lekérése

**Visszatérési érték:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Control Character Properties

**Visszatérési érték:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps