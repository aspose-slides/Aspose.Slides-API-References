---
title: IMathBlockFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math block
type: docs
url: /fa/com.aspose.slides/imathblockfactory/
---```
public interface IMathBlockFactory
```

اجازه ایجاد یک بلوک ریاضی را می‌دهد

--------------------

برای سازگاری COM
## متدها

| متد | توضیح |
| --- | --- |
| [createMathBlock()](#createMathBlock--) | ایجاد یک بلوک ریاضی |
| [createMathBlock(IMathElement mathElement)](#createMathBlock-com.aspose.slides.IMathElement-) | ایجاد یک بلوک ریاضی و قرار دادن عنصر در آن |
| [createMathBlock(IMathElementCollection mathElements)](#createMathBlock-com.aspose.slides.IMathElementCollection-) | ایجاد یک بلوک ریاضی و قرار دادن عناصر در آن |
### createMathBlock() {#createMathBlock--}
```
public abstract IMathBlock createMathBlock()
```

ایجاد یک بلوک ریاضی

**بازمی‌گرداند:**
[IMathBlock](../../com.aspose.slides/imathblock) - بلوک ریاضی جدید
### createMathBlock(IMathElement mathElement) {#createMathBlock-com.aspose.slides.IMathElement-}
```
public abstract IMathBlock createMathBlock(IMathElement mathElement)
```

ایجاد یک بلوک ریاضی و قرار دادن عنصر در آن

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | یک عنصر ریاضی |

**بازمی‌گرداند:**
[IMathBlock](../../com.aspose.slides/imathblock) - بلوک ریاضی جدید
### createMathBlock(IMathElementCollection mathElements) {#createMathBlock-com.aspose.slides.IMathElementCollection-}
```
public abstract IMathBlock createMathBlock(IMathElementCollection mathElements)
```

ایجاد یک بلوک ریاضی و قرار دادن عناصر در آن

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| mathElements | [IMathElementCollection](../../com.aspose.slides/imathelementcollection) | عناصر ریاضی |

**بازمی‌گرداند:**
[IMathBlock](../../com.aspose.slides/imathblock) - بلوک ریاضی جدید