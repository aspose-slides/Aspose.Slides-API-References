---
title: MathGroupingCharacterFactory
second_title: Aspose.Slides для Android через справочник API Java
description: Позволяет создавать математический группирующий символ
type: docs
url: /ru/com.aspose.slides/mathgroupingcharacterfactory/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathGroupingCharacterFactory](../../com.aspose.slides/imathgroupingcharacterfactory)
```
public class MathGroupingCharacterFactory implements IMathGroupingCharacterFactory
```

Позволяет создавать математический группирующий символ

--------------------

Для совместимости с COM
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathGroupingCharacterFactory()](#MathGroupingCharacterFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-) | Создает математический группирующий символ |
| [createMathGroupingCharacter(IMathElement element)](#createMathGroupingCharacter-com.aspose.slides.IMathElement-) | Создает математический группирующий символ |
### MathGroupingCharacterFactory() {#MathGroupingCharacterFactory--}
```
public MathGroupingCharacterFactory()
```


### createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-char-int-int-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element, char character, int position, int verticalJustification)
```


Создает математический группирующий символ

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент для применения группирующего символа |
| character | char | группирующий символ |
| position | int | позиция группирующего символа |
| verticalJustification | int | вертикальное выравнивание |

**Возвращаемое значение:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - новый элемент группирующего символа
### createMathGroupingCharacter(IMathElement element) {#createMathGroupingCharacter-com.aspose.slides.IMathElement-}
```
public final IMathGroupingCharacter createMathGroupingCharacter(IMathElement element)
```


Создает математический группирующий символ

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент для применения группирующего символа |

**Возвращаемое значение:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - новый элемент группирующего символа