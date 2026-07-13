---
title: MathBlockFactory
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Consente di creare un blocco matematico
type: docs
url: /it/com.aspose.slides/mathblockfactory/
---
**Eredità:**
java.lang.Object

**Tutte le interfacce implementate:**
[com.aspose.slides.IMathBlockFactory](../../com.aspose.slides/imathblockfactory)
```
public class MathBlockFactory implements IMathBlockFactory
```

Consente di creare un blocco matematico

--------------------

Per compatibilità COM
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Crea un blocco matematico |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Crea un blocco matematico e posiziona l'elemento al suo interno |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Crea un blocco matematico e posiziona gli elementi al suo interno |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```


### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```


Crea un blocco matematico

**Restituisce:**
[IMathBlock](../../com.aspose.slides/imathblock) - nuovo blocco matematico
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```


Crea un blocco matematico e posiziona l'elemento al suo interno

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Un elemento matematico |

**Restituisce:**
[IMathBlock](../../com.aspose.slides/imathblock) - nuovo blocco matematico
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Crea un blocco matematico e posiziona gli elementi al suo interno

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | elementi matematici |

**Restituisce:**
[IMathBlock](../../com.aspose.slides/imathblock) - nuovo blocco matematico