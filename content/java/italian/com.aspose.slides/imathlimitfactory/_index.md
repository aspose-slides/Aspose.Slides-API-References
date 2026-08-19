---
title: IMathLimitFactory
second_title: Aspose.Slides for Java API Reference
description: Consente di creare IMathLimit
type: docs
url: /it/com.aspose.slides/imathlimitfactory/
---```
public interface IMathLimitFactory
```

Consente di creare IMathLimit

--------------------

Per compatibilità COM
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-) | Creates IMathLimit |
| [createMathLimit(IMathElement baseArg, IMathElement limit)](#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates IMathLimit with limit at the bottom |
### createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-boolean-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit, boolean upperLimit)
```


Crea IMathLimit

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argomento di base a cui applicare il limite |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Elemento limite |
| upperLimit | boolean | Imposta il posizionamento del limite in alto |

**Restituisce:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nuovo limite matematico
### createMathLimit(IMathElement baseArg, IMathElement limit) {#createMathLimit-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public abstract IMathLimit createMathLimit(IMathElement baseArg, IMathElement limit)
```


Crea IMathLimit con limite in basso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| baseArg | [IMathElement](../../com.aspose.slides/imathelement) | Argomento di base a cui applicare il limite |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | Elemento limite |

**Restituisce:**
[IMathLimit](../../com.aspose.slides/imathlimit) - nuovo limite matematico