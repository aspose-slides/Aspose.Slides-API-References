---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Неизменяемый объект, содержащий эффективные свойства стиля текста.
type: docs
url: /ru/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Неизменяемый объект, содержащий эффективные свойства стиля текста.

--------------------

Этот интерфейс используется вместе с интерфейсом [ITextStyle](../../com.aspose.slides/itextstyle) для получения эффективных значений форматирования с применённым наследованием.
## Методы

| Метод | Описание |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Возвращает уровень эффективного стиля. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Возвращает эффективные свойства абзаца по умолчанию. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```


Возвращает уровень эффективного стиля.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нумерация уровней начинается с нуля. Должно находиться в диапазоне 0..8. |

**Возвращаемое значение:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Эффективное форматирование уровня [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```


Возвращает эффективные свойства абзаца по умолчанию. Только для чтения [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Возвращаемое значение:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)