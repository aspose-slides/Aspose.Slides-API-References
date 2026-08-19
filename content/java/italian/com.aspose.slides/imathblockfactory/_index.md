---
title: IMathBlockFactory
second_title: Aspose.Slides for Java API Reference
description: Consente di creare un blocco matematico
type: docs
url: /it/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Consente di creare un blocco matematico

--------------------

Per compatibilità COM
## Metodi

| Method | Description |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Crea un blocco matematico |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Crea un blocco matematico e inserisci l'elemento in esso |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Crea un blocco matematico e inserisci gli elementi in esso |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```


Crea un blocco matematico

**Restituisce:**
[IMathBlock](../../com.aspose.slides/imathblock) - nuovo blocco matematico
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```


Crea un blocco matematico e inserisci l'elemento in esso

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Un elemento matematico |

**Restituisce:**
[IMathBlock](../../com.aspose.slides/imathblock) - nuovo blocco matematico
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Crea un blocco matematico e inserisci gli elementi in esso

**Parametri:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | elementi matematici |

**Restituisce:**
[IMathBlock](../../com.aspose.slides/imathblock) - nuovo blocco matematico