---
title: Point
second_title: Справочник API Aspose.Slides для Android через Java
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
| [getFormula()](#getFormula--) | Формулы в значениях, атрибутах from, to, by могут быть составлены из следующих элементов: Стандартные арифметические операторы: '+', '-', '*', '/', '^', '%' (mod) Константы: 'pi' 'e' Условные операторы: 'abs', 'min', 'max', '?' (if) Операторы сравнения: '==', '>=', '', '!=', '!' Тригонометрические операторы: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Натуральный логарифм 'ln()' Ссылки на свойства (поддерживаемые хостом свойства), например: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Чтение/запись String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Формулы в значениях, атрибутах from, to, by могут быть составлены из следующих элементов: Стандартные арифметические операторы: '+', '-', '*', '/', '^', '%' (mod) Константы: 'pi' 'e' Условные операторы: 'abs', 'min', 'max', '?' (if) Операторы сравнения: '==', '>=', '', '!=', '!' Тригонометрические операторы: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Натуральный логарифм 'ln()' Ссылки на свойства (поддерживаемые хостом свойства), например: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Чтение/запись String. |
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

Формулы в значениях, атрибутах from, to, by могут быть составлены из следующих элементов: Стандартные арифметические операторы: '+', '-', '*', '/', '^', '%' (mod) Константы: 'pi' 'e' Условные операторы: 'abs', 'min', 'max', '?' (if) Операторы сравнения: '==', '>=', '', '!=', '!' Тригонометрические операторы: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Натуральный логарифм 'ln()' Ссылки на свойства (поддерживаемые хостом свойства), например: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Формулы в значениях, атрибутах from, to, by могут быть составлены из следующих элементов: Стандартные арифметические операторы: '+', '-', '*', '/', '^', '%' (mod) Константы: 'pi' 'e' Условные операторы: 'abs', 'min', 'max', '?' (if) Операторы сравнения: '==', '>=', '', '!=', '!' Тригонометрические операторы: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Натуральный логарифм 'ln()' Ссылки на свойства (поддерживаемые хостом свойства), например: "#ppt_x+(cos(-2*pi*(1-$))*-#ppt_x-sin(-2*pi*(1-$))*(1-#ppt_y))*(1-$)" Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |