---
title: PortionFactory
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يسمح بإنشاء أجزاء اختبار
type: docs
url: /ar/com.aspose.slides/portionfactory/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

يسمح بإنشاء أجزاء اختبار

--------------------

للتوافق مع COM
## المُنشئات

| المُنشئ | الوصف |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createPortion()](#createPortion--) | إنشاء جزء نصي فارغ. |
| [createPortion(String str)](#createPortion-java.lang.String-) | إنشاء جزء نصي من سلسلة محددة. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | إنشاء جزء باستخدام بيانات جزء محددة. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


إنشاء جزء نصي فارغ.

**القيمة المرجعة:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


إنشاء جزء نصي من سلسلة محددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | java.lang.String | String. |

**القيمة المرجعة:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


إنشاء جزء باستخدام بيانات جزء محددة.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | جزء للاستخدام. |

**القيمة المرجعة:**
[IPortion](../../com.aspose.slides/iportion) - Portion.