---
title: IMathBox
second_title: Aspose.Slides для Android через справку Java API
description: Указывает логическое упаковывание (коробку) математического элемента.
type: docs
url: /ru/com.aspose.slides/imathbox/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Указывает логическое упаковывание (коробку) математического элемента. Например, упакованный объект может служить эмулятором оператора с точкой выравнивания или без неё, служить точкой разрыва строки, либо группироваться так, чтобы не допустить разрывов строк внутри. Например, оператор “==” следует упаковать, чтобы предотвратить разрывы строк.

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
> ```
## Методы

| Метод | Описание |
| --- | --- |
| [getBase()](#getBase--) | Базовый аргумент |
| [getOperatorEmulator()](#getOperatorEmulator--) | Эмулятор оператора. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Эмулятор оператора. |
| [getNoBreak()](#getNoBreak--) | Без разрыва. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | Без разрыва. |
| [getDifferential()](#getDifferential--) | Дифференциал. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Дифференциал. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Когда истинно, этот эмулятор оператора служит точкой выравнивания; то есть назначенные точки выравнивания в других уравнениях могут быть выровнены с ней. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Когда истинно, этот эмулятор оператора служит точкой выравнивания; то есть назначенные точки выравнивания в других уравнениях могут быть выровнены с ней. |
| [getExplicitBreak()](#getExplicitBreak--) | Явный разрыв указывает, есть ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Явный разрыв указывает, есть ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта. |
### getBase() {#getBase--}
```
public abstract IMathElement getBase()
```

Базовый аргумент

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  IMathElement base = box.getBase();
> ```

**Возвращаемое значение:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

Эмулятор оператора. Когда истинно, коробка и её содержимое ведут себя как один оператор и наследуют свойства оператора. Это значит, что, например, символ может служить точкой разрыва строки и может быть выровнен с другими операторами. Эмуляторы операторов часто используются, когда один или несколько глифов комбинируются в оператор, например ‘==’. Значение по умолчанию: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Возвращаемое значение:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

Эмулятор оператора. Когда истинно, коробка и её содержимое ведут себя как один оператор и наследуют свойства оператора. Это значит, что, например, символ может служить точкой разрыва строки и может быть выровнен с другими операторами. Эмуляторы операторов часто используются, когда один или несколько глифов комбинируются в оператор, например ‘==’. Значение по умолчанию: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getNoBreak() {#getNoBreak--}
```
public abstract boolean getNoBreak()
```

Без разрыва. Это свойство задаёт «неразрывность» коробки объекта. Когда истинно, внутри коробки не может происходить разрыв строки. Это важно для эмуляторов операторов, состоящих из более чем одного бинарного оператора. Если элемент не указан, разрывы могут происходить внутри коробки. По умолчанию: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Возвращаемое значение:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

Без разрыва. Это свойство задаёт «неразрывность» коробки объекта. Когда истинно, внутри коробки не может происходить разрыв строки. Это важно для эмуляторов операторов, состоящих из более чем одного бинарного оператора. Если элемент не указан, разрывы могут происходить внутри коробки. По умолчанию: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getDifferential() {#getDifferential--}
```
public abstract boolean getDifferential()
```

Дифференциал. Когда истинно, коробка выступает как дифференциал (например, \\ud835\\udc51\\ud835\\udc65 в подынтеграле) и получает соответствующий горизонтальный интервал для математического дифференциала. Значение по умолчанию: false

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
public abstract void setDifferential(boolean value)
```

Дифференциал. Когда истинно, коробка выступает как дифференциал (например, \\ud835\\udc51\\ud835\\udc65 в подынтеграле) и получает соответствующий горизонтальный интервал для математического дифференциала. Значение по умолчанию: false

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
public abstract boolean getAlignmentPoint()
```

Когда истинно, этот эмулятор оператора служит точкой выравнивания; то есть назначенные точки выравнивания в других уравнениях могут быть выровнены с ней. Значение по умолчанию: false

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
public abstract void setAlignmentPoint(boolean value)
```

Когда истинно, этот эмулятор оператора служит точкой выравнивания; то есть назначенные точки выравнивания в других уравнениях могут быть выровнены с ней. Значение по умолчанию: false

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
public abstract byte getExplicitBreak()
```

Явный разрыв указывает, есть ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта. Задаёт номер оператора на предыдущей строке математического текста, который будет использоваться как точка выравнивания для текущей строки математического текста; возможные значения: 1..255. По умолчанию: 0 (нет явного разрыва)

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
public abstract void setExplicitBreak(byte value)
```

Явный разрыв указывает, есть ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта. Задаёт номер оператора на предыдущей строке математического текста, который будет использоваться как точка выравнивания для текущей строки математического текста; возможные значения: 1..255. По умолчанию: 0 (нет явного разрыва)

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