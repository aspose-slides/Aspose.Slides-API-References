---
title: IPoint
second_title: Aspose.Slides pour Android via Java API Référence
description: Représente un point d'animation.
type: docs
url: /fr/com.aspose.slides/ipoint/
---```
public interface IPoint
```

Représente un point d'animation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTime()](#getTime--) | Représente une valeur de temps. |
| [setTime(float value)](#setTime-float-) | Représente une valeur de temps. |
| [getValue()](#getValue--) | Représente une valeur de point. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Représente une valeur de point. |
| [getFormula()](#getFormula--) | Les formules dans les attributs values, from, to, by peuvent être composées de ces : Opérateurs arithmétiques standards : '+', '-', '*', '/', '^', '%' (mod) Constantes : 'pi' 'e' Opérateurs conditionnels : 'abs', 'min', 'max', '?' (if) Opérateurs de comparaison : '==', '>=', '', '!=', '!' Opérateurs trigonométriques : 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarithme naturel 'ln()' Références de propriétés (propriétés prises en charge par l'hôte) par exemple : "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lecture/écriture String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Les formules dans les attributs values, from, to, by peuvent être composées de ces : Opérateurs arithmétiques standards : '+', '-', '*', '/', '^', '%' (mod) Constantes : 'pi' 'e' Opérateurs conditionnels : 'abs', 'min', 'max', '?' (if) Opérateurs de comparaison : '==', '>=', '', '!=', '!' Opérateurs trigonométriques : 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarithme naturel 'ln()' Références de propriétés (propriétés prises en charge par l'hôte) par exemple : "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lecture/écriture String. |
### getTime() {#getTime--}
```
public abstract float getTime()
```

Représente une valeur de temps. Lecture/écriture float.

**Renvoie :**
float
### setTime(float value) {#setTime-float-}
```
public abstract void setTime(float value)
```

Représente une valeur de temps. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |
### getValue() {#getValue--}
```
public abstract Object getValue()
```

Représente une valeur de point. Only: bool, ColorFormat, float, int, string. Lecture/écriture Object.

**Renvoie :**
java.lang.Object
### setValue(Object value) {#setValue-java.lang.Object-}
```
public abstract void setValue(Object value)
```

Représente une valeur de point. Only: bool, ColorFormat, float, int, string. Lecture/écriture Object.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |
### getFormula() {#getFormula--}
```
public abstract String getFormula()
```

Les formules dans les attributs values, from, to, by peuvent être composées de ces : Opérateurs arithmétiques standards : '+', '-', '*', '/', '^', '%' (mod) Constantes : 'pi' 'e' Opérateurs conditionnels : 'abs', 'min', 'max', '?' (if) Opérateurs de comparaison : '==', '>=', '', '!=', '!' Opérateurs trigonométriques : 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarithme naturel 'ln()' Références de propriétés (propriétés prises en charge par l'hôte) par exemple : "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lecture/écriture String.

**Renvoie :**
java.lang.String
### setFormula(String value) {#setFormula-java.lang.String-}
```
public abstract void setFormula(String value)
```

Les formules dans les attributs values, from, to, by peuvent être composées de ces : Opérateurs arithmétiques standards : '+', '-', '*', '/', '^', '%' (mod) Constantes : 'pi' 'e' Opérateurs conditionnels : 'abs', 'min', 'max', '?' (if) Opérateurs de comparaison : '==', '>=', '', '!=', '!' Opérateurs trigonométriques : 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarithme naturel 'ln()' Références de propriétés (propriétés prises en charge par l'hôte) par exemple : "\#ppt\_x+(cos(-2\*pi\*(1-$))\*-\#ppt\_x-sin(-2\*pi\*(1-$))\*(1-\#ppt\_y))\*(1-$)" Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |