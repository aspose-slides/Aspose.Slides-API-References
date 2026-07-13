---
title: MathFunctionFactory
second_title: Riferimento API Java di Aspose.Slides per Android
description: Consente di creare una funzione matematica
type: docs
url: /it/com.aspose.slides/mathfunctionfactory/
---
**Ereditarietà:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IMathFunctionFactory](../../com.aspose.slides/imathfunctionfactory)
```
public class MathFunctionFactory implements IMathFunctionFactory
```

Consente di creare una funzione matematica

--------------------

Per compatibilità COM
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathFunctionFactory()](#MathFunctionFactory--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea una funzione matematica |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Crea una funzione matematica |
### MathFunctionFactory() {#MathFunctionFactory--}
```
public MathFunctionFactory()
```


### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Crea una funzione matematica

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Elemento usato come nome della funzione |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Elemento usato come argomento della funzione |

**Restituisce:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nuova funzione matematica
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public final IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Crea una funzione matematica

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| funcName | java.lang.String | Nome della funzione |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Elemento usato come argomento della funzione |

**Restituisce:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nuova funzione matematica