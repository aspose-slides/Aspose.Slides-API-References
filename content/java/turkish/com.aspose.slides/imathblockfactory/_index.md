---
title: IMathBlockFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math block
type: docs
url: /tr/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Matematik bloğu oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Matematik bloğu oluştur |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Matematik bloğu oluştur ve öğeyi içine yerleştir |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Matematik bloğu oluştur ve öğeleri içine yerleştir |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```


Matematik bloğu oluştur

**Döndürür:**
[IMathBlock](../../com.aspose.slides/imathblock) - yeni bir matematik bloğu
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```


Matematik bloğu oluştur ve öğeyi içine yerleştir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Bir matematik öğesi |

**Döndürür:**
[IMathBlock](../../com.aspose.slides/imathblock) - yeni bir matematik bloğu
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Matematik bloğu oluştur ve öğeleri içine yerleştir

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | matematik öğeleri |

**Döndürür:**
[IMathBlock](../../com.aspose.slides/imathblock) - yeni bir matematik bloğu