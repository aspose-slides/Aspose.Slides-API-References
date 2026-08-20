---
title: MathParagraphFactory
second_title: Tham chiếu API Aspose.Slides cho Java
description: Cho phép tạo một đoạn toán
type: docs
url: /vi/com.aspose.slides/mathparagraphfactory/
---
**Kế thừa:**
java.lang.Object

**Tất cả các giao diện được thực thi:**
[com.aspose.slides.IMathParagraphFactory](../../com.aspose.slides/imathparagraphfactory)
```
public class MathParagraphFactory implements IMathParagraphFactory
```

Cho phép tạo một đoạn toán

--------------------

Đối với khả năng tương thích COM
## Các hàm khởi tạo

| Hàm khởi tạo | Mô tả |
| --- | --- |
| [MathParagraphFactory()](#MathParagraphFactory--) |  |
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Tạo đoạn toán trống |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Tạo một đoạn toán và đặt khối toán được chỉ định vào trong đó |
### MathParagraphFactory() {#MathParagraphFactory--}
```
public MathParagraphFactory()
```


### createMathParagraph() {#createMathParagraph--}
```
public final IMathParagraph createMathParagraph()
```


Tạo đoạn toán trống

**Trả về:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - đoạn toán mới
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public final IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


Tạo một đoạn toán và đặt khối toán được chỉ định vào trong đó

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | khối toán để đặt vào đoạn |

**Trả về:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - đoạn toán mới