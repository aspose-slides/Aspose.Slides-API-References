---
title: ICachedChartValue
second_title: Aspose.Slides for Java API Reference
description: Représente une valeur de graphique en cache, par exemple X, Y, taille de bulle ou la valeur principale.
type: docs
url: /fr/com.aspose.slides/icachedchartvalue/
---```
public interface ICachedChartValue
```

Représente une valeur de graphique en cache (par exemple X, Y, taille de bulle ou la valeur principale).
## Méthodes

| Méthode | Description |
| --- | --- |
| [getData()](#getData--) | Récupère l'objet de données en cache. |
| [toDouble()](#toDouble--) | Convertit la valeur en cache en double. |
### getData() {#getData--}
```
public abstract Object getData()
```


Récupère l'objet de données en cache. Lecture seule  Object .

**Renvoie:**
java.lang.Object
### toDouble() {#toDouble--}
```
public abstract double toDouble()
```


Convertit la valeur en cache en double.

**Renvoie:**
double - La représentation numérique, ou Double.NaN si Data (\#getData.getData) est nul ou ne peut pas être converti en double.