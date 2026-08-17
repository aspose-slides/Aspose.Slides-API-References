---
title: IMathArray
second_title: Справочник API Aspose.Slides для Java
description: Указывает вертикальный массив уравнений или любых математических объектов
type: docs
url: /ru/com.aspose.slides/imatharray/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathArray extends IMathElement
```

Указывает вертикальный массив уравнений или любых математических объектов

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getArguments()](#getArguments--) | Набор элементов массива |
| [getBaseJustification()](#getBaseJustification--) | Указывает выравнивание массива относительно окружающего текста. Текст за пределами массива может быть выровнен по нижней, верхней или центральной части объекта массива. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Указывает выравнивание массива относительно окружающего текста. Текст за пределами массива может быть выровнен по нижней, верхней или центральной части объекта массива. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Максимальное распределение. При значении true массив растягивается до максимальной ширины содержащего элемента (страницы, колонки, ячейки и т.д.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Максимальное распределение. При значении true массив растягивается до максимальной ширины содержащего элемента (страницы, колонки, ячейки и т.д.). |
| [getObjectDistribution()](#getObjectDistribution--) | Распределение по объекту. При true содержимое массива растягивается до максимальной ширины объекта массива. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Распределение по объекту. При true содержимое массива растягивается до максимальной ширины объекта массива. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Тип вертикального интервала между элементами массива |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Тип вертикального интервала между элементами массива |
| [getRowSpacing()](#getRowSpacing--) | Интервал между строками массива. Используется только когда RowSpacingRule установлен в 3. Вариант Exactly — единица измерения точки, вариант Multiple — половины строк. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Интервал между строками массива. Используется только когда RowSpacingRule установлен в 3. Вариант Exactly — единица измерения точки, вариант Multiple — половины строк. |
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
> ```

**Возврат:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public abstract int getBaseJustification()
```

Указывает выравнивание массива относительно окружающего текста. Текст за пределами массива может быть выровнен по нижней, верхней или центральной части объекта массива. Значение по умолчанию: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Возврат:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public abstract void setBaseJustification(int value)
```

Указывает выравнивание массива относительно окружающего текста. Текст за пределами массива может быть выровнен по нижней, верхней или центральной части объекта массива. Значение по умолчанию: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getMaximumDistribution() {#getMaximumDistribution--}
```
public abstract boolean getMaximumDistribution()
```

Максимальное распределение. При значении true массив растягивается до максимальной ширины содержащего элемента (страницы, колонки, ячейки и т.д.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Возврат:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public abstract void setMaximumDistribution(boolean value)
```

Максимальное распределение. При значении true массив растягивается до максимальной ширины содержащего элемента (страницы, колонки, ячейки и т.д.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getObjectDistribution() {#getObjectDistribution--}
```
public abstract boolean getObjectDistribution()
```

Распределение по объекту. При true содержимое массива растягивается до максимальной ширины объекта массива.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Возврат:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public abstract void setObjectDistribution(boolean value)
```

Распределение по объекту. При true содержимое массива растягивается до максимальной ширины объекта массива.

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

**Возврат:**
int
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

Интервал между строками массива. Используется только когда RowSpacingRule установлен в 3. Вариант Exactly — единица измерения точки, вариант Multiple — половины строк. По умолчанию: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Возврат:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public abstract void setRowSpacing(long value)
```

Интервал между строками массива. Используется только когда RowSpacingRule установлен в 3. Вариант Exactly — единица измерения точки, вариант Multiple — половины строк. По умолчанию: 0

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