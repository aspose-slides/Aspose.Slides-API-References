---
title: Point
second_title: Aspose.Slides pour Android via la référence API Java
description: Représente le point d'animation.
type: docs
url: /fr/com.aspose.slides/point/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IPoint](../../com.aspose.slides/ipoint)
```
public class Point implements IPoint
```

Représente le point d'animation.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Point()](#Point--) | Constructeur par défaut. |
| [Point(float time, Object value, String formula)](#Point-float-java.lang.Object-java.lang.String-) | Créer un point d'animation avec le temps, la valeur et la formule. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTime()](#getTime--) | Représente la valeur temporelle. |
| [setTime(float value)](#setTime-float-) | Représente la valeur temporelle. |
| [getValue()](#getValue--) | Représente la valeur du point. |
| [setValue(Object value)](#setValue-java.lang.Object-) | Représente la valeur du point. |
| [getFormula()](#getFormula--) | Les formules dans les valeurs, les attributs from, to, by peuvent être composées de : Opérateurs arithmétiques standards : '+', '-', '*', '/', '^', '%' (mod) Constantes : 'pi' 'e' Opérateurs conditionnels : 'abs', 'min', 'max', '?' (if) Opérateurs de comparaison : '==', '>=', '', '!=', '!' Opérateurs trigonométriques : 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarithme naturel 'ln()' Références de propriétés (propriétés prises en charge par l’hôte) par exemple : "\#ppt_x+(cos(-2*pi*(1-$))*-\#ppt_x-sin(-2*pi*(1-$))*(1-\#ppt_y))*(1-$)" Lecture/écriture String. |
| [setFormula(String value)](#setFormula-java.lang.String-) | Les formules dans les valeurs, les attributs from, to, by peuvent être composées de : Opérateurs arithmétiques standards : '+', '-', '*', '/', '^', '%' (mod) Constantes : 'pi' 'e' Opérateurs conditionnels : 'abs', 'min', 'max', '?' (if) Opérateurs de comparaison : '==', '>=', '', '!=', '!' Opérateurs trigonométriques : 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarithme naturel 'ln()' Références de propriétés (propriétés prises en charge par l’hôte) par exemple : "\#ppt_x+(cos(-2*pi*(1-$))*-\#ppt_x-sin(-2*pi*(1-$))*(1-\#ppt_y))*(1-$)" Lecture/écriture String. |
### Point() {#Point--}
```
public Point()
```

Constructeur par défaut.

### Point(float time, Object value, String formula) {#Point-float-java.lang.Object-java.lang.String-}
```
public Point(float time, Object value, String formula)
```

Créer un point d'animation avec le temps, la valeur et la formule.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| time | float | Valeur temporelle. |
| value | java.lang.Object | Valeur du point. |
| formula | java.lang.String | Formule. |

### getTime() {#getTime--}
```
public final float getTime()
```

Représente la valeur temporelle. Lecture/écriture float.

**Renvoie :**
float

### setTime(float value) {#setTime-float-}
```
public final void setTime(float value)
```

Représente la valeur temporelle. Lecture/écriture float.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getValue() {#getValue--}
```
public final Object getValue()
```

Représente la valeur du point. Seulement : bool, ColorFormat, float, int, string. Lecture/écriture Object.

**Renvoie :**
java.lang.Object

### setValue(Object value) {#setValue-java.lang.Object-}
```
public final void setValue(Object value)
```

Représente la valeur du point. Seulement : bool, ColorFormat, float, int, string. Lecture/écriture Object.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### getFormula() {#getFormula--}
```
public final String getFormula()
```

Les formules dans les valeurs, les attributs from, to, by peuvent être composées de : Opérateurs arithmétiques standards : '+', '-', '*', '/', '^', '%' (mod) Constantes : 'pi' 'e' Opérateurs conditionnels : 'abs', 'min', 'max', '?' (if) Opérateurs de comparaison : '==', '>=', '', '!=', '!' Opérateurs trigonométriques : 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarithme naturel 'ln()' Références de propriétés (propriétés prises en charge par l’hôte) par exemple : "\#ppt_x+(cos(-2*pi*(1-$))*-\#ppt_x-sin(-2*pi*(1-$))*(1-\#ppt_y))*(1-$)" Lecture/écriture String.

**Renvoie :**
java.lang.String

### setFormula(String value) {#setFormula-java.lang.String-}
```
public final void setFormula(String value)
```

Les formules dans les valeurs, les attributs from, to, by peuvent être composées de : Opérateurs arithmétiques standards : '+', '-', '*', '/', '^', '%' (mod) Constantes : 'pi' 'e' Opérateurs conditionnels : 'abs', 'min', 'max', '?' (if) Opérateurs de comparaison : '==', '>=', '', '!=', '!' Opérateurs trigonométriques : 'sin()', 'cos()', 'tan()', 'asin()', 'acos()', 'atan()' Logarithme naturel 'ln()' Références de propriétés (propriétés prises en charge par l’hôte) par exemple : "\#ppt_x+(cos(-2*pi*(1-$))*-\#ppt_x-sin(-2*pi*(1-$))*(1-\#ppt_y))*(1-$)" Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |