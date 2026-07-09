---
title: SizeF
second_title: Référence de l'API Java d'Aspose.Slides pour Android
description: Classe décrivant les dimensions de largeur et de hauteur dans une unité arbitraire avec des valeurs à virgule flottante.
type: docs
url: /fr/com.aspose.slides.android/sizef/
---
**Héritage :**
java.lang.Object
```
public class SizeF
```

Classe décrivant les dimensions de largeur et de hauteur dans une unité arbitraire avec des valeurs à virgule flottante.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [SizeF(float width, float height)](#SizeF-float-float-) | Crée une nouvelle instance de SizeF. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Obtient la largeur de la taille. |
| [getHeight()](#getHeight--) | Obtient la hauteur de la taille. |
| [equals(Object obj)](#equals-java.lang.Object-) | Vérifie si cette taille est égale à une autre taille. |
| [hashCode()](#hashCode--) | \{@inheritDoc\} |
| [toString()](#toString--) | Renvoie la taille représentée sous forme de chaîne avec le format  "WxH"  |
### SizeF(float width, float height) {#SizeF-float-float-}
```
public SizeF(float width, float height)
```


Crée une nouvelle instance de SizeF.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | float | La largeur de la taille |
| height | float | La hauteur de la taille |

### getWidth() {#getWidth--}
```
public float getWidth()
```


Obtient la largeur de la taille.

**Retour :**
float - width
### getHeight() {#getHeight--}
```
public float getHeight()
```


Obtient la hauteur de la taille.

**Retour :**
float - height
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Vérifie si cette taille est égale à une autre taille.

Deux tailles sont égales si et seulement si leurs largeurs et hauteurs sont identiques.

À cet effet, les valeurs float de largeur/hauteur sont considérées comme identiques si et seulement si la méthode Float#floatToIntBits(float).floatToIntBits(float) renvoie la même valeur int lorsqu’elle est appliquée à chacune.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Retour :**
boolean -  true  si les objets sont égaux,  false  sinon
### hashCode() {#hashCode--}
```
public int hashCode()
```




**Retour :**
int
### toString() {#toString--}
```
public String toString()
```


Renvoie la taille représentée sous forme de chaîne avec le format  "WxH" 

**Retour :**
java.lang.String - représentation sous forme de chaîne de la taille