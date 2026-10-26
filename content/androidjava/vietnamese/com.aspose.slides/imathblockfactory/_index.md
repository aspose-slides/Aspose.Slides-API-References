---
title: IMathBlockFactory
second_title: Aspose.Slides cho Android qua Java API Reference
description: Cho phép tạo một khối toán học
type: docs
url: /vi/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Cho phép tạo một khối toán học

--------------------

For COM comparibility
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Tạo một khối toán học |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Tạo một khối toán học và đặt phần tử vào trong nó |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Tạo một khối toán học và đặt các phần tử vào trong nó |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

Tạo một khối toán học

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - khối toán học mới
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

Tạo một khối toán học và đặt phần tử vào trong nó

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Một phần tử toán học |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - khối toán học mới
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

Tạo một khối toán học và đặt các phần tử vào trong nó

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | các phần tử toán học |

**Returns:**
[IMathBlock](../../com.aspose.slides/imathblock) - khối toán học mới