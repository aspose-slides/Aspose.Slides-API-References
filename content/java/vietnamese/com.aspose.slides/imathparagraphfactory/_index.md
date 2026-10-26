---
title: IMathParagraphFactory
second_title: Aspose.Slides for Java API Reference
description: Cho phép tạo một đoạn văn toán học
type: docs
url: /vi/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

Cho phép tạo một đoạn văn toán học

--------------------

Để tương thích với COM
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Tạo đoạn văn toán học rỗng |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Tạo một đoạn văn toán học và đặt khối toán học đã chỉ định vào trong đó |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```


Tạo đoạn văn toán học rỗng

**Trả về:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - đoạn văn toán học mới
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


Tạo một đoạn văn toán học và đặt khối toán học đã chỉ định vào trong đó

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | khối toán học để đặt vào đoạn văn |

**Trả về:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - đoạn văn toán học mới