---
title: IMasterTheme
second_title: Aspose.Slides لمرجع API جافا
description: يمثّل سمة رئيسية.
type: docs
url: /ar/com.aspose.slides/imastertheme/
---
**جميع الواجهات المُنفّذة:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

يمثّل سمة رئيسية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | يُعيد مجموعة مخططات الألوان الإضافية. |
| [getName()](#getName--) | يُعيد اسم سمة. |
| [setName(String value)](#setName-java.lang.String-) | يُعيد اسم سمة. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```


يُعيد مجموعة مخططات الألوان الإضافية. لا تؤثر هذه المخططات على مظهر العرض التقديمي، ويمكن اختيارها كمخطط ألوان رئيسي لشريحة. قراءة فقط [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**الإرجاع:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```


يُعيد اسم سمة. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


يُعيد اسم سمة. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |