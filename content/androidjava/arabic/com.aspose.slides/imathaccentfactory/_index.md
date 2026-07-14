---
title: IMathAccentFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math accent
type: docs
url: /ar/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

يسمح بإنشاء تشديد رياضي

--------------------

لتوافق COM
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | يقوم بإنشاء تشديد رياضي يُطبق على عنصر رياضي محدد باستخدام قيمة حرف التشديد الافتراضية |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | يقوم بإنشاء تشديد رياضي يُطبق على عنصر رياضي محدد |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```


يقوم بإنشاء تشديد رياضي يُطبق على عنصر رياضي محدد باستخدام قيمة حرف التشديد الافتراضية

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الرياضي لتطبيق التشديد |

**القيمة المرجعة:**
[IMathAccent](../../com.aspose.slides/imathaccent) - تشديد رياضي جديد
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```


يقوم بإنشاء تشديد رياضي يُطبق على عنصر رياضي محدد

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الرياضي لتطبيق التشديد |
| accentCharacter | char | حرف التشديد |

**القيمة المرجعة:**
[IMathAccent](../../com.aspose.slides/imathaccent) - تشديد رياضي جديد