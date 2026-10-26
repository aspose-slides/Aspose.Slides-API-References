---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Java API Reference
description: Позволяет создать математическую рамку
type: docs
url: /ru/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Позволяет создать математическую рамку

--------------------

Для совместимости с COM
## Методы

| Метод | Описание |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Create a math border box by applying to the element |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Create a math border box by applying to the element |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

Создать математическую рамку, применяя к элементу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply border box |

**Возвращаемое значение:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - новый элемент рамки
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Создать математическую рамку, применяя к элементу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | math element to apply border box |
| hideTop | boolean | Скрыть верхний край |
| hideBottom | boolean | Скрыть нижний край |
| hideLeft | boolean | Скрыть левый край |
| hideRight | boolean | Скрыть правый край |
| strikethroughHorizontal | boolean | Перечёркнутая горизонтальная линия рамки |
| strikethroughVertical | boolean | Перечёркнутая вертикальная линия рамки |
| strikethroughBottomLeftToTopRight | boolean | Перечёркнутая линия рамки снизу-слева вверх-справа |
| strikethroughTopLeftToBottomRight | boolean | Перечёркнутая линия рамки сверху-слева вниз-справа |

**Возвращаемое значение:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - новый элемент рамки