---
title: MathArray
second_title: Справочник API Aspose.Slides для Java
description: Указывает вертикальный массив уравнений или любых математических объектов
type: docs
url: /ru/com.aspose.slides/matharray/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathArray](../../com.aspose.slides/imatharray)
```
public final class MathArray extends MathElementBase implements IMathArray
```

Определяет вертикальный массив уравнений или любых математических объектов

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathArray(IMathElement element)](#MathArray-com.aspose.slides.IMathElement-) | Создает математический массив и помещает в него указанный элемент |
| [MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)](#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--) | Создает математический массив и помещает в него указанные элементы |
## Методы

| Метод | Описание |
| --- | --- |
| [getArguments()](#getArguments--) | Набор элементов массива |
| [getBaseJustification()](#getBaseJustification--) | Задает выравнивание массива относительно окружающего текста. Текст за пределами массива может быть выровнен по нижней, верхней части или центру объекта массива. |
| [setBaseJustification(int value)](#setBaseJustification-int-) | Задает выравнивание массива относительно окружающего текста. Текст за пределами массива может быть выровнен по нижней, верхней части или центру объекта массива. |
| [getMaximumDistribution()](#getMaximumDistribution--) | Максимальное распределение. Если значение true, массив растягивается до максимальной ширины содержащего элемента (страница, колонка, ячейка и т.д.). |
| [setMaximumDistribution(boolean value)](#setMaximumDistribution-boolean-) | Максимальное распределение. Если значение true, массив растягивается до максимальной ширины содержащего элемента (страница, колонка, ячейка и т.д.). |
| [getObjectDistribution()](#getObjectDistribution--) | Распределение по объекту. Если значение true, содержимое массива распределяется по максимальной ширине объекта массива. |
| [setObjectDistribution(boolean value)](#setObjectDistribution-boolean-) | Распределение по объекту. Если значение true, содержимое массива распределяется по максимальной ширине объекта массива. |
| [getRowSpacingRule()](#getRowSpacingRule--) | Тип вертикального интервала между элементами массива. По умолчанию: SingleLineGap |
| [setRowSpacingRule(int value)](#setRowSpacingRule-int-) | Тип вертикального интервала между элементами массива. По умолчанию: SingleLineGap |
| [getRowSpacing()](#getRowSpacing--) | Интервал между строками массива. Используется только при значении RowSpacingRule 3. В случае Exactly единицей измерения являются пункты, в случае Multiple — половины строк. |
| [setRowSpacing(long value)](#setRowSpacing-long-) | Интервал между строками массива. Используется только при значении RowSpacingRule 3. В случае Exactly единицей измерения являются пункты, в случае Multiple — половины строк. |
| [getChildren()](#getChildren--) | Получить дочерние элементы |
### MathArray(IMathElement element) {#MathArray-com.aspose.slides.IMathElement-}
```
public MathArray(IMathElement element)
```

Создает математический массив и помещает в него указанный элемент

--------------------

> ```
> Example:
>  
>  MathArray mathArray = new MathArray(new MathematicalText("item1"));
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Элемент, который помещается в массив |

### MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements) {#MathArray-com.aspose.ms.System.Collections.Generic.IGenericEnumerable-com.aspose.slides.IMathElement--}
```
public MathArray(System.Collections.Generic.IGenericEnumerable<IMathElement> elements)
```

Создает математический массив и помещает в него указанные элементы

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| elements | com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides.IMathElement> | Элементы, которые помещаются в массив |

### getArguments() {#getArguments--}
```
public final IMathElementCollection getArguments()
```

Набор элементов массива

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.getArguments().add(new MathematicalText("item2"));
> ```

**Возвращает:**
[IMathElementCollection](../../com.aspose.slides/imathelementcollection)
### getBaseJustification() {#getBaseJustification--}
```
public final int getBaseJustification()
```

Задает выравнивание массива относительно окружающего текста. Текст за пределами массива может быть выровнен по нижней, верхней части или центру объекта массива. Значение по умолчанию: Center

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setBaseJustification(MathVerticalAlignment.Top);
> ```

**Возвращает:**
int
### setBaseJustification(int value) {#setBaseJustification-int-}
```
public final void setBaseJustification(int value)
```

Задает выравнивание массива относительно окружающего текста. Текст за пределами массива может быть выровнен по нижней, верхней части или центру объекта массива. Значение по умолчанию: Center

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
public final boolean getMaximumDistribution()
```

Максимальное распределение. Если значение true, массив растягивается до максимальной ширины содержащего элемента (страница, колонка, ячейка и т.д.).

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setMaximumDistribution(true);
> ```

**Возвращает:**
boolean
### setMaximumDistribution(boolean value) {#setMaximumDistribution-boolean-}
```
public final void setMaximumDistribution(boolean value)
```

Максимальное распределение. Если значение true, массив растягивается до максимальной ширины содержащего элемента (страница, колонка, ячейка и т.д.).

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
public final boolean getObjectDistribution()
```

Распределение по объекту. Если значение true, содержимое массива распределяется по максимальной ширине объекта массива.

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setObjectDistribution(true);
> ```

**Возвращает:**
boolean
### setObjectDistribution(boolean value) {#setObjectDistribution-boolean-}
```
public final void setObjectDistribution(boolean value)
```

Распределение по объекту. Если значение true, содержимое массива распределяется по максимальной ширине объекта массива.

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
public final int getRowSpacingRule()
```

Тип вертикального интервала между элементами массива. По умолчанию: SingleLineGap

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.OneAndAHalfLineGap);
> ```

**Возвращает:**
int
### setRowSpacingRule(int value) {#setRowSpacingRule-int-}
```
public final void setRowSpacingRule(int value)
```

Тип вертикального интервала между элементами массива. По умолчанию: SingleLineGap

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
public final long getRowSpacing()
```

Интервал между строками массива. Используется только при значении RowSpacingRule 3. В случае Exactly единицей измерения являются пункты, в случае Multiple — половины строк. Значение по умолчанию: 0

--------------------

> ```
> Example:
>  
>  IMathArray mathArray = new MathArray(new MathematicalText("item1"));
>  mathArray.setRowSpacingRule(MathRowSpacingRule.Exactly);
>  mathArray.setRowSpacing(10);
> ```

**Возвращает:**
long
### setRowSpacing(long value) {#setRowSpacing-long-}
```
public final void setRowSpacing(long value)
```

Интервал между строками массива. Используется только при значении RowSpacingRule 3. В случае Exactly единицей измерения являются пункты, в случае Multiple — половины строк. Значение по умолчанию: 0

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

### getChildren() {#getChildren--}
```
public final IMathElement[] getChildren()
```

Получить дочерние элементы

**Возвращает:**
com.aspose.slides.IMathElement[]