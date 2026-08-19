---
title: IMathParagraphFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math paragraph
type: docs
url: /fa/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

به شما امکان ایجاد یک پاراگراف ریاضی را می‌دهد

--------------------

برای سازگاری با COM
## متدها

| متد | توضیح |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | ایجاد پاراگراف ریاضی خالی |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | ایجاد یک پاراگراف ریاضی و قرار دادن بلوک ریاضی مشخص‌شده در آن |
### createMathParagraph() {#createMathParagraph--}
```
public abstract IMathParagraph createMathParagraph()
```

ایجاد پاراگراف ریاضی خالی

**بازگشت:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - پاراگراف ریاضی جدید
### createMathParagraph(IMathBlock mathBlock) {#createMathParagraph-com.aspose.slides.IMathBlock-}
```
public abstract IMathParagraph createMathParagraph(IMathBlock mathBlock)
```

یک پاراگراف ریاضی ایجاد می‌کند و بلوک ریاضی مشخص‌شده را در آن قرار می‌دهد

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | بلوک ریاضی برای قرار دادن در پاراگراف |

**بازگشت:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - پاراگراف ریاضی جدید