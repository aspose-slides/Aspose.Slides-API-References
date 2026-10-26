---
title: IPoint
second_title: Aspose.Slides for Android via Java API Reference
description: Представляет точку анимации.
type: docs
url: /ru/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Представляет точку анимации.
## Методы

| Method | Description |
| --- | --- |
| [getTime()](#getTime--) | Представляет значение времени. |
| [setTime(float value)](#setTime-float-) | Представляет значение времени. |
| [getValue()](#getValue--) | Представляет значение точки. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Представляет значение точки. |
| [getFormula()](#getFormula--) | Формулы в значениях, атрибутах from, to, by могут состоять из следующих элементов: Стандартные арифметические операторы: '+', '-', '*', '/', '^', '%' (mod) Константы: 'pi' 'e' Условные операторы: 'abs', 'min', 'max', '?' (if) Операторы сравнения: '==', '>=', '', '!=', '!' Тригонометрические операторы: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Натуральный логарифм 'ln()' Ссылки на свойства (поддерживаемые хостом свойства) например: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" Чтение/запись String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Формулы в значениях, атрибутах from, to, by могут состоять из следующих элементов: Стандартные арифметические операторы: '+', '-', '*', '/', '^', '%' (mod) Константы: 'pi' 'e' Условные операторы: 'abs', 'min', 'max', '?' (if) Операторы сравнения: '==', '>=', '', '!=', '!' Тригонометрические операторы: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Натуральный логарифм 'ln()' Ссылки на свойства (поддерживаемые хостом свойства) например: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" Чтение/запись String. |

### getTime() {#getTime--}
```
public abstract float getTime()
```

Представляет значение времени. Чтение/запись float.

**Возвращаемое значение:**
float

### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

Представляет значение времени. Чтение/запись float.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

Представляет значение точки. Допустимы только: bool, ColorFormat, float, int, string. Чтение/запись Object.

**Возвращаемое значение:**
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Представляет значение точки. Допустимы только: bool, ColorFormat, float, int, string. Чтение/запись Object.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

Формулы в значениях, атрибутах from, to, by могут состоять из следующих элементов: Стандартные арифметические операторы: '+', '-', '*', '/', '^', '%' (mod) Константы: 'pi' 'e' Условные операторы: 'abs', 'min', 'max', '?' (if) Операторы сравнения: '==', '>=', '', '!=', '!' Тригонометрические операторы: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Натуральный логарифм 'ln()' Ссылки на свойства (поддерживаемые хостом свойства) например: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" Чтение/запись String.

**Возвращаемое значение:**
java.lang.String

### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

Формулы в значениях, атрибутах from, to, by могут состоять из следующих элементов: Стандартные арифметические операторы: '+', '-', '*', '/', '^', '%' (mod) Константы: 'pi' 'e' Условные операторы: 'abs', 'min', 'max', '?' (if) Операторы сравнения: '==', '>=', '', '!=', '!' Тригонометрические операторы: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Натуральный логарифм 'ln()' Ссылки на свойства (поддерживаемые хостом свойства) например: "\#ppt\_x+(cos(-2*pi*(1-$))*-\#ppt\_x-sin(-2*pi*(1-$))*(1-\#ppt\_y))*(1-$)" Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |