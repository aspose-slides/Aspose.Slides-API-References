---
title: IActualLayout
second_title: Référence de l'API Aspose.Slides pour Java
description: Spécifie la position réelle d'un élément de graphique.
type: docs
url: /fr/com.aspose.slides/iactuallayout/
---```
public interface IActualLayout
```

Spécifie la position réelle d'un élément de graphique.
## Méthodes

| Method | Description |
| --- | --- |
| [getActualX()](#getActualX--) | Spécifie la position x réelle (gauche) de l'élément de graphique par rapport au coin supérieur gauche du graphique. |
| [getActualY()](#getActualY--) | Spécifie le haut réel de l'élément de graphique par rapport au coin supérieur gauche du graphique. |
| [getActualWidth()](#getActualWidth--) | Spécifie la largeur réelle de l'élément de graphique. |
| [getActualHeight()](#getActualHeight--) | Spécifie la hauteur réelle de l'élément de graphique. |
### getActualX() {#getActualX--}
```
public abstract float getActualX()
```

Spécifie la position x réelle (gauche) de l'élément de graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture float.

**Retour:**  
float
### getActualY() {#getActualY--}
```
public abstract float getActualY()
```

Spécifie le haut réel de l'élément de graphique par rapport au coin supérieur gauche du graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture float.

**Retour:**  
float
### getActualWidth() {#getActualWidth--}
```
public abstract float getActualWidth()
```

Spécifie la largeur réelle de l'élément de graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture float.

**Retour:**  
float
### getActualHeight() {#getActualHeight--}
```
public abstract float getActualHeight()
```

Spécifie la hauteur réelle de l'élément de graphique. Appelez la méthode IChart.ValidateChartLayout() avant pour obtenir les valeurs réelles. Lecture float.

**Retour:**  
float