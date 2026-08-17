---
title: MathBorderBoxFactory
second_title: Справочник API Aspose.Slides для Java
description: Позволяет создать математическую рамку
type: docs
url: /ru/com.aspose.slides/mathborderboxfactory/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

Позволяет создать математическую рамку

--------------------

Для совместимости с COM
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Создать математическую рамку, применяя к элементу |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Создать математическую рамку, применяя к элементу |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```


Создать математическую рамку, применяя к элементу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент для применения рамки |

**Возвращаемое значение:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - новый элемент рамки
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Создать математическую рамку, применяя к элементу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент для применения рамки |
| hideTop | boolean | Скрыть верхний край |
| hideBottom | boolean | Скрыть нижний край |
| hideLeft | boolean | Скрыть левый край |
| hideRight | boolean | Скрыть правый край |
| strikethroughHorizontal | boolean | Перекрещивание горизонтальное рамки |
| strikethroughVertical | boolean | Перекрещивание вертикальное рамки |
| strikethroughBottomLeftToTopRight | boolean | Перекрещивание рамки снизу-слева вверх-справа |
| strikethroughTopLeftToBottomRight | boolean | Перекрещивание рамки сверху-слева вниз-справа |

**Возвращаемое значение:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - новый элемент рамки