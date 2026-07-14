---
title: IFontSources
second_title: Aspose.Slides for Android عبر مرجع Java API
description: يوفر مصادر ملفات وذاكرة للخطوط الخارجية.
type: docs
url: /ar/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

يوفر مصادر ملفات وذاكرة للخطوط الخارجية.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | المجلدات التي تحتوي على ملفات الخطوط. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | المجلدات التي تحتوي على ملفات الخطوط. |
| [getMemoryFonts()](#getMemoryFonts--) | مجموعة من الخطوط ممثلة كمصفوفات بايت. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | مجموعة من الخطوط ممثلة كمصفوفات بايت. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```


المجلدات التي تحتوي على ملفات الخطوط. جميع ملفات الخطوط الموجودة في هذه المجلدات تُضمن في المجموعة. المجلدات التي يتم البحث فيها بصورة متكررة.

**الإرجاع:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```


المجلدات التي تحتوي على ملفات الخطوط. جميع ملفات الخطوط الموجودة في هذه المجلدات تُضمن في المجموعة. المجلدات التي يتم البحث فيها بصورة متكررة.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```


مجموعة من الخطوط ممثلة كمصفوفات بايت.

**الإرجاع:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```


مجموعة من الخطوط ممثلة كمصفوفات بايت.

**المعلمات:**
| المُعامل | النوع | الوصف |
| --- | --- | --- |
| value | byte[][] |  |