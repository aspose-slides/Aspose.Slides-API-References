---
title: IMathArray
second_title: Aspose.Slides для Android через справочник Java API
description: Определяет вертикальный массив уравнений или любых математических объектов
type: docs
url: /ru/com.aspose.slides/imatharray/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Определяет вертикальный массив уравнений или любых математических объектов

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  ```
## Методы

| Метод | Описание |
| --- | --- |
| [getArguments()](#getArguments--) | Набор элементов массива |
| [getBaseJustification()](#getBaseJustification--) | Указывает выравнивание массива относительно окружающего текста. Текст за пределами массива может быть выровнен по нижнему, верхнему краю или по центру объекта массива. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Указывает выравнивание массива относительно окружающего текста. Текст за пределами массива может быть выровнен по нижнему, верхнему краю или по центру объекта массива. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Максимальное распределение. Когда значение true, массив растягивается до максимальной ширины содержащего элемента (страница, колонка, ячейка и т.д.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Максимальное распределение. Когда значение true, массив растягивается до максимальной ширины содержащего элемента (страница, колонка, ячейка и т.д.). |
| [getObjectDistribution()](#getObjectDistribution--) | Распределение объекта. Когда значение true, содержимое массива растягивается до максимальной ширины объекта массива. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Распределение объекта. Когда значение true, содержимое массива растягивается до максимальной ширины объекта массива. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Тип вертикального интервала между элементами массива |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Тип вертикального интервала между элементами массива |
| [getRowSpacing()](#getRowSpacing--) | Интервал между строками массива. Используется только когда RowSpacingRule установлено в 3 — Exactly, в этом случае единица измерения — пункты, или Multiple, когда единица измерения — полустрочки. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Интервал между строками массива. Используется только когда RowSpacingRule установлено в 3 — Exactly, в этом случае единица измерения — пункты, или Multiple, когда единица измерения — полустрочки. |

### getArguments() {#getArguments--}
```
public abstract IMathElementCollection getArguments()
```

Набор элементов массива

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
>  ```

**Возвращает:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

Указывает выравнивание массива относительно окружающего текста. Текст за пределами массива может быть выровнен по нижнему, верхнему краю или по центру объекта массива. Значение по умолчанию: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
>  ```

**Возвращает:** int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Указывает выравнивание массива относительно окружающего текста. Текст за пределами массива может быть выровнен по нижнему, верхнему краю или по центру объекта массива. Значение по умолчанию: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
>  ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```

Максимальное распределение. Когда значение true, массив растягивается до максимальной ширины содержащего элемента (страница, колонка, ячейка и т.д.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
>  ```

**Возвращает:** boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

Максимальное распределение. Когда значение true, массив растягивается до максимальной ширины содержащего элемента (страница, колонка, ячейка и т.д.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
>  ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```

Распределение объекта. Когда значение true, содержимое массива растягивается до максимальной ширины объекта массива.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Возвращает:** boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```

Распределение объекта. Когда значение true, содержимое массива растягивается до максимальной ширины объекта массива.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getRowSpacingRule() {#getRowSpacingRule--}
```
public abstract int getRowSpacingRule()
```

Тип вертикального интервала между элементами массива

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Возвращает:** int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public abstract void setRowSpacingRule(int value)
```

Тип вертикального интервала между элементами массива

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getRowSpacing() {#getRowSpacing--}
```
public abstract long getRowSpacing()
```

Интервал между строками массива. Используется только когда RowSpacingRule установлено в 3 — Exactly, в этом случае единица измерения — пункты, или Multiple, когда единица измерения — полустрочки. Значение по умолчанию: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Возвращает:** long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```

Интервал между строками массива. Используется только когда RowSpacingRule установлено в 3 — Exactly, в этом случае единица измерения — пункты, или Multiple, когда единица измерения — полустрочки. Значение по умолчанию: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | long |  |