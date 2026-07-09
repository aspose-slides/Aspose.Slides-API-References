---
title: ITableFormat
second_title: Aspose.Slides pour Android via Référence de l'API Java
description: Représente le format d'un tableau.
type: docs
url: /fr/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Représente le format d'un tableau.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Renvoie un objet de propriétés de remplissage de tableau. |
| [getTransparency()](#getTransparency--) | Obtient ou définit la transparence de la couleur de remplissage. |
| [setTransparency(float value)](#setTransparency-float-) | Obtient ou définit la transparence de la couleur de remplissage. |
| [getEffective()](#getEffective--) | Obtient les propriétés de formatage effectif du tableau avec l'héritage et les styles de tableau appliqués. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Renvoie un objet de propriétés de remplissage de tableau. Lecture seule [IFillFormat](../../com.aspose.slides/ifillformat).

**Renvoie :**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Obtient ou définit la transparence de la couleur de remplissage. Lecture/écriture  float .

**Renvoie :**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Obtient ou définit la transparence de la couleur de remplissage. Lecture/écriture  float .

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ITableFormatEffectiveData getEffective()
```


Obtient les propriétés de formatage effectif du tableau avec l'héritage et les styles de tableau appliqués.

**Renvoie :**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Un [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).