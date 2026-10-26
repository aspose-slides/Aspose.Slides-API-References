---
title: ITextStyleEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective text style properties.
type: docs
url: /ru/com.aspose.slides/itextstyleeffectivedata/
---```
public interface ITextStyleEffectiveData
```

Неизменяемый объект, содержащий эффективные свойства стиля текста.

--------------------

Этот интерфейс используется вместе с интерфейсом [ITextStyle](../../com.aspose.slides/itextstyle) для возврата эффективных значений форматирования с применённым наследованием.
## Методы

| Метод | Описание |
| --- | --- |
| [getLevel(int index)](#getLevel-int-) | Возвращает уровень эффективного стиля. |
| [getDefaultParagraphFormat()](#getDefaultParagraphFormat--) | Возвращает эффективные свойства форматирования абзаца по умолчанию. |
### getLevel(int index) {#getLevel-int-}
```
public abstract IParagraphFormatEffectiveData getLevel(int index)
```

Возвращает уровень эффективного стиля.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| index | int | Нулевой базовый индекс уровня. Должен находиться в диапазоне 0..8. |

**Возвращает:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - Эффективное форматирование уровня [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).
### getDefaultParagraphFormat() {#getDefaultParagraphFormat--}
```
public abstract IParagraphFormatEffectiveData getDefaultParagraphFormat()
```

Возвращает эффективные свойства форматирования абзаца по умолчанию. Только для чтения [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

**Возвращает:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata)