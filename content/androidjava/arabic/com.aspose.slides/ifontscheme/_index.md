---
title: IFontScheme
second_title: Aspose.Slides for Android via Java API Reference
description: يخزن الخطوط المعرفة في السمة.
type: docs
url: /ar/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

يخزن الخطوط المعرفة في السمة.
## الطرق

| Method | Description |
| --- | --- |
| [getMinor()](#getMinor--) | إرجاع مجموعة الخطوط للجزء "body" من الشريحة. |
| [getMajor()](#getMajor--) | إرجاع مجموعة الخطوط للجزء "heading" من الشريحة. |
| [getName()](#getName--) | إرجاع اسم مخطط الخط. |
| [setName(String value)](#setName-java.lang.String-) | إرجاع اسم مخطط الخط. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```

إرجاع مجموعة الخطوط للجزء "body" من الشريحة. للقراءة فقط [IFonts](../../com.aspose.slides/ifonts).

**الإرجاع:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```

إرجاع مجموعة الخطوط للجزء "heading" من الشريحة. للقراءة فقط [IFonts](../../com.aspose.slides/ifonts).

**الإرجاع:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```

إرجاع اسم مخطط الخط. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

إرجاع اسم مخطط الخط. قراءة/كتابة String.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |