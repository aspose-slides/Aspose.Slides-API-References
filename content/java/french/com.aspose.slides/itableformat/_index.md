---
title: ITableFormat
second_title: Aspose.Slides for Java API Reference
description: Represents format of a table.
type: docs
url: /fr/com.aspose.slides/itableformat/
---```
public interface ITableFormat
```

Représente le format d'un tableau.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Returns a table fill properties object. |
| [getTransparency()](#getTransparency--) | Gets or sets the transparency of the fill color. |
| [setTransparency(float value)](#setTransparency-float-) | Gets or sets the transparency of the fill color. |
| [getEffective()](#getEffective--) | Gets effective table formatting properties with inheritance and table styles applied. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Renvoie un objet de propriétés de remplissage de tableau. Lecture seule [IFillFormat](../../com.aspose.slides/ifillformat).

**Retour :**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Obtient ou définit la transparence de la couleur de remplissage. Lecture/écriture  float .

**Retour :**
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


Obtient les propriétés de mise en forme de tableau effectives avec héritage et styles de tableau appliqués.

**Retour :**
[ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata) - Un [ITableFormatEffectiveData](../../com.aspose.slides/itableformateffectivedata).