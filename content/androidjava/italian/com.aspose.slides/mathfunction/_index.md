---
title: MathFunction
second_title: Riferimento API Java di Aspose.Slides per Android
description: Specifica una funzione di un argomento.
type: docs
url: /it/com.aspose.slides/mathfunction/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMathFunction](../../com.aspose.slides/imathfunction), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathFunction extends MathElementBase implements IMathFunction, IHasControlCharacterProperties
```

Specifica una funzione di un argomento.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathFunction(IMathElement funcName, IMathElement baseArgument)](#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Inizializza una nuova istanza della classe MathFunction. |
| [MathFunction(String funcName, IMathElement baseArgument)](#MathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Inizializza una nuova istanza della classe MathFunction. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getName()](#getName--) | Nome della funzione. Per esempio, i nomi delle funzioni sono sin e cos |
| [getBase()](#getBase--) | Argomento della funzione |
| [getChildren()](#getChildren--) | Ottieni gli elementi figli |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Proprietà del carattere di controllo |
### MathFunction(IMathElement funcName, IMathElement baseArgument) {#MathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public MathFunction(IMathElement funcName, IMathElement baseArgument)
```


Inizializza una nuova istanza della classe MathFunction.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction(new MathematicalText("sin"), new MathematicalText("x"));
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### MathFunction(String funcName, IMathElement baseArgument) {#MathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public MathFunction(String funcName, IMathElement baseArgument)
```


Inizializza una nuova istanza della classe MathFunction.

--------------------

> ```
> Example:
>  
>  MathFunction func = new MathFunction("sin", new MathematicalText("x"));
> ```

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| funcName | java.lang.String |  |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) |  |

### getName() {#getName--}
```
public final IMathElement getName()
```


Nome della funzione. Per esempio, i nomi delle funzioni sono sin e cos

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement funcName = func.getName();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Argomento della funzione

--------------------

> ```
> Example:
>  
>  IMathFunction func = new MathematicalText("sin").function("x");
>  IMathElement base = func.getBase();
> ```

**Restituisce:**
[IMathElement](../../com.aspose.slides/imathelement)
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```


Ottieni gli elementi figli

**Restituisce:**
com.aspose.slides.IMathElement[] - Array di [IMathElement](../../com.aspose.slides/imathelement)
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```


Proprietà del carattere di controllo

**Restituisce:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps