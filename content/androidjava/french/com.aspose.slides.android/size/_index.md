---
title: Size
second_title: Référence de l'API Java pour Aspose.Slides sur Android
description: Classe décrivant les dimensions de largeur et de hauteur dans une unité arbitraire.
type: docs
url: /fr/com.aspose.slides.android/size/
---
**Inheritance:**
java.lang.Object
```
public class Size
```

Classe décrivant les dimensions de largeur et de hauteur dans une unité arbitraire.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Size(int width, int height)](#Size-int-int-) | Crée une nouvelle instance de Size. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getWidth()](#getWidth--) | Obtient la largeur de la taille. |
| [getHeight()](#getHeight--) | Obtient la hauteur de la taille. |
| [equals(Object obj)](#equals-java.lang.Object-) | Vérifie si cette taille est égale à une autre taille. |
| [hashCode()](#hashCode--) | {@inheritDoc} |
| [toString()](#toString--) | Retourne la taille représentée sous forme de chaîne avec le format "WxH" |

### Size(int width, int height) {#Size-int-int-}
```
public Size(int width, int height)
```

Crée une nouvelle instance de Size.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| width | int | La largeur de la taille |
| height | int | La hauteur de la taille |

### getWidth() {#getWidth--}
```
public int getWidth()
```

Obtient la largeur de la taille.

**Renvoie :**
int - largeur

### getHeight() {#getHeight--}
```
public int getHeight()
```

Obtient la hauteur de la taille.

**Renvoie :**
int - hauteur

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Vérifie si cette taille est égale à une autre taille.

Deux tailles sont égales si et seulement si leurs largeurs et hauteurs sont toutes deux égales.

Un objet Size n’est jamais égal à un objet d’un autre type.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Renvoie :**
boolean - true si les objets sont égaux, false sinon

### hashCode() {#hashCode--}
```
public int hashCode()
```

**Renvoie :**
int

### toString() {#toString--}
```
public String toString()
```

Retourne la taille représentée sous forme de chaîne avec le format "WxH"

**Renvoie :**
java.lang.String - représentation sous forme de chaîne de la taille