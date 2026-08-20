---
title: MathAccentFactory
second_title: مرجع API ل Aspose.Slides للغة Java
description: يسمح بإنشاء لهجة رياضية
type: docs
url: /ar/com.aspose.slides/mathaccentfactory/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

يسمح بإنشاء لهجة رياضية

--------------------

للتوافق مع COM
## المُنشئات

| المنشئ | الوصف |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Creates a math accent applying to a specified math element with the default accent character value |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Creates a math accent applying to a specified math element |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```


ينشئ لهجة رياضية تُطبق على عنصر رياضي محدد باستخدام قيمة حرف اللهجة الافتراضية

**المعلمات:**
| المعامِل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الرياضي لتطبيق اللهجة |

**القيمة المرجعة:**
[IMathAccent](../../com.aspose.slides/imathaccent) - لهجة رياضية جديدة
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


ينشئ لهجة رياضية تُطبق على عنصر رياضي محدد

**المعلمات:**
| المعامِل | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الرياضي لتطبيق اللهجة |
| accentCharacter | char | حرف اللهجة |

**القيمة المرجعة:**
[IMathAccent](../../com.aspose.slides/imathaccent) - لهجة رياضية جديدة