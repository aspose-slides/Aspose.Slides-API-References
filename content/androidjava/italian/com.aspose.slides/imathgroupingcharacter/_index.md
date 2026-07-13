---
title: IMathGroupingCharacter
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Specifica un simbolo di raggruppamento sopra o sotto un'espressione, solitamente per evidenziare la relazione tra gli elementi
type: docs
url: /it/com.aspose.slides/imathgroupingcharacter/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathGroupingCharacter extends IMathElement
```

Specifica un simbolo di raggruppamento sopra o sotto un'espressione, solitamente per evidenziare la relazione tra gli elementi

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```
## Metodi

| Method | Description |
| --- | --- |
| [getBase()](#getBase--) | Argomento base |
| [getCharacter()](#getCharacter--) | Valore predefinito del carattere di raggruppamento: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Valore predefinito del carattere di raggruppamento: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Posizione del carattere di raggruppamento. |
| [setPosition(int value)](#setPosition-int-) | Posizione del carattere di raggruppamento. |
| [getVerticalJustification()](#getVerticalJustification--) | Giustificazione verticale del carattere di gruppo. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Giustificazione verticale del carattere di gruppo. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```


Argomento base

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  IMathElement baseArg = groupingCharacter.getBase();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getCharacter() {#getCharacter--}
```
public abstract char getCharacter()
```


Valore predefinito del carattere di raggruppamento: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Parentesi inferiore
> ```

**Restituisce:**
char
### setCharacter(char value) {#setCharacter-char-}
```
public abstract void setCharacter(char value)
```


Valore predefinito del carattere di raggruppamento: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Parentesi inferiore
> ```

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | char |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Posizione del carattere di raggruppamento. Predefinito: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Restituisce:**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Posizione del carattere di raggruppamento. Predefinito: Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```


Giustificazione verticale del carattere di gruppo. Specifica l’allineamento dell’oggetto rispetto alla linea di base. Ad esempio, quando il carattere di gruppo è sopra l’oggetto, VerticalJustification di Top indica che la parte superiore dell’oggetto si trova sulla linea di base; quando VerticalJustification è impostato su Bottom, la parte inferiore dell’oggetto è sulla linea di base Predefinito: Bottom per Position=Top, e Top per Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```


**Restituisce:**
int
### setVerticalJustification(int value) {#setVerticalJustification-int-}
```
public abstract void setVerticalJustification(int value)
```


Giustificazione verticale del carattere di gruppo. Specifica l’allineamento dell’oggetto rispetto alla linea di base. Ad esempio, quando il carattere di gruppo è sopra l’oggetto, VerticalJustification di Top indica che la parte superiore dell’oggetto si trova sulla linea di base; quando VerticalJustification è impostato su Bottom, la parte inferiore dell’oggetto è sulla linea di base Predefinito: Bottom per Position=Top, e Top per Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |