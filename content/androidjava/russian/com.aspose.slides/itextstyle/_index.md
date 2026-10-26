---
title: ITextStyle
second_title: Aspose.Slides for Android via Java API Reference
description: Свойства форматирования стиля текста.
type: docs
url: /ru/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Свойства форматирования стиля текста.
## Methods

| Method | Description |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Если уровень стиля существует, возвращает его, иначе возвращает null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Свойства абзаца по умолчанию. |
| [getEffective()](#getEffective--) | Получает эффективные данные форматирования стиля текста с учётом наследования. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```


Если уровень стиля существует, возвращает его, иначе возвращает null.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Индекс уровня, начиная с нуля. Должен находиться в диапазоне 0..8. |

**Returns:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) – Форматирование уровня [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```


Свойства абзаца по умолчанию. Только для чтения [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Returns:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```


Получает эффективные данные форматирования стиля текста с учётом наследования.

**Returns:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) – [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).