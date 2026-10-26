---
title: IMathBlockFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math block
type: docs
url: /it/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Consente di creare un blocco matematico

--------------------

Per compatibilità COM
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Crea un blocco matematico |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Crea un blocco matematico e posiziona l'elemento al suo interno |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Crea un blocco matematico e posiziona gli elementi al suo interno |
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


Crea un blocco matematico e posiziona l'elemento al suo interno

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Un elemento matematico |

**Restituisce:**
[IMathBlock](../../com.aspose.slides/imathblock) - nuovo blocco matematico
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Crea un blocco matematico e posiziona gli elementi al suo interno

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | elementi matematici |

**Restituisce:**
[IMathBlock](../../com.aspose.slides/imathblock) - nuovo blocco matematico