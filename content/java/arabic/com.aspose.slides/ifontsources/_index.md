---
title: IFontSources
second_title: Aspose.Slides for Java API Reference
description: Provides file and memory sources for external fonts.
type: docs
url: /ar/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

يوفر مصادر ملفات وذاكرة للخطوط الخارجية.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | مجلدات تحتوي على ملفات الخط. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | مجلدات تحتوي على ملفات الخط. |
| [getMemoryFonts()](#getMemoryFonts--) | مجموعة من الخطوط ممثلة كمصفوفات بايت. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | مجموعة من الخطوط ممثلة بمصفوفات بايت. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```


مجلدات تحتوي على ملفات الخط. جميع ملفات الخط الموجودة في هذه المجلدات تُضمّن في المجموعة. المجلدات التي يتم البحث فيها بشكل متكرر.

**الإرجاع:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```


مجلدات تحتوي على ملفات الخط. جميع ملفات الخط الموجودة في هذه المجلدات تُضمّن في المجموعة. المجلدات التي يتم البحث فيها بشكل متكرر.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```


مجموعة من الخطوط ممثلة بمصفوفات بايت.

**الإرجاع:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```


مجموعة من الخطوط ممثلة بمصفوفات بايت.

**المعلمات:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | byte[][] |  |