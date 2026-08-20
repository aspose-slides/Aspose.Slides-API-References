---
title: MathematicalTextFactory
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يسمح بإنشاء عنصر MathematicalText
type: docs
url: /ar/com.aspose.slides/mathematicaltextfactory/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IMathematicalTextFactory](../../com.aspose.slides/imathematicaltextfactory)
```
public class MathematicalTextFactory implements IMathematicalTextFactory
```

يسمح بإنشاء عنصر MathematicalText element

--------------------

للتوافق مع COM
## المنشئون

| المنشئ | الوصف |
| --- | --- |
| [MathematicalTextFactory()](#MathematicalTextFactory--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Create empty mathematical text element |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Create mathematical text element with the specified value |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Create empty mathematical text element with the specified value |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Create empty mathematical text element with the specified value and formatting properties |
### MathematicalTextFactory() {#MathematicalTextFactory--}
```
public MathematicalTextFactory()
```


### createMathematicalText() {#createMathematicalText--}
```
public final IMathematicalText createMathematicalText()
```


إنشاء عنصر نص رياضي فارغ

**القيمة المرجعة:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public final IMathematicalText createMathematicalText(char mathSymbol)
```


إنشاء عنصر نص رياضي بالقيمة المحددة

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| mathSymbol | char | رمز واحد لاستخدامه كقيمة للنص |

**القيمة المرجعة:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public final IMathematicalText createMathematicalText(String mathText)
```


إنشاء عنصر نص رياضي فارغ بالقيمة المحددة

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| mathText | java.lang.String | قيمة النص |

**القيمة المرجعة:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public final IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```


إنشاء عنصر نص رياضي فارغ بالقيمة المحددة وخصائص التنسيق

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| mathText | java.lang.String | قيمة النص |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | إعدادات تنسيق النص |

**القيمة المرجعة:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - new Mathematical Text