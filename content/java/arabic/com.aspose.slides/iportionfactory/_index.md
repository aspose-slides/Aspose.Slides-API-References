---
title: IPortionFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create test portions
type: docs
url: /ar/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

يسمح بإنشاء أجزاء اختبار

--------------------

للتوافق مع COM
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createPortion()](#createPortion--) | ينشئ جزء نصي فارغ. |
| [createPortion(String str)](#createPortion-java.lang.String-) | ينشئ جزءًا نصيًا من سلسلة محددة. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | ينشئ جزءًا باستخدام بيانات جزء محدد. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


ينشئ جزءًا نصيًا فارغًا.

**القيمة المرجعة:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


ينشئ جزءًا نصيًا من سلسلة محددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | java.lang.String | سلسلة. |

**القيمة المرجعة:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```


ينشئ جزءًا باستخدام بيانات جزء محدد.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | جزء للاستخدام. |

**القيمة المرجعة:**
[IPortion](../../com.aspose.slides/iportion) - Portion.