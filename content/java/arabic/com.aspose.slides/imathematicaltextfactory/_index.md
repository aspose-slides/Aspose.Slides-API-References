---
title: IMathematicalTextFactory
second_title: Aspose.Slides for Java API Reference
description: يسمح بإنشاء عنصر MathematicalText
type: docs
url: /ar/com.aspose.slides/imathematicaltextfactory/
---```
public interface IMathematicalTextFactory
```

يسمح بإنشاء عنصر MathematicalText

--------------------

للتوافق مع COM
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createMathematicalText()](#createMathematicalText--) | Create empty mathematical text element |
| [createMathematicalText(char mathSymbol)](#createMathematicalText-char-) | Create mathematical text element with the specified value |
| [createMathematicalText(String mathText)](#createMathematicalText-java.lang.String-) | Create empty mathematical text element with the specified value |
| [createMathematicalText(String mathText, IPortionFormat portionFormat)](#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-) | Create empty mathematical text element with the specified value and formatting properties |
### createMathematicalText() {#createMathematicalText--}
```
public abstract IMathematicalText createMathematicalText()
```

إنشاء عنصر Mathematical Text فارغ

**القيمة المرجعة:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - جديد Mathematical Text
### createMathematicalText(char mathSymbol) {#createMathematicalText-char-}
```
public abstract IMathematicalText createMathematicalText(char mathSymbol)
```

إنشاء عنصر Mathematical Text مع القيمة المحددة

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathSymbol | char | رمز واحد لاستخدامه كقيمة نص |

**القيمة المرجعة:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - جديد Mathematical Text
### createMathematicalText(String mathText) {#createMathematicalText-java.lang.String-}
```
public abstract IMathematicalText createMathematicalText(String mathText)
```

إنشاء عنصر Mathematical Text فارغ بالقيمة المحددة

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathText | java.lang.String | قيمة النص |

**القيمة المرجعة:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - جديد Mathematical Text
### createMathematicalText(String mathText, IPortionFormat portionFormat) {#createMathematicalText-java.lang.String-com.aspose.slides.IPortionFormat-}
```
public abstract IMathematicalText createMathematicalText(String mathText, IPortionFormat portionFormat)
```

إنشاء عنصر Mathematical Text فارغ بالقيمة المحددة وخصائص التنسيق

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| mathText | java.lang.String | قيمة النص |
| portionFormat | [IPortionFormat](../../com.aspose.slides/iportionformat) | إعدادات تنسيق النص |

**القيمة المرجعة:**
[IMathematicalText](../../com.aspose.slides/imathematicaltext) - جديد Mathematical Text