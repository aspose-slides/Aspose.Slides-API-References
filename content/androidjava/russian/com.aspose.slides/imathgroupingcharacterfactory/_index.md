---
title: IMathGroupingCharacterFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math grouping character
type: docs
url: /ru/com.aspose.slides/imathgroupingcharacterfactory/
---```
public interface IMathGroupingCharacterFactory
```

Позволяет создавать математический символ группировки

--------------------

Для совместимости с COM
## Методы

| Метод | Описание |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Creates a math grouping character |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Creates a math grouping character |
### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Создает математический символ группировки

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply grouping character |
| character | char | grouping character |
| position | int | position of grouping character |
| verticalJustification | int | vertical justification |

**Возвращаемое значение:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - new grouping character element
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public abstract IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```


Создает математический символ группировки

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply grouping character |

**Возвращаемое значение:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - new grouping character element