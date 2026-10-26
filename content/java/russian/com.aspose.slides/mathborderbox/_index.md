---
title: MathBorderBox
second_title: Справочник API Aspose.Slides для Java
description: Рисует прямоугольную или другую границу вокруг IMathElement.
type: docs
url: /ru/com.aspose.slides/mathborderbox/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathBorderBox](../../com.aspose.slides/imathborderbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBorderBox extends MathElementBase implements IMathBorderBox, IHasControlCharacterProperties
```

Рисует прямоугольную или другую границу вокруг IMathElement.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathBorderBox(IMathElement element)](#MathBorderBox-com.aspose.slides.IMathElement-) | Создаёт элемент MathBorderBox с прямоугольной границей |
| [MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Создаёт элемент MathBorderBox |
## Методы

| Метод | Описание |
| --- | --- |
| [getBase()](#getBase--) | Базовый аргумент |
| [getHideTop()](#getHideTop--) | Скрыть верхнее ребро (по умолчанию false) — указывает, скрыто или отображено верхнее ребро рамки. |
| [setHideTop(boolean value)](#setHideTop-boolean-) | Скрыть верхнее ребро (по умолчанию false) — указывает, скрыто или отображено верхнее ребро рамки. |
| [getHideBottom()](#getHideBottom--) | Скрыть нижнее ребро (по умолчанию false) — указывает, скрыто или отображено нижнее ребро рамки. |
| [setHideBottom(boolean value)](#setHideBottom-boolean-) | Скрыть нижнее ребро (по умолчанию false) — указывает, скрыто или отображено нижнее ребро рамки. |
| [getHideLeft()](#getHideLeft--) | Скрыть левое ребро (по умолчанию false) — указывает, скрыто или отображено левое ребро рамки. |
| [setHideLeft(boolean value)](#setHideLeft-boolean-) | Скрыть левое ребро (по умолчанию false) — указывает, скрыто или отображено левое ребро рамки. |
| [getHideRight()](#getHideRight--) | Скрыть правое ребро (по умолчанию false) — указывает, скрыто или отображено правое ребро рамки. |
| [setHideRight(boolean value)](#setHideRight-boolean-) | Скрыть правое ребро (по умолчанию false) — указывает, скрыто или отображено правое ребро рамки. |
| [getStrikethroughHorizontal()](#getStrikethroughHorizontal--) | Перечёркнутая горизонтальная линия (по умолчанию false) — указывает, скрыта или отображена перечёркнутая горизонтальная линия. |
| [setStrikethroughHorizontal(boolean value)](#setStrikethroughHorizontal-boolean-) | Перечёркнутая горизонтальная линия (по умолчанию false) — указывает, скрыта или отображена перечёркнутая горизонтальная линия. |
| [getStrikethroughVertical()](#getStrikethroughVertical--) | Перечёркнутая вертикальная линия (по умолчанию false) — указывает, скрыта или отображена перечёркнутая вертикальная линия. |
| [setStrikethroughVertical(boolean value)](#setStrikethroughVertical-boolean-) | Перечёркнутая вертикальная линия (по умолчанию false) — указывает, скрыта или отображена перечёркнутая вертикальная линия. |
| [getStrikethroughBottomLeftToTopRight()](#getStrikethroughBottomLeftToTopRight--) | Перечёркнутая линия из нижнего левого в верхний правый (по умолчанию false). |
| [setStrikethroughBottomLeftToTopRight(boolean value)](#setStrikethroughBottomLeftToTopRight-boolean-) | Перечёркнутая линия из нижнего левого в верхний правый (по умолчанию false). |
| [getStrikethroughTopLeftToBottomRight()](#getStrikethroughTopLeftToBottomRight--) | Перечёркнутая линия из верхнего левого в нижний правый (по умолчанию false). |
| [setStrikethroughTopLeftToBottomRight(boolean value)](#setStrikethroughTopLeftToBottomRight-boolean-) | Перечёркнутая линия из верхнего левого в нижний правый (по умолчанию false). |
| [getChildren()](#getChildren--) | Получить дочерние элементы |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Свойства управляющих символов |
### MathBorderBox(IMathElement element) {#MathBorderBox-com.aspose.slides.IMathElement-}
```
public MathBorderBox(IMathElement element)
```

Создаёт элемент MathBorderBox с прямоугольной границей

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Базовый элемент, к которому применяется рамка. Может быть null. |

### MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#MathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public MathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Создаёт элемент MathBorderBox

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"), true, true, true, false, true, true, true, true)
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Базовый элемент, к которому применяется рамка |
| hideTop | boolean | Скрыть верхнее ребро |
| hideBottom | boolean | Скрыть нижнее ребро |
| hideLeft | boolean | Скрыть левое ребро |
| hideRight | boolean | Скрыть правое ребро |
| strikethroughHorizontal | boolean | Перечёркнутая горизонтальная линия |
| strikethroughVertical | boolean | Перечёркнутая вертикальная линия |
| strikethroughBottomLeftToTopRight | boolean | Перечёркнутая линия из нижнего левого в верхний правый |
| strikethroughTopLeftToBottomRight | boolean | Перечёркнутая линия из верхнего левого в нижний правый |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```

Базовый аргумент

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  IMathElement base = borderBox.getBase();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getHideTop() {#getHideTop--}
```
public final boolean getHideTop()
```

Скрыть верхнее ребро (по умолчанию false) — указывает, скрыто или отображено верхнее ребро рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Возвращаемое значение:**
boolean
### setHideTop(boolean value) {#setHideTop-boolean-}
```
public final void setHideTop(boolean value)
```

Скрыть верхнее ребро (по умолчанию false) — указывает, скрыто или отображено верхнее ребро рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideTop(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getHideBottom() {#getHideBottom--}
```
public final boolean getHideBottom()
```

Скрыть нижнее ребро (по умолчанию false) — указывает, скрыто или отображено нижнее ребро рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Возвращаемое значение:**
boolean
### setHideBottom(boolean value) {#setHideBottom-boolean-}
```
public final void setHideBottom(boolean value)
```

Скрыть нижнее ребро (по умолчанию false) — указывает, скрыто или отображено нижнее ребро рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideBottom(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getHideLeft() {#getHideLeft--}
```
public final boolean getHideLeft()
```

Скрыть левое ребро (по умолчанию false) — указывает, скрыто или отображено левое ребро рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Возвращаемое значение:**
boolean
### setHideLeft(boolean value) {#setHideLeft-boolean-}
```
public final void setHideLeft(boolean value)
```

Скрыть левое ребро (по умолчанию false) — указывает, скрыто или отображено левое ребро рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideLeft(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getHideRight() {#getHideRight--}
```
public final boolean getHideRight()
```

Скрыть правое ребро (по умолчанию false) — указывает, скрыто или отображено правое ребро рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Возвращаемое значение:**
boolean
### setHideRight(boolean value) {#setHideRight-boolean-}
```
public final void setHideRight(boolean value)
```

Скрыть правое ребро (по умолчанию false) — указывает, скрыто или отображено правое ребро рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setHideRight(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughHorizontal() {#getStrikethroughHorizontal--}
```
public final boolean getStrikethroughHorizontal()
```

Перечёркнутая горизонтальная линия (по умолчанию false) — указывает, скрыта или отображена перечёркнутая горизонтальная линия.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Возвращаемое значение:**
boolean
### setStrikethroughHorizontal(boolean value) {#setStrikethroughHorizontal-boolean-}
```
public final void setStrikethroughHorizontal(boolean value)
```

Перечёркнутая горизонтальная линия (по умолчанию false) — указывает, скрыта или отображена перечёркнутая горизонтальная линия.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughHorizontal(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughVertical() {#getStrikethroughVertical--}
```
public final boolean getStrikethroughVertical()
```

Перечёркнутая вертикальная линия (по умолчанию false) — указывает, скрыта или отображена перечёркнутая вертикальная линия.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Возвращаемое значение:**
boolean
### setStrikethroughVertical(boolean value) {#setStrikethroughVertical-boolean-}
```
public final void setStrikethroughVertical(boolean value)
```

Перечёркнутая вертикальная линия (по умолчанию false) — указывает, скрыта или отображена перечёркнутая вертикальная линия.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughVertical(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughBottomLeftToTopRight() {#getStrikethroughBottomLeftToTopRight--}
```
public final boolean getStrikethroughBottomLeftToTopRight()
```

Перечёркнутая линия из нижнего левого в верхний правый (по умолчанию false). Указывает, скрыта или отображена диагональная перечёркнутая линия от нижнего-левого угла к верх-ному правому углу рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Возвращаемое значение:**
boolean
### setStrikethroughBottomLeftToTopRight(boolean value) {#setStrikethroughBottomLeftToTopRight-boolean-}
```
public final void setStrikethroughBottomLeftToTopRight(boolean value)
```

Перечёркнутая линия из нижнего левого в верхний правый (по умолчанию false). Указывает, скрыта или отображена диагональная перечёркнутая линия от нижнего-левого угла к верх-ному правому углу рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughBottomLeftToTopRight(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getStrikethroughTopLeftToBottomRight() {#getStrikethroughTopLeftToBottomRight--}
```
public final boolean getStrikethroughTopLeftToBottomRight()
```

Перечёркнутая линия из верхнего левого в нижний правый (по умолчанию false). Указывает, скрыта или отображена диагональная перечёркнутая линия от верх-него левого угла к нижнему правому углу рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Возвращаемое значение:**
boolean
### setStrikethroughTopLeftToBottomRight(boolean value) {#setStrikethroughTopLeftToBottomRight-boolean-}
```
public final void setStrikethroughTopLeftToBottomRight(boolean value)
```

Перечёркнутая линия из верхнего левого в нижний правый (по умолчанию false). Указывает, скрыта или отображена диагональная перечёркнутая линия от верх-него левого угла к нижнему правому углу рамки.

--------------------

> ```
> Example:
>  
>  MathBorderBox borderBox = new MathBorderBox(new MathematicalText("x"));
>  borderBox.setStrikethroughTopLeftToBottomRight(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |
### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Получить дочерние элементы

**Возвращаемое значение:**
com.aspose.slides.IMathElement[]
### getControlCharacterProperties() {#getControlCharacterProperties--}
```
public final OmmlControlCharacterPPTXUnsupportedProps getControlCharacterProperties()
```

Свойства управляющих символов

**Возвращаемое значение:**
com.aspose.slides.OmmlControlCharacterPPTXUnsupportedProps