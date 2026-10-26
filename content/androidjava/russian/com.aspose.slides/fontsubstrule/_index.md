---
title: FontSubstRule
second_title: Aspose.Slides для Android через справочник Java API
description: Представляет информацию о замене шрифтов
type: docs
url: /ru/com.aspose.slides/fontsubstrule/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IFontSubstRule](../../com.aspose.slides/ifontsubstrule)
```
public class FontSubstRule implements IFontSubstRule
```

Представляет информацию о заменах шрифтов
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [FontSubstRule(IFontData sourceFont, IFontData destFont)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-) | Создает новый экземпляр. |
| [FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)](#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-) | Создает новый экземпляр. |
## Методы

| Метод | Описание |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Шрифт для замены. |
| [getDestFont()](#getDestFont--) | Шрифт, используемый для замены. |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Правило, применяемое для замены. |
### FontSubstRule(IFontData sourceFont, IFontData destFont) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont)
```


Создает новый экземпляр.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Исходный шрифт. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Шрифт назначения. |

### FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule) {#FontSubstRule-com.aspose.slides.IFontData-com.aspose.slides.IFontData-int-}
```
public FontSubstRule(IFontData sourceFont, IFontData destFont, int fontSubstRule)
```


Создает новый экземпляр.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| sourceFont | [IFontData](../../com.aspose.slides/ifontdata) | Исходный шрифт. |
| destFont | [IFontData](../../com.aspose.slides/ifontdata) | Шрифт назначения. |
| fontSubstRule | int | Правило замены шрифта. |

### getSourceFont() {#getSourceFont--}
```
public final IFontData getSourceFont()
```


Шрифт для замены. Только для чтения [IFontData](../../com.aspose.slides/ifontdata).

**Возвращаемое значение:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public final IFontData getDestFont()
```


Шрифт, используемый для замены. Только для чтения [IFontData](../../com.aspose.slides/ifontdata).

**Возвращаемое значение:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public final int getReplaceFontCondition()
```


Правило, применяемое для замены. Только для чтения [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Возвращаемое значение:**
int