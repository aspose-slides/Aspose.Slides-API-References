---
title: Fonts
second_title: Справочник API Aspose.Slides для Java
description: Коллекция шрифтов.
type: docs
url: /ru/com.aspose.slides/fonts/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IFonts](../../com.aspose.slides/ifonts)
```
public class Fonts implements IFonts
```

Коллекция шрифтов.

## Методы

| Метод | Описание |
| --- | --- |
| [getScriptFontMap()](#getScriptFontMap--) | Возвращает словарь всех определений шрифтов сценариев в презентации. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Получает имя шрифта, связанное с определённым тегом сценария из темы презентации. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Назначает имя шрифта конкретному тегу сценария, определяя, как будет отображаться текст этого сценария в презентации. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Удаляет настройку шрифта, связанную с определённым тегом сценария, из коллекции шрифтов темы. |
| [getLatinFont()](#getLatinFont--) | Возвращает или задаёт латинский шрифт. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Возвращает или задаёт латинский шрифт. |
| [getEastAsianFont()](#getEastAsianFont--) | Возвращает или задаёт восточноазиатский шрифт. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Возвращает или задаёт восточноазиатский шрифт. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Возвращает или задаёт шрифт сложного сценария. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Возвращает или задаёт шрифт сложного сценария. |

### getScriptFontMap() {#getScriptFontMap--}
```
public final System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
```

Возвращает словарь всех определений шрифтов сценариев в презентации.

--------------------

> ```
> Dictionary.Enumerator<String, String> map = presentation.getMasterTheme().getFontScheme().getMajor().getScriptFontMap().iterator();
>  while (map.hasNext())
>  {
>      KeyValuePair<String, String> kvp = map.next();
>      System.out.println(kvp.getKey() + " ? " + kvp.getValue());
>  }
> ```


**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Словарь, отображающий коды сценариев в имена шрифтов.

### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public final String getScriptFont(String script)
```

Получает имя шрифта, связанное с определённым тегом сценария из темы презентации.

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
| script | java.lang.String | Код сценария BCP-47 (например, "Latn", "Cyrl", "Jpan"), используемый для идентификации системы письма. |

**Возвращаемое значение:**
java.lang.String - Имя шрифта, используемого для указанного сценария, или  null  если сценарий не определён.

### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public final void setScriptFont(String script, String fontName)
```

Назначает имя шрифта конкретному тегу сценария, определяя, как будет отображаться текст этого сценария в презентации.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| script | java.lang.String | Код сценария BCP-47 (например, "Arab", "Hebr", "Hans"), идентифицирующий систему письма. |
| fontName | java.lang.String | Имя шрифта, которое будет назначено указанному сценарию. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public final void removeScriptFont(String script)
```

Удаляет настройку шрифта, связанную с определённым тегом сценария, из коллекции шрифтов темы.

--------------------

> ```
> This example demonstrates how to remove the font mapping for the Hebrew script:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| script | java.lang.String | Код сценария BCP-47, настройка шрифта которого должна быть удалена. |

### getLatinFont() {#getLatinFont--}
```
public final IFontData getLatinFont()
```

Возвращает или задаёт латинский шрифт. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращаемое значение:**
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

Возвращает или задаёт восточноазиатский шрифт. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращаемое значение:**
[IFontData](../../com.aspose.slides/ifontdata)

### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public final void setEastAsianFont(IFontData value)
```

Возвращает или задаёт восточноазиатский шрифт. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public final IFontData getComplexScriptFont()
```

Возвращает или задаёт шрифт сложного сценария. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращаемое значение:**
[IFontData](../../com.aspose.slides/ifontdata)

### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public final void setComplexScriptFont(IFontData value)
```

Возвращает или задаёт шрифт сложного сценария. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |