---
title: MathElementBase
second_title: Aspose.Slides для Android через Java API Reference
description: Базовый класс для IMathElement с реализацией некоторых методов, общих для всех наследуемых классов. Предназначен только для внутреннего использования.
type: docs
url: /ru/com.aspose.slides/mathelementbase/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IMathElement](../../com.aspose.slides/imathelement), com.aspose.slides.IDOMObject
```
public abstract class MathElementBase implements IMathElement, IDOMObject
```

Base class for IMathElement with the implementation of some methods that are common to all inherited classes For internal use only. Inherited class must be IMathElement.
## Методы

| Метод | Описание |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) | Возвращает объект Parent_Immediate. |
| [join(IMathElement mathElement)](#join-com.aspose.slides.IMathElement-) | Объединяет математический элемент и формирует математический блок |
| [join(String mathText)](#join-java.lang.String-) | Объединяет математический текст и формирует математический блок |
| [divide(IMathElement denominator)](#divide-com.aspose.slides.IMathElement-) | Создает дробь с этим числителем и указанным знаменателем |
| [divide(String denominator)](#divide-java.lang.String-) | Создает дробь с этим числителем и указанным знаменателем |
| [divide(IMathElement denominator, int fractionType)](#divide-com.aspose.slides.IMathElement-int-) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [divide(String denominator, int fractionType)](#divide-java.lang.String-int-) | Создает дробь указанного типа с этим числителем и указанным знаменателем |
| [enclose()](#enclose--) | Обрамляет математический элемент скобками |
| [enclose(char beginningCharacter, char endingCharacter)](#enclose-char-char-) | Обрамляет математический элемент указанными символами, такими как скобки или другими символами, в качестве рамки |
| [function(IMathElement functionArgument)](#function-com.aspose.slides.IMathElement-) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [function(String functionArgument)](#function-java.lang.String-) | Принимает функцию аргумента, используя этот экземпляр в качестве имени функции |
| [asArgumentOfFunction(IMathElement functionName)](#asArgumentOfFunction-com.aspose.slides.IMathElement-) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [asArgumentOfFunction(String functionName)](#asArgumentOfFunction-java.lang.String-) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [asArgumentOfFunction(int functionType)](#asArgumentOfFunction-int-) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента |
| [asArgumentOfFunction(int functionType, IMathElement additionalArgument)](#asArgumentOfFunction-int-com.aspose.slides.IMathElement-) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [asArgumentOfFunction(int functionType, String additionalArgument)](#asArgumentOfFunction-int-java.lang.String-) | Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент |
| [setSubscript(IMathElement subscript)](#setSubscript-com.aspose.slides.IMathElement-) | Создает нижний индекс |
| [setSubscript(String subscript)](#setSubscript-java.lang.String-) | Создает нижний индекс |
| [setSuperscript(IMathElement superscript)](#setSuperscript-com.aspose.slides.IMathElement-) | Создает верхний индекс |
| [setSuperscript(String superscript)](#setSuperscript-java.lang.String-) | Создает верхний индекс |
| [setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Создает нижний и верхний индексы справа |
| [setSubSuperscriptOnTheRight(String subscript, String superscript)](#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-) | Создает нижний и верхний индексы справа |
| [setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)](#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Creates subscript and superscript on the left |
| [setSubSuperscriptOnTheLeft(String subscript, String superscript)](#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-) | Creates subscript and superscript on the left |
| [radical(IMathElement degree)](#radical-com.aspose.slides.IMathElement-) | Указывает математический корень заданной степени из указанного аргумента. |
| [radical(String degree)](#radical-java.lang.String-) | Указывает математический корень заданной степени из указанного аргумента. |
| [setUpperLimit(IMathElement limit)](#setUpperLimit-com.aspose.slides.IMathElement-) | Принимает верхний предел |
| [setUpperLimit(String limit)](#setUpperLimit-java.lang.String-) | Принимает верхний предел |
| [setLowerLimit(IMathElement limit)](#setLowerLimit-com.aspose.slides.IMathElement-) | Принимает нижний предел |
| [setLowerLimit(String limit)](#setLowerLimit-java.lang.String-) | Принимает нижний предел |
| [nary(int type, IMathElement lowerLimit, IMathElement upperLimit)](#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Создает N-арный оператор |
| [nary(int type, String lowerLimit, String upperLimit)](#nary-int-java.lang.String-java.lang.String-) | Создает N-арный оператор |
| [toMathArray()](#toMathArray--) | Размещает в вертикальном массиве |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-) | Принимает интеграл |
| [integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)](#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-) | Принимает интеграл |
| [integral(int integralType)](#integral-int-) | Принимает интеграл без пределов |
| [integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)](#integral-int-java.lang.String-java.lang.String-int-) | Принимает интеграл |
| [integral(int integralType, String lowerLimit, String upperLimit)](#integral-int-java.lang.String-java.lang.String-) | Принимает интеграл |
| [accent(char accentCharacter)](#accent-char-) | Устанавливает знак акцента (символ над этим элементом) |
| [overbar()](#overbar--) | Устанавливает черту вверху этого элемента |
| [underbar()](#underbar--) | Устанавливает черту внизу этого элемента |
| [group()](#group--) | Размещает этот элемент в группе, используя нижнюю фигурную скобку |
| [group(char character, int position, int verticalJustification)](#group-char-int-int-) | Размещает этот элемент в группе, используя символ группировки, такой как нижняя фигурная скобка или иной |
| [toBorderBox()](#toBorderBox--) | Размещает этот элемент в border-box |
| [toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Размещает этот элемент в border-box |
| [toBox()](#toBox--) | Размещает этот элемент в невизуальном блоке (логическая группировка), который используется для группировки компонентов уравнения или другого экземпляра математического текста. |
| [getChildren()](#getChildren--) | Получить дочерние элементы |
### getParent_Immediate() {#getParent-Immediate--}
```
public IDOMObject getParent_Immediate()
```

Возвращает объект Parent_Immediate. Только для чтения IDOMObject.

**Возвращает:**
com.aspose.slides.IDOMObject
### join(IMathElement mathElement) {#join-com.aspose.slides.IMathElement-}
```
public IMathBlock join(IMathElement mathElement)
```

Объединяет математический элемент и формирует математический блок

--------------------

> ```
> Example:
>  
>  IMathElement element1 = new MathematicalText("x");
>  IMathElement element2 = new MathematicalText("y");
>  IMathBlock block = element1.join(element2);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathElement | [IMathElement](../../com.aspose.slides/imathelement) | Элемент, который будет объединён |

**Возвращает:**
[IMathBlock](../../com.aspose.slides/imathblock) - Новый IMathBlock, содержащий этот экземпляр и указанный аргумент
### join(String mathText) {#join-java.lang.String-}
```
public IMathBlock join(String mathText)
```

Объединяет математический текст и формирует математический блок

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathBlock block = element.join("+y");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| mathText | java.lang.String | Математический текст, который будет объединён |

**Возвращает:**
[IMathBlock](../../com.aspose.slides/imathblock) - Новый IMathBlock, содержащий этот экземпляр и указанный аргумент
### divide(IMathElement denominator) {#divide-com.aspose.slides.IMathElement-}
```
public final IMathFraction divide(IMathElement denominator)
```

Создает дробь с этим числителем и указанным знаменателем

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Знаменатель |

**Возвращает:**
[IMathFraction](../../com.aspose.slides/imathfraction) - новая дробь
### divide(String denominator) {#divide-java.lang.String-}
```
public final IMathFraction divide(String denominator)
```

Создает дробь с этим числителем и указанным знаменателем

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| denominator | java.lang.String | Знаменатель |

**Возвращает:**
[IMathFraction](../../com.aspose.slides/imathfraction) - новая дробь
### divide(IMathElement denominator, int fractionType) {#divide-com.aspose.slides.IMathElement-int-}
```
public final IMathFraction divide(IMathElement denominator, int fractionType)
```

Создает дробь указанного типа с этим числителем и указанным знаменателем

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathElement denumerator = new MathematicalText("y");
>  IMathFraction fraction = numerator.divide(denumerator, MathFractionTypes.Linear);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| denominator | [IMathElement](../../com.aspose.slides/imathelement) | Знаменатель |
| fractionType | int | Тип дроби: Bar, NoBar, Skewed, Linear |

**Возвращает:**
[IMathFraction](../../com.aspose.slides/imathfraction) - новая дробь
### divide(String denominator, int fractionType) {#divide-java.lang.String-int-}
```
public final IMathFraction divide(String denominator, int fractionType)
```

Создает дробь указанного типа с этим числителем и указанным знаменателем

--------------------

> ```
> Example:
>  
>  IMathElement numerator = new MathematicalText("x");
>  IMathFraction fraction = numerator.divide("y", MathFractionTypes.Linear);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| denominator | java.lang.String | Знаменатель |
| fractionType | int | Тип дроби: Bar, NoBar, Skewed, Linear |

**Возвращает:**
[IMathFraction](../../com.aspose.slides/imathfraction) - новая дробь
### enclose() {#enclose--}
```
public final IMathDelimiter enclose()
```

Обрамляет математический элемент скобками

--------------------

> ```
> Example:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose();
> ```

**Возвращает:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Математический элемент типа [IMathDelimiter](../../com.aspose.slides/imathdelimiter), включающий скобки
### enclose(char beginningCharacter, char endingCharacter) {#enclose-char-char-}
```
public IMathDelimiter enclose(char beginningCharacter, char endingCharacter)
```

Обрамляет математический элемент указанными символами, такими как скобки или другими символами, в качестве рамки

--------------------

> ```
> Пример:
>  
>  IMathElement element = new MathematicalText("x");
>  IMathDelimiter delimiter = element.enclose('[', ']');
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| beginningCharacter | char | Начальный символ (обычно левая скобка) |
| endingCharacter | char | Конечный символ (обычно правая скобка) |

**Возвращает:**
[IMathDelimiter](../../com.aspose.slides/imathdelimiter) - Математический элемент типа [IMathDelimiter](../../com.aspose.slides/imathdelimiter), включающий указанные символы в качестве рамки
### function(IMathElement functionArgument) {#function-com.aspose.slides.IMathElement-}
```
public final IMathFunction function(IMathElement functionArgument)
```

Принимает функцию аргумента, используя этот экземпляр в качестве имени функции

--------------------

> ```
> Пример:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionName.function(functionArg);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| functionArgument | [IMathElement](../../com.aspose.slides/imathelement) | Аргумент функции |

**Возвращает:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Новый математический элемент типа [IMathFunction](../../com.aspose.slides/imathfunction)
### function(String functionArgument) {#function-java.lang.String-}
```
public final IMathFunction function(String functionArgument)
```

Принимает функцию аргумента, используя этот экземпляр в качестве имени функции

--------------------

> ```
> Пример:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathFunction func = functionName.function("x");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| functionArgument | java.lang.String | Аргумент функции |

**Возвращает:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Новый математический элемент типа [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(IMathElement functionName) {#asArgumentOfFunction-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(IMathElement functionName)
```

Принимает указанную функцию, используя этот экземпляр в качестве аргумента

--------------------

> ```
> Пример:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| functionName | [IMathElement](../../com.aspose.slides/imathelement) | Имя функции |

**Возвращает:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Новый математический элемент типа [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(String functionName) {#asArgumentOfFunction-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(String functionName)
```

Принимает указанную функцию, используя этот экземпляр в качестве аргумента

--------------------

> ```
> Пример:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction("cos");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| functionName | java.lang.String | Имя функции |

**Возвращает:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Новый математический элемент типа [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType) {#asArgumentOfFunction-int-}
```
public final IMathFunction asArgumentOfFunction(int functionType)
```

Принимает указанную функцию, используя этот экземпляр в качестве аргумента

--------------------

> ```
> Пример:
>  
>  IMathElement functionName = new MathematicalText("sin");
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(functionName);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| functionType | int | Один из распространённых типов функции с одним аргументом |

**Возвращает:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Новый математический элемент типа [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, IMathElement additionalArgument) {#asArgumentOfFunction-int-com.aspose.slides.IMathElement-}
```
public final IMathFunction asArgumentOfFunction(int functionType, IMathElement additionalArgument)
```

Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathElement logarithmBase = new MathematicalText("5");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, logarithmBase); // Возвращает логарифм 'x' по основанию '5'
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| functionType | int | Один из распространённых типов функции из двух аргументов: Log, Lim, Min, Max |
| additionalArgument | [IMathElement](../../com.aspose.slides/imathelement) | Дополнительный аргумент в зависимости от типа функции |

**Возвращает:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Новый математический элемент типа [IMathFunction](../../com.aspose.slides/imathfunction)
### asArgumentOfFunction(int functionType, String additionalArgument) {#asArgumentOfFunction-int-java.lang.String-}
```
public final IMathFunction asArgumentOfFunction(int functionType, String additionalArgument)
```

Принимает указанную функцию, используя этот экземпляр в качестве аргумента и указанный дополнительный аргумент

--------------------

> ```
> Example:
>  
>  IMathElement functionArg = new MathematicalText("x");
>  IMathFunction func = functionArg.asArgumentOfFunction(MathFunctionsOfTwoArguments.Log, "5"); // Возвращает логарифм 'x' по основанию '5'
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| functionType | int | Один из распространённых типов функции из двух аргументов: Log, Lim, Min, Max |
| additionalArgument | java.lang.String | Дополнительный аргумент в зависимости от типа функции |

**Возвращает:**
[IMathFunction](../../com.aspose.slides/imathfunction) - Новый математический элемент типа [IMathFunction](../../com.aspose.slides/imathfunction)
### setSubscript(IMathElement subscript) {#setSubscript-com.aspose.slides.IMathElement-}
```
public final IMathSubscriptElement setSubscript(IMathElement subscript)
```

Создает нижний индекс

--------------------

> ```
> Пример:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("i");
>  IMathSubscriptElement subscript = element.setSubscript(index);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Нижний индекс (нижний индекс справа) |

**Возвращает:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Новый математический элемент типа [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSubscript(String subscript) {#setSubscript-java.lang.String-}
```
public final IMathSubscriptElement setSubscript(String subscript)
```

Создает нижний индекс

--------------------

> ```
> Пример:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSubscriptElement subscript = element.setSubscript("i");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| subscript | java.lang.String | Нижний индекс (нижний индекс справа) |

**Возвращает:**
[IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement) - Новый математический элемент типа [IMathSubscriptElement](../../com.aspose.slides/imathsubscriptelement)
### setSuperscript(IMathElement superscript) {#setSuperscript-com.aspose.slides.IMathElement-}
```
public final IMathSuperscriptElement setSuperscript(IMathElement superscript)
```

Создает верхний индекс

--------------------

> ```
> Пример:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathElement index = new MathematicalText("4");
>  IMathSuperscriptElement superscript = element.setSuperscript(index);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Верхний индекс (верхний индекс справа) |

**Возвращает:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Новый математический элемент типа [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSuperscript(String superscript) {#setSuperscript-java.lang.String-}
```
public final IMathSuperscriptElement setSuperscript(String superscript)
```

Создает верхний индекс

--------------------

> ```
> Пример:
>  
>  IMathElement element = new MathematicalText("N");
>  IMathSuperscriptElement superscript = element.setSuperscript("4");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| superscript | java.lang.String | Верхний индекс (верхний индекс справа) |

**Возвращает:**
[IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement) - Новый математический элемент типа [IMathSuperscriptElement](../../com.aspose.slides/imathsuperscriptelement)
### setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheRight-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(IMathElement subscript, IMathElement superscript)
```

Создает нижний и верхний индексы справа

--------------------

> ```
> Пример:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight(subscript, superscript);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Нижний индекс (нижний индекс справа) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Верхний индекс (верхний индекс справа) |

**Возвращает:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Новый математический элемент типа [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheRight(String subscript, String superscript) {#setSubSuperscriptOnTheRight-java.lang.String-java.lang.String-}
```
public final IMathRightSubSuperscriptElement setSubSuperscriptOnTheRight(String subscript, String superscript)
```

Создает нижний и верхний индексы справа

--------------------

> ```
> Пример:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathRightSubSuperscriptElement subsuperscript = baseElement.setSubSuperscriptOnTheRight("i", "j");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| subscript | java.lang.String | Нижний индекс (нижний индекс справа) |
| superscript | java.lang.String | Верхний индекс (верхний индекс справа) |

**Возвращает:**
[IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement) - Новый математический элемент типа [IMathRightSubSuperscriptElement](../../com.aspose.slides/imathrightsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript) {#setSubSuperscriptOnTheLeft-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(IMathElement subscript, IMathElement superscript)
```

Создает нижний и верхний индексы слева

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathElement subscript = new MathematicalText("i");
>  IMathElement superscript = new MathematicalText("j");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft(subscript, superscript);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| subscript | [IMathElement](../../com.aspose.slides/imathelement) | Нижний индекс (нижний индекс слева) |
| superscript | [IMathElement](../../com.aspose.slides/imathelement) | Верхний индекс (верхний индекс слева) |

**Возвращает:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Новый математический элемент типа [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### setSubSuperscriptOnTheLeft(String subscript, String superscript) {#setSubSuperscriptOnTheLeft-java.lang.String-java.lang.String-}
```
public final IMathLeftSubSuperscriptElement setSubSuperscriptOnTheLeft(String subscript, String superscript)
```

Создает нижний и верхний индексы слева

--------------------

> ```
> Пример:
>  
>  IMathElement baseElement = new MathematicalText("N");
>  IMathLeftSubSuperscriptElement leftSubsuperscript = baseElement.setSubSuperscriptOnTheLeft("i", "j");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| subscript | java.lang.String | Нижний индекс (нижний индекс слева) |
| superscript | java.lang.String | Верхний индекс (верхний индекс слева) |

**Возвращает:**
[IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement) - Новый математический элемент типа [IMathLeftSubSuperscriptElement](../../com.aspose.slides/imathleftsubsuperscriptelement)
### radical(IMathElement degree) {#radical-com.aspose.slides.IMathElement-}
```
public final IMathRadical radical(IMathElement degree)
```

Указывает математический корень заданной степени из указанного аргумента.

--------------------

> ```
> Пример:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathElement degree = new MathematicalText("y");
>  IMathRadical radical = baseElement.radical(degree);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| degree | [IMathElement](../../com.aspose.slides/imathelement) | Аргумент радикала |

**Возвращает:**
[IMathRadical](../../com.aspose.slides/imathradical) - Новый экземпляр типа [IMathRadical](../../com.aspose.slides/imathradical)
### radical(String degree) {#radical-java.lang.String-}
```
public final IMathRadical radical(String degree)
```

Указывает математический корень заданной степени из указанного аргумента.

--------------------

> ```
> Пример:
>  
>  IMathElement baseElement = new MathematicalText("2px");
>  IMathRadical radical = baseElement.radical("3");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| degree | java.lang.String | Аргумент радикала |

**Возвращает:**
[IMathRadical](../../com.aspose.slides/imathradical) - Новый экземпляр типа [IMathRadical](../../com.aspose.slides/imathradical)
### setUpperLimit(IMathElement limit) {#setUpperLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setUpperLimit(IMathElement limit)
```

Принимает верхний предел

--------------------

> ```
> Пример:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathElement limitValue = new MathematicalText("y\u2212>1");
>  IMathLimit limitElement = baseElement.setUpperLimit(limitValue);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | предел |

**Возвращает:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Новый экземпляр типа [IMathLimit](../../com.aspose.slides/imathlimit)
### setUpperLimit(String limit) {#setUpperLimit-java.lang.String-}
```
public final IMathLimit setUpperLimit(String limit)
```

Принимает верхний предел

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("y");
>  IMathLimit limitElement = baseElement.setUpperLimit("y\u2212>1");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| limit | java.lang.String | предел |

**Возвращает:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Новый экземпляр типа [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(IMathElement limit) {#setLowerLimit-com.aspose.slides.IMathElement-}
```
public final IMathLimit setLowerLimit(IMathElement limit)
```

Принимает нижний предел

--------------------

> ```
> Пример:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathElement limitValue = new MathematicalText("\ud835\udc5b\u2192\u221e");
>  IMathLimit limitElement = baseElement.setLowerLimit(limitValue);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| limit | [IMathElement](../../com.aspose.slides/imathelement) | предел |

**Возвращает:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Новый экземпляр типа [IMathLimit](../../com.aspose.slides/imathlimit)
### setLowerLimit(String limit) {#setLowerLimit-java.lang.String-}
```
public final IMathLimit setLowerLimit(String limit)
```

Принимает нижний предел

--------------------

> ```
> Пример:
>  
>  IMathElement baseElement = new MathematicalText("lim");
>  IMathLimit limitElement = baseElement.setLowerLimit("\ud835\udc5b\u2192\u221e");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| limit | java.lang.String | предел |

**Возвращает:**
[IMathLimit](../../com.aspose.slides/imathlimit) - Новый экземпляр типа [IMathLimit](../../com.aspose.slides/imathlimit)
### nary(int type, IMathElement lowerLimit, IMathElement upperLimit) {#nary-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator nary(int type, IMathElement lowerLimit, IMathElement upperLimit)
```

Создает N-арный оператор

--------------------

> ```
> Пример:
>  
>  IMathElement baseElement = new MathematicalText("i-1");
>  IMathElement lowerLimit = new MathematicalText("i=0");
>  IMathElement upperLimit = new MathematicalText("\ud835\udc5b");
>  IMathNaryOperator naryOperator = baseElement.nary(MathNaryOperatorTypes.Summation, lowerLimit, upperLimit);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Тип N-арного оператора |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Нижний предел |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Верхний предел |

**Возвращает:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Новый экземпляр типа [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### nary(int type, String lowerLimit, String upperLimit) {#nary-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator nary(int type, String lowerLimit, String upperLimit)
```

Создает N-арный оператор

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("i").nary(MathNaryOperatorTypes.Summation, "i=0", "\ud835\udc5b");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| type | int | Тип N-арного оператора |
| lowerLimit | java.lang.String | Нижний предел |
| upperLimit | java.lang.String | Верхний предел |

**Возвращает:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Новый экземпляр типа [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### toMathArray() {#toMathArray--}
```
public IMathArray toMathArray()
```

Размещает в вертикальном массиве

--------------------

> ```
> Пример:
>  
>  IMathArray array = new MathematicalText("x1").join("x2").join("x3").toMathArray();
> ```


**Возвращает:**
[IMathArray](../../com.aspose.slides/imatharray) - Новый экземпляр типа [IMathArray](../../com.aspose.slides/imatharray)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-int-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit, int limitLocations)
```

Принимает интеграл

--------------------

> ```
> Пример:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| integralType | int | Тип интеграла |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Нижний предел интеграла |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Верхний предел интеграла |
| limitLocations | int | расположение пределов |

**Возвращает:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Новый экземпляр типа [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit) {#integral-int-com.aspose.slides.IMathElement-com.aspose.slides.IMathElement-}
```
public final IMathNaryOperator integral(int integralType, IMathElement lowerLimit, IMathElement upperLimit)
```

Принимает интеграл

--------------------

> ```
> Пример:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathElement lowerLimit = new MathematicalText("1");
>  IMathElement upperLimit = new MathematicalText("2");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, lowerLimit, upperLimit, MathLimitLocations.UnderOver);
> ```


**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| integralType | int | Тип интеграла |
| lowerLimit | [IMathElement](../../com.aspose.slides/imathelement) | Нижний предел интеграла |
| upperLimit | [IMathElement](../../com.aspose.slides/imathelement) | Верхний предел интеграла |

**Возвращает:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Новый экземпляр типа [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType) {#integral-int-}
```
public final IMathNaryOperator integral(int integralType)
```

Принимает интеграл без пределов

--------------------

> ```
> Пример:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Contour);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| integralType | int | Тип интеграла |

**Возвращает:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Новый экземпляр типа [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit, int limitLocations) {#integral-int-java.lang.String-java.lang.String-int-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit, int limitLocations)
```

Принимает интеграл

--------------------

> ```
> Пример:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5", MathLimitLocations.UnderOver);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| integralType | int | Тип интеграла |
| lowerLimit | java.lang.String | Нижний предел интеграла |
| upperLimit | java.lang.String | Верхний предел интеграла |
| limitLocations | int | расположение пределов |

**Возвращает:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Новый экземпляр типа [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### integral(int integralType, String lowerLimit, String upperLimit) {#integral-int-java.lang.String-java.lang.String-}
```
public final IMathNaryOperator integral(int integralType, String lowerLimit, String upperLimit)
```

Принимает интеграл

--------------------

> ```
> Example:
>  
>  IMathElement baseElement = new MathematicalText("\ud835\udc65");
>  IMathNaryOperator integral = baseElement.integral(MathIntegralTypes.Simple, "1", "5");
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| integralType | int | Тип интеграла |
| lowerLimit | java.lang.String | Нижний предел интеграла |
| upperLimit | java.lang.String | Верхний предел интеграла |

**Возвращает:**
[IMathNaryOperator](../../com.aspose.slides/imathnaryoperator) - Новый экземпляр типа [IMathNaryOperator](../../com.aspose.slides/imathnaryoperator)
### accent(char accentCharacter) {#accent-char-}
```
public final IMathAccent accent(char accentCharacter)
```

Устанавливает знак акцента (символ над этим элементом)

--------------------

> ```
> Пример:
>  
>  IMathAccent accent = new MathematicalText("x").accent('~');
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| accentCharacter | char | Символ акцента. Значение должно находиться в диапазоне (U+0300–U+036F) или (U+20D0–U+20EF) |

**Возвращает:**
[IMathAccent](../../com.aspose.slides/imathaccent) - Новый экземпляр типа [IMathAccent](../../com.aspose.slides/imathaccent)
### overbar() {#overbar--}
```
public final IMathBar overbar()
```

Устанавливает черту вверху этого элемента

--------------------

> ```
> Пример:
>  
>  IMathBar bar = new MathematicalText("x").overbar();
> ```

**Возвращает:**
[IMathBar](../../com.aspose.slides/imathbar) - Новый экземпляр типа [IMathBar](../../com.aspose.slides/imathbar)
### underbar() {#underbar--}
```
public final IMathBar underbar()
```

Устанавливает черту внизу этого элемента

--------------------

> ```
> Пример:
>  
>  IMathBar bar = new MathematicalText("x").underbar();
> ```

**Возвращает:**
[IMathBar](../../com.aspose.slides/imathbar) - Новый экземпляр типа [IMathBar](../../com.aspose.slides/imathbar)
### group() {#group--}
```
public final IMathGroupingCharacter group()
```

Размещает этот элемент в группе, используя нижнюю фигурную скобку

--------------------

> ```
> Example:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group();
> ```

**Возвращает:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Новый экземпляр типа [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### group(char character, int position, int verticalJustification) {#group-char-int-int-}
```
public final IMathGroupingCharacter group(char character, int position, int verticalJustification)
```

Размещает этот элемент в группе, используя символ группировки, такой как нижняя фигурная скобка или иной

--------------------

> ```
> Пример:
>  
>  IMathGroupingCharacter groupingElement = new MathematicalText("x;y;z").group('\u23e1', MathTopBotPositions.Bottom, MathTopBotPositions.Top);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| character | char | Символ группировки, например НИЖНЯЯ ФИГУРНАЯ СКОБКА (U+23DF) или любой другой |
| position | int | Позиция символа группировки |
| verticalJustification | int | Вертикальное выравнивание символа группы. Определяет выравнивание объекта относительно базовой линии. Например, когда символ группы находится выше объекта, значение VerticalJustification Top означает, что верх объекта падает на базовую линию; когда VerticalJustification установлен в Bottom, низ объекта находится на базовой линии. |

**Возвращает:**
[IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter) - Новый экземпляр типа [IMathGroupingCharacter](../../com.aspose.slides/imathgroupingcharacter)
### toBorderBox() {#toBorderBox--}
```
public final IMathBorderBox toBorderBox()
```

Размещает этот элемент в border-box

--------------------

> ```
> Пример:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox();
> ```

**Возвращает:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box с этим элементом внутри
### toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#toBorderBox-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox toBorderBox(boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Размещает этот элемент в border-box

--------------------

> ```
> Пример:
>  
>  IMathBorderBox borderBox = new MathematicalText("x+y+z").toBorderBox(false, false, true, true, false, false, false, false);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| hideTop | boolean | Скрыть верхний край |
| hideBottom | boolean | Скрыть нижний край |
| hideLeft | boolean | Скрыть левый край |
| hideRight | boolean | Скрыть правый край |
| strikethroughHorizontal | boolean | Горизонтальная зачерка в Border Box |
| strikethroughVertical | boolean | Вертикальная зачерка в Border Box |
| strikethroughBottomLeftToTopRight | boolean | Зачерка Bottom-Left to Top-Right в Border Box |
| strikethroughTopLeftToBottomRight | boolean | Зачерка Top-Left to Bottom-Right в Border Box |

**Возвращает:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - Border-box с этим элементом внутри
### toBox() {#toBox--}
```
public final IMathBox toBox()
```

Размещает этот элемент в невизуальном блоке (логическая группировка), который используется для группировки компонентов уравнения или другого экземпляра математического текста. Объект в коробке может (например) служить эмулятором оператора с или без точки выравнивания, служить точкой разрыва строки или быть сгруппированным так, чтобы не допускать разрывов строк внутри.

--------------------

> ```
> Пример:
>  
>  IMathBox box = new MathematicalText("x:=y").toBox();
```

**Возвращает:**
[IMathBox](../../com.aspose.slides/imathbox) - Логический блок с этим элементом внутри
### getChildren() {#getChildren--}
```
public IMathElement[] getChildren()
```

Получить дочерние элементы

**Возвращает:**
com.aspose.slides.IMathElement[] - Массив [IMathElement](../../com.aspose.slides/imathelement)