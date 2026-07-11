---
title: IFonts
second_title: Aspose.Slides for Android через Java API Reference
description: Представляет коллекцию шрифтов.
type: docs
url: /ru/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Представляет коллекцию шрифтов.
## Методы

| Метод | Описание |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Возвращает или задает латинский шрифт. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Возвращает или задает латинский шрифт. |
| [getEastAsianFont()](#getEastAsianFont--) | Возвращает или задает восточноазиатский шрифт. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Возвращает или задает восточноазиатский шрифт. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Возвращает или задает шрифт сложного письма. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Возвращает или задает шрифт сложного письма. |
| [getScriptFontMap()](#getScriptFontMap--) | Возвращает словарь всех определений шрифтов сценариев в презентации. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Получает имя шрифта, связанное с указанным тегом сценария из темы презентации. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Назначает имя шрифта конкретному тегу сценария, определяя, как будет отображаться текст этого сценария в презентации. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Удаляет настройку шрифта, связанную с указанным тегом сценария, из коллекции шрифтов темы. |
### getLatinFont() {#getLatinFont--}
```
public abstract IFontData getLatinFont()
```

Возвращает или задает латинский шрифт. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращаемое значение:**
[IFontData](../../com.aspose.slides/ifontdata)
### setLatinFont(IFontData value) {#setLatinFont-com.aspose.slides.IFontData-}
```
public abstract void setLatinFont(IFontData value)
```

Возвращает или задает латинский шрифт. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getEastAsianFont() {#getEastAsianFont--}
```
public abstract IFontData getEastAsianFont()
```

Возвращает или задает восточноазиатский шрифт. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращаемое значение:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```

Возвращает или задает восточноазиатский шрифт. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```

Возвращает или задает шрифт сложного письма. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращаемое значение:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```

Возвращает или задает шрифт сложного письма. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
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
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Словарь, сопоставляющий коды сценариев с именами шрифтов.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
```

Получает имя шрифта, связанное с указанным тегом сценария из темы презентации.

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
java.lang.String - Имя шрифта, используемого для указанного сценария, или null, если сценарий не определён.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
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
| fontName | java.lang.String | Имя шрифта, которое следует назначить указанному сценарию. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```

Удаляет настройку шрифта, связанную с указанным тегом сценария, из коллекции шрифтов темы.

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