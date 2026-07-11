---
title: IFontSources
second_title: Aspose.Slides for Android via Java API Reference
description: Обеспечивает файловые и памяти источники внешних шрифтов.
type: docs
url: /ru/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Обеспечивает файловые и памяти источники внешних шрифтов.
## Methods

| Method | Description |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Папки, содержащие файлы шрифтов. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Папки, содержащие файлы шрифтов. |
| [getMemoryFonts()](#getMemoryFonts--) | Коллекция шрифтов, представленных массивами байтов. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Коллекция шрифтов, представленных массивами байтов. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```


Папки, содержащие файлы шрифтов. Все файлы шрифтов, расположенные в этих папках, включаются в коллекцию. Папки, которые просматриваются рекурсивно.

**Возвращаемое значение:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```


Папки, содержащие файлы шрифтов. Все файлы шрифтов, расположенные в этих папках, включаются в коллекцию. Папки, которые просматриваются рекурсивно.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```


Коллекция шрифтов, представленных массивами байтов.

**Возвращаемое значение:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```


Коллекция шрифтов, представленных массивами байтов.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[][] |  |