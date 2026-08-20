---
title: IMathBlockFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math block
type: docs
url: /vi/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

Cho phép tạo một khối toán

--------------------

Để tương thích COM
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Tạo một khối toán |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Tạo một khối toán và đặt phần tử vào trong đó |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Tạo một khối toán và đặt các phần tử vào trong đó |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

Tạo một khối toán

**Trả về:**
[IMathBlock](../../com.aspose.slides/imathblock) - khối toán mới
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

Tạo một khối toán và đặt phần tử vào trong đó

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Một phần tử toán |

**Trả về:**
[IMathBlock](../../com.aspose.slides/imathblock) - khối toán mới
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

Tạo một khối toán và đặt các phần tử vào trong đó

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | các phần tử toán |

**Trả về:**
[IMathBlock](../../com.aspose.slides/imathblock) - khối toán mới