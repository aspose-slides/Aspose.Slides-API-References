---
title: IMathBlockFactory
second_title: Aspose.Slides برای Android از طریق Java API Reference
description: اجازه می‌دهد یک بلوک ریاضی ایجاد کند
type: docs
url: /fa/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

اجازه می‌دهد یک بلوک ریاضی ایجاد کند

--------------------

برای سازگاری COM
## متدها

| متد | توضیح |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | یک بلوک ریاضی ایجاد می‌کند |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | یک بلوک ریاضی ایجاد می‌کند و عنصر را در آن قرار می‌دهد |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | یک بلوک ریاضی ایجاد می‌کند و عناصر را در آن قرار می‌دهد |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```


یک بلوک ریاضی ایجاد می‌کند

**بازگشت:**
[IMathBlock](../../com.aspose.slides/imathblock) - بلوک ریاضی جدید
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```


یک بلوک ریاضی ایجاد می‌کند و عنصر را در آن قرار می‌دهد

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | یک عنصر ریاضی |

**بازگشت:**
[IMathBlock](../../com.aspose.slides/imathblock) - بلوک ریاضی جدید
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```


یک بلوک ریاضی ایجاد می‌کند و عناصر را در آن قرار می‌دهد

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | عناصر ریاضی |

**بازگشت:**
[IMathBlock](../../com.aspose.slides/imathblock) - بلوک ریاضی جدید