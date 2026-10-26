---
title: IPoint
second_title: Aspose.Slides pro Android přes Java API Reference
description: Představuje animační bod.
type: docs
url: /cs/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Představuje animační bod.
## Metody

| Metoda | Popis |
| --- | --- |
| [getTime()](#getTime--) | Představuje časovou hodnotu. |
| [setTime(float value)](#setTime-float-) | Představuje časovou hodnotu. |
| [getValue()](#getValue--) | Představuje hodnotu bodu. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Představuje hodnotu bodu. |
| [getFormula()](#getFormula--) | Formule v hodnotách, atributy from, to, by mohou být vytvořeny z následujících: Standardní aritmetické operátory: '+', '-', '*', '/', '^', '%' (mod) Konstanty: 'pi' 'e' Podmíněné operátory: 'abs', 'min', 'max', '?' (if) Porovnávací operátory: '==', '>=', '', '!=', '!' Trigonometrické operátory: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Přirozený logaritmus 'ln()' Odkazy na vlastnosti (vlastnosti podporované hostitelem) například: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Čtení/Zápis String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Formule v hodnotách, atributy from, to, by mohou být vytvořeny z následujících: Standardní aritmetické operátory: '+', '-', '*', '/', '^', '%' (mod) Konstanty: 'pi' 'e' Podmíněné operátory: 'abs', 'min', 'max', '?' (if) Porovnávací operátory: '==', '>=', '', '!=', '!' Trigonometrické operátory: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Přirozený logaritmus 'ln()' Odkazy na vlastnosti (vlastnosti podporované hostitelem) například: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Čtení/Zápis String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

Představuje časovou hodnotu. Čtení/Zápis float.

**Vrací:**  
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

Představuje časovou hodnotu. Čtení/Zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Představuje hodnotu bodu. Pouze: bool, ColorFormat, float, int, string. Čtení/Zápis Object.

**Vrací:**  
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Představuje hodnotu bodu. Pouze: bool, ColorFormat, float, int, string. Čtení/Zápis Object.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

Formule v hodnotách, atributy from, to, by mohou být vytvořeny z následujících: Standardní aritmetické operátory: '+', '-', '*', '/', '^', '%' (mod) Konstanty: 'pi' 'e' Podmíněné operátory: 'abs', 'min', 'max', '?' (if) Porovnávací operátory: '==', '>=', '', '!=', '!' Trigonometrické operátory: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Přirozený logaritmus 'ln()' Odkazy na vlastnosti (vlastnosti podporované hostitelem) například: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Čtení/Zápis String.

**Vrací:**  
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

Formule v hodnotách, atributy from, to, by mohou být vytvořeny z následujících: Standardní aritmetické operátory: '+', '-', '*', '/', '^', '%' (mod) Konstanty: 'pi' 'e' Podmíněné operátory: 'abs', 'min', 'max', '?' (if) Porovnávací operátory: '==', '>=', '', '!=', '!' Trigonometrické operátory: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Přirozený logaritmus 'ln()' Odkazy na vlastnosti (vlastnosti podporované hostitelem) například: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Čtení/Zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |