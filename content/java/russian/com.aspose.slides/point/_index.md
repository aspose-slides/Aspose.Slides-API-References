---
title: Point
second_title: Справочник API Aspose.Slides для Java
description: Представляет точку анимации.
type: docs
url: /ru/com.aspose.slides/point/
---
**Наследование:**
java.lang.Object

**Все реализованные интерфейсы:**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

Представляет точку анимации.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [Point()](#Point--) | Конструктор по умолчанию. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Создает точку анимации с временем, значением и формулой. |
## Методы

| Метод | Описание |
| --- | --- |
| [getTime()](#getTime--) | Представляет значение времени. |
| [setTime(float value)](#setTime-float-) | Представляет значение времени. |
| [getValue()](#getValue--) | Представляет значение точки. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Представляет значение точки. |
| [getFormula()](#getFormula--) | Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: '+', '-', '\*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Чтение/запись String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: '+', '-', '\*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Чтение/запись String. |
### Point() {#Point--}
```
public Point()
```


Конструктор по умолчанию.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```


Создает точку анимации с временем, значением и формулой.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| time | float | Значение времени. |
| value | java.lang.Object | Значение точки. |
| formula | java.lang.String | Формула. |

### getTime() {#getTime--}
```
public final float getTime()
```


Представляет значение времени. Чтение/запись float.

**Возвращаемое значение:**
float
### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```


Представляет значение времени. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```


Представляет значение точки. Только: bool, ColorFormat, float, int, string. Чтение/запись Object.

**Возвращаемое значение:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```


Представляет значение точки. Только: bool, ColorFormat, float, int, string. Чтение/запись Object.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```


Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: '+', '-', '\*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```


Formulas within values, from, to, by attributes can be made up of these: Standard arithmetic operators: '+', '-', '\*', '/', '^', '%' (mod) Constants: 'pi' 'e' Conditional operators: 'abs', 'min', 'max', '?' (if) Comparison operators: '==', '>=', '', '!=', '!' Trigonometric operators: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natural logarithm 'ln()' Property references (host supported properties) for example: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |