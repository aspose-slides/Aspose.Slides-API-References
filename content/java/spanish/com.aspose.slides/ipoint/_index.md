---
title: IPoint
second_title: Aspose.Slides for Java API Reference
description: Represent animation point.
type: docs
url: /es/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Representa un punto de animación.
## Métodos

| Método | Descripción |
| --- | --- |
| [getTime()](#getTime--) | Representa un valor de tiempo. |
| [setTime(float value)](#setTime-float-) | Representa un valor de tiempo. |
| [getValue()](#getValue--) | Representa un valor de punto. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Representa un valor de punto. |
| [getFormula()](#getFormula--) | Las fórmulas dentro de los atributos values, from, to, by pueden estar compuestas por lo siguiente: Operadores aritméticos estándar: '+', '-', '*', '/', '^', '%' (mod) Constantes: 'pi' 'e' Operadores condicionales: 'abs', 'min', 'max', '?' (if) Operadores de comparación: '==', '>=', '', '!=', '!' Operadores trigonométricos: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo natural 'ln()' Referencias a propiedades (propiedades admitidas por el host) por ejemplo: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lectura/escritura String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Las fórmulas dentro de los atributos values, from, to, by pueden estar compuestas por lo siguiente: Operadores aritméticos estándar: '+', '-', '*', '/', '^', '%' (mod) Constantes: 'pi' 'e' Operadores condicionales: 'abs', 'min', 'max', '?' (if) Operadores de comparación: '==', '>=', '', '!=', '!' Operadores trigonométricos: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo natural 'ln()' Referencias a propiedades (propiedades admitidas por el host) por ejemplo: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lectura/escritura String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

Representa un valor de tiempo. Lectura/escritura float.

**Devuelve:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

Representa un valor de tiempo. Lectura/escritura float.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | float |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Representa un valor de punto. Sólo: bool, ColorFormat, float, int, string. Lectura/escritura Object.

**Devuelve:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Representa un valor de punto. Sólo: bool, ColorFormat, float, int, string. Lectura/escritura Object.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

Las fórmulas dentro de los atributos values, from, to, by pueden estar compuestas por lo siguiente: Operadores aritméticos estándar: '+', '-', '*', '/', '^', '%' (mod) Constantes: 'pi' 'e' Operadores condicionales: 'abs', 'min', 'max', '?' (if) Operadores de comparación: '==', '>=', '', '!=', '!' Operadores trigonométricos: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo natural 'ln()' Referencias a propiedades (propiedades admitidas por el host) por ejemplo: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lectura/escritura String.

**Devuelve:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

Las fórmulas dentro de los atributos values, from, to, by pueden estar compuestas por lo siguiente: Operadores aritméticos estándar: '+', '-', '*', '/', '^', '%' (mod) Constantes: 'pi' 'e' Operadores condicionales: 'abs', 'min', 'max', '?' (if) Operadores de comparación: '==', '>=', '', '!=', '!' Operadores trigonométricos: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo natural 'ln()' Referencias a propiedades (propiedades admitidas por el host) por ejemplo: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lectura/escritura String.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | java.lang.String |  |