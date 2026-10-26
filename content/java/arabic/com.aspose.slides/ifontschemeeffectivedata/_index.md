---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Java API Reference
description: كائن غير قابل للتغيير يحتوي على خصائص مخطط الخطوط الفعّالة.
type: docs
url: /ar/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

كائن غير قابل للتغيير يحتوي على خصائص مخطط الخطوط الفعّالة.

--------------------

يتم استخدام هذه الواجهة كجزء من [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getMinor()](#getMinor--) | يرجع مجموعة الخطوط لجزء "body" من الشريحة. |
| [getMajor()](#getMajor--) | يرجع مجموعة الخطوط لجزء "heading" من الشريحة. |
| [getName()](#getName--) | يرجع اسم مخطط الخطوط. |
### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```

يرجع مجموعة الخطوط لجزء "body" من الشريحة. للقراءة فقط [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**الإرجاع:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```

يرجع مجموعة الخطوط لجزء "heading" من الشريحة. للقراءة فقط [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**الإرجاع:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)
### getName() {#getName--}
```
public abstract String getName()
```

يرجع اسم مخطط الخطوط. للقراءة فقط String.

**الإرجاع:**
java.lang.String