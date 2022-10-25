---
title: IMathBlockFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math block
type: docs
weight: 886
url: /androidjava/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Allows to create a math block

--------------------

For COM comparibility
## Methods

| Method | Description |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Create a math block |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Create a math block and place the element in it |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Create a math block and place elements in it |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```


Create a math block

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - new math block
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```


Create a math block and place the element in it

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | A math element |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - new math block
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Create a math block and place elements in it

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | math elements |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - new math block
