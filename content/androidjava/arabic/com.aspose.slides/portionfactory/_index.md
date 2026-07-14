---
title: PortionFactory
second_title: Aspose.Slides لنظام Android عبر مرجع API للجافا
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

السماح بإنشاء أجزاء اختبار

--------------------

للتوافق مع COM
## المُنشئون

| المُنشئ | الوصف |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [createPortion()](#createPortion--) | Creates an empty text portion. |
| [createPortion(String str)](#createPortion-java.lang.String-) | Creates a text portion from specified string. |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | Creates a portion with the using of a specified portion data. |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


Creates an empty text portion.

**الإرجاع:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


Creates a text portion from specified string.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| str | java.lang.String | String. |

**الإرجاع:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


Creates a portion with the using of a specified portion data.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | A portion to use. |

**الإرجاع:**
[IPortion](../../com.aspose.slides/iportion) - Portion.