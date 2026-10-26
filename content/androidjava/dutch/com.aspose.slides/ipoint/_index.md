---
title: IPoint
second_title: Aspose.Slides for Android via Java API Reference
description: Represent animation point.
type: docs
url: /nl/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Vertegenwoordigt animatiepunt.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTime()](#getTime--) | Vertegenwoordigt tijdwaarde. |
| [setTime(float value)](#setTime-float-) | Vertegenwoordigt tijdwaarde. |
| [getValue()](#getValue--) | Vertegenwoordigt puntwaarde. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Vertegenwoordigt puntwaarde. |
| [getFormula()](#getFormula--) | Formules binnen waarden, from, to, by attributen kunnen bestaan uit de volgende: Standaard rekenkundige operatoren: '+', '-', '*', '/', '^', '%' (mod) Constanten: 'pi' 'e' Voorwaardelijke operatoren: 'abs', 'min', 'max', '?' (if) Vergelijkingsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natuurlijke logaritme 'ln()' Eigenschapsreferenties (door host ondersteunde eigenschappen) bijvoorbeeld: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lezen/schrijven String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Formules binnen waarden, from, to, by attributen kunnen bestaan uit de volgende: Standaard rekenkundige operatoren: '+', '-', '*', '/', '^', '%' (mod) Constanten: 'pi' 'e' Voorwaardelijke operatoren: 'abs', 'min', 'max', '?' (if) Vergelijkingsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natuurlijke logaritme 'ln()' Eigenschapsreferenties (door host ondersteunde eigenschappen) bijvoorbeeld: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lezen/schrijven String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

Vertegenwoordigt tijdwaarde. Lezen/schrijven float.

**Retour:**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

Vertegenwoordigt tijdwaarde. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Vertegenwoordigt puntwaarde. Alleen: bool, ColorFormat, float, int, string. Lezen/schrijven Object.

**Retour:**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Vertegenwoordigt puntwaarde. Alleen: bool, ColorFormat, float, int, string. Lezen/schrijven Object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

Formules binnen waarden, from, to, by attributen kunnen bestaan uit de volgende: Standaard rekenkundige operatoren: '+', '-', '*', '/', '^', '%' (mod) Constanten: 'pi' 'e' Voorwaardelijke operatoren: 'abs', 'min', 'max', '?' (if) Vergelijkingsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natuurlijke logaritme 'ln()' Eigenschapsreferenties (door host ondersteunde eigenschappen) bijvoorbeeld: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lezen/schrijven String.

**Retour:**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

Formules binnen waarden, from, to, by attributen kunnen bestaan uit de volgende: Standaard rekenkundige operatoren: '+', '-', '*', '/', '^', '%' (mod) Constanten: 'pi' 'e' Voorwaardelijke operatoren: 'abs', 'min', 'max', '?' (if) Vergelijkingsoperatoren: '==', '>=', '', '!=', '!' Trigonometrische operatoren: 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Natuurlijke logaritme 'ln()' Eigenschapsreferenties (door host ondersteunde eigenschappen) bijvoorbeeld: "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lezen/schrijven String.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.String |  |