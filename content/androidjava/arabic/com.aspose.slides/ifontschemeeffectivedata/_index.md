---
title: IFontSchemeEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: كائن غير قابل للتعديل يحتوي على خصائص مخطط الخطوط الفعّال.
type: docs
url: /ar/com.aspose.slides/ifontschemeeffectivedata/
---```
public interface IFontSchemeEffectiveData
```

كائن غير قابل للتعديل يحتوي على خصائص مخطط الخطوط الفعّال.

--------------------

يتم استخدام هذه الواجهة كجزء من [IThemeEffectiveData](../../com.aspose.slides/ithemeeffectivedata).
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getMinor()](#getMinor--) | يعيد مجموعة الخطوط لجزء "body" من الشريحة. |
| [getMajor()](#getMajor--) | يعيد مجموعة الخطوط لجزء "heading" من الشريحة. |
| [getName()](#getName--) | يعيد اسم مخطط الخطوط. |

### getMinor() {#getMinor--}
```
public abstract IFontsEffectiveData getMinor()
```

يعيد مجموعة الخطوط لجزء "body" من الشريحة. قراءة فقط [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**الإرجاع:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)

### getMajor() {#getMajor--}
```
public abstract IFontsEffectiveData getMajor()
```

يعيد مجموعة الخطوط لجزء "heading" من الشريحة. قراءة فقط [IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata).

**الإرجاع:**
[IFontsEffectiveData](../../com.aspose.slides/ifontseffectivedata)

### getName() {#getName--}
```
public abstract String getName()
```

يعيد اسم مخطط الخطوط. قراءة فقط String.

**الإرجاع:**
java.lang.String