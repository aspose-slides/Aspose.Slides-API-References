---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Java API Reference
description: Allows to create a math grouping character
type: docs
url: /ru/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

Позволяет создать символ группировки Math

--------------------

Для совместимости с COM
## Методы

| Метод | Описание |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Создает символ группировки Math |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Создает символ группировки Math |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```

Создает символ группировки Math

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент для применения символа группировки |
| character | char | символ группировки |
| position | int | позиция символа группировки |
| verticalJustification | int | вертикальное выравнивание |

**Возвращаемое значение:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - новый элемент символа группировки

### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```

Создает символ группировки Math

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент для применения символа группировки |

**Возвращаемое значение:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - новый элемент символа группировки