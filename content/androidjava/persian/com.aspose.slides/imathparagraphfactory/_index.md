---
title: IMathParagraphFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math paragraph
type: docs
url: /fa/com.aspose.slides/imathparagraphfactory/
---```
public interface IMathParagraphFactory
```

اجازه می‌دهد یک پاراگراف ریاضی ایجاد شود

--------------------

برای سازگاری با COM
## متدها

| Method | Description |
| --- | --- |
| [createMathParagraph()](#createMathParagraph--) | ایجاد پاراگراف ریاضی خالی |
| [createMathParagraph(IMathBlock mathBlock)](#createMathParagraph-com.aspose.slides.IMathBlock-) | یک پاراگراف ریاضی ایجاد می‌کند و بلوک ریاضی مشخص شده را در آن قرار می‌دهد |
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


یک پاراگراف ریاضی ایجاد می‌کند و بلوک ریاضی مشخص شده را در آن قرار می‌دهد

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| mathBlock | [IMathBlock](../../com.aspose.slides/imathblock) | بلوک ریاضی برای قرار دادن در پاراگراف |

**بازگشت:**
[IMathParagraph](../../com.aspose.slides/imathparagraph) - پاراگراف ریاضی جدید