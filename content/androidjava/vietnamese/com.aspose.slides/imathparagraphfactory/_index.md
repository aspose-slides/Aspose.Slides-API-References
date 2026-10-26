---
title: IMathParagraphFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Cho phép tạo một đoạn toán
type: docs
url: /vi/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

Cho phép tạo một đoạn toán

--------------------

Để tương thích COM
## Phương thức

| Phương thức | Mô tả |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | Tạo đoạn toán trống |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | Tạo một đoạn toán và đặt khối toán được chỉ định vào trong |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```


Tạo đoạn toán trống

**Trả về:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - đoạn toán mới
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```


Tạo một đoạn toán và đặt khối toán được chỉ định vào trong

**Tham số:**
| Tham số | Kiểu | Mô tả |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | khối toán để đặt trong đoạn |

**Trả về:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - đoạn toán mới