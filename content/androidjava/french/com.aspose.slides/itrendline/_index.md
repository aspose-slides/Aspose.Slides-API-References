---
title: ITrendline
second_title: Aspose.Slides pour Android via la référence API Java
description: Classe représentant la ligne de tendance d'une série de graphique
type: docs
url: /fr/com.aspose.slides/itrendline/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IOverridableText](../../com.aspose.slides/ioverridabletext)
```
public interface ITrendline extends IOverridableText
```

La classe représente la ligne de tendance d’une série de graphique
## Méthodes

| Méthode | Description |
| --- | --- |
| [getTrendlineName()](#getTrendlineName--) | Obtient ou définit le nom de la ligne de tendance. |
| [setTrendlineName(String value)](#setTrendlineName-java.lang.String-) | Obtient ou définit le nom de la ligne de tendance. |
| [getTrendlineType()](#getTrendlineType--) | Obtient ou définit le type de ligne de tendance. |
| [setTrendlineType(int value)](#setTrendlineType-int-) | Obtient ou définit le type de ligne de tendance. |
| [getFormat()](#getFormat--) | Représente le format de la ligne de tendance. |
| [setFormat(IFormat value)](#setFormat-com.aspose.slides.IFormat-) | Représente le format de la ligne de tendance. |
| [getBackward()](#getBackward--) | Spécifie le nombre de catégories (ou d’unités sur un graphique en nuage de points) que la ligne de tendance étend avant les données pour la série qui est tendance. |
| [setBackward(double value)](#setBackward-double-) | Spécifie le nombre de catégories (ou d’unités sur un graphique en nuage de points) que la ligne de tendance étend avant les données pour la série qui est tendance. |
| [getForward()](#getForward--) | Spécifie le nombre de catégories (ou d’unités sur un graphique en nuage de points) que la ligne de tendance étend après les données pour la série qui est tendance. |
| [setForward(double value)](#setForward-double-) | Spécifie le nombre de catégories (ou d’unités sur un graphique en nuage de points) que la ligne de tendance étend après les données pour la série qui est tendance. |
| [getIntercept()](#getIntercept--) | Spécifie la valeur où la ligne de tendance doit traverser l’axe y. |
| [setIntercept(double value)](#setIntercept-double-) | Spécifie la valeur où la ligne de tendance doit traverser l’axe y. |
| [getDisplayEquation()](#getDisplayEquation--) | Spécifie que l’équation de la ligne de tendance est affichée sur le graphique (dans la même étiquette que la valeur Rsquared). |
| [setDisplayEquation(boolean value)](#setDisplayEquation-boolean-) | Spécifie que l’équation de la ligne de tendance est affichée sur le graphique (dans la même étiquette que la valeur Rsquared). |
| [getOrder()](#getOrder--) | Spécifie l’ordre de la ligne de tendance polynomiale. |
| [setOrder(byte value)](#setOrder-byte-) | Spécifie l’ordre de la ligne de tendance polynomiale. |
| [getPeriod()](#getPeriod--) | Spécifie la période de la ligne de tendance pour une ligne de moyenne mobile. |
| [setPeriod(byte value)](#setPeriod-byte-) | Spécifie la période de la ligne de tendance pour une ligne de moyenne mobile. |
| [getDisplayRSquaredValue()](#getDisplayRSquaredValue--) | Spécifie que la valeur R-carré de la ligne de tendance est affichée sur le graphique (dans la même étiquette que l’équation). |
| [setDisplayRSquaredValue(boolean value)](#setDisplayRSquaredValue-boolean-) | Spécifie que la valeur R-carré de la ligne de tendance est affichée sur le graphique (dans la même étiquette que l’équation). |
| [getRelatedLegendEntry()](#getRelatedLegendEntry--) | Représente l’entrée de légende liée à cette ligne de tendance Lecture seule [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties). |
### getTrendlineName() {#getTrendlineName--}
```
public abstract String getTrendlineName()
```

Obtient ou définit le nom de la ligne de tendance. Lecture/écriture String.

**Retour :**
java.lang.String
### setTrendlineName(String value) {#setTrendlineName-java.lang.String-}
```
public abstract void setTrendlineName(String value)
```

Obtient ou définit le nom de la ligne de tendance. Lecture/écriture String.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |
### getTrendlineType() {#getTrendlineType--}
```
public abstract int getTrendlineType()
```

Obtient ou définit le type de ligne de tendance. Lecture/écriture [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Retour :**
int
### setTrendlineType(int value) {#setTrendlineType-int-}
```
public abstract void setTrendlineType(int value)
```

Obtient ou définit le type de ligne de tendance. Lecture/écriture [TrendlineType](../../com.aspose.slides/trendlinetype)(\#getTrendlineType.getTrendlineType/\#setTrendlineType(int).setTrendlineType(int)).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```

Représente le format de la ligne de tendance. Lecture/écriture [IFormat](../../com.aspose.slides/iformat).

**Retour :**
[IFormat](../../com.aspose.slides/iformat)
### setFormat(IFormat value) {#setFormat-com.aspose.slides.IFormat-}
```
public abstract void setFormat(IFormat value)
```

Représente le format de la ligne de tendance. Lecture/écriture [IFormat](../../com.aspose.slides/iformat).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [IFormat](../../com.aspose.slides/iformat) |  |
### getBackward() {#getBackward--}
```
public abstract double getBackward()
```

Spécifie le nombre de catégories (ou d’unités sur un graphique en nuage de points) que la ligne de tendance étend avant les données pour la série qui est tendance. Sur les graphiques en nuage de points et non-nuage de points, la valeur doit être non négative. Lecture/écriture double.

**Retour :**
double
### setBackward(double value) {#setBackward-double-}
```
public abstract void setBackward(double value)
```

Spécifie le nombre de catégories (ou d’unités sur un graphique en nuage de points) que la ligne de tendance étend avant les données pour la série qui est tendance. Sur les graphiques en nuage de points et non-nuage de points, la valeur doit être non négative. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getForward() {#getForward--}
```
public abstract double getForward()
```

Spécifie le nombre de catégories (ou d’unités sur un graphique en nuage de points) que la ligne de tendance étend après les données pour la série qui est tendance. Sur les graphiques en nuage de points et non-nuage de points, la valeur doit être non négative. Lecture/écriture double.

**Retour :**
double
### setForward(double value) {#setForward-double-}
```
public abstract void setForward(double value)
```

Spécifie le nombre de catégories (ou d’unités sur un graphique en nuage de points) que la ligne de tendance étend après les données pour la série qui est tendance. Sur les graphiques en nuage de points et non-nuage de points, la valeur doit être non négative. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getIntercept() {#getIntercept--}
```
public abstract double getIntercept()
```

Spécifie la valeur où la ligne de tendance doit traverser l’axe y. Cette propriété n’est prise en charge que lorsque le type de ligne de tendance est exp, linéaire ou poly. Lecture/écriture double.

**Retour :**
double
### setIntercept(double value) {#setIntercept-double-}
```
public abstract void setIntercept(double value)
```

Spécifie la valeur où la ligne de tendance doit traverser l’axe y. Cette propriété n’est prise en charge que lorsque le type de ligne de tendance est exp, linéaire ou poly. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getDisplayEquation() {#getDisplayEquation--}
```
public abstract boolean getDisplayEquation()
```

Spécifie que l’équation de la ligne de tendance est affichée sur le graphique (dans la même étiquette que la valeur Rsquared). Lecture/écriture boolean.

**Retour :**
boolean
### setDisplayEquation(boolean value) {#setDisplayEquation-boolean-}
```
public abstract void setDisplayEquation(boolean value)
```

Spécifie que l’équation de la ligne de tendance est affichée sur le graphique (dans la même étiquette que la valeur Rsquared). Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getOrder() {#getOrder--}
```
public abstract byte getOrder()
```

Spécifie l’ordre de la ligne de tendance polynomiale. Elle est ignorée pour les autres types de ligne de tendance. La valeur doit être comprise entre 2 et 6. Lecture/écriture byte.

**Retour :**
byte
### setOrder(byte value) {#setOrder-byte-}
```
public abstract void setOrder(byte value)
```

Spécifie l’ordre de la ligne de tendance polynomiale. Elle est ignorée pour les autres types de ligne de tendance. La valeur doit être comprise entre 2 et 6. Lecture/écriture byte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getPeriod() {#getPeriod--}
```
public abstract byte getPeriod()
```

Spécifie la période de la ligne de tendance pour une ligne de moyenne mobile. Elle est ignorée pour les autres variantes de ligne de tendance. La valeur doit être comprise entre 2 et 255. Lecture/écriture byte.

**Retour :**
byte
### setPeriod(byte value) {#setPeriod-byte-}
```
public abstract void setPeriod(byte value)
```

Spécifie la période de la ligne de tendance pour une ligne de moyenne mobile. Elle est ignorée pour les autres variantes de ligne de tendance. La valeur doit être comprise entre 2 et 255. Lecture/écriture byte.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getDisplayRSquaredValue() {#getDisplayRSquaredValue--}
```
public abstract boolean getDisplayRSquaredValue()
```

Spécifie que la valeur R-carré de la ligne de tendance est affichée sur le graphique (dans la même étiquette que l’équation). Lecture/écriture boolean.

**Retour :**
boolean
### setDisplayRSquaredValue(boolean value) {#setDisplayRSquaredValue-boolean-}
```
public abstract void setDisplayRSquaredValue(boolean value)
```

Spécifie que la valeur R-carré de la ligne de tendance est affichée sur le graphique (dans la même étiquette que l’équation). Lecture/écriture boolean.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getRelatedLegendEntry() {#getRelatedLegendEntry--}
```
public abstract ILegendEntryProperties getRelatedLegendEntry()
```

Représente l’entrée de légende liée à cette ligne de tendance Lecture seule [ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties).

**Retour :**
[ILegendEntryProperties](../../com.aspose.slides/ilegendentryproperties)