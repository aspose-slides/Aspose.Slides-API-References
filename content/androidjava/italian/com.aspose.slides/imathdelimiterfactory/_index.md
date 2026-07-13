---
title: IMathDelimiterFactory
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Consente di creare un delimitatore matematico
type: docs
url: /it/com.aspose.slides/imathdelimiterfactory/
---```
public interface IMathDelimiterFactory
```

Consente di creare un delimitatore matematico

--------------------

Per compatibilità COM
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createMathDelimiter(IMathElement element)](#createMathDelimiter-com.aspose.slides.IMathElement-) | Crea un delimitatore matematico applicandolo all'elemento |
| [createMathDelimiter(IMathElementCollection mathElements)](#createMathDelimiter-com.aspose.slides.IMathElementCollection-) | Crea un delimitatore matematico applicandolo all'elemento |
### createMathDelimiter(IMathElement element) {#createMathDelimiter-com.aspose.slides.IMathElement-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElement element)
```

Crea un delimitatore matematico applicandolo all'elemento

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matematico a cui applicare il delimitatore |

**Restituisce:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - nuovo delimitatore matematico
### createMathDelimiter(IMathElementCollection mathElements) {#createMathDelimiter-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathDelimiter createMathDelimiter(IMathElementCollection mathElements)
```

Crea un delimitatore matematico applicandolo all'elemento

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | elementi matematici a cui applicare il delimitatore |

**Restituisce:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - nuovo delimitatore matematico