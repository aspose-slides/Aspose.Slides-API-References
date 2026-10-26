---
title: IMasterTheme
second_title: Aspose.Slides لنظام Android عبر مرجع API جافا
description: يمثل سمة رئيسية.
type: docs
url: /ar/com.aspose.slides/imastertheme/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

يمثل سمة رئيسية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | يُرجِع مجموعة مخططات الألوان الإضافية. |
| [getName()](#getName--) | يُرجِع اسم السمة. |
| [setName(String value)](#setName-java.lang.String-) | يُرجِع اسم السمة. |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```

يُرجِع مجموعة مخططات الألوان الإضافية. هذه المخططات لا تؤثر على مظهر العرض، يمكن اختيارها كمخطط اللون الرئيسي للشرائح. قراءة فقط [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection).

**قيمة الإرجاع:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```

يُرجِع اسم السمة. قراءة/كتابة String.

**قيمة الإرجاع:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

يُرجِع اسم السمة. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |