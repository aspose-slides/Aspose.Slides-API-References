---
title: FontSources
second_title: Aspose.Slides для Android через справку по Java API
description: Предоставляет файловые и памятьные источники для внешних шрифтов.
type: docs
url: /ru/com.aspose.slides/fontsources/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IFontSources](../../com.aspose.slides/ifontsources)
``` 
public class FontSources implements IFontSources
```

Предоставляет файловые и памятьные источники для внешних шрифтов.
## Конструкторы

| Constructor | Описание |
| --- | --- |
| [FontSources()](#FontSources--) | Создаёт новые параметры шрифта по умолчанию. |
## Методы

| Method | Описание |
| --- | --- |
| [getFontFolders()](#getFontFolders--) | Папки, содержащие файлы шрифтов. |
| [setFontFolders(String[] value)](#setFontFolders-java.lang.String---) | Папки, содержащие файлы шрифтов. |
| [getMemoryFonts()](#getMemoryFonts--) | Коллекция шрифтов, представленных в виде массивов байтов. |
| [setMemoryFonts(byte[][] value)](#setMemoryFonts-byte-----) | Коллекция шрифтов, представленных в виде массивов байтов. |
### FontSources() {#FontSources--}
```
public FontSources()
```


Создаёт новые параметры шрифта по умолчанию.

### getFontFolders() {#getFontFolders--}
```
public final String[] getFontFolders()
```


Папки, содержащие файлы шрифтов. Все файлы шрифтов, находящиеся в этих папках, включены в коллекцию. Папки, которые просматриваются рекурсивно.

**Возвращаемое значение:**
java.lang.String[]
### setFontFolders(String[] value) {#setFontFolders-java.lang.String---}
```
public final void setFontFolders(String[] value)
```


Папки, содержащие файлы шрифтов. Все файлы шрифтов, находящиеся в этих папках, включены в коллекцию. Папки, которые просматриваются рекурсивно.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String[] |  |

### getMemoryFonts() {#getMemoryFonts--}
```
public final byte[][] getMemoryFonts()
```


Коллекция шрифтов, представленных в виде массивов байтов.

**Возвращаемое значение:**
byte[][]
### setMemoryFonts(byte[][] value) {#setMemoryFonts-byte-----}
```
public final void setMemoryFonts(byte[][] value)
```


Коллекция шрифтов, представленных в виде массивов байтов.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[][] |  |