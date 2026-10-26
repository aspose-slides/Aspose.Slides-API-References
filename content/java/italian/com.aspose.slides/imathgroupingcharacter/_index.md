---
title: IMathGroupingCharacter
second_title: Riferimento API di Aspose.Slides per Java
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

| Metodo | Descrizione |
| --- | --- |
| [getBase()](#getBase--) | Argomento base |
| [getCharacter()](#getCharacter--) | Carattere di raggruppamento Valore predefinito: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Carattere di raggruppamento Valore predefinito: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Posizione del carattere di raggruppamento. |
| [setPosition(int value)](#setPosition-int-) | Posizione del carattere di raggruppamento. |
| [getVerticalJustification()](#getVerticalJustification--) | Giustificazione verticale del carattere di raggruppamento. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Giustificazione verticale del carattere di raggruppamento. |
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

Carattere di raggruppamento Valore predefinito: U+23DF (BOTTOM CURLY BRACKET)

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

Carattere di raggruppamento Valore predefinito: U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setCharacter('\u23dd'); // Parentesi inferiore
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
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
> Esempio:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setPosition(MathTopBotPositions.Top);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getVerticalJustification() {#getVerticalJustification--}
```
public abstract int getVerticalJustification()
```

Giustificazione verticale del carattere di raggruppamento. Specifica l'allineamento dell'oggetto rispetto alla linea base. Per esempio, quando il carattere di raggruppamento è sopra l'oggetto, VerticalJustification di Top indica che la parte superiore dell'oggetto cade sulla linea base; quando VerticalJustification è impostata a Bottom, la parte inferiore dell'oggetto è sulla linea base Valore predefinito: Bottom per Position=Top, e Top per Position=Bottom

--------------------

> ```
> Esempio:
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

Giustificazione verticale del carattere di raggruppamento. Specifica l'allineamento dell'oggetto rispetto alla linea base. Per esempio, quando il carattere di raggruppamento è sopra l'oggetto, VerticalJustification di Top indica che la parte superiore dell'oggetto cade sulla linea base; quando VerticalJustification è impostata a Bottom, la parte inferiore dell'oggetto è sulla linea base Valore predefinito: Bottom per Position=Top, e Top per Position=Bottom

--------------------

> ```
> Esempio:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |