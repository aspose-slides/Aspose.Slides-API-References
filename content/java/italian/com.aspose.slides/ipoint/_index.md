---
title: IPoint
second_title: Aspose.Slides for Java API Reference
description: Rappresenta un punto di animazione.
type: docs
url: /it/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Rappresenta un punto di animazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTime()](#getTime--) | Rappresenta il valore di tempo. |
| [setTime(float value)](#setTime-float-) | Rappresenta il valore di tempo. |
| [getValue()](#getValue--) | Rappresenta il valore di punto. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Rappresenta il valore di punto. |
| [getFormula()](#getFormula--) | Le formule all'interno dei valori, negli attributi from, to, by, possono essere composte da questi: Operatori aritmetici standard: '+', '-', '*', '/', '^', '%' (mod) Costanti: 'pi' 'e' Operatori condizionali: 'abs', 'min', 'max', '?' (if) Operatori di confronto: '==', '>=', '', '!=', '!' Operatori trigonometrici: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo naturale 'ln()' Riferimenti a proprietà (proprietà supportate dall'host) per esempio: "#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lettura/Scrittura Stringa. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Le formule all'interno dei valori, negli attributi from, to, by, possono essere composte da questi: Operatori aritmetici standard: '+', '-', '*', '/', '^', '%' (mod) Costanti: 'pi' 'e' Operatori condizionali: 'abs', 'min', 'max', '?' (if) Operatori di confronto: '==', '>=', '', '!=', '!' Operatori trigonometrici: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo naturale 'ln()' Riferimenti a proprietà (proprietà supportate dall'host) per esempio: "#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lettura/Scrittura Stringa. |
### getTime() {#getTime--}
```
public abstract float getTime()
```


Rappresenta il valore di tempo. Lettura/Scrittura float.

**Restituisce:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```


Rappresenta il valore di tempo. Lettura/Scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public abstract Object getValue()
```


Rappresenta il valore di punto. Solo: bool, ColorFormat, float, int, string. Lettura/Scrittura Object.

**Restituisce:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```


Rappresenta il valore di punto. Solo: bool, ColorFormat, float, int, string. Lettura/Scrittura Object.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public abstract String getFormula()
```


Le formule all'interno dei valori, negli attributi from, to, by, possono essere composte da questi: Operatori aritmetici standard: '+', '-', '*', '/', '^', '%' (mod) Costanti: 'pi' 'e' Operatori condizionali: 'abs', 'min', 'max', '?' (if) Operatori di confronto: '==', '>=', '', '!=', '!' Operatori trigonometrici: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo naturale 'ln()' Riferimenti a proprietà (proprietà supportate dall'host) per esempio: "#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lettura/Scrittura Stringa.

**Restituisce:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```


Le formule all'interno dei valori, negli attributi from, to, by, possono essere composte da questi: Operatori aritmetici standard: '+', '-', '*', '/', '^', '%' (mod) Costanti: 'pi' 'e' Operatori condizionali: 'abs', 'min', 'max', '?' (if) Operatori di confronto: '==', '>=', '', '!=', '!' Operatori trigonometrici: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logaritmo naturale 'ln()' Riferimenti a proprietà (proprietà supportate dall'host) per esempio: "#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lettura/Scrittura Stringa.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |