---
title: IOverrideTheme
second_title: مرجع API لـ Aspose.Slides للـ Java
description: يمثل سمة متجاوزة.
type: docs
url: /ar/com.aspose.slides/ioverridetheme/
---
**All Implemented Interfaces:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IOverrideTheme extends ITheme
```

يمثل سمة متجاوزة.
## الطرق

| Method | Description |
| --- | --- |
| [isEmpty()](#isEmpty--) | القيمة true تعني أن ColorScheme و FontScheme و FormatScheme قيمتها null وأن أي تجاوز باستخدام كائن السمة هذا معطل. |
| [initColorScheme()](#initColorScheme--) | قم بتهيئة ColorScheme كائنًا جديدًا لتجاوز ColorScheme الخاص بـ InheritedTheme. |
| [initColorSchemeFrom(IColorScheme colorScheme)](#initColorSchemeFrom-com.aspose.slides.IColorScheme-) | قم بتهيئة ColorScheme كائنًا جديدًا لتجاوز ColorScheme الخاص بـ InheritedTheme. |
| [initColorSchemeFromInherited()](#initColorSchemeFromInherited--) | قم بتهيئة ColorScheme كائنًا جديدًا لتجاوز ColorScheme الخاص بـ InheritedTheme. |
| [initFontScheme()](#initFontScheme--) | قم بتهيئة FontScheme كائنًا جديدًا لتجاوز FontScheme الخاص بـ InheritedTheme. |
| [initFontSchemeFrom(IFontScheme fontScheme)](#initFontSchemeFrom-com.aspose.slides.IFontScheme-) | قم بتهيئة FontScheme كائنًا جديدًا لتجاوز FontScheme الخاص بـ InheritedTheme. |
| [initFontSchemeFromInherited()](#initFontSchemeFromInherited--) | قم بتهيئة FontScheme كائنًا جديدًا لتجاوز FontScheme الخاص بـ InheritedTheme. |
| [initFormatScheme()](#initFormatScheme--) | قم بتهيئة FormatScheme كائنًا جديدًا لتجاوز FormatScheme الخاص بـ InheritedTheme. |
| [initFormatSchemeFrom(IFormatScheme formatScheme)](#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-) | قم بتهيئة FormatScheme كائنًا جديدًا لتجاوز FormatScheme الخاص بـ InheritedTheme. |
| [initFormatSchemeFromInherited()](#initFormatSchemeFromInherited--) | قم بتهيئة FormatScheme كائنًا جديدًا لتجاوز FormatScheme الخاص بـ InheritedTheme. |
| [clear()](#clear--) | عيّن ColorScheme و FontScheme و FormatScheme إلى null لتعطيل أي تجاوز باستخدام كائن السمة هذا. |
### isEmpty() {#isEmpty--}
```
public abstract boolean isEmpty()
```

القيمة true تعني أن ColorScheme و FontScheme و FormatScheme قيمتها null وأن أي تجاوز باستخدام كائن السمة هذا معطل. قيمة منطقية للقراءة فقط.

**الإرجاع:**  
boolean
### initColorScheme() {#initColorScheme--}
```
public abstract void initColorScheme()
```

قم بتهيئة ColorScheme كائنًا جديدًا لتجاوز ColorScheme الخاص بـ InheritedTheme.

### initColorSchemeFrom(IColorScheme colorScheme) {#initColorSchemeFrom-com.aspose.slides.IColorScheme-}
```
public abstract void initColorSchemeFrom(IColorScheme colorScheme)
```

قم بتهيئة ColorScheme كائنًا جديدًا لتجاوز ColorScheme الخاص بـ InheritedTheme.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| colorScheme | [IColorScheme](../../com.aspose.slides/icolorscheme) | البيانات للتهيئة منها. |

### initColorSchemeFromInherited() {#initColorSchemeFromInherited--}
```
public abstract void initColorSchemeFromInherited()
```

قم بتهيئة ColorScheme كائنًا جديدًا لتجاوز ColorScheme الخاص بـ InheritedTheme. وقم بتهيئة بيانات هذا الكائن الجديد ببيانات ColorScheme الخاص بـ InheritedTheme.

### initFontScheme() {#initFontScheme--}
```
public abstract void initFontScheme()
```

قم بتهيئة FontScheme كائنًا جديدًا لتجاوز FontScheme الخاص بـ InheritedTheme.

### initFontSchemeFrom(IFontScheme fontScheme) {#initFontSchemeFrom-com.aspose.slides.IFontScheme-}
```
public abstract void initFontSchemeFrom(IFontScheme fontScheme)
```

قم بتهيئة FontScheme كائنًا جديدًا لتجاوز FontScheme الخاص بـ InheritedTheme.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontScheme | [IFontScheme](../../com.aspose.slides/ifontscheme) | البيانات للتهيئة منها. |

### initFontSchemeFromInherited() {#initFontSchemeFromInherited--}
```
public abstract void initFontSchemeFromInherited()
```

قم بتهيئة FontScheme كائنًا جديدًا لتجاوز FontScheme الخاص بـ InheritedTheme. وقم بتهيئة بيانات هذا الكائن الجديد ببيانات FontScheme الخاص بـ InheritedTheme.

### initFormatScheme() {#initFormatScheme--}
```
public abstract void initFormatScheme()
```

قم بتهيئة FormatScheme كائنًا جديدًا لتجاوز FormatScheme الخاص بـ InheritedTheme.

### initFormatSchemeFrom(IFormatScheme formatScheme) {#initFormatSchemeFrom-com.aspose.slides.IFormatScheme-}
```
public abstract void initFormatSchemeFrom(IFormatScheme formatScheme)
```

قم بتهيئة FormatScheme كائنًا جديدًا لتجاوز FormatScheme الخاص بـ InheritedTheme.

**المعلمات:**
| Parameter | Type | Description |
| --- | --- | --- |
| formatScheme | [IFormatScheme](../../com.aspose.slides/iformatscheme) | البيانات للتهيئة منها. |

### initFormatSchemeFromInherited() {#initFormatSchemeFromInherited--}
```
public abstract void initFormatSchemeFromInherited()
```

قم بتهيئة FormatScheme كائنًا جديدًا لتجاوز FormatScheme الخاص بـ InheritedTheme. وقم بتهيئة بيانات هذا الكائن الجديد ببيانات FormatScheme الخاص بـ InheritedTheme.

### clear() {#clear--}
```
public abstract void clear()
```

عيّن ColorScheme و FontScheme و FormatScheme إلى null لتعطيل أي تجاوز باستخدام كائن السمة هذا.