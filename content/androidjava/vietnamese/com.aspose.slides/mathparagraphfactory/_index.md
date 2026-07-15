---
title: MathParagraphFactory
second_title: Aspose.Slides cho Android qua Tham chiếu API Java
description: Cho phép tạo một đoạn văn toán học
type: docs
url: /vi/com.aspose.slides/mathparagraphfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathParagraphFactory](../../com.aspose.slides/imathparagraphfactory)
```
public class MathParagraphFactory implements IMathParagraphFactory
```

Cho phép tạo một đoạn văn toán học

--------------------

Để tương thích COM
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [MathParagraphFactory()](#MathParagraphFactory--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Tạo đoạn văn toán học trống |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Tạo một đoạn văn toán học và đặt khối toán học đã chỉ định vào trong nó |
### MathParagraphFactory() {#MathParagraphFactory--}
```
public MathParagraphFactory()
```


### createMathParagraph() {#createMathParagraph--}
```
public final IMathParagraph createMathParagraph()
```


Tạo đoạn văn toán học trống

**Trả về:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - đoạn văn toán học mới
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public final IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


Tạo một đoạn văn toán học và đặt khối toán học đã chỉ định vào trong nó

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | khối toán học để đặt vào đoạn văn |

**Trả về:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - đoạn văn toán học mới