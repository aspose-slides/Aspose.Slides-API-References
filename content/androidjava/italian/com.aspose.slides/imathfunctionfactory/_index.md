---
title: IMathFunctionFactory
second_title: Aspose.Slides per Android tramite Java API Reference
description: Consente di creare una funzione matematica
type: docs
url: /it/com.aspose.slides/imathfunctionfactory/
---```
public interface IMathFunctionFactory
```

Consente di creare una funzione matematica

--------------------

Per compatibilità COM
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createMathFunction(IMathElement funcName, IMathElement baseArgument)](#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea funzione matematica |
| [createMathFunction(String funcName, IMathElement baseArgument)](#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-) | Crea funzione matematica |
### createMathFunction(IMathElement funcName, IMathElement baseArgument) {#createMathFunction-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(IMathElement funcName, IMathElement baseArgument)
```


Crea funzione matematica

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| funcName | [IMathElement](../../com.aspose.slides/imathelement) | Elemento usato come nome della funzione |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Elemento usato come argomento della funzione |

**Restituisce:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nuova funzione matematica
### createMathFunction(String funcName, IMathElement baseArgument) {#createMathFunction-java.lang.String-com.aspose.slides.IMathElement-}
```
public abstract IMathFunction createMathFunction(String funcName, IMathElement baseArgument)
```


Crea funzione matematica

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| funcName | java.lang.String | Nome della funzione |
| baseArgument | [IMathElement](../../com.aspose.slides/imathelement) | Elemento usato come argomento della funzione |

**Restituisce:**
[IMathFunction](../../com.aspose.slides/imathfunction) - nuova funzione matematica