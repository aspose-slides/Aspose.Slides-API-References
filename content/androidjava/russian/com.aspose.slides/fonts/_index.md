---
title: Fonts
second_title: Aspose.Slides для Android через Java API Справочник
description: Коллекция шрифтов.
type: docs
url: /ru/com.aspose.slides/fonts/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Коллекция шрифтов.
## Методы

| Метод | Описание |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Возвращает словарь всех определений шрифтов скриптов в презентации. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Получает имя шрифта, связанное с определённым тегом скрипта из темы презентации. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Назначает имя шрифта определённому тегу скрипта, определяя как будет отображаться текст этого скрипта в презентации. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Удаляет настройку шрифта, связанную с определённым тегом скрипта, из коллекции шрифтов темы. |
| [getLatinFont()](#getLatinFont--) | Возвращает или задаёт латинский шрифт. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Возвращает или задаёт латинский шрифт. |
| [getEastAsianFont()](#getEastAsianFont--) | Возвращает или задаёт шрифт Восточной Азии. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Возвращает или задаёт шрифт Восточной Азии. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Возвращает или задаёт шрифт сложного скрипта. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Возвращает или задаёт шрифт сложного скрипта. |
### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Возвращает словарь всех определений шрифтов скриптов в презентации.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```

**Возвращает:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Словарь, сопоставляющий коды скриптов с именами шрифтов.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```

Получает имя шрифта, связанное с определённым тегом скрипта из темы презентации.

--------------------

> ```
> This example demonstrates how to retrieve the font assigned to the Cyrillic script in the presentation theme.
>  
>  String font = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFont("Cyrl");
>  System.out.println("Font for Cyrillic script: " + font);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| script | java.lang.String | Код скрипта BCP-47 (например, "Latn", "Cyrl", "Jpan"), используемый для идентификации системы письма. |

**Возвращает:**
java.lang.String - Имя шрифта, используемого для указанного скрипта, или  null  если скрипт не определён.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

Назначает имя шрифта определённому тегу скрипта, определяя как будет отображаться текст этого скрипта в презентации.

--------------------

> ```
> Этот пример показывает, как установить шрифт для арабского скрипта "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segue UI");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| script | java.lang.String | Код скрипта BCP-47 (например, "Arab", "Hebr", "Hans"), идентифицирующий систему письма. |
| fontName | java.lang.String | Имя шрифта, которое будет назначено указанному скрипту. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

Удаляет настройку шрифта, связанную с определённым тегом скрипта, из коллекции шрифтов темы.

--------------------

> ```
> Этот пример демонстрирует, как удалить сопоставление шрифта для еврейского скрипта:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| script | java.lang.String | Код скрипта BCP-47, настройку шрифта которого следует удалить. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Возвращает или задаёт латинский шрифт. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращает:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public final void setLatinFont(IFontData value)
```

Возвращает или задаёт латинский шрифт. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public final IFontData getEastAsianFont()
```

Возвращает или задаёт шрифт Восточной Азии. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращает:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Возвращает или задаёт шрифт Восточной Азии. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Возвращает или задаёт шрифт сложного скрипта. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращает:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Возвращает или задаёт шрифт сложного скрипта. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |