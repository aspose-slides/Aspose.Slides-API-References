---
title: ILegend
second_title: Aspose.Slides pour Android via la référence de l'API Java
description: Représente les propriétés de la légende des graphiques.
type: docs
url: /fr/com.aspose.slides/ilegend/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.ILayoutable](../../com.aspose.slides/ilayoutable), [com.aspose.slides.IFormattedTextContainer](../../com.aspose.slides/iformattedtextcontainer), [com.aspose.slides.IActualLayout](../../com.aspose.slides/iactuallayout)
```
public interface ILegend extends ILayoutable, IFormattedTextContainer, IActualLayout
```

Représente les propriétés de la légende du graphique.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getOverlay()](#getOverlay--) | Détermine si les autres éléments du graphique doivent être autorisés à chevaucher la légende. |
| [setOverlay(boolean value)](#setOverlay-boolean-) | Détermine si les autres éléments du graphique doivent être autorisés à chevaucher la légende. |
| [getPosition()](#getPosition--) | Spécifie la position de la légende sur un graphique. |
| [setPosition(int value)](#setPosition-int-) | Spécifie la position de la légende sur un graphique. |
| [getFormat()](#getFormat--) | Renvoie le format d'une légende. |
| [getEntries()](#getEntries--) | Obtient les entrées de légende. |
### getOverlay() {#getOverlay--}
```
public abstract boolean getOverlay()
```


Détermine si les autres éléments du graphique doivent être autorisés à chevaucher la légende. Lecture/écriture booléen.

**Renvoie :**
boolean
### setOverlay(boolean value) {#setOverlay-boolean-}
```
public abstract void setOverlay(boolean value)
```


Détermine si les autres éléments du graphique doivent être autorisés à chevaucher la légende. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getPosition() {#getPosition--}
```
public abstract int getPosition()
```


Spécifie la position de la légende sur un graphique. Les valeurs non NaN des propriétés X, Y, Width, Heigt remplacent l'effet de cette propriété. Lecture/écriture [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Renvoie :**
int
### setPosition(int value) {#setPosition-int-}
```
public abstract void setPosition(int value)
```


Spécifie la position de la légende sur un graphique. Les valeurs non NaN des propriétés X, Y, Width, Heigt remplacent l'effet de cette propriété. Lecture/écriture [LegendPositionType](../../com.aspose.slides/legendpositiontype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |

### getFormat() {#getFormat--}
```
public abstract IFormat getFormat()
```


Renvoie le format d'une légende. Lecture seule [IFormat](../../com.aspose.slides/iformat).

**Renvoie :**
[IFormat](../../com.aspose.slides/iformat)
### getEntries() {#getEntries--}
```
public abstract ILegendEntryCollection getEntries()
```


Obtient les entrées de légende. Lecture seule [ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection).

**Renvoie :**
[ILegendEntryCollection](../../com.aspose.slides/ilegendentrycollection)