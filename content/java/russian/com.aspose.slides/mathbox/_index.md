---
title: MathBox
second_title: Справочник API Aspose.Slides для Java
description: Определяет логическую упаковку математического элемента.
type: docs
url: /ru/com.aspose.slides/mathbox/
---
**Наследование:**
java.lang.Object, [com.aspose.slides.MathElementBase](../../com.aspose.slides/mathelementbase)

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathBox](../../com.aspose.slides/imathbox), com.aspose.slides.IHasControlCharacterProperties
```
public final class MathBox extends MathElementBase implements IMathBox, IHasControlCharacterProperties
```

Определяет логическое выделение (упаковку) математического элемента. Например, выделенный объект может выступать в роли эмулятора оператора с точкой выравнивания или без неё, служить точкой разрыва строки или быть сгруппированным так, чтобы не допускать разрывы внутри. Например, оператор "==" следует выделять, чтобы предотвратить разрывы строк.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Инициализирует MathBox указанным элементом в качестве аргумента |
## Методы

| Метод | Описание |
| --- | --- |
| [getBase()](#getBase--) | Базовый аргумент |
| [getOperatorEmulator()](#getOperatorEmulator--) | Эмулятор оператора. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Эмулятор оператора. |
| [getNoBreak()](#getNoBreak--) | Без разрыва Это свойство указывает на свойство "неразрывности" у объекта коробки. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Без разрыва Это свойство указывает на свойство "неразрывности" у объекта коробки. |
| [getDifferential()](#getDifferential--) | Дифференциал Когда true, коробка действует как дифференциал (например, \\ud835\\udc51\\ud835\\udc65 в интегранте) и получает соответствующее горизонтальное расстояние для математического дифференциала. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Дифференциал Когда true, коробка действует как дифференциал (например, \\ud835\\udc51\\ud835\\udc65 в интегранте) и получает соответствующее горизонтальное расстояние для математического дифференциала. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Когда true, этот эмулятор оператора служит точкой выравнивания; то есть назначенные точки выравнивания в других уравнениях могут быть выровнены с ним. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Когда true, этот эмулятор оператора служит точкой выравнивания; то есть назначенные точки выравнивания в других уравнениях могут быть выровнены с ним. |
| [getExplicitBreak()](#getExplicitBreak--) | Явный разрыв указывает, есть ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта коробки. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Явный разрыв указывает, есть ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта коробки. |
| [getChildren()](#getChildren--) | Получить дочерние элементы |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Свойства управляющих символов |
### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```


Инициализирует MathBox указанным элементом в качестве аргумента

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | Базовый элемент, к которому применяется коробка. Может быть null. |

### getBase() {#getBase--}
```
public final IMathElement getBase()
```


Базовый аргумент

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  IMathElement base = box.getBase();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public final boolean getOperatorEmulator()
```


Эмулятор оператора. Когда true, коробка и её содержимое ведут себя как один оператор и наследуют свойства оператора. Это означает, что, например, символ может служить точкой разрыва строки и может быть выровнен с другими операторами. Эмуляторы операторов часто используются, когда один или несколько глифов объединяются в оператор, например '=='. Значение по умолчанию: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Возвращаемое значение:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public final void setOperatorEmulator(boolean value)
```


Эмулятор оператора. Когда true, коробка и её содержимое ведут себя как один оператор и наследуют свойства оператора. Это означает, что, например, символ может служить точкой разрыва строки и может быть выровнен с другими операторами. Эмуляторы операторов часто используются, когда один или несколько глифов объединяются в оператор, например '=='. Значение по умолчанию: false

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
>  box.setOperatorEmulator(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public final boolean getNoBreak()
```


Без разрыва Это свойство указывает на свойство "неразрывности" у объекта коробки. Когда true, внутри коробки не могут возникать разрывы строк. Это может быть важно для эмуляторов операторов, состоящих более чем из одного бинарного оператора. Если элемент не указан, разрывы могут происходить внутри коробки. По умолчанию: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Возвращаемое значение:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public final void setNoBreak(boolean value)
```


Без разрыва Это свойство указывает на свойство "неразрывности" у объекта коробки. Когда true, внутри коробки не могут возникать разрывы строк. Это может быть важно для эмуляторов операторов, состоящих более чем из одного бинарного оператора. Если элемент не указан, разрывы могут происходить внутри коробки. По умолчанию: true

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("*****"));
>  box.setNoBreak(false);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public final boolean getDifferential()
```


Дифференциал Когда true, коробка действует как дифференциал (например, \\ud835\\udc51\\ud835\\udc65 в интегранте) и получает соответствующее горизонтальное расстояние для математического дифференциала. По умолчанию: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Возвращаемое значение:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public final void setDifferential(boolean value)
```


Дифференциал Когда true, коробка действует как дифференциал (например, \\ud835\\udc51\\ud835\\udc65 в интегранте) и получает соответствующее горизонтальное расстояние для математического дифференциала. По умолчанию: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getAlignmentPoint() {#getAlignmentPoint--}
```
public final boolean getAlignmentPoint()
```


Когда true, этот эмулятор оператора служит точкой выравнивания; то есть назначенные точки выравнивания в других уравнениях могут быть выровнены с ним. По умолчанию: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Возвращаемое значение:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public final void setAlignmentPoint(boolean value)
```


Когда true, этот эмулятор оператора служит точкой выравнивания; то есть назначенные точки выравнивания в других уравнениях могут быть выровнены с ним. По умолчанию: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getExplicitBreak() {#getExplicitBreak--}
```
public final byte getExplicitBreak()
```


Явный разрыв указывает, есть ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта коробки. Указывает номер оператора на предыдущей строке математического текста, который будет использоваться как точка выравнивания для текущей строки. Возможные значения: 1..255. По умолчанию: 0 (нет явного разрыва)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Возвращаемое значение:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public final void setExplicitBreak(byte value)
```


Явный разрыв указывает, есть ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта коробки. Указывает номер оператора на предыдущей строке математического текста, который будет использоваться как точка выравнивания для текущей строки. Возможные значения: 1..255. По умолчанию: 0 (нет явного разрыва)

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

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