---
title: IMathAccentFactory
second_title: Aspose.Slides ل Java دليل API Reference
description: يسمح بإنشاء تشديد رياضي
type: docs
url: /ar/com.aspose.slides/imathaccentfactory/
---```
public interface IMathAccentFactory
```

يسمح بإنشاء تشديد رياضي

--------------------

لتوافق COM
## Methods

| Method | Description |
| --- | --- |
| [createMathAccent(IMathElement element)](#createMathAccent-com.aspose.slides.IMathElement-) | Creates a math accent applying to a specified math element with the default accent character value |
| [createMathAccent(IMathElement element, char accentCharacter)](#createMathAccent-com.aspose.slides.IMathElement-char-) | Creates a math accent applying to a specified math element |
### createMathAccent(IMathElement element) {#createMathAccent-com.aspose.slides.IMathElement-}
```
public abstract IMathAccent createMathAccent(IMathElement element)
```

ينشئ تشديدًا رياضيًا يطبق على عنصر رياضي محدد باستخدام قيمة الحرف الافتراضية للتشديد

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الرياضي لتطبيق التشديد |

**Returns:**
[IMathAccent](../../com.aspose.slides/imathaccent) - new math accent
### createMathAccent(IMathElement element, char accentCharacter) {#createMathAccent-com.aspose.slides.IMathElement-char-}
```
public abstract IMathAccent createMathAccent(IMathElement element, char accentCharacter)
```

ينشئ تشديدًا رياضيًا يطبق على عنصر رياضي محدد

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | العنصر الرياضي لتطبيق التشديد |
| accentCharacter | char | حرف التشديد |

**Returns:**
[IMathAccent](../../com.aspose.slides/imathaccent) - new math accent