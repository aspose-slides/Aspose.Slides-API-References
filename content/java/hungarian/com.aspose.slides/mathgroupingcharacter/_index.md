---
title: MathGroupingCharacter
second_title: Aspose.Slides Java API hivatkozás
description: Egy kifejezés fölött vagy alatt lévő csoportosító szimbólumot ad meg, általában az elemek közötti kapcsolat kiemelésére
type: docs
url: /hu/com.aspose.slides/mathgroupingcharacter/
---
**Inheritance:**  
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**All Implemented Interfaces:**  
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties  
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

Megad egy csoportosító szimbólumot egy kifejezés fölött vagy alatt, általában az elemek közötti kapcsolat kiemelésére

--------------------

> ```
> Példa:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## Constructors

| Constructor | Description |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | Inicializál egy új példányt a MathGroupingCharacter osztályból az alapértelmezett csoportosító karakterrel U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Inicializál egy új példányt a MathGroupingCharacter osztályból. |
## Methods

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getCharacter()](#getCharacter--) | Csoportosító karakter alapértelmezett értéke: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Csoportosító karakter alapértelmezett értéke: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | A csoportosító karakter pozíciója. |
| [setPosition(int value)](#setPosition-int-) | A csoportosító karakter pozíciója. |
| [getVerticalJustification()](#getVerticalJustification--) | A csoportosító karakter függőleges igazítása. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | A csoportosító karakter függőleges igazítása. |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Kontroll karakter tulajdonságok |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```


Inicializál egy új példányt a MathGroupingCharacter osztályból az alapértelmezett csoportosító karakterrel U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Példa:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Az az alap elem, amelyre a vonalat alkalmazzák |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Inicializál egy új példányt a MathGroupingCharacter osztályból.

--------------------

> ```
> Példa:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Az az alap elem, amelyre a vonalat alkalmazzák |
| character | char | Csoportosító karakter |
| position | int | A csoportosító karakter pozíciója |
| verticalJustification | int | A csoportosító karakter függőleges igazítása |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Alap argumentum

--------------------

> ```
> Példa:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**Returns:**  
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


Csoportosító karakter alapértelmezett értéke: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Alsó zárójel
> ```

**Returns:**  
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```


Csoportosító karakter alapértelmezett értéke: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Alsó zárójel
> ```

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


A csoportosító karakter pozíciója. Alapértelmezett: Alul

--------------------

> ```
> Példa:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Returns:**  
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


A csoportosító karakter pozíciója. Alapértelmezett: Alul

--------------------

> ```
> Példa:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingcharacter.setPosition(MathTopBotPositions.Top);
> ```

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```


A csoportosító karakter függőleges igazítása. Meghatározza az objektum igazítását az alapvonallal szemben. Például ha a csoportosító karakter az objektum felett van, a „Top” függőleges igazítás azt jelenti, hogy az objektum teteje az alapvonalon van; ha a „Bottom” érték van beállítva, az objektum alja az alapvonalon van. Alapértelmezett: Alul a Position=Top esetén, és Fent a Position=Bottom esetén

--------------------

> ```
> Példa:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Returns:**  
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```


A csoportosító karakter függőleges igazítása. Meghatározza az objektum igazítását az alapvonallal szemben. Például ha a csoportosító karakter az objektum felett van, a „Top” függőleges igazítás azt jelenti, hogy az objektum teteje az alapvonalon van; ha a „Bottom” érték van beállítva, az objektum alja az alapvonalon van. Alapértelmezett: Alul a Position=Top esetén, és Fent a Position=Bottom esetén

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingcharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Gyermekelemek lekérése

**Returns:**  
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Kontroll karakter tulajdonságok

**Returns:**  
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps