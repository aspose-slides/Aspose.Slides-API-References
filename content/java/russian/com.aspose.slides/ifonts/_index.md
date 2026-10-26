---
title: IFonts
second_title: Aspose.Slides for Java справочник API
description: Представляет коллекцию шрифтов.
type: docs
url: /ru/com.aspose.slides/ifonts/
---```
public interface IFonts
```

Представляет коллекцию шрифтов.
## Methods

| Метод | Описание |
| --- | --- |
| [getLatinFont()](#getLatinFont--) | Returns or sets the Latin font. |
| [setLatinFont(IFontData value)](#setLatinFont-com.aspose.slides.IFontData-) | Returns or sets the Latin font. |
| [getEastAsianFont()](#getEastAsianFont--) | Returns or sets the East Asian font. |
| [setEastAsianFont(IFontData value)](#setEastAsianFont-com.aspose.slides.IFontData-) | Returns or sets the East Asian font. |
| [getComplexScriptFont()](#getComplexScriptFont--) | Returns or sets the complex script font. |
| [setComplexScriptFont(IFontData value)](#setComplexScriptFont-com.aspose.slides.IFontData-) | Returns or sets the complex script font. |
| [getScriptFontMap()](#getScriptFontMap--) | Returns a dictionary of all script font definitions in the presentation. |
| [getScriptFont(String script)](#getScriptFont-java.lang.String-) | Gets the font name associated with a specific script tag from the presentation theme. |
| [setScriptFont(String script, String fontName)](#setScriptFont-java.lang.String-java.lang.String-) | Assigns a font name to a specific script tag, which defines how text of that script will be rendered in the presentation. |
| [removeScriptFont(String script)](#removeScriptFont-java.lang.String-) | Removes the font setting associated with a specific script tag from the theme's font collection. |
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


Возвращает или задает Восточноазиатский шрифт. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращаемое значение:**
[IFontData](../../com.aspose.slides/ifontdata)
### setEastAsianFont(IFontData value) {#setEastAsianFont-com.aspose.slides.IFontData-}
```
public abstract void setEastAsianFont(IFontData value)
```


Возвращает или задает Восточноазиатский шрифт. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getComplexScriptFont() {#getComplexScriptFont--}
```
public abstract IFontData getComplexScriptFont()
```


Возвращает или задает сложный скриптовый шрифт. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Возвращаемое значение:**
[IFontData](../../com.aspose.slides/ifontdata)
### setComplexScriptFont(IFontData value) {#setComplexScriptFont-com.aspose.slides.IFontData-}
```
public abstract void setComplexScriptFont(IFontData value)
```


Возвращает или задает сложный скриптовый шрифт. Чтение/запись [IFontData](../../com.aspose.slides/ifontdata).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getScriptFontMap() {#getScriptFontMap--}
```
public abstract System.Collections.Generic.Dictionary<String,String> getScriptFontMap()
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


**Возвращаемое значение:**
com.aspose.ms.System.Collections.Generic.Dictionary<java.lang.String,java.lang.String> - Словарь, сопоставляющий коды скриптов с именами шрифтов.
### getScriptFont(String script) {#getScriptFont-java.lang.String-}
```
public abstract String getScriptFont(String script)
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

**Возвращаемое значение:**
java.lang.String - Имя шрифта, используемого для указанного скрипта, или  null  если скрипт не определён.
### setScriptFont(String script, String fontName) {#setScriptFont-java.lang.String-java.lang.String-}
```
public abstract void setScriptFont(String script, String fontName)
```


Назначает имя шрифта определённому тегу скрипта, что определяет, как текст этого скрипта будет отображаться в презентации.

--------------------

> ```
> This example shows how to set the font for the Arabic script to "Segoe UI":
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().setScriptFont("Arab", "Segoe UI");
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| script | java.lang.String | Код скрипта BCP-47 (например, "Arab", "Hebr", "Hans"), идентифицирующий систему письма. |
| fontName | java.lang.String | Имя шрифта, которое следует назначить указанному скрипту. |

### removeScriptFont(String script) {#removeScriptFont-java.lang.String-}
```
public abstract void removeScriptFont(String script)
```


Удаляет настройку шрифта, связанную с определённым тегом скрипта, из коллекции шрифтов темы.

--------------------

> ```
> Этот пример демонстрирует, как удалить соответствие шрифта для еврейского скрипта:
>  
>  presentation.getMasterTheme().getFontScheme().getMajor().removeScriptFont("Hebr");
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| script | java.lang.String | Код скрипта BCP-47, настройка шрифта которого должна быть удалена. |