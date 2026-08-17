---
title: IFontSubstRule
second_title: Aspose.Slides для Java API справка
description: Представляет информацию о замене шрифтов
type: docs
url: /ru/com.aspose.slides/ifontsubstrule/
---```
public interface IFontSubstRule
```

Представляет информацию о замене шрифтов
## Методы

| Метод | Описание |
| --- | --- |
| [getSourceFont()](#getSourceFont--) | Шрифт для замены только для чтения [IFontData](../../com.aspose.slides/ifontdata). |
| [getDestFont()](#getDestFont--) | Шрифт для использования при замене только для чтения [IFontData](../../com.aspose.slides/ifontdata). |
| [getReplaceFontCondition()](#getReplaceFontCondition--) | Правило, применяемое для замены, только для чтения [FontSubstCondition](../../com.aspose.slides/fontsubstcondition). |
### getSourceFont() {#getSourceFont--}
```
public abstract IFontData getSourceFont()
```


Шрифт для замены только для чтения [IFontData](../../com.aspose.slides/ifontdata).

**Возвращает:**
[IFontData](../../com.aspose.slides/ifontdata)
### getDestFont() {#getDestFont--}
```
public abstract IFontData getDestFont()
```


Шрифт для использования при замене только для чтения [IFontData](../../com.aspose.slides/ifontdata).

**Возвращает:**
[IFontData](../../com.aspose.slides/ifontdata)
### getReplaceFontCondition() {#getReplaceFontCondition--}
```
public abstract int getReplaceFontCondition()
```


Правило, применяемое для замены, только для чтения [FontSubstCondition](../../com.aspose.slides/fontsubstcondition).

**Возвращает:**
int