---
title: MathBlockFactory
second_title: Aspose.Slides cho Android thông qua Tham chiếu API Java
description: Cho phép tạo một khối toán học
type: docs
url: /vi/com.aspose.slides/mathblockfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathBlockFactory](../../com.aspose.slides/imathblockfactory)
```
public class MathBlockFactory implements IMathBlockFactory
```

Cho phép tạo một khối toán học

--------------------

Để tương thích COM
## Constructors

| Constructor | Description |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Tạo một khối toán học |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Tạo một khối toán học và đặt phần tử vào trong đó |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Tạo một khối toán học và đặt các phần tử vào trong đó |
### MathBlockFactory() {#MathBlockFactory--}
```
public MathBlockFactory()
```


### createMathBlock() {#createMathBlock--}
```
public final IMathBlock createMathBlock()
```


Tạo một khối toán học

**Trả về:**
[IMathBlock](../../com.aspose.slides/imathblock) - khối toán học mới
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public final IMathBlock createMathBlock(IMathElement mathElement)
```


Tạo một khối toán học và đặt phần tử vào trong đó

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Một phần tử toán học |

**Trả về:**
[IMathBlock](../../com.aspose.slides/imathblock) - khối toán học mới
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Tạo một khối toán học và đặt các phần tử vào trong đó

**Tham số:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | các phần tử toán học |

**Trả về:**
[IMathBlock](../../com.aspose.slides/imathblock) - khối toán học mới