---
title: FontSources
second_title: مرجع API الخاص بـ Aspose.Slides for Java
description: يوفر مصادر ملفات وذاكرة للخطوط الخارجية.
type: docs
url: /ar/com.aspose.slides/fontsources/
---
**الوراثة:**
java.lang.Object

**جميع الواجهات المنفذة:**
[com.aspose.slides.IFontSources](../../com.aspose.slides/ifontsources)
```
public class FontSources implements IFontSources
```

يوفر مصادر ملفات وذاكرة للخطوط الخارجية.
## المنشئات

| المنشئ | الوصف |
| --- | --- |
| [FontSources()](#FontSources--) | ينشئ خيارات الخط الافتراضية الجديدة. |
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | مجلدات تحتوي على ملفات الخطوط. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | مجلدات تحتوي على ملفات الخطوط. |
| [getMemoryFonts()](#getMemoryFonts--) | مجموعة من الخطوط ممثلة بمصفوفات بايت. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | مجموعة من الخطوط ممثلة بمصفوفات بايت. |
### FontSources() {#FontSources--}
```
public FontSources()
```

ينشئ خيارات الخط الافتراضية الجديدة.

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```

مجلدات تحتوي على ملفات الخطوط. جميع ملفات الخطوط الموجودة في هذه المجلدات تُضمن في المجموعة. المجلدات التي يتم البحث فيها بشكل متكرر.

**القيمة المرجعة:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```

مجلدات تحتوي على ملفات الخطوط. جميع ملفات الخطوط الموجودة في هذه المجلدات تُضمن في المجموعة. المجلدات التي يتم البحث فيها بشكل متكرر.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```

مجموعة من الخطوط ممثلة بمصفوفات بايت.

**القيمة المرجعة:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```

مجموعة من الخطوط ممثلة بمصفوفات بايت.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte[][] |  |