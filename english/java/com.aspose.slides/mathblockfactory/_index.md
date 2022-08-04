---
title: MathBlockFactory
second_title: Aspose.Sildes for Java API Reference
description: p
 Allows to create a math block
type: docs
weight: 312
url: /java/com.aspose.slides/mathblockfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathBlockFactory](../../com.aspose.slides/imathblockfactory)
```
public class MathBlockFactory implements IMathBlockFactory
```

Allows to create a math block

--------------------

For COM comparibility
## Constructors

| Constructor | Description |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Create a math block |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Create a math block and place the element in it |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Create a math block and place elements in it |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```


### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```


Create a math block

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - new math block
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
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
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Create a math block and place elements in it

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | math elements |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - new math block
