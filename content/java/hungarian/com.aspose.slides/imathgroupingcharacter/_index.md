---
title: IMathGroupingCharacter
second_title: Aspose.Slides Java API hivatkozás
description: Megad egy csoportosító szimbólumot egy kifejezés fölött vagy alatt, általában az elemek közötti kapcsolat kiemelésére.
type: docs
url: /hu/com.aspose.slides/imathgroupingcharacter/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Megad egy csoportosító szimbólumot egy kifejezés fölött vagy alatt, általában az elemek közötti kapcsolat kiemelésére

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
| [getCharacter()](#getCharacter--) | Csoportosítási karakter alapértelmezett értéke: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Csoportosítási karakter alapértelmezett értéke: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | A csoportosítási karakter pozíciója. |
| [setPosition(int value)](#setPosition-int-) | A csoportosítási karakter pozíciója. |
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

**Visszatér:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```

Csoportosítási karakter alapértelmezett értéke: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Alsó zárójel
```

**Visszatér:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```

Csoportosítási karakter alapértelmezett értéke: U+23DF (BOTTOM CURLY BRACKET)

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

A csoportosítási karakter pozíciója. Alapértelmezett: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Visszatér:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```

A csoportosítási karakter pozíciója. Alapértelmezett: Bottom

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

A csoport karakter függőleges igazítása. Meghatározza az objektum elhelyezkedését az alapvonalhoz képest. Például, ha a csoport karakter az objektum felett van, a Top értékű VerticalJustification azt jelenti, hogy az objektum teteje az alapvonalon helyezkedik el; ha a VerticalJustification értéke Bottom, akkor az objektum alja az alapvonalon van. Alapértelmezett: Bottom, ha Position=Top, és Top, ha Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Visszatér:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```

A csoport karakter függőleges igazítása. Meghatározza az objektum elhelyezkedését az alapvonalhoz képest. Például, ha a csoport karakter az objektum felett van, a Top értékű VerticalJustification azt jelenti, hogy az objektum teteje az alapvonalon helyezkedik el; ha a VerticalJustification értéke Bottom, akkor az objektum alja az alapvonalon van. Alapértelmezett: Bottom, ha Position=Top, és Top, ha Position=Bottom

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