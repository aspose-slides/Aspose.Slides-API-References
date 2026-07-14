---
title: MathAccentFactory
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يسمح بإنشاء تظليل رياضي
type: docs
url: /ar/com.aspose.slides/mathaccentfactory/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المُنفذة:**
[com.aspose.slides.IMathAccentFactory](../../com.aspose.slides/imathaccentfactory)
```
public class MathAccentFactory implements IMathAccentFactory
```

يسمح بإنشاء تظليل رياضي

--------------------

للتوافق مع COM
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [MathAccentFactory()](#MathAccentFactory--) |  |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | ينشئ تظليلًا رياضيًا يُطبق على عنصر رياضي محدد باستخدام قيمة حرف التظليل الافتراضية |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | ينشئ تظليلًا رياضيًا يُطبق على عنصر رياضي محدد |
### MathAccentFactory() {#MathAccentFactory--}
```
public MathAccentFactory()
```


### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public final IMathAccent createMathAccent(IMathElement element)
```


ينشئ تظليلًا رياضيًا يُطبق على عنصر رياضي محدد باستخدام قيمة حرف التظليل الافتراضية

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الرياضي لتطبيق التظليل عليه |

**القيمة المرجعة:**
[IMathAccent](../../com.aspose.slides/imathaccent) - تظليل رياضي جديد
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public final IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


ينشئ تظليلًا رياضيًا يُطبق على عنصر رياضي محدد

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الرياضي لتطبيق التظليل عليه |
| accentCharacter | char | حرف التظليل |

**القيمة المرجعة:**
[IMathAccent](../../com.aspose.slides/imathaccent) - تظليل رياضي جديد