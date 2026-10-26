---
title: IPortionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: يسمح بإنشاء أجزاء اختبار
type: docs
url: /ar/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

يسمح بإنشاء أجزاء اختبار

--------------------

متوافق مع COM
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createPortion()](#createPortion--) | ينشئ جزء نصي فارغ. |
| [createPortion(String str)](#createPortion-java.lang.String-) | ينشئ جزء نصي من سلسلة محددة. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | ينشئ جزءًا باستخدام بيانات جزء محددة. |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```

ينشئ جزء نصي فارغ.

**الإرجاع:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```

ينشئ جزء نصي من سلسلة محددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | java.lang.String | String. |

**الإرجاع:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public abstract IPortion createPortion(IPortion portion)
```

ينشئ جزءًا باستخدام بيانات جزء محددة.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | A portion to use. |

**الإرجاع:**
[IPortion](../../com.aspose.slides/iportion) - Portion.