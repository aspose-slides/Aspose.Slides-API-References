---
title: MathLimitFactory
second_title: Riferimento API di Aspose.Slides per Java
description: Consente di creare IMathLimit
type: docs
url: /it/com.aspose.slides/mathlimitfactory/
---
**Eredità:**
java.lang.Object

**Tutte le Interfacce Implementate:**
[com.aspose.slides.IMathLimitFactory](../../com.aspose.slides/imathlimitfactory)
```
public class MathLimitFactory implements IMathLimitFactory
```

Consente di creare IMathLimit

--------------------

Per compatibilità COM
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathLimitFactory()](#MathLimitFactory--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Crea IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Crea IMathLimit con limite in basso |
### MathLimitFactory() {#MathLimitFactory--}
```
public MathLimitFactory()
```


### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Crea IMathLimit

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argomento di base a cui applicare il limite |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Elemento limite |
| upperLimit | boolean | Imposta la posizione del limite in alto |

**Restituisce:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nuovo limite matematico
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Crea IMathLimit con limite in basso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argomento di base a cui applicare il limite |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Elemento limite |

**Restituisce:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nuovo limite matematico