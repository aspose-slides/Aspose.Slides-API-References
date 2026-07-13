---
title: MathBar
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Specifica la funzione di barra costituita da un argomento di base e da una barra superiore o inferiore
type: docs
url: /it/com.aspose.slides/mathbar/
---
**Ereditarietà:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMathBar](../../com.aspose.slides/imathbar), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBar extends MathElementBase implements IMathBar, IHasControlCharacterProperties
```

Specifica la funzione di barra, costituita da un argomento di base e una barra superiore o inferiore

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathBar(IMathElement element)](#MathBar-com.aspose.slides.IMathElement-) | Inizializza MathBar con barra superiore (posizione Top) |
| [MathBar(IMathElement element, int position)](#MathBar-com.aspose.slides.IMathElement-int-) | Inizializza MathBar con la posizione specificata |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBase()](#getBase--) | Argomento di base |
| [getPosition()](#getPosition--) | Posizione della linea della barra. |
| [setPosition(int value)](#setPosition-int-) | Posizione della linea della barra. |
| [getChildren()](#getChildren--) | Ottieni gli elementi figli |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Proprietà del carattere di controllo |
### MathBar(IMathElement element) {#MathBar-com.aspose.slides.IMathElement-}
```
public MathBar(IMathElement element)
```

Inizializza MathBar con barra superiore (posizione Top)

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'elemento base al quale viene applicata la barra |

### MathBar(IMathElement element, int position) {#MathBar-com.aspose.slides.IMathElement-int-}
```
public MathBar(IMathElement element, int position)
```

Inizializza MathBar con la posizione specificata

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"), MathTopBotPositions.Bottom);
> ```


**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | L'elemento base al quale viene applicata la barra |
| position | int | Posizione della linea della barra. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Argomento di base

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  IMathElement base = mathBar.getBase();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getPosition() {#getPosition--}
```
public final int getPosition()
```

Posizione della linea della barra. Predefinito: Top

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
> ```


**Restituisce:**
int
### setPosition(int value) {#setPosition-int-}
```
public final void setPosition(int value)
```

Posizione della linea della barra. Predefinito: Top

--------------------

> ```
> Example:
>  
>  MathBar mathBar = new MathBar(new MathematicalText("x"));
>  mathBar.setPosition(MathTopBotPositions.Bottom);
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