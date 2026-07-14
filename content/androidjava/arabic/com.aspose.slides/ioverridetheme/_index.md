---
title: IOverrideTheme
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل سمةً متجاوزة.
type: docs
url: /ar/com.aspose.slides/ioverridetheme/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

يمثل سمةً متجاوزة.
## الأساليب

| الطريقة | الوصف |
| --- | --- |
| [isEmpty()](#isEmpty--) | القيمة true تعني أن ColorScheme و FontScheme و FormatScheme هي null وأي تجاوز باستخدام كائن السمة هذا مُعطَّل. |
| [initColorScheme()](#initColorScheme--) | تهيئة ColorScheme باستخدام كائن جديد لتجاوز ColorScheme الخاص بـ InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | تهيئة ColorScheme باستخدام كائن جديد لتجاوز ColorScheme الخاص بـ InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | تهيئة ColorScheme باستخدام كائن جديد لتجاوز ColorScheme الخاص بـ InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | تهيئة FontScheme باستخدام كائن جديد لتجاوز FontScheme الخاص بـ InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | تهيئة FontScheme باستخدام كائن جديد لتجاوز FontScheme الخاص بـ InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | تهيئة FontScheme باستخدام كائن جديد لتجاوز FontScheme الخاص بـ InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | تهيئة FormatScheme باستخدام كائن جديد لتجاوز FormatScheme الخاص بـ InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | تهيئة FormatScheme باستخدام كائن جديد لتجاوز FormatScheme الخاص بـ InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | تهيئة FormatScheme باستخدام كائن جديد لتجاوز FormatScheme الخاص بـ InheritedTheme. |
| [clear()](#clear--) | ضبط ColorScheme و FontScheme و FormatScheme إلى null لتعطيل أي تجاوز باستخدام كائن السمة هذا. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

القيمة true تعني أن ColorScheme و FontScheme و FormatScheme هي null وأي تجاوز باستخدام كائن السمة هذا مُعطَّل. boolean للقراءة فقط.

**القيمة المرجعة:**
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

تهيئة ColorScheme باستخدام كائن جديد لتجاوز ColorScheme الخاص بـ InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

تهيئة ColorScheme باستخدام كائن جديد لتجاوز ColorScheme الخاص بـ InheritedTheme.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | البيانات للتهيئة من. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

تهيئة ColorScheme باستخدام كائن جديد لتجاوز ColorScheme الخاص بـ InheritedTheme. وتثبيت بيانات هذا الكائن الجديد ببيانات ColorScheme الخاص بـ InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

تهيئة FontScheme باستخدام كائن جديد لتجاوز FontScheme الخاص بـ InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

تهيئة FontScheme باستخدام كائن جديد لتجاوز FontScheme الخاص بـ InheritedTheme.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | البيانات للتهيئة من. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

تهيئة FontScheme باستخدام كائن جديد لتجاوز FontScheme الخاص بـ InheritedTheme. وتثبيت بيانات هذا الكائن الجديد ببيانات FontScheme الخاص بـ InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

تهيئة FormatScheme باستخدام كائن جديد لتجاوز FormatScheme الخاص بـ InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

تهيئة FormatScheme باستخدام كائن جديد لتجاوز FormatScheme الخاص بـ InheritedTheme.

**المعاملات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | البيانات للتهيئة من. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

تهيئة FormatScheme باستخدام كائن جديد لتجاوز FormatScheme الخاص بـ InheritedTheme. وتثبيت بيانات هذا الكائن الجديد ببيانات FormatScheme الخاص بـ InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```

ضبط ColorScheme و FontScheme و FormatScheme إلى null لتعطيل أي تجاوز باستخدام كائن السمة هذا.