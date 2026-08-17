---
title: IFontSources
second_title: Aspose.Slides для Java справочник API
description: Предоставляет файловые и оперативные источники для внешних шрифтов.
type: docs
url: /ru/com.aspose.slides/ifontsources/
---```
public interface IFontSources
```

Предоставляет файловые и оперативные источники для внешних шрифтов.
## Методы

| Метод | Описание |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Папки, содержащие файлы шрифтов. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Папки, содержащие файлы шрифтов. |
| [getMemoryFonts()](#getMemoryFonts--) | Коллекция шрифтов, представленных в виде массивов байтов. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Коллекция шрифтов, представленных в виде массивов байтов. |
### getFontFolders() {#getFontFolders--}
```
public abstract String[] getFontFolders()
```

Папки, содержащие файлы шрифтов. Все файлы шрифтов, находящиеся в этих папках, включаются в коллекцию. Папки, которые просматриваются рекурсивно.

**Возвращаемое значение:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public abstract void setFontFolders(String[] value)
```

Папки, содержащие файлы шрифтов. Все файлы шрифтов, находящиеся в этих папках, включаются в коллекцию. Папки, которые просматриваются рекурсивно.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String[] |  |
### getMemoryFonts() {#getMemoryFonts--}
```
public abstract byte[][] getMemoryFonts()
```

Коллекция шрифтов, представленных в виде массивов байтов.

**Возвращаемое значение:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public abstract void setMemoryFonts(byte[][] value)
```

Коллекция шрифтов, представленных в виде массивов байтов.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[][] |  |