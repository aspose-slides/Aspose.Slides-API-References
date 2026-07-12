---
title: IMathGroupingCharacter
second_title: Aspose.Slides Androidhoz a Java API hivatkozással
description: Megad egy csoportosító jelet egy kifejezés fölött vagy alatt, általában az elemek közötti kapcsolat kiemelésére
type: docs
url: /hu/com.aspose.slides/imathgroupingcharacter/
---
**Az összes megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Megad egy csoportosító jelet egy kifejezés fölött vagy alatt, általában az elemek közötti kapcsolat kiemelésére

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getBase()](#getBase--) | Alap argumentum |
| [getCharacter()](#getCharacter--) | Csoportosító karakter alapértelmezett értéke: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Csoportosító karakter alapértelmezett értéke: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | A csoportosító karakter pozíciója. |
| [setPosition(int value)](#setPosition-int-) | A csoportosító karakter pozíciója. |
| [getVerticalJustification()](#getVerticalJustification--) | A csoport karakter függőleges igazítása. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | A csoport karakter függőleges igazítása. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Alap argumentum

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
public abstract char getCharacter()
```


Csoportosító karakter alapértelmezett értéke: U+23DF (BOTTOM CURLY BRACKET)

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
public abstract void setCharacter(char value)
```


Csoportosító karakter alapértelmezett értéke: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Alsó zárójel
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
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
public abstract void setPosition(int value)
```


A csoportosító karakter pozíciója. Alapértelmezett: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```


A csoport karakter függőleges igazítása. Meghatározza az objektum igazítását az alapvonalhoz képest. Például, ha a csoport karakter az objektum felett van, a Top értékű VerticalJustification azt jelenti, hogy az objektum teteje az alapvonalon van; ha a VerticalJustification értéke Bottom, akkor az objektum alja az alapvonalon van. Alapértelmezett: Bottom a Position=Top esetén, és Top a Position=Bottom esetén

--------------------

> ```
> Példa:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Visszatérési érték:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```


A csoport karakter függőleges igazítása. Meghatározza az objektum igazítását az alapvonalhoz képest. Például, ha a csoport karakter az objektum felett van, a Top értékű VerticalJustification azt jelenti, hogy az objektum teteje az alapvonalon van; ha a VerticalJustification értéke Bottom, akkor az objektum alja az alapvonalon van. Alapértelmezett: Bottom a Position=Top esetén, és Top a Position=Bottom esetén

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |