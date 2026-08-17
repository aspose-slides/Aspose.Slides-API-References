---
title: IMathNaryOperatorProperties
second_title: Aspose.Slides для Java справочник API
description: Указывает свойства IMathNaryOperator
type: docs
url: /ru/com.aspose.slides/imathnaryoperatorproperties/
---```
public interface IMathNaryOperatorProperties
```

Указывает свойства IMathNaryOperator
## Методы

| Метод | Описание |
| --- | --- |
| [getOperator()](#getOperator--) | Символ n-арного оператора, например: '\\u2211', '\\u222b' |
| [setOperator(char value)](#setOperator-char-) | Символ n-арного оператора, например: '\\u2211', '\\u222b' |
| [getLimitLocation()](#getLimitLocation--) | Расположение пределов (подстрочный и надстрочный) |
| [setLimitLocation(int value)](#setLimitLocation-int-) | Расположение пределов (подстрочный и надстрочный) |
| [getGrowToMatchOperandHeight()](#getGrowToMatchOperandHeight--) | Символ оператора растет вертикально, чтобы соответствовать высоте его операнда |
| [setGrowToMatchOperandHeight(boolean value)](#setGrowToMatchOperandHeight-boolean-) | Символ оператора растет вертикально, чтобы соответствовать высоте его операнда |
| [getHideSubscript()](#getHideSubscript--) | Скрыть подстрочный индекс |
| [setHideSubscript(boolean value)](#setHideSubscript-boolean-) | Скрыть подстрочный индекс |
| [getHideSuperscript()](#getHideSuperscript--) | Скрыть надстрочный индекс |
| [setHideSuperscript(boolean value)](#setHideSuperscript-boolean-) | Скрыть надстрочный индекс |
### getOperator() {#getOperator--}
```
public abstract char getOperator()
```


Символ n-арного оператора, например: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Возвращает:**
char
### setOperator(char value) {#setOperator-char-}
```
public abstract void setOperator(char value)
```


Символ n-арного оператора, например: '\\u2211', '\\u222b'

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  char operatorSymbol = naryOperator.getOperator();
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char |  |

### getLimitLocation() {#getLimitLocation--}
```
public abstract int getLimitLocation()
```


Расположение пределов (подстрочный и надстрочный)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Возвращает:**
int
### setLimitLocation(int value) {#setLimitLocation-int-}
```
public abstract void setLimitLocation(int value)
```


Расположение пределов (подстрочный и надстрочный)

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setLimitLocation(MathLimitLocations.SubscriptSuperscript);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getGrowToMatchOperandHeight() {#getGrowToMatchOperandHeight--}
```
public abstract boolean getGrowToMatchOperandHeight()
```


Символ оператора растет вертикально, чтобы соответствовать высоте его операнда

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Возвращает:**
boolean
### setGrowToMatchOperandHeight(boolean value) {#setGrowToMatchOperandHeight-boolean-}
```
public abstract void setGrowToMatchOperandHeight(boolean value)
```


Символ оператора растет вертикально, чтобы соответствовать высоте его операнда

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setGrowToMatchOperandHeight(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHideSubscript() {#getHideSubscript--}
```
public abstract boolean getHideSubscript()
```


Скрыть подстрочный индекс

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Возвращает:**
boolean
### setHideSubscript(boolean value) {#setHideSubscript-boolean-}
```
public abstract void setHideSubscript(boolean value)
```


Скрыть подстрочный индекс

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSubscript(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### getHideSuperscript() {#getHideSuperscript--}
```
public abstract boolean getHideSuperscript()
```


Скрыть надстрочный индекс

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Возвращает:**
boolean
### setHideSuperscript(boolean value) {#setHideSuperscript-boolean-}
```
public abstract void setHideSuperscript(boolean value)
```


Скрыть надстрочный индекс

--------------------

> ```
> Example:
>  
>  IMathNaryOperator naryOperator = new MathematicalText("x").nary(MathNaryOperatorTypes.Summation, "x=1", "100");
>  naryOperator.setHideSuperscript(true);
> ```

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |