---
title: MathBlockFactory
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cho phép tạo một khối toán học
type: docs
url: /vi/com.aspose.slides/mathblockfactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả giao diện đã triển khai:**
[com.aspose.slides.IMathBlockFactory](../../com.aspose.slides/imathblockfactory)
```
public class MathBlockFactory implements IMathBlockFactory
```

Cho phép tạo một khối toán học

--------------------

Để tương thích COM
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [MathBlockFactory()](#MathBlockFactory--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | Tạo một khối toán học |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | Tạo một khối toán học và đặt phần tử vào trong |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | Tạo một khối toán học và đặt các phần tử vào trong |
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


Tạo một khối toán học và đặt phần tử vào trong

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Một phần tử toán học |

**Trả về:**
[IMathBlock](../../com.aspose.slides/imathblock) - khối toán học mới
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public final IMathBlock createMathBlock(IMathElementCollection mathElements)
```


Tạo một khối toán học và đặt các phần tử vào trong

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | các phần tử toán học |

**Trả về:**
[IMathBlock](../../com.aspose.slides/imathblock) - khối toán học mới