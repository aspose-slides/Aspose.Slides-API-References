---
title: IMathBlockFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math block
type: docs
url: /tr/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Matematik bloğu oluşturmayı sağlar

--------------------

COM uyumluluğu için
## Methods

| Method | Description |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Bir matematik bloğu oluşturur |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Bir matematik bloğu oluşturur ve öğeyi içine yerleştirir |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Bir matematik bloğu oluşturur ve öğeleri içine yerleştirir |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```


Bir matematik bloğu oluşturur

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - yeni matematik bloğu
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```


Bir matematik bloğu oluşturur ve öğeyi içine yerleştirir

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Bir matematik öğesi |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - yeni matematik bloğu
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Bir matematik bloğu oluşturur ve öğeleri içine yerleştirir

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | matematik öğeleri |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - yeni matematik bloğu