---
title: MathGroupingCharacter
second_title: Aspose.Slides per Android tramite Java API Reference
description: Specifica un simbolo di raggruppamento sopra o sotto un'espressione, solitamente per evidenziare la relazione tra gli elementi
type: docs
url: /it/com.aspose.slides/mathgroupingcharacter/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathGroupingCharacter extends MathElementBase implements IMathGroupingCharacter, IHasControlCharacterProperties
```

Specifica un simbolo di raggruppamento sopra o sotto un'espressione, solitamente per evidenziare la relazione tra gli elementi

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathGroupingCharacter(IMathElement element)](#MathGroupingCharacter-com.aspose.slides.IMathElement-) | Inizializza una nuova istanza della classe MathGroupingCharacter con il carattere di raggruppamento predefinito U+23DF (BOTTOM CURLY BRACKET) |
| [MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Inizializza una nuova istanza della classe MathGroupingCharacter. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBase()](#getBase--) | Argomento di base |
| [getCharacter()](#getCharacter--) | Carattere di raggruppamento Valore predefinito: U+23DF (BOTTOM CURLY BRACKET) |
| [setCharacter(char value)](#setCharacter-char-) | Carattere di raggruppamento Valore predefinito: U+23DF (BOTTOM CURLY BRACKET) |
| [getPosition()](#getPosition--) | Posizione del carattere di raggruppamento. |
| [setPosition(int value)](#setPosition-int-) | Posizione del carattere di raggruppamento. |
| [getVerticalJustification()](#getVerticalJustification--) | Allineamento verticale del carattere di raggruppamento. |
| [setVerticalJustification(int value)](#setVerticalJustification-int-) | Allineamento verticale del carattere di raggruppamento. |
| [getChildren()](#getChildren--) | Ottieni gli elementi figli |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Proprietà del carattere di controllo |
### MathGroupingCharacter(IMathElement element) {#MathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public MathGroupingCharacter(IMathElement element)
```

Inizializza una nuova istanza della classe MathGroupingCharacter con il carattere di raggruppamento predefinito U+23DF (BOTTOM CURLY BRACKET)

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'elemento base a cui viene applicata la barra |

### MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#MathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public MathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Inizializza una nuova istanza della classe MathGroupingCharacter.

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"), '_', MathTopBotPositions.Top, MathTopBotPositions.Bottom);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'elemento base a cui viene applicata la barra |
| character | char | Carattere di raggruppamento |
| position | int | Posizione del carattere di raggruppamento |
| verticalJustification | int | Allineamento verticale del carattere di raggruppamento |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argomento di base

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
public final char getCharacter()
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
public final void setCharacter(char value)
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
public final int getPosition()
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
public final void setPosition(int value)
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getVerticalJustification() {#getVerticalJustification--}
```
public final int getVerticalJustification()
```

Allineamento verticale del carattere di raggruppamento. Specifica l'allineamento dell'oggetto rispetto alla linea di base. Ad esempio, quando il carattere di raggruppamento è sopra l'oggetto, VerticalJustification di Top indica che la parte superiore dell'oggetto si trova sulla linea di base; quando VerticalJustification è impostato a Bottom, la parte inferiore dell'oggetto è sulla linea di base Predefinito: Bottom per Position=Top e Top per Position=Bottom

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
public final void setVerticalJustification(int value)
```

Allineamento verticale del carattere di raggruppamento. Specifica l'allineamento dell'oggetto rispetto alla linea di base. Ad esempio, quando il carattere di raggruppamento è sopra l'oggetto, VerticalJustification di Top indica che la parte superiore dell'oggetto si trova sulla linea di base; quando VerticalJustification è impostato a Bottom, la parte inferiore dell'oggetto è sulla linea di base Predefinito: Bottom per Position=Top e Top per Position=Bottom

--------------------

> ```
> Example:
>  
>  MathGroupingCharacter groupingCharacter = new MathGroupingCharacter(new MathematicalText("abc"));
>  groupingCharacter.setVerticalJustification(MathTopBotPositions.Top);
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Ottieni gli elementi figli

**Restituisce:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Proprietà del carattere di controllo

**Restituisce:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps