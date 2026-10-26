---
title: MathBox
second_title: Aspose.Slides для Android через справочник Java API
description: Указывает логическую упаковку (упаковку) математического элемента.
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

Определяет логическое упаковывание (упаковку) математического элемента. Например, упакованный объект может служить эмулятором оператора с точкой выравнивания или без неё, служить точкой разрыва строки или быть сгруппированным так, чтобы не допускать разрывы строки внутри. Например, оператор "==" должен быть упакован, чтобы предотвратить разрывы строки.

--------------------

> ```
> Example:
>  
>  MathBox box = new MathBox(new MathematicalText("=="));
> ```
## Constructors

| Конструктор | Описание |
| --- | --- |
| [MathBox(IMathElement element)](#MathBox-com.aspose.slides.IMathElement-) | Инициализирует MathBox с указанным элементом в качестве аргумента |
## Methods

| Метод | Описание |
| --- | --- |
| [getBase()](#getBase--) | Базовый аргумент |
| [getOperatorEmulator()](#getOperatorEmulator--) | Эмулятор оператора. |
| [setOperatorEmulator(boolean value)](#setOperatorEmulator-boolean-) | Эмулятор оператора. |
| [getNoBreak()](#getNoBreak--) | No break Это свойство указывает свойство "unbreakable" (неразрывное) на объектном боксе. |
| [setNoBreak(boolean value)](#setNoBreak-boolean-) | No break Это свойство указывает свойство "unbreakable" (неразрывное) на объектном боксе. |
| [getDifferential()](#getDifferential--) | Differential Когда истинно, коробка действует как дифференциал (например, \\ud835\\udc51\\ud835\\udc65 в интегранде) и получает соответствующее горизонтальное пространство для математического дифференциала. |
| [setDifferential(boolean value)](#setDifferential-boolean-) | Differential Когда истинно, коробка действует как дифференциал (например, \\ud835\\udc51\\ud835\\udc65 в интегранде) и получает соответствующее горизонтальное пространство для математического дифференциала. |
| [getAlignmentPoint()](#getAlignmentPoint--) | Когда истинно, этот эмулятор оператора служит точкой выравнивания; то есть назначенные точки выравнивания в других уравнениях могут быть выровнены с ним. |
| [setAlignmentPoint(boolean value)](#setAlignmentPoint-boolean-) | Когда истинно, этот эмулятор оператора служит точкой выравнивания; то есть назначенные точки выравнивания в других уравнениях могут быть выровнены с ним. |
| [getExplicitBreak()](#getExplicitBreak--) | Explicit break указывает, есть ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта box. |
| [setExplicitBreak(byte value)](#setExplicitBreak-byte-) | Explicit break указывает, есть ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта box. |
| [getChildren()](#getChildren--) | Получить дочерние элементы |
| [getControlCharacterProperties()](#getControlCharacterProperties--) | Свойства управляющих символов |

### MathBox(IMathElement element) {#MathBox-com.aspose.slides.IMathElement-}
```
public MathBox(IMathElement element)
```

Инициализирует MathBox с указанным элементом в качестве аргумента

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

Эмулятор оператора. Когда истинно, коробка и её содержимое ведут себя как один оператор и наследуют свойства оператора. Это означает, например, что символ может служить точкой разрыва строки и может быть выровнен с другими операторами. Эмуляторы операторов часто используются, когда один или несколько глифов комбинируются в оператор, например '=='. Значение по умолчанию: false

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

Эмулятор оператора. Когда истинно, коробка и её содержимое ведут себя как один оператор и наследуют свойства оператора. Это означает, например, что символ может служить точкой разрыва строки и может быть выровнен с другими операторами. Эмуляторы операторов часто используются, когда один или несколько глифов комбинируются в оператор, например '=='. Значение по умолчанию: false

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

No break Это свойство указывает свойство "unbreakable" (неразрывное) на объектном боксе. Когда истинно, внутри бокса не может происходить разрыв строки. Это может быть важно для эмуляторов операторов, состоящих более чем из одного бинарного оператора. Когда этот элемент не указан, разрывы могут происходить внутри бокса. По умолчанию: true

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

No break Это свойство указывает свойство "unbreakable" (неразрывное) на объектном боксе. Когда истинно, внутри бокса не может происходить разрыв строки. Это может быть важно для эмуляторов операторов, состоящих более чем из одного бинарного оператора. Когда этот элемент не указан, разрывы могут происходить внутри бокса. По умолчанию: true

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

Differential Когда истинно, коробка действует как дифференциал (например, \\ud835\\udc51\\ud835\\udc65 в интегранде) и получает соответствующее горизонтальное пространство для математического дифференциала. Значение по умолчанию: false

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

Differential Когда истинно, коробка действует как дифференциал (например, \\ud835\\udc51\\ud835\\udc65 в интегранде) и получает соответствующее горизонтальное пространство для математического дифференциала. Значение по умолчанию: false

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

Когда истинно, этот эмулятор оператора служит точкой выравнивания; то есть назначенные точки выравнивания в других уравнениях могут быть выровнены с ним. Значение по умолчанию: false

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

Когда истинно, этот эмулятор оператора служит точкой выравнивания; то есть назначенные точки выравнивания в других уравнениях могут быть выровнены с ним. Значение по умолчанию: false

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

Explicit break указывает, есть ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта box. Указывает номер оператора на предыдущей строке математического текста, который будет использоваться как точка выравнивания для текущей строки. Возможные значения: 1..255. Значение по умолчанию: 0 (нет явного разрыва)

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

Explicit break указывает, есть ли разрыв строки в начале объекта Box, так что строка переносится в начале объекта box. Указывает номер оператора на предыдущей строке математического текста, который будет использоваться как точка выравнивания для текущей строки. Возможные значения: 1..255. Значение по умолчанию: 0 (нет явного разрыва)

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