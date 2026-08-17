---
title: IMathBox
second_title: Aspose.Slides для Java — справочник API
description: Определяет логическое упаковывание (упаковку) математического элемента.
type: docs
url: /ru/com.aspose.slides/imathbox/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement)
```
public interface IMathBox extends IMathElement
```

Определяет логическое упаковывание (упаковку) математического элемента. Например, упакованный объект может служить эмулятором оператора с точкой выравнивания или без неё, служить точкой разрыва строки или быть сгруппирован так, чтобы не допускать разрывы строк внутри. Например, оператор "==" следует упаковать, чтобы предотвратить разрывы строк.

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
| [getAlignmentPoint()](#getAlignmentPoint--) | Если true, этот эмулятор оператора служит точкой выравнивания; то есть назначенные точки выравнивания в других уравнениях могут быть выровнены с ним. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Если true, этот эмулятор оператора служит точкой выравнивания; то есть назначенные точки выравнивания в других уравнениях могут быть выровнены с ним. |
| [getExplicitBreak()](#getExplicitBreak--) | Явный разрыв указывает, есть ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта Box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Явный разрыв указывает, есть ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта Box. |
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

**Возвращает:**
[IMathElement](../../com.aspose.slides/imathelement)
### getOperatorEmulator() {#getOperatorEmulator--}
```
public abstract boolean getOperatorEmulator()
```

Эмулятор оператора. Если true, коробка и её содержимое ведут себя как единый оператор и наследуют свойства оператора. Это означает, например, что символ может служить точкой разрыва строки и может быть выровнен с другими операторами. Эмуляторы операторов часто используются, когда один или несколько глифов комбинируются в оператор, например '=='. Значение по умолчанию: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setOperatorEmulator(true);
> ```

**Возвращает:**
boolean
### setOperatorEmulator(boolean value) {#setOperatorEmulator-boolean-}
```
public abstract void setOperatorEmulator(boolean value)
```

Эмулятор оператора. Если true, коробка и её содержимое ведут себя как единый оператор и наследуют свойства оператора. Это означает, например, что символ может служить точкой разрыва строки и может быть выровнен с другими операторами. Эмуляторы операторов часто используются, когда один или несколько глифов комбинируются в оператор, например '=='. Значение по умолчанию: false

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

Без разрыва. Это свойство задаёт свойство «unbreakable» у коробки объекта. Если true, внутри коробки не может происходить разрыв строки. Это может быть важно для эмуляторов операторов, состоящих из более чем одного бинарного оператора. Если этот элемент не указан, разрывы могут происходить внутри коробки. По умолчанию: true

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("**********").toBox();
>  box.setNoBreak(false);
> ```

**Возвращает:**
boolean
### setNoBreak(boolean value) {#setNoBreak-boolean-}
```
public abstract void setNoBreak(boolean value)
```

Без разрыва. Это свойство задаёт свойство «unbreakable» у коробки объекта. Если true, внутри коробки не может происходить разрыв строки. Это может быть важно для эмуляторов операторов, состоящих из более чем одного бинарного оператора. Если этот элемент не указан, разрывы могут происходить внутри коробки. По умолчанию: true

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

Дифференциал. Если true, коробка действует как дифференциал (например, \\ud835\\udc51\\ud835\\udc65 в подынтеграле) и получает соответствующий горизонтальный интервал для математического дифференциала. По умолчанию: false

--------------------

> ```
> Example:
>  
>  IMathBox differential = new MathematicalText("dx").toBox();
>  differential.setDifferential(true);
>  IMathBlock baseArg = new MathematicalText("x").join(differential);
>  IMathNaryOperator integral = baseArg.integral(MathIntegralTypes.Simple, "0", "1");
> ```

**Возвращает:**
boolean
### setDifferential(boolean value) {#setDifferential-boolean-}
```
public abstract void setDifferential(boolean value)
```

Дифференциал. Если true, коробка действует как дифференциал (например, \\ud835\\udc51\\ud835\\udc65 в подынтеграле) и получает соответствующий горизонтальный интервал для математического дифференциала. По умолчанию: false

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

Если true, этот эмулятор оператора служит точкой выравнивания; то есть назначенные точки выравнивания в других уравнениях могут быть выровнены с ним. По умолчанию: false

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setAlignmentPoint(true);
> ```

**Возвращает:**
boolean
### setAlignmentPoint(boolean value) {#setAlignmentPoint-boolean-}
```
public abstract void setAlignmentPoint(boolean value)
```

Если true, этот эмулятор оператора служит точкой выравнивания; то есть назначенные точки выравнивания в других уравнениях могут быть выровнены с ним. По умолчанию: false

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

Явный разрыв указывает, есть ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта Box. Указывает номер оператора в предыдущей строке математического текста, который будет использоваться в качестве точки выравнивания для текущей строки математического текста. Возможные значения: 1..255. По умолчанию: 0 (нет явного разрыва).

--------------------

> ```
> Example:
>  
>  IMathBox box = new MathematicalText("==").toBox();
>  box.setExplicitBreak(1);
> ```

**Возвращает:**
byte
### setExplicitBreak(byte value) {#setExplicitBreak-byte-}
```
public abstract void setExplicitBreak(byte value)
```

Явный разрыв указывает, есть ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта Box. Указывает номер оператора в предыдущей строке математического текста, который будет использоваться в качестве точки выравнивания для текущей строки математического текста. Возможные значения: 1..255. По умолчанию: 0 (нет явного разрыва).

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