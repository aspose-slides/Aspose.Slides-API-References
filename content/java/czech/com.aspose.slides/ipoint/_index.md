---
title: IPoint
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje animační bod.
type: docs
url: /cs/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Reprezentuje animační bod.
## Metody

| Metoda | Popis |
| --- | --- |
| [getTime()](#getTime--) | Reprezentuje časovou hodnotu. |
| [setTime(float value)](#setTime-float-) | Reprezentuje časovou hodnotu. |
| [getValue()](#getValue--) | Reprezentuje hodnotu bodu. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Reprezentuje hodnotu bodu. |
| [getFormula()](#getFormula--) | Formule v hodnotách, atributech from, to, by mohou být sestaveny z následujících: Standardní aritmetické operátory: '+', '-', '*', '/', '^', '%' (mod) Konstanty: 'pi' 'e' Podmínkové operátory: 'abs', 'min', 'max', '?' (if) Porovnávací operátory: '==', '>=', '', '!=', '!' Trigonometrické operátory: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Přirozený logaritmus 'ln()' Reference na vlastnosti (vlastnosti podporované hostitelem) například: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Čtení/zápis String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Formule v hodnotách, atributech from, to, by mohou být sestaveny z následujících: Standardní aritmetické operátory: '+', '-', '*', '/', '^', '%' (mod) Konstanty: 'pi' 'e' Podmínkové operátory: 'abs', 'min', 'max', '?' (if) Porovnávací operátory: '==', '>=', '', '!=', '!' Trigonometrické operátory: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Přirozený logaritmus 'ln()' Reference na vlastnosti (vlastnosti podporované hostitelem) například: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Čtení/zápis String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

Reprezentuje časovou hodnotu. Čtení/zápis float.

**Vrací:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

Reprezentuje časovou hodnotu. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```

Reprezentuje hodnotu bodu. Pouze: bool, ColorFormat, float, int, string. Čtení/zápis Object.

**Vrací:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Reprezentuje hodnotu bodu. Pouze: bool, ColorFormat, float, int, string. Čtení/zápis Object.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

Formule v hodnotách, atributech from, to, by mohou být sestaveny z následujících: Standardní aritmetické operátory: '+', '-', '*', '/', '^', '%' (mod) Konstanty: 'pi' 'e' Podmínkové operátory: 'abs', 'min', 'max', '?' (if) Porovnávací operátory: '==', '>=', '', '!=', '!' Trigonometrické operátory: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Přirozený logaritmus 'ln()' Reference na vlastnosti (vlastnosti podporované hostitelem) například: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Čtení/zápis String.

**Vrací:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

Formule v hodnotách, atributech from, to, by mohou být sestaveny z následujících: Standardní aritmetické operátory: '+', '-', '*', '/', '^', '%' (mod) Konstanty: 'pi' 'e' Podmínkové operátory: 'abs', 'min', 'max', '?' (if) Porovnávací operátory: '==', '>=', '', '!=', '!' Trigonometrické operátory: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Přirozený logaritmus 'ln()' Reference na vlastnosti (vlastnosti podporované hostitelem) například: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |