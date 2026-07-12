---
title: MathGroupingCharacter
second_title: Aspose.Slides Androidhoz Java API referencia
description: Megad egy csoportosító szimbólumot egy kifejezés fölött vagy alatt, általában az elemek közötti kapcsolat kiemelésére
type: docs
url: /hu/com.aspose.slides/mathgroupingcharacter/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Minden megvalósított interfész:**
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

Megad egy csoportosító szimbólumot egy kifejezés fölött vagy alatt, általában a elemek közötti kapcsolat kiemelésére

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | Inicializál egy új példányt a MathGroupingCharacter osztályból az alapértelmezett csoportosító karakterrel U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Inicializál egy új példányt a MathGroupingCharacter osztályból. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alapargumentum |
| [getCharacter()](#getCharacter--) | Csoportosító karakter Alapértelmezett érték: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Csoportosító karakter Alapértelmezett érték: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | A csoportosító karakter pozíciója. |
| [setPosition(int value)](#setPosition-int-) | A csoportosító karakter pozíciója. |
| [getVerticalJustification()](#getVerticalJustification--) | A csoportosító karakter függőleges igazítása. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | A csoportosító karakter függőleges igazítása. |
| [getChildren()](#getChildren--) | Gyermekelemek lekérése |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Vezérlő karakter tulajdonságok |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```


Inicializál egy új példányt a MathGroupingCharacter osztályból az alapértelmezett csoportosító karakterrel U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Az alapelem, amelyhez a vonalat alkalmazzák |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Inicializál egy új példányt a MathGroupingCharacter osztályból.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Az alapelem, amelyhez a vonalat alkalmazzák |
| character | char | Csoportosító karakter |
| position | int | A csoportosító karakter pozíciója |
| verticalJustification | int | A csoportosító karakter függőleges igazítása |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Alapargumentum

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**Visszatérési érték:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public final char getCharacter()
```


Csoportosító karakter Alapértelmezett érték: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Alsó zárójel
> ```

**Visszatérési érték:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public final void setCharacter(char value)
```


Csoportosító karakter Alapértelmezett érték: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingcharacter.setCharacter('\u23dd'); // Alsó zárójel
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public final int getPosition()
```


A csoportosító karakter pozíciója. Alapértelmezett: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Visszatérési érték:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```


A csoportosító karakter pozíciója. Alapértelmezett: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingcharacter.setPosition(MathTopBotPositions.Top);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```


A csoportosító karakter függőleges igazítása. Megadja az objektum igazítását az alapvonalhoz képest. Például ha a csoportosító karakter az objektum felett van, a Top függőleges igazítás azt jelenti, hogy az objektum teteje az alapvonalon van; ha Bottom-ra van állítva, az objektum alja van az alapvonalon. Alapértelmezett: Bottom, ha Position=Top, és Top, ha Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Visszatérési érték:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public final void setVerticalJustification(int value)
```


A csoportosító karakter függőleges igazítása. Megadja az objektum igazítását az alapvonalhoz képest. Például ha a csoportosító karakter az objektum felett van, a Top függőleges igazítás azt jelenti, hogy az objektum teteje az alapvonalon van; ha Bottom-ra van állítva, az objektum alja van az alapvonalon. Alapértelmezett: Bottom, ha Position=Top, és Top, ha Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingcharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

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


Vezérlő karakter tulajdonságok

**Visszatérési érték:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps