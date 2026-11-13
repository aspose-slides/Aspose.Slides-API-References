---
title: CachedChartValue
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente une valeur de graphique mise en cache, par exemple X, Y, taille de bulle ou la valeur principale.
type: docs
url: /fr/com.aspose.slides/cachedchartvalue/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.ICachedChartValue](../../com.aspose.slides/icachedchartvalue)
```
public class CachedChartValue implements ICachedChartValue
```

Représente une valeur de graphique mise en cache (p. ex. X, Y, taille de bulle ou la valeur principale).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CachedChartValue()](#CachedChartValue--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [toString()](#toString--) | Renvoie une représentation sous forme de chaîne de la valeur mise en cache. |
| [toDouble()](#toDouble--) | Convertit la valeur mise en cache en double. |
| [getData()](#getData--) | Obtient l'objet de données mis en cache. |
### CachedChartValue() {#CachedChartValue--}
```
public CachedChartValue()
```


### toString() {#toString--}
```
public String toString()
```


Renvoie une représentation sous forme de chaîne de la valeur mise en cache.

**Retourne :**
java.lang.String
### toDouble() {#toDouble--}
```
public final double toDouble()
```


Convertit la valeur mise en cache en double.

**Retourne :**
double - La représentation numérique, ou Double.NaN si Data (\#getData.getData/\#setData(Object).setData(Object)) est nul ou ne peut pas être converti en double.
### getData() {#getData--}
```
public final Object getData()
```


Obtient l'objet de données mis en cache. Lecture seule Object .

**Retourne :**
java.lang.Object