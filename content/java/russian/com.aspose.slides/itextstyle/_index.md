---
title: ITextStyle
second_title: Aspose.Slides for Java API Reference
description: Text style formatting properties.
type: docs
url: /ru/com.aspose.slides/itextstyle/
---```
public interface ITextStyle
```

Свойства форматирования стиля текста.
## Методы

| Метод | Описание |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Если уровень стиля существует, возвращает его, иначе возвращает null. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Свойства абзаца по умолчанию. |
| [getEffective()](#getEffective--) | Получает применяемые данные форматирования стиля текста с учётом наследования. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormat getLevel(int index)
```


Если уровень стиля существует, возвращает его, иначе возвращает null.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой индекс уровня. Должен находиться в диапазоне 0..8. |

**Возврат:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat) - Форматирование уровня [IParagraphFormat](../../com.aspose.slides/iparagraphformat).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormat getDefaultParagraphFormat()
```


Свойства абзаца по умолчанию. Только для чтения [IParagraphFormat](../../com.aspose.slides/iparagraphformat).

**Возврат:**
[IParagraphFormat](../../com.aspose.slides/iparagraphformat)
### getEffective() {#getEffective--}
```
public abstract ITextStyleEffectiveData getEffective()
```


Получает применяемые данные форматирования стиля текста с учётом наследования.

**Возврат:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata) - [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).