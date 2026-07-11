---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math border box
type: docs
url: /ru/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Позволяет создавать рамку математической формулы

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

Создать рамку математической формулы, применяя к элементу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент, к которому применяется рамка |

**Возврат:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - новый элемент рамки
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Создать рамку математической формулы, применяя к элементу

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | математический элемент, к которому применяется рамка |
| hideTop | boolean | Скрыть верхний край |
| hideBottom | boolean | Скрыть нижний край |
| hideLeft | boolean | Скрыть левый край |
| hideRight | boolean | Скрыть правый край |
| strikethroughHorizontal | boolean | Перечёркивание рамки горизонтальное |
| strikethroughVertical | boolean | Перечёркивание рамки вертикальное |
| strikethroughBottomLeftToTopRight | boolean | Перечёркивание рамки снизу-слева вверх-справа |
| strikethroughTopLeftToBottomRight | boolean | Перечёркивание рамки сверху-слева вниз-справа |

**Возврат:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - новый элемент рамки