---
title: IFontScheme
second_title: Aspose.Slides for Java API Reference
description: يخزن الخطوط المعرفة في السمة.
type: docs
url: /ar/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

يخزن الخطوط المعرفة في السمة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getMinor()](#getMinor--) | يعيد مجموعة الخطوط لجزء "body" من الشريحة. |
| [getMajor()](#getMajor--) | يعيد مجموعة الخطوط لجزء "heading" من الشريحة. |
| [getName()](#getName--) | يعيد اسم مخطط الخط. |
| [setName(String value)](#setName-java.lang.String-) | يعيد اسم مخطط الخط. |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```


يعيد مجموعة الخطوط لجزء "body" من الشريحة. للقراءة فقط [IFonts](../../com.aspose.slides/ifonts).

**الإرجاع:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```


يعيد مجموعة الخطوط لجزء "heading" من الشريحة. للقراءة فقط [IFonts](../../com.aspose.slides/ifonts).

**الإرجاع:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```


يعيد اسم مخطط الخط. قراءة/كتابة String.

**الإرجاع:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


يعيد اسم مخطط الخط. قراءة/كتابة String.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String |  |